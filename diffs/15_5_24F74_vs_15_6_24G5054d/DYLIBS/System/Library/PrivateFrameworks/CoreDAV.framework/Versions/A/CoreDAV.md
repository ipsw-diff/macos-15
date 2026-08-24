## CoreDAV

> `/System/Library/PrivateFrameworks/CoreDAV.framework/Versions/A/CoreDAV`

```diff

-1230.5.2.0.0
-  __TEXT.__text: 0x5a4a8
+1230.7.2.0.0
+  __TEXT.__text: 0x5a628
   __TEXT.__auth_stubs: 0x730
-  __TEXT.__objc_methlist: 0x5768
+  __TEXT.__objc_methlist: 0x5798
   __TEXT.__cstring: 0x3c6d
   __TEXT.__const: 0xf0
   __TEXT.__oslogstring: 0x440b
   __TEXT.__gcc_except_tab: 0x820
   __TEXT.__unwind_info: 0x10d8
   __TEXT.__objc_classname: 0xd8d
-  __TEXT.__objc_methname: 0xbc8e
+  __TEXT.__objc_methname: 0xbd44
   __TEXT.__objc_methtype: 0x1a7e
-  __TEXT.__objc_stubs: 0x7620
+  __TEXT.__objc_stubs: 0x7660
   __DATA_CONST.__got: 0x4a0
   __DATA_CONST.__const: 0xac0
   __DATA_CONST.__objc_classlist: 0x380
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2790
+  __DATA_CONST.__objc_selrefs: 0x27b0
   __DATA_CONST.__objc_superrefs: 0x360
   __DATA_CONST.__objc_arraydata: 0x18
   __AUTH_CONST.__auth_got: 0x3a8
   __AUTH_CONST.__const: 0x7d0
   __AUTH_CONST.__cfstring: 0x5940
-  __AUTH_CONST.__objc_const: 0xaef8
+  __AUTH_CONST.__objc_const: 0xaf28
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0x79c
+  __DATA.__objc_ivar: 0x7a0
   __DATA.__data: 0x978
   __DATA.__bss: 0x90
   __DATA_DIRTY.__objc_data: 0x2260

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1747
-  Symbols:   4669
-  CStrings:  3317
+  Functions: 1750
+  Symbols:   4676
+  CStrings:  3323
 
Symbols:
+ +[CoreDAVContainerSyncTaskGroup _isInsufficientStorage:]
+ -[CoreDAVContainerSyncTaskGroup insufficientStorageRetryCount]
+ -[CoreDAVContainerSyncTaskGroup setInsufficientStorageRetryCount:]
+ OBJC_IVAR_$_CoreDAVContainerSyncTaskGroup._insufficientStorageRetryCount
+ __OBJC_$_CLASS_METHODS_CoreDAVContainerSyncTaskGroup
+ _objc_msgSend$_isInsufficientStorage:
+ _objc_msgSend$shouldSkipAddForOverQuota
CStrings:
+ "TQ,N,V_insufficientStorageRetryCount"
+ "_insufficientStorageRetryCount"
+ "_isInsufficientStorage:"
+ "insufficientStorageRetryCount"
+ "setInsufficientStorageRetryCount:"
+ "shouldSkipAddForOverQuota"
```
