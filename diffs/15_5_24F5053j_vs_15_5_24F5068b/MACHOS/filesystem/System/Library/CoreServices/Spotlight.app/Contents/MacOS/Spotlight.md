## Spotlight

> `/System/Library/CoreServices/Spotlight.app/Contents/MacOS/Spotlight`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-120.4.6.0.0
-  __TEXT.__text: 0x3c894
-  __TEXT.__auth_stubs: 0x1960
+120.4.7.0.0
+  __TEXT.__text: 0x3c954
+  __TEXT.__auth_stubs: 0x1970
   __TEXT.__objc_stubs: 0x4920
   __TEXT.__objc_methlist: 0x30e4
   __TEXT.__const: 0xcb4
-  __TEXT.__objc_methname: 0x88cd
+  __TEXT.__objc_methname: 0x88dd
   __TEXT.__objc_classname: 0x69a
   __TEXT.__objc_methtype: 0x25ba
   __TEXT.__cstring: 0x2681

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__unwind_info: 0xeb8
   __TEXT.__eh_frame: 0x300
-  __DATA_CONST.__auth_got: 0xcc0
+  __DATA_CONST.__auth_got: 0xcc8
   __DATA_CONST.__got: 0x880
   __DATA_CONST.__auth_ptr: 0x3f8
   __DATA_CONST.__const: 0x1718

   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_intobj: 0x18
   __DATA.__objc_const: 0x5198
-  __DATA.__objc_selrefs: 0x2960
+  __DATA.__objc_selrefs: 0x2968
   __DATA.__objc_ivar: 0x210
   __DATA.__objc_data: 0x20a8
   __DATA.__data: 0x18d8

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 1469
-  Symbols:   850
-  CStrings:  2278
+  Symbols:   851
+  CStrings:  2279
 
Symbols:
+ _swift_getObjCClassFromObject
Functions:
~ sub_100017748 : 1656 -> 1780
~ sub_100037454 -> sub_1000374d0 : 728 -> 796
CStrings:
+ "initWithResult:"
```
