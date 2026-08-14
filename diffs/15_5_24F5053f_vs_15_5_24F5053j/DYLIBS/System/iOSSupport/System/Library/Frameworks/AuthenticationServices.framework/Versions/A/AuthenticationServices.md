## AuthenticationServices

> `/System/iOSSupport/System/Library/Frameworks/AuthenticationServices.framework/Versions/A/AuthenticationServices`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__objc_classname`

```diff

-621.2.3.11.1
-  __TEXT.__text: 0x5dacc
+621.2.4.11.2
+  __TEXT.__text: 0x5d968
   __TEXT.__auth_stubs: 0x1690
-  __TEXT.__objc_methlist: 0x4270
-  __TEXT.__const: 0x2d54
+  __TEXT.__objc_methlist: 0x4298
+  __TEXT.__const: 0x2d34
   __TEXT.__gcc_except_tab: 0xc74
-  __TEXT.__oslogstring: 0x1411
+  __TEXT.__oslogstring: 0x12e1
   __TEXT.__cstring: 0x3a56
   __TEXT.__dlopen_cstrs: 0x1a1
   __TEXT.__ustring: 0x31cc

   __TEXT.__unwind_info: 0x2018
   __TEXT.__eh_frame: 0x1040
   __TEXT.__objc_classname: 0x1306
-  __TEXT.__objc_methname: 0xabb8
-  __TEXT.__objc_methtype: 0x1ae7
-  __TEXT.__objc_stubs: 0x5c20
-  __DATA_CONST.__got: 0x738
-  __DATA_CONST.__const: 0x1090
+  __TEXT.__objc_methname: 0xac60
+  __TEXT.__objc_methtype: 0x1af8
+  __TEXT.__objc_stubs: 0x5c00
+  __DATA_CONST.__got: 0x730
+  __DATA_CONST.__const: 0x10b8
   __DATA_CONST.__objc_classlist: 0x2d8
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2148
+  __DATA_CONST.__objc_selrefs: 0x2158
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x220
   __DATA_CONST.__objc_arraydata: 0x140
   __AUTH_CONST.__auth_got: 0xb60
-  __AUTH_CONST.__const: 0x1ff0
+  __AUTH_CONST.__const: 0x1fd0
   __AUTH_CONST.__cfstring: 0x2780
-  __AUTH_CONST.__objc_const: 0x9108
+  __AUTH_CONST.__objc_const: 0x9128
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH.__objc_data: 0x1430
   __AUTH.__data: 0x8d0
-  __DATA.__objc_ivar: 0x4f0
+  __DATA.__objc_ivar: 0x4f4
   __DATA.__data: 0x1730
   __DATA.__bss: 0x4c50
   __DATA.__common: 0x18

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2881
-  Symbols:   4196
+  Functions: 2879
+  Symbols:   4198
   CStrings:  2324
 
Symbols:
+ +[_ASWebsiteNameProvider debug_fetchWebsiteNameForDomain:completionHandler:]
+ -[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:]
+ -[_ASWebsiteNameProvider _canRefreshDataForDateLastRefreshed:]
+ -[_ASWebsiteNameProvider _fetchDataForDomainIfNeeded:metadataEntry:]
+ -[_ASWebsiteNameProvider _processMetadataEntryFetchedFromKeychain:forDomain:allowRefreshingDataFromNetwork:]
+ GCC_except_table27
+ GCC_except_table60
+ GCC_except_table62
+ GCC_except_table64
+ GCC_except_table67
+ GCC_except_table69
+ OBJC_IVAR_$__ASWebsiteNameProvider._cachedDomainToDateLastRefreshed
+ ___52-[_ASWebsiteNameProvider knownWebsiteNameForDomain:]_block_invoke_5
+ ___68-[_ASWebsiteNameProvider _fetchDataForDomainIfNeeded:metadataEntry:]_block_invoke
+ ___96-[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:]_block_invoke
+ ___block_descriptor_40_ea8_32s_e38_B16?0"_ASWebsiteNameFetchOperation"8ls32l8
+ ___block_descriptor_64_ea8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ _objc_msgSend$_cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:
+ _objc_msgSend$_canRefreshDataForDateLastRefreshed:
+ _objc_msgSend$_processMetadataEntryFetchedFromKeychain:forDomain:allowRefreshingDataFromNetwork:
+ _objc_msgSend$operations
+ _objc_msgSend$safari_containsObjectPassingTest:
+ _objc_msgSend$websiteNameDateLastRefreshed
- -[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:]
- -[_ASWebsiteNameProvider _processFetchedMetadataEntry:forDomain:]
- GCC_except_table25
- GCC_except_table31
- GCC_except_table36
- GCC_except_table59
- GCC_except_table61
- _OBJC_CLASS_$_LPMetadataProvider
- __70+[_ASWebsiteNameProvider fetchWebsiteNameForDomain:completionHandler:]_block_invoke
- __ZZL35isProcessAllowedToFetchWebsiteNamesvE9onceToken
- ___70+[_ASWebsiteNameProvider fetchWebsiteNameForDomain:completionHandler:]_block_invoke
- ___78-[_ASWebsiteNameProvider _cacheFetchedAndKeychainBackedWebsiteName:forDomain:]_block_invoke
- ____ZL35isProcessAllowedToFetchWebsiteNamesv_block_invoke
- ___block_descriptor_56_ea8_32s40bs_e36_v24?0"LPLinkMetadata"8"NSError"16ls32l8s40l8
- _objc_msgSend$_cacheFetchedAndKeychainBackedWebsiteName:forDomain:
- _objc_msgSend$_processFetchedMetadataEntry:forDomain:
- _objc_msgSend$setRequirePrivateRelayForAllNetworkTraffic:
- _objc_msgSend$setShouldFetchSubresources:
- _objc_msgSend$setTimeout:
- _objc_msgSend$startFetchingMetadataForURL:completionHandler:
- _objc_msgSend$websiteNameForLinkMetadata:
CStrings:
+ "B16@?0@\"_ASWebsiteNameFetchOperation\"8"
+ "_cacheFetchedAndKeychainBackedWebsiteName:forDomain:dateLastRefreshed:"
+ "_cachedDomainToDateLastRefreshed"
+ "_canRefreshDataForDateLastRefreshed:"
+ "_fetchDataForDomainIfNeeded:metadataEntry:"
+ "_processMetadataEntryFetchedFromKeychain:forDomain:allowRefreshingDataFromNetwork:"
+ "debug_fetchWebsiteNameForDomain:completionHandler:"
+ "operations"
+ "safari_containsObjectPassingTest:"
+ "v36@0:8@16@24B32"
+ "websiteNameDateLastRefreshed"
- "Fetch for %{sensitive}@ failed with error %@"
- "Starting fetch for %{sensitive}@\n"
- "WebsiteNameProvider found \"%{sensitive}@\" as a website name for domain \"%{sensitive}@\""
- "WebsiteNameProvider got metadata for domain \"%{sensitive}@\": siteName: %{sensitive}@, title: %{sensitive}@, originalTitle: %{sensitive}@"
- "_cacheFetchedAndKeychainBackedWebsiteName:forDomain:"
- "_processFetchedMetadataEntry:forDomain:"
- "setRequirePrivateRelayForAllNetworkTraffic:"
- "setShouldFetchSubresources:"
- "setTimeout:"
- "startFetchingMetadataForURL:completionHandler:"
- "v24@?0@\"LPLinkMetadata\"8@\"NSError\"16"
```
