## LocalAuthenticationCore

> `/System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/Versions/A/LocalAuthenticationCore`

```diff

-1656.120.5.0.0
-  __TEXT.__text: 0xd3690
-  __TEXT.__auth_stubs: 0x1e60
-  __TEXT.__objc_methlist: 0x7a68
-  __TEXT.__const: 0x3ac4
-  __TEXT.__cstring: 0xb0f6
+1656.120.6.0.0
+  __TEXT.__text: 0xd3f50
+  __TEXT.__auth_stubs: 0x1e90
+  __TEXT.__objc_methlist: 0x7ae8
+  __TEXT.__const: 0x3b14
+  __TEXT.__cstring: 0xb256
   __TEXT.__oslogstring: 0x5488
   __TEXT.__gcc_except_tab: 0x1104
   __TEXT.__dlopen_cstrs: 0x1b0

   __TEXT.__swift_as_entry: 0xc8
   __TEXT.__swift_as_ret: 0xd4
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0x3818
+  __TEXT.__unwind_info: 0x3838
   __TEXT.__eh_frame: 0x20e8
-  __TEXT.__objc_classname: 0x1d14
-  __TEXT.__objc_methname: 0xbdde
-  __TEXT.__objc_methtype: 0x3342
-  __TEXT.__objc_stubs: 0x8600
+  __TEXT.__objc_classname: 0x1d2e
+  __TEXT.__objc_methname: 0xbe85
+  __TEXT.__objc_methtype: 0x33b0
+  __TEXT.__objc_stubs: 0x8680
   __DATA_CONST.__got: 0x8b0
-  __DATA_CONST.__const: 0x2158
-  __DATA_CONST.__objc_classlist: 0x700
+  __DATA_CONST.__const: 0x22f8
+  __DATA_CONST.__objc_classlist: 0x708
   __DATA_CONST.__objc_protolist: 0x518
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2d88
+  __DATA_CONST.__objc_selrefs: 0x2dc8
   __DATA_CONST.__objc_protorefs: 0x220
-  __DATA_CONST.__objc_superrefs: 0x448
+  __DATA_CONST.__objc_superrefs: 0x450
   __DATA_CONST.__objc_arraydata: 0x40
-  __AUTH_CONST.__auth_got: 0xf40
+  __AUTH_CONST.__auth_got: 0xf58
   __AUTH_CONST.__const: 0x4fe8
-  __AUTH_CONST.__cfstring: 0x4d00
-  __AUTH_CONST.__objc_const: 0x30168
+  __AUTH_CONST.__cfstring: 0x54c0
+  __AUTH_CONST.__objc_const: 0x30268
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH.__objc_data: 0x4d98
+  __AUTH.__objc_data: 0x4de8
   __AUTH.__data: 0xcd0
-  __DATA.__objc_ivar: 0x714
+  __DATA.__objc_ivar: 0x71c
   __DATA.__data: 0x41d8
   __DATA.__bss: 0x20a1
   __DATA.__common: 0xb8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 5251
-  Symbols:   11897
-  CStrings:  4663
+  Functions: 5262
+  Symbols:   11985
+  CStrings:  4737
 
Symbols:
+ +[LACAccessControl _checkConstraints:contain:]
+ +[LACAccessControl checkACL:hasConstraint:forOperation:]
+ +[LACAccessControl constraintsFromACL:]
+ +[LACAccessControl denyAllACL]
+ +[LACAccessControl deserializeACL:]
+ +[LACAccessControl serializeACL:]
+ -[LACAccessControlOperation .cxx_destruct]
+ -[LACAccessControlOperation initWithTypeErasedOperation:]
+ -[LACAccessControlOperation keyOp]
+ -[LACAccessControlOperation rawValue]
+ OBJC_IVAR_$_LACAccessControlOperation._aksOp
+ OBJC_IVAR_$_LACAccessControlOperation._rawValue
+ _CFDictionaryCreateCopy
+ _LACAccessControlOperationRawValueACL
+ _LACAccessControlOperationRawValueAKS
+ _LACAccessControlOperationRawValueCreateItem
+ _LACAccessControlOperationRawValueCreateKey
+ _LACAccessControlOperationRawValueUseItem
+ _LACAccessControlOperationRawValueUseKeyDecrypt
+ _LACAccessControlOperationRawValueUseKeyKeyExchange
+ _LACAccessControlOperationRawValueUseKeySign
+ _LACPolicyOptionPushButtonUseMaxPreArmAge
+ _NSStringFromLACAccessControlOperationRawValue
+ _OBJC_CLASS_$_LACAccessControlOperation
+ _OBJC_METACLASS_$_LACAccessControlOperation
+ _SecAccessControlCreate
+ _SecAccessControlSetConstraints
+ __OBJC_$_INSTANCE_METHODS_LACAccessControlOperation
+ __OBJC_$_INSTANCE_VARIABLES_LACAccessControlOperation
+ __OBJC_$_PROP_LIST_LACAccessControlOperation
+ __OBJC_CLASS_RO_$_LACAccessControlOperation
+ __OBJC_METACLASS_RO_$_LACAccessControlOperation
+ _kAKSKeyACMHandle
+ _kAKSKeyAccessGroups
+ _kAKSKeyAcl
+ _kAKSKeyAclConstraintAccessGroups
+ _kAKSKeyAclConstraintBio
+ _kAKSKeyAclConstraintKofN
+ _kAKSKeyAclConstraintOpBool
+ _kAKSKeyAclConstraintPolicy
+ _kAKSKeyAclConstraintUserPasscode
+ _kAKSKeyAclParamCredentialMaxAge
+ _kAKSKeyAclParamKofN
+ _kAKSKeyAclParamRequirePasscode
+ _kAKSKeyAuthData
+ _kAKSKeyBagId
+ _kAKSKeyData
+ _kAKSKeyExternalData
+ _kAKSKeyFlags
+ _kAKSKeyIterations
+ _kAKSKeyKeybagClass
+ _kAKSKeyKeybagHandle
+ _kAKSKeyOpAttest
+ _kAKSKeyOpComputeKey
+ _kAKSKeyOpCreate
+ _kAKSKeyOpDecrypt
+ _kAKSKeyOpDefaultAcl
+ _kAKSKeyOpDelete
+ _kAKSKeyOpECIESDecrypt
+ _kAKSKeyOpECIESEncrypt
+ _kAKSKeyOpECIESTranscode
+ _kAKSKeyOpEncrpyt
+ _kAKSKeyOpEncrypt
+ _kAKSKeyOpKEMDecapsulate
+ _kAKSKeyOpKEMEncapsulate
+ _kAKSKeyOpSetKeyClass
+ _kAKSKeyOpSign
+ _kAKSKeyOpSync
+ _kAKSKeyOpTranscrypt
+ _kAKSKeyOpUnwrap
+ _kAKSKeyOpWrap
+ _kAKSKeyOperation
+ _kAKSKeyPad
+ _kAKSKeyPasscode
+ _kAKSKeyProtectedData
+ _kAKSKeyPublicKey
+ _kAKSKeyRefKey
+ _kAKSKeyRefKeyMac
+ _kAKSKeySalt
+ _kAKSKeyTag
+ _kAKSKeyType
+ _kAKSKeyUUID
+ _kAKSKeyVersion
+ _kAKSKeyWrappedKey
+ _objc_msgSend$_checkConstraints:contain:
+ _objc_msgSend$constraintsFromACL:
+ _objc_msgSend$deserializeACL:
+ _objc_msgSend$keyOp
CStrings:
+ "@24@0:8^{__SecAccessControl=}16"
+ "ACL"
+ "AKS"
+ "B40@0:8@16@24@32"
+ "Could not initialize trivial ACL (%@)"
+ "Could note deserialize ACL (%@)"
+ "CreateItem"
+ "CreateKey"
+ "LACAccessControlOperation"
+ "UseItem"
+ "UseKeyDecrypt"
+ "UseKeyKeyExchange"
+ "UseKeySign"
+ "^{__SecAccessControl=}16@0:8"
+ "^{__SecAccessControl=}24@0:8@16"
+ "_aksOp"
+ "_checkConstraints:contain:"
+ "acmh"
+ "ad"
+ "ag"
+ "bc"
+ "bh"
+ "bid"
+ "cag"
+ "cbio"
+ "checkACL:hasConstraint:forOperation:"
+ "ckon"
+ "cob"
+ "constraintsFromACL:"
+ "cpo"
+ "cup"
+ "dacl"
+ "denyAllACL"
+ "deserializeACL:"
+ "ed"
+ "f"
+ "initWithTypeErasedOperation:"
+ "iter"
+ "keyOp"
+ "kid"
+ "kt"
+ "kv"
+ "o"
+ "oa"
+ "oacl"
+ "oc"
+ "ock"
+ "od"
+ "odel"
+ "oe"
+ "oecd"
+ "oece"
+ "oect"
+ "okd"
+ "oke"
+ "orwk"
+ "os"
+ "osgn"
+ "oskc"
+ "ouw"
+ "ow"
+ "p"
+ "pad"
+ "pcma"
+ "pd"
+ "pkofn"
+ "prp"
+ "pub"
+ "rk"
+ "rkm"
+ "salt"
+ "serializeACL:"
+ "tag"
+ "wk"
```
