## LocalAuthentication

> `/System/Library/Frameworks/LocalAuthentication.framework/Versions/A/LocalAuthentication`

```diff

-1656.120.5.0.0
-  __TEXT.__text: 0x3bf0c
-  __TEXT.__auth_stubs: 0x940
-  __TEXT.__objc_methlist: 0x34a0
+1656.120.6.0.0
+  __TEXT.__text: 0x3bbe8
+  __TEXT.__auth_stubs: 0x920
+  __TEXT.__objc_methlist: 0x3470
   __TEXT.__const: 0x2f0
   __TEXT.__gcc_except_tab: 0x1330
-  __TEXT.__cstring: 0x1b5e
+  __TEXT.__cstring: 0x1b18
   __TEXT.__dlopen_cstrs: 0x177
   __TEXT.__oslogstring: 0x2cb9
   __TEXT.__swift5_typeref: 0x6e

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x1378
+  __TEXT.__unwind_info: 0x1368
   __TEXT.__eh_frame: 0x48
-  __TEXT.__objc_classname: 0x914
-  __TEXT.__objc_methname: 0x68d4
-  __TEXT.__objc_methtype: 0x1ead
-  __TEXT.__objc_stubs: 0x4740
-  __DATA_CONST.__got: 0x4c0
+  __TEXT.__objc_classname: 0x901
+  __TEXT.__objc_methname: 0x68f5
+  __TEXT.__objc_methtype: 0x1e6d
+  __TEXT.__objc_stubs: 0x4720
+  __DATA_CONST.__got: 0x4c8
   __DATA_CONST.__const: 0x3a8
-  __DATA_CONST.__objc_classlist: 0x240
+  __DATA_CONST.__objc_classlist: 0x238
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b00
+  __DATA_CONST.__objc_selrefs: 0x1b08
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x1c8
   __DATA_CONST.__objc_arraydata: 0x18
-  __AUTH_CONST.__auth_got: 0x4b0
+  __AUTH_CONST.__auth_got: 0x4a0
   __AUTH_CONST.__const: 0x20e0
-  __AUTH_CONST.__cfstring: 0x1980
-  __AUTH_CONST.__objc_const: 0x7e50
+  __AUTH_CONST.__cfstring: 0x1940
+  __AUTH_CONST.__objc_const: 0x7dc0
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH.__objc_data: 0x1680
+  __AUTH.__objc_data: 0x1630
   __DATA.__objc_ivar: 0x28c
   __DATA.__data: 0xc10
   __DATA.__bss: 0x488

   - /usr/lib/swift/libswift_time.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1510
-  Symbols:   3430
-  CStrings:  2024
+  Functions: 1507
+  Symbols:   3420
+  CStrings:  2020
 
Symbols:
+ -[LAContext optionPushButtonUseMaxPreArmAge]
+ -[LAContext setOptionPushButtonUseMaxPreArmAge:]
+ _OBJC_CLASS_$_LACAccessControl
- +[LASecAccessControl allowAllACL]
- +[LASecAccessControl constraintsFromACL:]
- +[LASecAccessControl denyAllACL]
- +[LASecAccessControl deserializeACL:]
- +[LASecAccessControl serializeACL:]
- _CFDictionaryCreateCopy
- _OBJC_CLASS_$_LASecAccessControl
- _OBJC_METACLASS_$_LASecAccessControl
- __OBJC_$_CLASS_METHODS_LASecAccessControl
- __OBJC_CLASS_RO_$_LASecAccessControl
- __OBJC_METACLASS_RO_$_LASecAccessControl
- _objc_exception_throw
- _objc_msgSend$exceptionWithName:reason:userInfo:
CStrings:
+ "optionPushButtonUseMaxPreArmAge"
+ "setOptionPushButtonUseMaxPreArmAge:"
- "@24@0:8^{__SecAccessControl=}16"
- "Could not initialize trivial ACL (%@)"
- "Could note deserialize ACL (%@)"
- "LASecAccessControl"
- "^{__SecAccessControl=}24@0:8@16"
- "exceptionWithName:reason:userInfo:"
```
