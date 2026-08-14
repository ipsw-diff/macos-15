## AdCore

> `/System/Library/PrivateFrameworks/AdCore.framework/Versions/A/AdCore`

```diff

-636.4.1.0.0
-  __TEXT.__text: 0x2cff8
+636.4.3.0.0
+  __TEXT.__text: 0x2d0dc
   __TEXT.__auth_stubs: 0x730
-  __TEXT.__objc_methlist: 0x3d4c
+  __TEXT.__objc_methlist: 0x3d64
   __TEXT.__const: 0x188
-  __TEXT.__cstring: 0x3b23
+  __TEXT.__cstring: 0x3b51
   __TEXT.__gcc_except_tab: 0x448
   __TEXT.__ustring: 0x4
   __TEXT.__oslogstring: 0x53
   __TEXT.__unwind_info: 0xb68
   __TEXT.__objc_classname: 0x3a1
-  __TEXT.__objc_methname: 0x6e3c
+  __TEXT.__objc_methname: 0x6e74
   __TEXT.__objc_methtype: 0xa9f
-  __TEXT.__objc_stubs: 0x3c60
+  __TEXT.__objc_stubs: 0x3ca0
   __DATA_CONST.__got: 0x348
   __DATA_CONST.__const: 0x3d8
   __DATA_CONST.__objc_classlist: 0x140
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1e30
+  __DATA_CONST.__objc_selrefs: 0x1e40
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x140
   __DATA_CONST.__objc_arraydata: 0x188
   __AUTH_CONST.__auth_got: 0x3a8
   __AUTH_CONST.__const: 0x6e0
-  __AUTH_CONST.__cfstring: 0x4820
-  __AUTH_CONST.__objc_const: 0x5710
+  __AUTH_CONST.__cfstring: 0x4860
+  __AUTH_CONST.__objc_const: 0x5740
   __AUTH_CONST.__objc_intobj: 0x408
   __AUTH_CONST.__objc_dictobj: 0x280
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH.__objc_data: 0x730
-  __DATA.__objc_ivar: 0x3b0
+  __DATA.__objc_ivar: 0x3b4
   __DATA.__data: 0x1e0
   __DATA.__bss: 0x48
   __DATA_DIRTY.__objc_data: 0x550

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1363
-  Symbols:   2745
-  CStrings:  2035
+  Functions: 1365
+  Symbols:   2750
+  CStrings:  2040
 
Symbols:
+ -[DSIDRecord isProtoU13]
+ -[DSIDRecord setIsProtoU13:]
+ OBJC_IVAR_$_DSIDRecord._isProtoU13
+ _objc_msgSend$isProtoU13
+ _objc_msgSend$setIsProtoU13:
Functions:
~ -[DSIDRecord initWithDSID:serializedRecord:version:] : 1648 -> 1692
~ -[DSIDRecord copyWithZone:] : 632 -> 652
~ -[DSIDRecord dictionaryRepresentation] : 1568 -> 1632
~ -[DSIDRecord _parseItunesFlags] : 1012 -> 1076
+ -[DSIDRecord setLastJingleAccountStatus:]
+ -[DSIDRecord iAdIDBeforeReset]
CStrings:
+ "TB,N,V_isProtoU13"
+ "_isProtoU13"
+ "isProtoU13"
+ "kADDSIDRecord_AccountIsProtoU13Key"
+ "setIsProtoU13:"
```
