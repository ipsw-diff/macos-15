## com.apple.MEValidationService

> `/System/Library/Frameworks/MediaExtension.framework/Versions/A/XPCServices/com.apple.MEValidationService.xpc/Contents/MacOS/com.apple.MEValidationService`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

-3225.5.2.0.0
-  __TEXT.__text: 0x1010
-  __TEXT.__auth_stubs: 0x4f0
+3225.7.1.0.0
+  __TEXT.__text: 0x106c
+  __TEXT.__auth_stubs: 0x510
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__const: 0x10
   __TEXT.__cstring: 0x54e
   __TEXT.__oslogstring: 0x15b
   __TEXT.__objc_methname: 0x82
   __TEXT.__unwind_info: 0x88
-  __DATA_CONST.__auth_got: 0x280
+  __DATA_CONST.__auth_got: 0x290
   __DATA_CONST.__got: 0x70
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x70

   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/Frameworks/MediaToolbox.framework/Versions/A/MediaToolbox
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/RunningBoardServices.framework/Versions/A/RunningBoardServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 10
-  Symbols:   100
+  Symbols:   102
   CStrings:  31
 
Symbols:
+ _CFSetGetTypeID
+ _FigCopySetOfSystemSupportedMediaFileExtensions
Functions:
~ sub_100000c98 -> sub_100000d00 : 1956 -> 1980
~ sub_100001784 -> sub_100001804 : 600 -> 668
```
