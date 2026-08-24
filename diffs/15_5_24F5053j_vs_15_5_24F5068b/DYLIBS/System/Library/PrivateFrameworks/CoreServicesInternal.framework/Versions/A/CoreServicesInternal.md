## CoreServicesInternal

> `/System/Library/PrivateFrameworks/CoreServicesInternal.framework/Versions/A/CoreServicesInternal`

```diff

-554.8.0.0.0
-  __TEXT.__text: 0x364c4
-  __TEXT.__auth_stubs: 0x1bf0
+554.9.0.0.0
+  __TEXT.__text: 0x36c68
+  __TEXT.__auth_stubs: 0x1ca0
   __TEXT.__delay_stubs: 0x1b8
   __TEXT.__delay_helper: 0x49c
   __TEXT.__const: 0x500
-  __TEXT.__cstring: 0x279f
-  __TEXT.__oslogstring: 0x2ace
+  __TEXT.__cstring: 0x2801
+  __TEXT.__oslogstring: 0x2afb
   __TEXT.__unwind_info: 0x100
-  __DATA_CONST.__got: 0x7e0
+  __DATA_CONST.__got: 0x7e8
   __DATA_CONST.__const: 0x320
-  __AUTH_CONST.__auth_got: 0xe48
-  __AUTH_CONST.__const: 0x3f8
-  __AUTH_CONST.__cfstring: 0x1900
+  __AUTH_CONST.__auth_got: 0xea0
+  __AUTH_CONST.__const: 0x428
+  __AUTH_CONST.__cfstring: 0x1920
   __DATA.__data: 0x131
   __DATA.__bss: 0x1370
   __DATA_DIRTY.__data: 0x1b8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libfakelink.dylib
-  Functions: 741
-  Symbols:   1433
-  CStrings:  632
+  Functions: 746
+  Symbols:   1452
+  CStrings:  637
 
Symbols:
+ _ZL25resolveScopedBookmarkDataPK13__CFAllocatorPK8__CFDatamPK7__CFURLPhPP9__CFError
+ _ZL37createByResolvingBookmarkDataInternalPK13__CFAllocatorPK8__CFDatamPK7__CFURLPK9__CFArrayPhPP9__CFErrorPS7_
+ __CFFileCoordinateReadingItemAtURL2
+ __CFURLCopyPromiseURLOfLogicalURL
+ __CFURLPromiseCopyPhysicalURL
+ __CFURLPromiseCopyResourcePropertyForKey
+ __CFURLPromiseSetPhysicalURL
+ __CFURLPromiseSetResourcePropertyForKey
+ __ZL19URLHasSecurityScopePK7__CFURL
+ __ZL25DownloadCloudDocumentSyncPK7__CFURL
+ __ZL25resolveScopedBookmarkDataPK13__CFAllocatorPK8__CFDatamPK7__CFURLPhPP9__CFError
+ __ZL37createByResolvingBookmarkDataInternalPK13__CFAllocatorPK8__CFDatamPK7__CFURLPK9__CFArrayPhPP9__CFErrorPS7_
+ ____ZL25DownloadCloudDocumentSyncPK7__CFURL_block_invoke
+ __kCFURLPromisePhysicalURLKey
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_wait
+ _dispatch_release
CStrings:
+ "%s: downloading %@"
+ "%s: finished %@, error=%@"
+ "DownloadCloudDocumentSync"
+ "com.apple.bookmarkresolution"
+ "v32@?0^{__CFURL=}8^{__CFError=}16@?<v@?>24"
```
