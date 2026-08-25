## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__data`
- `__DATA_DIRTY.__all_image_info`

```diff

-1286.9.0.0.0
-  __TEXT.__text: 0x8767c
+1286.10.0.0.0
+  __TEXT.__text: 0x876bc
   __TEXT.__const: 0x2420
-  __TEXT.__cstring: 0x1010c
+  __TEXT.__cstring: 0x1010d
   __TEXT.__unwind_info: 0x4a8
   __DATA_CONST.__auth_ptr: 0x80
   __DATA_CONST.__const: 0x76e0
Functions:
~ __ZN5dyld44APIs27getImagePlatformAndVersionsEPKN6mach_o6HeaderE : 228 -> 280
~ __ZN5dyld44APIs19dyld_minos_at_leastEPK11mach_header20dyld_build_version_t : 316 -> 328
CStrings:
+ "1286.10"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Jun 17 22:10:25 PDT 2025; root:libignition-56~62314/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Tue Jun 17 22:10:25 PDT 2025; root:libignition-56~62314/libignition_core/RELEASE_ARM64E"
- "1286.9"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Jun 11 21:16:08 PDT 2025; root:libignition-56~62282/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Wed Jun 11 21:16:08 PDT 2025; root:libignition-56~62282/libignition_core/RELEASE_ARM64E"
```
