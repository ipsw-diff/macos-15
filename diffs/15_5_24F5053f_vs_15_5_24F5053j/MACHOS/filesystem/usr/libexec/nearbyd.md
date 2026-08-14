## nearbyd

> `/usr/libexec/nearbyd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-466.0.3.0.0
-  __TEXT.__text: 0x41b580
+466.0.4.0.0
+  __TEXT.__text: 0x41b6ec
   __TEXT.__auth_stubs: 0x2310
   __TEXT.__objc_stubs: 0x10140
   __TEXT.__init_offsets: 0x288
   __TEXT.__objc_methlist: 0xb39c
-  __TEXT.__gcc_except_tab: 0x43d90
+  __TEXT.__gcc_except_tab: 0x43dbc
   __TEXT.__const: 0x2d5618
-  __TEXT.__cstring: 0x30260
+  __TEXT.__cstring: 0x302b0
   __TEXT.__objc_methname: 0x18765
-  __TEXT.__oslogstring: 0x47fc2
+  __TEXT.__oslogstring: 0x48005
   __TEXT.__objc_classname: 0x177e
   __TEXT.__objc_methtype: 0x1abac
   __TEXT.__constg_swiftt: 0x80

   __DATA_CONST.__got: 0x7d0
   __DATA_CONST.__auth_ptr: 0x58
   __DATA_CONST.__const: 0x1fba0
-  __DATA_CONST.__cfstring: 0x11c00
+  __DATA_CONST.__cfstring: 0x11c20
   __DATA_CONST.__objc_classlist: 0x4a0
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x220

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 18053
   Symbols:   842
-  CStrings:  15471
+  CStrings:  15475
 
Functions:
~ sub_1002a4ff0 : 8828 -> 8980
~ sub_1002c0db4 -> sub_1002c0e4c : 1096 -> 1308
CStrings:
+ "#rose-ses,AlishaSubsystem: trigger crash on URSK retrieval failure"
+ "AlishaTriggerCrashOnURSKRetrievalFailure"
+ "AlishaURSKRetrievalFailed"
+ "URSKC"
```
