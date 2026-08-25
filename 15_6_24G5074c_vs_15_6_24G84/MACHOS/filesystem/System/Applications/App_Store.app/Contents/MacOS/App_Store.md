## App Store

> `/System/Applications/App Store.app/Contents/MacOS/App Store`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 10.6.3.0.0
-  __TEXT.__text: 0x3f9904
+  __TEXT.__text: 0x3f9908
   __TEXT.__auth_stubs: 0xdb40
   __TEXT.__objc_stubs: 0x740
   __TEXT.__objc_methlist: 0x6eec

   __TEXT.__eh_frame: 0xfac
   __DATA_CONST.__auth_got: 0x6da8
   __DATA_CONST.__got: 0x3188
-  __DATA_CONST.__auth_ptr: 0x5888
+  __DATA_CONST.__auth_ptr: 0x5950
   __DATA_CONST.__const: 0x10d00
   __DATA_CONST.__cfstring: 0x380
   __DATA_CONST.__objc_classlist: 0x7e8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 15595
+  Functions: 15596
   Symbols:   6057
   CStrings:  4662
 
Functions:
~ sub_100005708 : 20 -> 16
- sub_10000571c
+ sub_1000058e8
~ sub_100007840 : 856 -> 4
+ sub_100007844
```
