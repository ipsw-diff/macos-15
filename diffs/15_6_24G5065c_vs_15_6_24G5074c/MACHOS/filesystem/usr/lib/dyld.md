## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Jul  2 22:50:20 PDT 2025; root:libignition-56~62400/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Wed Jul  2 22:50:20 PDT 2025; root:libignition-56~62400/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Jun 17 22:10:25 PDT 2025; root:libignition-56~62314/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Tue Jun 17 22:10:25 PDT 2025; root:libignition-56~62314/libignition_core/RELEASE_ARM64E"
```
