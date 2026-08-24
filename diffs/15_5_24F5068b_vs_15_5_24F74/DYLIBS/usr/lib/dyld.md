## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1285.18.0.0.0
+1285.19.0.0.0
   __TEXT.__text: 0x8767c
   __TEXT.__const: 0x23c0
   __TEXT.__cstring: 0x10102
CStrings:
+ "1285.19"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Fri Apr 25 17:51:08 PDT 2025; root:libignition-56~61884/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Fri Apr 25 17:51:08 PDT 2025; root:libignition-56~61884/libignition_core/RELEASE_ARM64E"
- "1285.18"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Apr 22 20:35:19 PDT 2025; root:libignition-56~61848/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Tue Apr 22 20:35:19 PDT 2025; root:libignition-56~61848/libignition_core/RELEASE_ARM64E"
```
