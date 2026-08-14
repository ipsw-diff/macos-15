## Feedback

> `/System/Library/PrivateFrameworks/Feedback.framework/Versions/A/Feedback`

```diff

-150.10.0.0.0
-  __TEXT.__text: 0x18561c
-  __TEXT.__auth_stubs: 0x3de0
+150.12.0.0.0
+  __TEXT.__text: 0x185d0c
+  __TEXT.__auth_stubs: 0x3dd0
   __TEXT.__objc_methlist: 0xfd0
   __TEXT.__const: 0xc194
   __TEXT.__cstring: 0x7b90

   __TEXT.__swift5_assocty: 0xd58
   __TEXT.__swift5_proto: 0x69c
   __TEXT.__swift5_types: 0x3f8
-  __TEXT.__oslogstring: 0x432b
+  __TEXT.__oslogstring: 0x445b
   __TEXT.__swift5_capture: 0x1450
   __TEXT.__swift_as_entry: 0x80
   __TEXT.__swift_as_ret: 0xc0
   __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_mpenum: 0x40
-  __TEXT.__unwind_info: 0x48d0
+  __TEXT.__unwind_info: 0x48c8
   __TEXT.__eh_frame: 0x2bfc
   __TEXT.__objc_classname: 0x105
   __TEXT.__objc_methname: 0x346d

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x10b0
   __DATA_CONST.__objc_protorefs: 0x80
-  __AUTH_CONST.__auth_got: 0x1ef0
+  __AUTH_CONST.__auth_got: 0x1ee8
   __AUTH_CONST.__const: 0x81f8
   __AUTH_CONST.__cfstring: 0x120
   __AUTH_CONST.__objc_const: 0x5558

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 7034
+  Functions: 7039
   Symbols:   2601
-  CStrings:  1757
+  CStrings:  1761
 
CStrings:
+ "Should show batch UI? NO because score is zero AND failed to fetch donations"
+ "Should show batch UI? NO because score is zero AND there are no donations"
+ "Should show batch UI? Yes because score is > 0. Raw score [%ld]"
+ "Should show batch UI? Yes because score is zero but there are donations"
```
