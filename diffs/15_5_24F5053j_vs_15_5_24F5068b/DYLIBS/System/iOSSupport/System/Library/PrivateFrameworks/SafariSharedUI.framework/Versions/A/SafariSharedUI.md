## SafariSharedUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/SafariSharedUI.framework/Versions/A/SafariSharedUI`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-621.2.4.11.2
-  __TEXT.__text: 0x9e210
+621.2.5.11.5
+  __TEXT.__text: 0x9e504
   __TEXT.__auth_stubs: 0x10a0
-  __TEXT.__objc_methlist: 0x8438
+  __TEXT.__objc_methlist: 0x8430
   __TEXT.__const: 0x29a8
-  __TEXT.__oslogstring: 0x4c95
+  __TEXT.__oslogstring: 0x4d3e
   __TEXT.__cstring: 0xbc8c
-  __TEXT.__gcc_except_tab: 0x89c0
+  __TEXT.__gcc_except_tab: 0x8a1c
   __TEXT.__ustring: 0x1a82
   __TEXT.__dlopen_cstrs: 0x30e
   __TEXT.__constg_swiftt: 0x60

   __TEXT.__swift5_reflstr: 0x1c
   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x45d0
+  __TEXT.__unwind_info: 0x45c8
   __TEXT.__objc_classname: 0x17cf
-  __TEXT.__objc_methname: 0x1cc9d
-  __TEXT.__objc_methtype: 0x43b5
-  __TEXT.__objc_stubs: 0x11680
+  __TEXT.__objc_methname: 0x1ccc6
+  __TEXT.__objc_methtype: 0x439d
+  __TEXT.__objc_stubs: 0x116a0
   __DATA_CONST.__got: 0xc80
   __DATA_CONST.__const: 0x4c28
   __DATA_CONST.__objc_classlist: 0x4c0
   __DATA_CONST.__objc_catlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5a38
+  __DATA_CONST.__objc_selrefs: 0x5a40
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x370
   __DATA_CONST.__objc_arraydata: 0x18f8
   __AUTH_CONST.__auth_got: 0x868
-  __AUTH_CONST.__const: 0x1040
-  __AUTH_CONST.__cfstring: 0xc320
+  __AUTH_CONST.__const: 0x1020
+  __AUTH_CONST.__cfstring: 0xc300
   __AUTH_CONST.__objc_const: 0xfe50
   __AUTH_CONST.__objc_intobj: 0x558
   __AUTH_CONST.__objc_doubleobj: 0x40

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3900
+  Functions: 3903
   Symbols:   9607
-  CStrings:  6724
+  CStrings:  6725
 
Symbols:
+ -[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]
+ __ZN12SafariShared42WBSSQLiteDatabaseExecuteWithParameterArrayIU8__strongP8NSStringEEiP17WBSSQLiteDatabaseS2_P7NSArrayIT_E
+ ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke
+ ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke_2
+ ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke_3
+ ___block_descriptor_104_ea8_32s40s48s56s64s72s80s88bs_e17_v16?0"UIImage"8ls88l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_88_ea8_32s40s48s56s64s72bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s40l8s48l8s72l8s56l8s64l8
+ _objc_msgSend$_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:
+ _objc_msgSend$maximumParameterCount
+ _objc_msgSend$safari_stringByRepeatingWithCount:joinedByString:
- -[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]
- -[WBSLPLinkMetadataSQLiteStore _queryListWithStrings:]
- ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke
- ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke_2
- ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke_3
- ___54-[WBSLPLinkMetadataSQLiteStore _queryListWithStrings:]_block_invoke
- ___block_descriptor_112_ea8_32s40s48s56s64s72s80s88bs_e17_v16?0"UIImage"8ls88l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_96_ea8_32s40s48s56s64s72bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s40l8s48l8s72l8s56l8s64l8
- _objc_msgSend$_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:
- _objc_msgSend$_queryListWithStrings:
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
- "v56@0:8@16@24@32Q40@?48"
```
