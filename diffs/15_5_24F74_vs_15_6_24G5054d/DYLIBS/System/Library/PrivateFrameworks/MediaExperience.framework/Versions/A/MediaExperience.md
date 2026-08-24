## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/Versions/A/MediaExperience`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-240.6.1.0.0
-  __TEXT.__text: 0x80e80
-  __TEXT.__auth_stubs: 0x12a0
-  __TEXT.__objc_methlist: 0x124c
+250.7.1.0.0
+  __TEXT.__text: 0x80e14
+  __TEXT.__auth_stubs: 0x1270
+  __TEXT.__objc_methlist: 0x123c
   __TEXT.__const: 0x1a0
   __TEXT.__cstring: 0xe7f7
   __TEXT.__oslogstring: 0xafbf
-  __TEXT.__gcc_except_tab: 0xb5c
+  __TEXT.__gcc_except_tab: 0xb64
   __TEXT.__dlopen_cstrs: 0xae
-  __TEXT.__unwind_info: 0x1680
+  __TEXT.__unwind_info: 0x1688
   __TEXT.__objc_classname: 0x207
-  __TEXT.__objc_methname: 0x3659
-  __TEXT.__objc_methtype: 0xa0e
-  __TEXT.__objc_stubs: 0x25c0
+  __TEXT.__objc_methname: 0x362d
+  __TEXT.__objc_methtype: 0xa19
+  __TEXT.__objc_stubs: 0x25a0
   __DATA_CONST.__got: 0x6d0
   __DATA_CONST.__const: 0x24c8
   __DATA_CONST.__objc_classlist: 0x90
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc30
+  __DATA_CONST.__objc_selrefs: 0xc28
   __DATA_CONST.__objc_superrefs: 0x78
-  __AUTH_CONST.__auth_got: 0x960
+  __AUTH_CONST.__auth_got: 0x948
   __AUTH_CONST.__const: 0x1f60
   __AUTH_CONST.__cfstring: 0x92a0
   __AUTH_CONST.__objc_const: 0x1d78
   __AUTH.__objc_data: 0x5a0
   __DATA.__objc_ivar: 0x178
   __DATA.__data: 0x2b8
-  __DATA.__common: 0x1c0
   __DATA.__bss: 0x8e8
+  __DATA.__common: 0x1b0
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreMedia.framework/Versions/A/CoreMedia

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1902
-  Symbols:   4253
+  Functions: 1901
+  Symbols:   4246
   CStrings:  2995
 
Symbols:
+ +[MXSystemController(Common) copyMXSystemControllerList:]
+ _gMXSystemControllerListLock
+ _objc_msgSend$copyMXSystemControllerList:
- +[MXSystemController(Common) mxSystemControllerListBeginIteration]
- +[MXSystemController(Common) mxSystemControllerListEndIteration]
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
- _gMXSystemControllerListActiveReaders
- _gMXSystemControllerListReadLock
- _gMXSystemControllerListWriteSemaphore
- _objc_msgSend$mxSystemControllerListBeginIteration
- _objc_msgSend$mxSystemControllerListEndIteration
CStrings:
+ "22:54:33"
+ "@20@0:8B16"
+ "Jun  3 2025"
+ "copyMXSystemControllerList:"
- "22:10:41"
- "Apr 18 2025"
- "mxSystemControllerListBeginIteration"
- "mxSystemControllerListEndIteration"
```
