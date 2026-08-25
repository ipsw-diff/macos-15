## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Mon Jul 14 23:38:16 PDT 2025; root:libignition-56~62468/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Mon Jul 14 23:38:16 PDT 2025; root:libignition-56~62468/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Jul  2 22:50:20 PDT 2025; root:libignition-56~62400/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Wed Jul  2 22:50:20 PDT 2025; root:libignition-56~62400/libignition_core/RELEASE_ARM64E"
```
