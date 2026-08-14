## syspolicyd

> `/usr/libexec/syspolicyd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__dof_security_`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-620.120.1.0.0
-  __TEXT.__text: 0xb5040
+620.120.4.0.0
+  __TEXT.__text: 0xb5418
   __TEXT.__auth_stubs: 0x29d0
-  __TEXT.__objc_stubs: 0x9b00
+  __TEXT.__objc_stubs: 0x9b60
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x4fec
+  __TEXT.__objc_methlist: 0x5014
   __TEXT.__const: 0x1d74
-  __TEXT.__objc_methname: 0xc3ca
-  __TEXT.__cstring: 0x11aa8
+  __TEXT.__objc_methname: 0xc455
+  __TEXT.__cstring: 0x11ac8
   __TEXT.__objc_classname: 0x754
-  __TEXT.__objc_methtype: 0x236a
-  __TEXT.__oslogstring: 0x94c8
-  __TEXT.__gcc_except_tab: 0x1c78
+  __TEXT.__objc_methtype: 0x2384
+  __TEXT.__oslogstring: 0x94f8
+  __TEXT.__gcc_except_tab: 0x1c6c
   __TEXT.__swift5_typeref: 0x390
   __TEXT.__swift5_capture: 0x134
   __TEXT.__constg_swiftt: 0x3dc

   __TEXT.__swift5_proto: 0x40
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__dof_security_: 0x325
-  __TEXT.__unwind_info: 0x23b0
+  __TEXT.__unwind_info: 0x23b8
   __TEXT.__eh_frame: 0x248
   __DATA_CONST.__auth_got: 0x1500
   __DATA_CONST.__got: 0x830
   __DATA_CONST.__auth_ptr: 0x1d8
   __DATA_CONST.__const: 0x3d28
-  __DATA_CONST.__cfstring: 0x8820
+  __DATA_CONST.__cfstring: 0x8860
   __DATA_CONST.__objc_classlist: 0x300
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x1f0
-  __DATA_CONST.__objc_intobj: 0x270
+  __DATA_CONST.__objc_intobj: 0x2d0
   __DATA_CONST.__objc_arraydata: 0x588
   __DATA_CONST.__objc_arrayobj: 0x270
   __DATA_CONST.__objc_dictobj: 0xa0
-  __DATA.__objc_const: 0x9af0
-  __DATA.__objc_selrefs: 0x2ce0
-  __DATA.__objc_ivar: 0x7e4
+  __DATA.__objc_const: 0x9b30
+  __DATA.__objc_selrefs: 0x2cf8
+  __DATA.__objc_ivar: 0x7e8
   __DATA.__objc_data: 0x20f8
   __DATA.__data: 0xc92
   __DATA.__bss: 0xabd

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3419
+  Functions: 3425
   Symbols:   1014
-  CStrings:  5399
+  CStrings:  5407
 
CStrings:
+ "T@\"NSNumber\",R,N"
+ "TB,N,VdidAuthOverrideSucceed"
+ "Unable to check birth time of database: %d, %s"
+ "dbAge"
+ "didAuthOverrideSucceed"
+ "didAuthSucceed"
+ "roundedDBAgeDays"
+ "sendGatekeeperDialog:withOptions:withResponse:withTime:withSoftwarePolicy:withSoftwareCdhash:isLibraryLoad:isBundled:isQuarantined:isLowFriction:withURL:withMainExecutable:withSigningID:withTeamID:withEvaluationPath:withTimeStamp:withValidationCategory:withDBAge:withAuthSuccess:"
+ "setDidAuthOverrideSucceed:"
+ "v148@0:8q16q24q32d40Q48@\"NSString\"56B64B68B72B76@\"NSURL\"80@\"NSURL\"88@\"NSString\"96@\"NSString\"104Q112d120@\"NSNumber\"128@\"NSNumber\"136B144"
+ "v148@0:8q16q24q32d40Q48@56B64B68B72B76@80@88@96@104Q112d120@128@136B144"
- "sendGatekeeperDialog:withOptions:withResponse:withTime:withSoftwarePolicy:withSoftwareCdhash:isLibraryLoad:isBundled:isQuarantined:isLowFriction:withURL:withMainExecutable:withSigningID:withTeamID:withEvaluationPath:withTimeStamp:withValidationCategory:"
- "v136@0:8q16q24q32d40Q48@\"NSString\"56B64B68B72B76@\"NSURL\"80@\"NSURL\"88@\"NSString\"96@\"NSString\"104Q112d120@\"NSNumber\"128"
- "v136@0:8q16q24q32d40Q48@56B64B68B72B76@80@88@96@104Q112d120@128"
```
