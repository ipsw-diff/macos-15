## SiriMailInternal

> `/System/Library/PrivateFrameworks/SiriMailInternal.framework/Versions/A/SiriMailInternal`

```diff

-3405.4.1.0.0
-  __TEXT.__text: 0xf8f40
-  __TEXT.__auth_stubs: 0x4140
+3405.8.1.0.0
+  __TEXT.__text: 0xfb6b0
+  __TEXT.__auth_stubs: 0x41a0
   __TEXT.__objc_methlist: 0x334
-  __TEXT.__const: 0x6310
+  __TEXT.__const: 0x6320
   __TEXT.__cstring: 0x2364
-  __TEXT.__constg_swiftt: 0x2360
-  __TEXT.__swift5_typeref: 0x3ac0
-  __TEXT.__swift5_fieldmd: 0x1c54
-  __TEXT.__oslogstring: 0x6cf7
+  __TEXT.__constg_swiftt: 0x2368
+  __TEXT.__swift5_typeref: 0x3b08
+  __TEXT.__swift5_fieldmd: 0x1c60
+  __TEXT.__oslogstring: 0x6da7
   __TEXT.__swift5_types: 0x1b0
   __TEXT.__swift5_proto: 0x2b4
   __TEXT.__swift_as_entry: 0x364
   __TEXT.__swift_as_ret: 0x428
-  __TEXT.__swift5_reflstr: 0x1be3
+  __TEXT.__swift5_reflstr: 0x1c03
   __TEXT.__swift5_assocty: 0x490
   __TEXT.__swift5_protos: 0x2c
   __TEXT.__swift5_builtin: 0xc8
   __TEXT.__swift5_mpenum: 0x80
-  __TEXT.__swift5_capture: 0x6ec
-  __TEXT.__unwind_info: 0x2ff0
-  __TEXT.__eh_frame: 0x69a8
+  __TEXT.__swift5_capture: 0x6fc
+  __TEXT.__unwind_info: 0x3020
+  __TEXT.__eh_frame: 0x69e0
   __TEXT.__objc_classname: 0xb8
   __TEXT.__objc_methname: 0xd3b
   __TEXT.__objc_methtype: 0x1d1
-  __DATA_CONST.__got: 0x1360
+  __DATA_CONST.__got: 0x1368
   __DATA_CONST.__const: 0x138
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x590
   __DATA_CONST.__objc_protorefs: 0x60
-  __AUTH_CONST.__auth_got: 0x20a0
+  __AUTH_CONST.__auth_got: 0x20d0
   __AUTH_CONST.__const: 0x2b28
   __AUTH_CONST.__objc_const: 0x2238
   __AUTH.__objc_data: 0x7a0
-  __AUTH.__data: 0x3028
-  __DATA.__data: 0x2910
+  __AUTH.__data: 0x3030
+  __DATA.__data: 0x2938
   __DATA.__bss: 0x56e0
   __DATA.__common: 0x260
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
+  - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswift_errno.dylib
   - /usr/lib/swift/libswift_math.dylib
   - /usr/lib/swift/libswift_signal.dylib

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4624
-  Symbols:   1377
-  CStrings:  900
+  Functions: 4654
+  Symbols:   1383
+  CStrings:  903
 
Symbols:
+ __swiftEmptyDictionarySingleton
+ _symbolic SS3key______5valuet 13SiriInference7ContactV
+ _symbolic SaySSG
+ _symbolic Say_____G 13SiriInference13ContactHandleV
+ _symbolic _____ySS_____G s17_NativeDictionaryV 13SiriInference7ContactV
+ _symbolic _____ySay_____GG s23_ContiguousArrayStorageC 13SiriInference13ContactHandleV
+ objectdestroy.5Tm
- objectdestroy.2Tm
CStrings:
+ "#ResolveRecipientsFlow alternateState: %s"
+ "#ResolveRecipientsFlow found 1 handle match"
+ "#ResolveRecipientsFlow found multiple contact matches"
+ "#ResolveRecipientsFlow found multiple handle matches"
+ "#ResolveRecipientsFlow one contact match from Contacts and at least one match from Mail, disambiguating together"
+ "#ResolveRecipientsFlow one exact match from Contacts and at least one match from Mail, disambiguating together"
- "#ResolveRecipientsFlow found at least one match from Mail, disambiguating alongside Contact recommendations: %s"
- "#ResolveRecipientsFlow no match from ContactResolver, found 1 match from Mail"
- "#ResolveRecipientsFlow no match from ContactResolver, found multiple matches from Mail: %s"
```
