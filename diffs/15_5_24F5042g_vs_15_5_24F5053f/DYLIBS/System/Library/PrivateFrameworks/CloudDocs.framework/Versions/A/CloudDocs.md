## CloudDocs

> `/System/Library/PrivateFrameworks/CloudDocs.framework/Versions/A/CloudDocs`

```diff

-3437.120.2.0.0
-  __TEXT.__text: 0x98148
+3437.120.13.0.1
+  __TEXT.__text: 0x9833c
   __TEXT.__auth_stubs: 0x1330
-  __TEXT.__objc_methlist: 0x6b04
+  __TEXT.__objc_methlist: 0x6b1c
   __TEXT.__const: 0x1d8
   __TEXT.__gcc_except_tab: 0x4ee4
-  __TEXT.__cstring: 0xb043
+  __TEXT.__cstring: 0xb085
   __TEXT.__oslogstring: 0x9350
   __TEXT.__dlopen_cstrs: 0x4c
   __TEXT.__ustring: 0x10
-  __TEXT.__unwind_info: 0x27d8
+  __TEXT.__unwind_info: 0x27d0
   __TEXT.__objc_classname: 0xe2e
-  __TEXT.__objc_methname: 0x11789
-  __TEXT.__objc_methtype: 0x44bc
-  __TEXT.__objc_stubs: 0xb1e0
+  __TEXT.__objc_methname: 0x11813
+  __TEXT.__objc_methtype: 0x44cd
+  __TEXT.__objc_stubs: 0xb220
   __DATA_CONST.__got: 0x8b8
   __DATA_CONST.__const: 0xb00
   __DATA_CONST.__objc_classlist: 0x310
   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x130
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4338
+  __DATA_CONST.__objc_selrefs: 0x4350
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_classrefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x268
   __DATA_CONST.__objc_arraydata: 0x30
   __AUTH_CONST.__auth_got: 0x9a8
   __AUTH_CONST.__const: 0x3000
-  __AUTH_CONST.__cfstring: 0x5a20
+  __AUTH_CONST.__cfstring: 0x5a60
   __AUTH_CONST.__objc_const: 0xe168
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x4f8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3152
-  Symbols:   6803
-  CStrings:  5503
+  Functions: 3154
+  Symbols:   6807
+  CStrings:  5509
 
Symbols:
+ +[NSError(BRAdditions) brc_genericDownloadErrorWithUnderlyingError:]
+ -[NSError(BRAdditions) br_isGenericDownloadError]
+ -[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:]
+ __91-[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:]_block_invoke
+ ___91-[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:]_block_invoke
+ ___91-[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:]_block_invoke_2
+ _br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:.brUserInfoKeyToBRErrorCodeFPUserInfoKeyMap
+ _br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:.brUserInfoKeyToFPUserInfoKey
+ _br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:.once
+ _objc_msgSend$_br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:
+ _objc_msgSend$br_isGenericDownloadError
+ _objc_msgSend$brc_errorWithDomain:code:underlyingError:
- -[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:]
- __66-[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:]_block_invoke
- ___66-[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:]_block_invoke
- ___66-[NSError(BRFPAdditions) _br_populateUserInfoDictWithDomain:code:]_block_invoke_2
- _br_populateUserInfoDictWithDomain:code:.brUserInfoKeyToBRErrorCodeFPUserInfoKeyMap
- _br_populateUserInfoDictWithDomain:code:.brUserInfoKeyToFPUserInfoKey
- _br_populateUserInfoDictWithDomain:code:.once
- _objc_msgSend$_br_populateUserInfoDictWithDomain:code:
CStrings:
+ "3437.120.13.0.1"
+ "@36@0:8@16q24B32"
+ "DOWNLOAD_GENERIC_ERROR_HEADER"
+ "DOWNLOAD_GENERIC_ERROR_MESSAGE"
+ "_br_populateUserInfoDictWithDomain:code:setSelfAsUnderlyingError:"
+ "br_isGenericDownloadError"
+ "brc_errorWithDomain:code:underlyingError:"
+ "brc_genericDownloadErrorWithUnderlyingError:"
- "3437.120.2"
- "_br_populateUserInfoDictWithDomain:code:"
```
