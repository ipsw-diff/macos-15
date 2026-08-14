## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Apr 15 21:31:38 PDT 2025; root:libignition-56~61740/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Tue Apr 15 21:31:38 PDT 2025; root:libignition-56~61740/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Thu Apr 10 20:17:43 PDT 2025; root:libignition-56~61641/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Thu Apr 10 20:17:43 PDT 2025; root:libignition-56~61641/libignition_core/RELEASE_ARM64E"
```
