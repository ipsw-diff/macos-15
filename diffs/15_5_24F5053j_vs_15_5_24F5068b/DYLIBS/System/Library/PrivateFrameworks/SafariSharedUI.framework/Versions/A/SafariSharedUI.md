## SafariSharedUI

> `/System/Library/PrivateFrameworks/SafariSharedUI.framework/Versions/A/SafariSharedUI`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-621.2.4.11.2
-  __TEXT.__text: 0xfe86c
+621.2.5.11.5
+  __TEXT.__text: 0xfeb60
   __TEXT.__auth_stubs: 0xfe0
-  __TEXT.__objc_methlist: 0xbe20
+  __TEXT.__objc_methlist: 0xbe18
   __TEXT.__const: 0x2b28
-  __TEXT.__oslogstring: 0x7f62
+  __TEXT.__oslogstring: 0x800b
   __TEXT.__cstring: 0xf7bc
-  __TEXT.__gcc_except_tab: 0xe88c
+  __TEXT.__gcc_except_tab: 0xe8e0
   __TEXT.__ustring: 0x29fe
   __TEXT.__dlopen_cstrs: 0x3b5
   __TEXT.__constg_swiftt: 0x60

   __TEXT.__swift5_reflstr: 0x1c
   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x6548
+  __TEXT.__unwind_info: 0x6540
   __TEXT.__objc_classname: 0x1e1b
-  __TEXT.__objc_methname: 0x2aa53
-  __TEXT.__objc_methtype: 0x556c
+  __TEXT.__objc_methname: 0x2aa60
+  __TEXT.__objc_methtype: 0x5554
   __TEXT.__objc_stubs: 0x1a0e0
   __DATA_CONST.__got: 0x1268
   __DATA_CONST.__const: 0x1740

   __DATA_CONST.__objc_superrefs: 0x478
   __DATA_CONST.__objc_arraydata: 0x1a00
   __AUTH_CONST.__auth_got: 0x808
-  __AUTH_CONST.__const: 0x72e0
-  __AUTH_CONST.__cfstring: 0xf9c0
+  __AUTH_CONST.__const: 0x72c0
+  __AUTH_CONST.__cfstring: 0xf9a0
   __AUTH_CONST.__objc_const: 0x15500
   __AUTH_CONST.__objc_intobj: 0x6a8
   __AUTH_CONST.__objc_doubleobj: 0x70

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 5634
-  Symbols:   13476
+  Functions: 5636
+  Symbols:   13475
   CStrings:  9401
 
Symbols:
+ -[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]
+ __ZN12SafariShared42WBSSQLiteDatabaseExecuteWithParameterArrayIU8__strongP8NSStringEEiP17WBSSQLiteDatabaseS2_P7NSArrayIT_E
+ ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke
+ ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke_2
+ ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke_3
+ ___block_descriptor_104_ea8_32s40s48s56s64s72s80s88bs_e17_v16?0"NSImage"8l
+ ___block_descriptor_88_ea8_32s40s48s56s64s72bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24l
+ _objc_msgSend$_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:
+ _objc_msgSend$maximumParameterCount
+ _objc_msgSend$safari_stringByRepeatingWithCount:joinedByString:
- -[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]
- -[WBSLPLinkMetadataSQLiteStore _queryListWithStrings:]
- ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke
- ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke_2
- ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke_3
- ___54-[WBSLPLinkMetadataSQLiteStore _queryListWithStrings:]_block_invoke
- ___block_descriptor_112_ea8_32s40s48s56s64s72s80s88bs_e17_v16?0"NSImage"8l
- ___block_descriptor_96_ea8_32s40s48s56s64s72bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24l
- _objc_msgSend$_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:
- _objc_msgSend$_queryListWithStrings:
- _objc_msgSend$_setPrivacyProxyFailClosed:
CStrings:
+ "Failed to delete URLs. Error code: %d"
+ "Failed to delete UUIDs. Error code: %d"
+ "Trying to delete metadata info for too many URLs. Proceeding with the maximum allowed count."
+ "Trying to delete too many UUIDs. Proceeding with the maximum allowed count."
+ "_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:"
+ "maximumParameterCount"
+ "safari_stringByRepeatingWithCount:joinedByString:"
- "'%@'"
- "Failed to delete urls. Error code: %d"
- "Failed to delete uuids. Error code: %d"
- "_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:"
- "_queryListWithStrings:"
- "_setPrivacyProxyFailClosed:"
- "v56@0:8@16@24@32Q40@?48"
```
