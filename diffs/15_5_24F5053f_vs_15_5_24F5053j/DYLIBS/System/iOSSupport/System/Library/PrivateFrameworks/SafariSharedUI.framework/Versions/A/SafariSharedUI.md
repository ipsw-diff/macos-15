## SafariSharedUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/SafariSharedUI.framework/Versions/A/SafariSharedUI`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-621.2.3.11.1
-  __TEXT.__text: 0x9dd80
-  __TEXT.__auth_stubs: 0x1070
+621.2.4.11.2
+  __TEXT.__text: 0x9e210
+  __TEXT.__auth_stubs: 0x10a0
   __TEXT.__objc_methlist: 0x8438
   __TEXT.__const: 0x29a8
-  __TEXT.__oslogstring: 0x4bf6
+  __TEXT.__oslogstring: 0x4c95
   __TEXT.__cstring: 0xbc8c
-  __TEXT.__gcc_except_tab: 0x8818
+  __TEXT.__gcc_except_tab: 0x89c0
   __TEXT.__ustring: 0x1a82
   __TEXT.__dlopen_cstrs: 0x30e
   __TEXT.__constg_swiftt: 0x60

   __TEXT.__swift5_reflstr: 0x1c
   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x4558
+  __TEXT.__unwind_info: 0x45d0
   __TEXT.__objc_classname: 0x17cf
-  __TEXT.__objc_methname: 0x1cc83
-  __TEXT.__objc_methtype: 0x439d
-  __TEXT.__objc_stubs: 0x11660
+  __TEXT.__objc_methname: 0x1cc9d
+  __TEXT.__objc_methtype: 0x43b5
+  __TEXT.__objc_stubs: 0x11680
   __DATA_CONST.__got: 0xc80
   __DATA_CONST.__const: 0x4c28
   __DATA_CONST.__objc_classlist: 0x4c0
   __DATA_CONST.__objc_catlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5a30
+  __DATA_CONST.__objc_selrefs: 0x5a38
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x370
   __DATA_CONST.__objc_arraydata: 0x18f8
-  __AUTH_CONST.__auth_got: 0x850
+  __AUTH_CONST.__auth_got: 0x868
   __AUTH_CONST.__const: 0x1040
   __AUTH_CONST.__cfstring: 0xc320
   __AUTH_CONST.__objc_const: 0xfe50

   __AUTH.__data: 0x128
   __DATA.__objc_ivar: 0xb20
   __DATA.__data: 0x1270
-  __DATA.__bss: 0x4e0
+  __DATA.__bss: 0x4f0
   __DATA_DIRTY.__objc_data: 0x13b0
   __DATA_DIRTY.__data: 0x10
-  __DATA_DIRTY.__bss: 0xa8
+  __DATA_DIRTY.__bss: 0x98
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3897
-  Symbols:   9601
-  CStrings:  6718
+  Functions: 3900
+  Symbols:   9607
+  CStrings:  6724
 
Symbols:
+ -[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]
+ _WKPageCopyStandardUserAgentWithApplicationName
+ _WKStringCopyCFString
+ _WKStringCreateWithUTF8CString
+ __ZZ54+[WBSImageFetchingURLSessionTaskManager sharedManager]E13sharedManager
+ __ZZ54+[WBSImageFetchingURLSessionTaskManager sharedManager]E9onceToken
+ ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke
+ ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke_2
+ ___150-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:]_block_invoke_3
+ ___block_descriptor_112_ea8_32s40s48s56s64s72s80s88bs_e17_v16?0"UIImage"8ls88l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_40_ea8_32bs_e73_v48?0"UIImage"8"NSData"16"NSURL"24"NSURLResponse"32"NSDictionary"40ls32l8
+ ___block_descriptor_56_ea8_32s40s48bs_e19_v16?0"WKWebView"8ls32l8s40l8s48l8
+ ___block_descriptor_56_ea8_32s40s48bs_e29_v24?0"UIImage"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_72_ea8_32s40r48r56r64r_e56_v40?0"UIImage"8"NSData"16"NSURL"24"NSURLResponse"32lr40l8r48l8r56l8r64l8s32l8
+ ___block_descriptor_72_ea8_32s40s48s56s64bs_e5_v8?0ls64l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_80_ea8_32s40bs48r56r64r72r_e5_v8?0ls40l8r48l8r56l8r64l8r72l8s32l8
+ ___block_descriptor_96_ea8_32s40s48s56s64s72bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s40l8s48l8s72l8s56l8s64l8
+ _objc_msgSend$_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:
+ _objc_msgSend$setHTTPUserAgent:
- -[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]
- ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke
- ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke_2
- ___142-[WBSImageFetchingURLSessionTaskManager _downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:]_block_invoke_3
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88bs_e17_v16?0"UIImage"8ls88l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_40_e8_32bs_e73_v48?0"UIImage"8"NSData"16"NSURL"24"NSURLResponse"32"NSDictionary"40ls32l8
- ___block_descriptor_56_e8_32s40s48bs_e19_v16?0"WKWebView"8ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"UIImage"8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40r48r56r64r_e56_v40?0"UIImage"8"NSData"16"NSURL"24"NSURLResponse"32lr40l8r48l8r56l8r64l8s32l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls64l8s32l8s40l8s48l8s56l8
- ___block_descriptor_80_e8_32s40bs48r56r64r72r_e5_v8?0ls40l8r48l8r56l8r64l8r72l8s32l8
- ___block_descriptor_88_e8_32s40s48s56s64s72bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24ls32l8s40l8s48l8s72l8s56l8s64l8
- _objc_msgSend$_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:
CStrings:
+ "Cannot release LP metadata response for empty URL."
+ "Cannot retain LP metadata response for empty URL."
+ "Cannot reuse LP metadata for empty source or target URLs."
+ "Safari"
+ "_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:options:completionHandler:"
+ "setHTTPUserAgent:"
+ "v56@0:8@16@24@32Q40@?48"
- "_downloadFirstValidImageWithURLs:inURLSession:failedURLDownloadsToErrorsDictionary:completionHandler:"
```
