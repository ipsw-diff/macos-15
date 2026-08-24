## Apple Diagnostics

> `/System/Library/CoreServices/Apple Diagnostics.app/Contents/MacOS/Apple Diagnostics`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-820.121.1.0.0
-  __TEXT.__text: 0x1269c
+820.140.8.0.0
+  __TEXT.__text: 0x126e4
   __TEXT.__auth_stubs: 0xa60
   __TEXT.__objc_methlist: 0x864
-  __TEXT.__const: 0x9c4
-  __TEXT.__cstring: 0xf71
+  __TEXT.__const: 0xa24
+  __TEXT.__cstring: 0xfb1
   __TEXT.__objc_methname: 0x1671
   __TEXT.__constg_swiftt: 0x4b8
   __TEXT.__swift5_typeref: 0xaf0

   __TEXT.__eh_frame: 0x378
   __DATA_CONST.__auth_got: 0x530
   __DATA_CONST.__got: 0x240
-  __DATA_CONST.__auth_ptr: 0x378
+  __DATA_CONST.__auth_ptr: 0x3b8
   __DATA_CONST.__const: 0x7b8
   __DATA_CONST.__objc_classlist: 0x70
   __DATA_CONST.__objc_catlist: 0x8

   __DATA.__objc_const: 0xd98
   __DATA.__objc_selrefs: 0x718
   __DATA.__objc_data: 0x9b8
-  __DATA.__data: 0x898
+  __DATA.__data: 0x838
   __DATA.__bss: 0x558
   __DATA.__common: 0x80
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 395
+  Functions: 396
   Symbols:   1209
-  CStrings:  418
+  CStrings:  420
 
CStrings:
+ "tapTurnOnFromEnableWiFi"
+ "viewWifiDisabled"
```
