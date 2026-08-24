## powerexperienced

> `/usr/libexec/powerexperienced`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-57.100.8.0.0
-  __TEXT.__text: 0xd7e0
+57.140.3.0.0
+  __TEXT.__text: 0xda30
   __TEXT.__auth_stubs: 0x500
-  __TEXT.__objc_stubs: 0x1c40
-  __TEXT.__objc_methlist: 0x11a4
+  __TEXT.__objc_stubs: 0x1d40
+  __TEXT.__objc_methlist: 0x11dc
   __TEXT.__const: 0xd8
   __TEXT.__cstring: 0x89a
-  __TEXT.__objc_methname: 0x203c
-  __TEXT.__oslogstring: 0x10c1
+  __TEXT.__objc_methname: 0x2099
+  __TEXT.__oslogstring: 0x117b
   __TEXT.__objc_classname: 0x214
   __TEXT.__objc_methtype: 0x54a
   __TEXT.__gcc_except_tab: 0x48
   __TEXT.__dlopen_cstrs: 0x8d
-  __TEXT.__unwind_info: 0x398
+  __TEXT.__unwind_info: 0x3a8
   __DATA_CONST.__auth_got: 0x290
   __DATA_CONST.__got: 0xa8
   __DATA_CONST.__const: 0x648

   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x78
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA.__objc_const: 0x26f0
-  __DATA.__objc_selrefs: 0x928
-  __DATA.__objc_ivar: 0x10c
+  __DATA.__objc_const: 0x2720
+  __DATA.__objc_selrefs: 0x958
+  __DATA.__objc_ivar: 0x110
   __DATA.__objc_data: 0x550
   __DATA.__data: 0x300
   __DATA.__bss: 0x160

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 403
+  Functions: 408
   Symbols:   114
-  CStrings:  703
+  CStrings:  715
 
CStrings:
+ "No trial experiments"
+ "TB,V_experimentActive"
+ "Trial ended, treatmentID %@, experimentID %@, deploymentID %d"
+ "Trial started. treatmentID %@, experimentID %@, deploymentID %d"
+ "Trial updated. treatmentID %@, experimentID %@, deploymentID %d"
+ "Trial:No trial value for CLPC tuning option. Resetting to default"
+ "_experimentActive"
+ "deploymentId"
+ "didTrialEnd:"
+ "didTrialStart:"
+ "didTrialUpdate:"
+ "experimentActive"
+ "experimentId"
+ "experimentIdentifier %@"
+ "setExperimentActive:"
+ "treatmentId"
- "Trial experiment status. treatmentID %@, rolloutID %@, experimentID %@"
- "Trial:No trial value for CLPC tuning option"
- "rolloutIdentifiersWithNamespaceName:"
- "treatmentIdWithNamespaceName:"
```
