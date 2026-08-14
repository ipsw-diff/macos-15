## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/Versions/A/AuthenticationServices`

```diff

-621.2.3.11.1
-  __TEXT.__text: 0x8fa8c
+621.2.4.11.2
+  __TEXT.__text: 0x8fd10
   __TEXT.__auth_stubs: 0x1830
-  __TEXT.__objc_methlist: 0x6ee0
+  __TEXT.__objc_methlist: 0x6f08
   __TEXT.__const: 0x3364
   __TEXT.__cstring: 0x63e6
   __TEXT.__oslogstring: 0x2528
   __TEXT.__ustring: 0x6aba
-  __TEXT.__gcc_except_tab: 0xfa0
+  __TEXT.__gcc_except_tab: 0xff8
   __TEXT.__dlopen_cstrs: 0x1fe
   __TEXT.__swift5_typeref: 0xe34
   __TEXT.__constg_swiftt: 0x9c8

   __TEXT.__swift5_capture: 0x5c
   __TEXT.__swift5_mpenum: 0x48
   __TEXT.__swift5_protos: 0x10
-  __TEXT.__unwind_info: 0x2c18
+  __TEXT.__unwind_info: 0x2c30
   __TEXT.__eh_frame: 0x1228
-  __TEXT.__objc_classname: 0x1c91
-  __TEXT.__objc_methname: 0x13b66
+  __TEXT.__objc_classname: 0x1c8d
+  __TEXT.__objc_methname: 0x13c03
   __TEXT.__objc_methtype: 0x3440
   __TEXT.__objc_stubs: 0xcb60
   __DATA_CONST.__got: 0xb60

   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x210
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x43d0
+  __DATA_CONST.__objc_selrefs: 0x43d8
   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x328
   __DATA_CONST.__objc_arraydata: 0x170
   __AUTH_CONST.__auth_got: 0xc30
-  __AUTH_CONST.__const: 0x4220
+  __AUTH_CONST.__const: 0x4250
   __AUTH_CONST.__cfstring: 0x4520
-  __AUTH_CONST.__objc_const: 0xd6d8
+  __AUTH_CONST.__objc_const: 0xd6f8
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_intobj: 0xa8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x2010
   __AUTH.__data: 0x8d0
-  __DATA.__objc_ivar: 0x71c
+  __DATA.__objc_ivar: 0x720
   __DATA.__data: 0x1fc8
   __DATA.__bss: 0x5380
   __DATA.__common: 0x58

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4116
-  Symbols:   6895
-  CStrings:  4228
+  Functions: 4120
+  Symbols:   6902
+  CStrings:  4230
 
Symbols:
+ +[_ASWebsiteNameProvider debug_fetchWebsiteNameForDomain:completionHandler:]
+ -[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:]
+ -[_ASWebsiteNameProvider _canRefreshDataForDateLastRefreshed:]
+ -[_ASWebsiteNameProvider _fetchDataForDomainIfNeeded:metadataEntry:]
+ -[_ASWebsiteNameProvider _processMetadataEntryFetchedFromKeychain:forDomain:allowRefreshingDataFromNetwork:]
+ GCC_except_table23
+ GCC_except_table75
+ GCC_except_table80
+ GCC_except_table82
+ GCC_except_table84
+ GCC_except_table88
+ GCC_except_table95
+ GCC_except_table96
+ GCC_except_table97
+ OBJC_IVAR_$__ASWebsiteNameProvider._cachedDomainToDateLastRefreshed
+ ___52-[_ASWebsiteNameProvider knownWebsiteNameForDomain:]_block_invoke_4
+ ___68-[_ASWebsiteNameProvider _fetchDataForDomainIfNeeded:metadataEntry:]_block_invoke
+ ___96-[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:]_block_invoke
+ ___block_descriptor_64_ea8_32s40s48s56s_e5_v8?0l
+ ___copy_helper_block_ea8_32s40s48s56s
+ _objc_msgSend$_cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:
+ _objc_msgSend$_canRefreshDataForDateLastRefreshed:
+ _objc_msgSend$_fetchDataForDomainIfNeeded:metadataEntry:
+ _objc_msgSend$_processMetadataEntryFetchedFromKeychain:forDomain:allowRefreshingDataFromNetwork:
- -[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:]
- -[_ASWebsiteNameProvider _processFetchedMetadataEntry:forDomain:]
- GCC_except_table19
- GCC_except_table21
- GCC_except_table74
- GCC_except_table78
- GCC_except_table85
- GCC_except_table91
- GCC_except_table92
- GCC_except_table93
- __ZL42getWBSPrivacyProxyAvailabilityManagerClassv
- ___65-[_ASWebsiteNameProvider _processFetchedMetadataEntry:forDomain:]_block_invoke
- ___78-[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:]_block_invoke
- _objc_msgSend$_cacheFetchedAndKeychainBackedWebsiteName:forDomain:
- _objc_msgSend$_processFetchedMetadataEntry:forDomain:
- _objc_msgSend$safari_isPasswordManagerFamily
- _objc_msgSend$safari_isSafariPlatformSupportHelper
CStrings:
+ "_cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:"
+ "_cachedDomainToDateLastRefreshed"
+ "_canRefreshDataForDateLastRefreshed:"
+ "_fetchDataForDomainIfNeeded:metadataEntry:"
+ "_processMetadataEntryFetchedFromKeychain:forDomain:allowRefreshingDataFromNetwork:"
+ "debug_fetchWebsiteNameForDomain:completionHandler:"
- "_cacheFetchedAndKeychainBackedWebsiteName:forDomain:"
- "_processFetchedMetadataEntry:forDomain:"
- "safari_isPasswordManagerFamily"
- "safari_isSafariPlatformSupportHelper"
```
