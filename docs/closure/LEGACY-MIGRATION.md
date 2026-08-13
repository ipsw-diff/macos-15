# macOS 15 legacy migration closure

Recorded: 2026-08-13

## Claim and scope

Question: can the complete ordinary macOS 15 payload set in frozen legacy
commit `d881e84676308404c6947d0218c11f347a6f3a89` be copied exactly into this
archive shard and later cataloged with immutable provenance?

- First lifecycle stage: select the two ordinary macOS 15 roots in the frozen
  census whose same-device IPSW inputs use the macOS 15 (`24*`) build train.
- Last lifecycle stage: catalog entries independently verify both source trees
  against this shard's merged default-branch commit.
- Supported claim after closure: the two named Git subtrees were faithfully
  migrated and cataloged.
- Excluded: the separate macOS 15 beta directory lacking a root README,
  generating missing release history, and resolving other census exceptions.

## Authority map

| Property | Authority |
| --- | --- |
| Frozen migration membership | Catalog census at the pinned legacy commit |
| Versions, builds, device, and inputs | Strictly parsed source READMEs |
| Files, bytes, modes, and trees | Git objects at the pinned legacy commit |
| Destination payloads and manifests | Reviewed specs plus atomic batch staging |
| Catalog destination pins | Merged shard default-branch commit |

## Closure matrix

| Stage | Evidence | Status before publication |
| --- | --- | --- |
| Selection and trigger | Exactly two ordinary macOS 15 census roots | Closed |
| Inputs and resources | Both rows contain two `UniversalMac` IPSW inputs | Closed |
| Transformation | Atomic staging and independent revalidation reproduce both payload trees | Closed |
| Advertisement and options | Generated shard README lists exactly two comparisons | Closed |
| Dispatch and transport | One unsigned shard commit and pull request | Unresolved |
| State transition | Shard merge precedes catalog publication | Unresolved |
| Outcome oracle | Catalog audit matches source and merged destination | Unresolved |

## Expected and observed inventory

| Source path | Files | Logical bytes | Git tree |
| --- | ---: | ---: | --- |
| `15_3_2_24D81__vs_15_4_24E248` | 7,660 | 218,638,978 | `7ff83e3092b48840eafda969a8c0464e8d23c6ba` |
| `15_4_24E248__vs_15_5_24F5042g` | 1,350 | 19,499,337 | `75de4ad3a1104de53862220b80a7acf6d14fb88d` |

The complete batch contains 9,010 payload files and 238,138,315 logical bytes.
Atomic staging produced root tree
`13f9b869388d705460f7ea6260d2dbceaba8f6f1` for the initial shard plus both
payloads and manifests.

## Negative-evidence audit and stop conditions

The absence of other ordinary macOS 15 rows is scoped to the frozen census; it
does not claim a complete Apple release history. The separate
`15_0_24A5279h__vs_15_0_24A5289g` tree is blocked because it has no tracked
root README, so it is neither silently migrated nor treated as proof of
inapplicability. Stop if membership, README metadata, source trees, batch
inventory, staged scope, destination merge commit, or catalog audit differs.

## Review-time bounded conclusion

Selection, input validation, atomic staging, independent revalidation, and
archive advertisement are closed. Publication, merged destination state, and
catalog verification remain unresolved until their GitHub transitions occur.
