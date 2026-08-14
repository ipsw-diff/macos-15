## liblog_location.dylib

> `/usr/lib/log/liblog_location.dylib`

```diff

-2960.0.61.0.0
-  __TEXT.__text: 0x5bf0
-  __TEXT.__auth_stubs: 0x260
+2964.0.3.0.0
+  __TEXT.__text: 0x5cc4
+  __TEXT.__auth_stubs: 0x270
   __TEXT.__objc_methlist: 0x32c
   __TEXT.__const: 0x70
   __TEXT.__gcc_except_tab: 0x44
-  __TEXT.__cstring: 0x3873
+  __TEXT.__cstring: 0x3897
   __TEXT.__unwind_info: 0x150
   __TEXT.__objc_classname: 0xf
-  __TEXT.__objc_methname: 0x1004
-  __TEXT.__objc_methtype: 0xb4
+  __TEXT.__objc_methname: 0x1017
+  __TEXT.__objc_methtype: 0xc0
   __TEXT.__objc_stubs: 0x6c0
   __DATA_CONST.__got: 0x98
   __DATA_CONST.__const: 0x920

   __DATA_CONST.__objc_selrefs: 0x370
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__objc_arraydata: 0xa0
-  __AUTH_CONST.__auth_got: 0x148
+  __AUTH_CONST.__auth_got: 0x150
   __AUTH_CONST.__const: 0x50
   __AUTH_CONST.__cfstring: 0x4600
-  __AUTH_CONST.__objc_const: 0xf8
+  __AUTH_CONST.__objc_const: 0x118
   __AUTH_CONST.__objc_dictobj: 0xc8
-  __DATA.__objc_ivar: 0xc
+  __DATA.__objc_ivar: 0x10
   __DATA.__data: 0x820
   __DATA_DIRTY.__objc_data: 0x50
   __DATA_DIRTY.__bss: 0x10

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 83
-  Symbols:   480
-  CStrings:  687
+  Symbols:   482
+  CStrings:  691
 
Symbols:
+ OBJC_IVAR_$_CLLogFormatter._encryptionKeyPath
+ __ZL20extractEncryptedDataP11objc_objectPmP8NSStringPP8NSObject
+ _getenv
- __ZL20extractEncryptedDataP11objc_objectPmPP8NSObject
Functions:
~ -[CLLogFormatter init] : 156 -> 216
~ -[CLLogFormatter dealloc] : 104 -> 116
~ -[CLLogFormatter JSONObjectWith_Encrypted_latitude:info:] : 184 -> 192
~ -[CLLogFormatter JSONObjectWith_Encrypted_longitude:info:] : 184 -> 192
~ -[CLLogFormatter JSONObjectWith_Encrypted_CLLocationCoordinate2D:info:] : 224 -> 232
~ __ZL20extractEncryptedDataP11objc_objectPmPP8NSObject -> __ZL20extractEncryptedDataP11objc_objectPmP8NSStringPP8NSObject : 880 -> 992
~ -[CLLogFormatter JSONObjectWith_Encrypted_CLClientLocation:info:] : 192 -> 196
CStrings:
+ "%04d_%03d"
+ "@\"NSString\""
+ "CLLOG_ENCRYPTION_KEY_PATH"
+ "_encryptionKeyPath"
```
