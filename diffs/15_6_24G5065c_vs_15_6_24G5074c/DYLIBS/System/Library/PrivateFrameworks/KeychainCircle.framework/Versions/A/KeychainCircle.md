## KeychainCircle

> `/System/Library/PrivateFrameworks/KeychainCircle.framework/Versions/A/KeychainCircle`

```diff

-61439.140.10.0.0
-  __TEXT.__text: 0x2c570
+61439.140.10.0.1
+  __TEXT.__text: 0x2cb78
   __TEXT.__auth_stubs: 0xe60
-  __TEXT.__objc_methlist: 0x1d44
+  __TEXT.__objc_methlist: 0x1dbc
   __TEXT.__const: 0x100
   __TEXT.__dlopen_cstrs: 0x1aa
-  __TEXT.__gcc_except_tab: 0x15f0
-  __TEXT.__cstring: 0x2de2
-  __TEXT.__oslogstring: 0x3822
+  __TEXT.__gcc_except_tab: 0x1670
+  __TEXT.__cstring: 0x2e28
+  __TEXT.__oslogstring: 0x38d0
   __TEXT.__ustring: 0x32
   __TEXT.__unwind_info: 0x8b8
-  __TEXT.__objc_classname: 0x2e4
-  __TEXT.__objc_methname: 0x40d5
-  __TEXT.__objc_methtype: 0xf52
-  __TEXT.__objc_stubs: 0x2ea0
+  __TEXT.__objc_classname: 0x2e6
+  __TEXT.__objc_methname: 0x41a3
+  __TEXT.__objc_methtype: 0xf62
+  __TEXT.__objc_stubs: 0x2f40
   __DATA_CONST.__got: 0x2b8
   __DATA_CONST.__const: 0x920
   __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfe8
+  __DATA_CONST.__objc_selrefs: 0x1018
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x88
   __AUTH_CONST.__auth_got: 0x740
   __AUTH_CONST.__const: 0xa20
-  __AUTH_CONST.__cfstring: 0x3240
-  __AUTH_CONST.__objc_const: 0x2ac0
+  __AUTH_CONST.__cfstring: 0x32a0
+  __AUTH_CONST.__objc_const: 0x2b80
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH.__objc_data: 0x690
-  __DATA.__objc_ivar: 0x1f8
+  __DATA.__objc_ivar: 0x208
   __DATA.__data: 0x318
   __DATA.__bss: 0x1a8
   __DATA.__common: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 815
-  Symbols:   2167
-  CStrings:  1587
+  Functions: 825
+  Symbols:   2186
+  CStrings:  1603
 
Symbols:
+ -[KCJoiningAcceptSession piggybacking_version_for_tests]
+ -[KCJoiningAcceptSession setPiggybackingVersion:]
+ -[KCJoiningAcceptSession setPiggybacking_version_for_tests:]
+ -[KCJoiningRequestCircleSession piggybacking_version_for_tests]
+ -[KCJoiningRequestCircleSession setPiggybackingVersion:]
+ -[KCJoiningRequestCircleSession setPiggybacking_version_for_tests:]
+ -[OTPairingMessage hasVersion]
+ -[OTPairingMessage setHasVersion:]
+ -[OTPairingMessage setVersion:]
+ -[OTPairingMessage version]
+ GCC_except_table358
+ GCC_except_table428
+ GCC_except_table435
+ GCC_except_table569
+ GCC_except_table578
+ GCC_except_table580
+ GCC_except_table630
+ GCC_except_table634
+ GCC_except_table639
+ OBJC_IVAR_$_KCJoiningAcceptSession._piggybacking_version_for_tests
+ OBJC_IVAR_$_KCJoiningRequestCircleSession._piggybacking_version_for_tests
+ OBJC_IVAR_$_OTPairingMessage._has
+ OBJC_IVAR_$_OTPairingMessage._version
+ ___block_descriptor_56_e8_32s40r48r_e74_v56?0"NSString"8"NSData"16"NSData"24"NSData"32"NSData"40"NSError"48l
+ _objc_msgSend$hasVersion
+ _objc_msgSend$piggybacking_version_for_tests
+ _objc_msgSend$setPiggybacking_version_for_tests:
+ _objc_msgSend$setVersion:
+ _objc_msgSend$version
- GCC_except_table354
- GCC_except_table422
- GCC_except_table429
- GCC_except_table559
- GCC_except_table568
- GCC_except_table570
- GCC_except_table620
- GCC_except_table624
- GCC_except_table629
- ___block_descriptor_48_e8_32r40r_e74_v56?0"NSString"8"NSData"16"NSData"24"NSData"32"NSData"40"NSError"48l
CStrings:
+ "TQ,N,V_piggybacking_version_for_tests"
+ "TQ,N,V_version"
+ "Unexpected piggybacking version"
+ "_piggybacking_version_for_tests"
+ "_version"
+ "failed to decrypt voucher packet, fall back to legacy path, error: %@"
+ "failed to encrypt the voucher"
+ "hasVersion"
+ "joining: failed to encrypt voucher payload: %@"
+ "joining: unexpected piggybacking version, received: %llu"
+ "piggybacking_version_for_tests"
+ "setHasVersion:"
+ "setPiggybacking_version_for_tests:"
+ "setVersion:"
+ "version"
+ "{?=\"version\"b1}"
```
