# Reusable shard generation closure

Recorded: 2026-08-13

## Claim and scope

Question: can the macOS 15 shard hand the first edge in its reviewed queue to
the reusable catalog generator, publish it on a review branch, and prove that
exact edge left the queue without guessing source identity or writing directly
to `main`?

- First lifecycle stage: scheduled or manual default-branch discovery reports
  a candidate and selects the first edge without caller-controlled build input.
- Last lifecycle stage: the reusable workflow validates the two-commit
  publication branch, atomically pushes it with its permanent source tag, and
  opens one ready review pull request.
- Supported claim after a successful hosted run: the first edge from one exact
  AppleDB commit and `ipsw` source inventory produced one immutable payload
  tree, canonical shard metadata, and a branch where that edge is no longer
  queued. Later macOS 15 edges may remain.
- Excluded: approving checks or merging the shard pull request, central catalog
  insertion, later backlog edges, and external announcements.

## Authority map

| Property | Authority |
| --- | --- |
| Track identity and activation anchor | Reviewed schema-v2 `track.json` plus merged anchor manifest |
| Ordered release edges | Catalog detector at its immutable workflow pin |
| Firmware metadata | Exact AppleDB Git commit plus the pinned `ipsw dl appledb` inventory |
| Firmware bytes | Detector-selected Apple URLs plus verified sizes and SHA-256 values |
| Diff transformation | Reusable catalog generator pinned at `b2acda91fb3a16d1a9779d564b64ba8bac37b50d` |
| Payload identity | Git tree in the payload-only source commit and permanent source tag |
| Manifest and README | Catalog tooling at the same immutable commit |
| Publication state | Git branch/tag refs and GitHub pull-request API |

## Feature-closure matrix

| Stage | Required evidence | Status before hosted run |
| --- | --- | --- |
| Selection and trigger | Scheduled or manual candidate selects only queue edge zero; no build inputs | Unresolved |
| Inputs and resources | Detector builds, unambiguous `ipsw` URL records, and verified bytes | Unresolved |
| Transformation and signing | Pinned `ipsw`; exact flags; unsigned Git commits | Unresolved |
| Advertisement and options | Full workflow pins, no build overrides, and bounded permissions | Unresolved |
| Dispatch and transport | Non-overwriting source-tag/branch push and exactly one ready review PR | Unresolved |
| State transition | Payload-only source commit then metadata/publication commit | Unresolved |
| Outcome oracle | Equal source/destination Git trees and generated edge absent from the remaining queue | Unresolved |

## Expected phase inventory

Exactly the first forward edge from the reviewed macOS 15 queue is accepted.
`ipsw` must confirm the AppleDB-selected active Apple URL, size, SHA-256, and
device compatibility for both endpoints. Exactly two verified IPSW files, one
generated payload directory, one source commit, one permanent source tag, one
publication commit, one manifest, one provenance record, and one review handoff
are expected.

## Negative evidence and stop conditions

A green discovery job alone does not prove acquisition, generation, or
publication. The workflow stops on a non-default dispatch ref, no forward
candidate, an existing payload or branch, invalid policy or source metadata,
byte or hash mismatch, unexpected generated paths, a stale rendered README, a
signed commit, an existing or mismatched source tag, unequal Git trees, a dirty
worktree, or a post-publication detector that still queues the generated build
as a destination. An existing generation branch makes later runs no-op instead
of launching duplicate expensive work. A branch/tag push followed by a
pull-request API failure is a review-only partial state and blocks automatic
retry.

## Bounded conclusion

All rows remain unresolved until this caller is merged and one hosted candidate
run supplies direct evidence. That run can establish only the first macOS 15
edge. It cannot establish later-backlog, other-major, catalog, merge, or
announcement readiness.
