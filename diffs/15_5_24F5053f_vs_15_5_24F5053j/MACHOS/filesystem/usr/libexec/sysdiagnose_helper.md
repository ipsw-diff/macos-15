## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1438.120.8.0.0
-  __TEXT.__text: 0x3f4d0
+1438.120.9.0.0
+  __TEXT.__text: 0x3f518
   __TEXT.__auth_stubs: 0xdb0
   __TEXT.__objc_stubs: 0x19c0
   __TEXT.__objc_methlist: 0x738
   __TEXT.__const: 0x3a8
-  __TEXT.__cstring: 0x43e62
+  __TEXT.__cstring: 0x43e9e
   __TEXT.__objc_methname: 0x1b3a
   __TEXT.__oslogstring: 0x2243
   __TEXT.__objc_classname: 0x132

   - @rpath/CoreRepairCore.framework/Versions/A/CoreRepairCore
   Functions: 348
   Symbols:   295
-  CStrings:  5420
+  CStrings:  5422
 
Functions:
~ sub_10002f784 : 48280 -> 48352
CStrings:
+ "massScanForceStartWithPilot"
+ "massScanPilotIgnoredTooFrequent"
```
