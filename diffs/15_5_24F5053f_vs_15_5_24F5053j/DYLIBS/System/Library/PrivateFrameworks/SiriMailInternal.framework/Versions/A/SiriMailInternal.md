## SiriMailInternal

> `/System/Library/PrivateFrameworks/SiriMailInternal.framework/Versions/A/SiriMailInternal`

```diff

-3405.8.1.0.0
-  __TEXT.__text: 0xfb6b0
-  __TEXT.__auth_stubs: 0x41a0
+3405.9.2.0.0
+  __TEXT.__text: 0xfdbfc
+  __TEXT.__auth_stubs: 0x4220
   __TEXT.__objc_methlist: 0x334
   __TEXT.__const: 0x6320
-  __TEXT.__cstring: 0x2364
+  __TEXT.__cstring: 0x23b4
   __TEXT.__constg_swiftt: 0x2368
-  __TEXT.__swift5_typeref: 0x3b08
-  __TEXT.__swift5_fieldmd: 0x1c60
-  __TEXT.__oslogstring: 0x6da7
+  __TEXT.__swift5_typeref: 0x3b14
+  __TEXT.__swift5_fieldmd: 0x1c84
+  __TEXT.__oslogstring: 0x6e87
   __TEXT.__swift5_types: 0x1b0
   __TEXT.__swift5_proto: 0x2b4
   __TEXT.__swift_as_entry: 0x364
   __TEXT.__swift_as_ret: 0x428
-  __TEXT.__swift5_reflstr: 0x1c03
+  __TEXT.__swift5_reflstr: 0x1c53
   __TEXT.__swift5_assocty: 0x490
   __TEXT.__swift5_protos: 0x2c
   __TEXT.__swift5_builtin: 0xc8
   __TEXT.__swift5_mpenum: 0x80
-  __TEXT.__swift5_capture: 0x6fc
-  __TEXT.__unwind_info: 0x3020
-  __TEXT.__eh_frame: 0x69e0
+  __TEXT.__swift5_capture: 0x788
+  __TEXT.__unwind_info: 0x3050
+  __TEXT.__eh_frame: 0x6a78
   __TEXT.__objc_classname: 0xb8
   __TEXT.__objc_methname: 0xd3b
   __TEXT.__objc_methtype: 0x1d1

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x590
   __DATA_CONST.__objc_protorefs: 0x60
-  __AUTH_CONST.__auth_got: 0x20d0
-  __AUTH_CONST.__const: 0x2b28
+  __AUTH_CONST.__auth_got: 0x2110
+  __AUTH_CONST.__const: 0x2b50
   __AUTH_CONST.__objc_const: 0x2238
   __AUTH.__objc_data: 0x7a0
-  __AUTH.__data: 0x3030
+  __AUTH.__data: 0x3038
   __DATA.__data: 0x2938
   __DATA.__bss: 0x56e0
   __DATA.__common: 0x260

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4654
+  Functions: 4671
   Symbols:   1383
-  CStrings:  903
+  CStrings:  906
 
Symbols:
+ _symbolic Sb19isReadOrReplyIntent_Sb0a4SendcdE0Sb17hasExactSpanMatchypSg7anyTaskt
+ objectdestroy.50Tm
+ objectdestroy.99Tm
- _symbolic Sb19isReadOrReplyIntent_Sb17hasExactSpanMatchypSg7anyTaskt
- objectdestroy.45Tm
- objectdestroy.90Tm
CStrings:
+ "#GuardFlow Mail is Class C data but notification previews are restricted or user is trying to send/reply - need authentication to read emails or present the compose sheet"
+ "#GuardFlow Mail is Class C data, not sending nor replying, and notification previews are not restricted - no need to authenticate"
+ "#ReadMailActingFlow: Unexpected return value from Guard flows: %s"
+ "Unexpected return value from Guard flows: "
+ "ensureAuthenticated"
- "#GuardFlow Mail is Class C data but notification previews are restricted - need authentication to read emails"
- "#GuardFlow Mail is not Class C data, no need to authenticate"
```
