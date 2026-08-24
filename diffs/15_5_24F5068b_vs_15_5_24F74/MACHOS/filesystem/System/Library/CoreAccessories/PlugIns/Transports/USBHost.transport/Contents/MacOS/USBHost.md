## USBHost

> `/System/Library/CoreAccessories/PlugIns/Transports/USBHost.transport/Contents/MacOS/USBHost`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`

```diff

 1043.120.6.0.0
-  __TEXT.__text: 0x1cf44
+  __TEXT.__text: 0x1cf34
   __TEXT.__auth_stubs: 0x820
   __TEXT.__objc_methlist: 0x1310
   __TEXT.__const: 0x160

   __AUTH.__objc_data: 0x410
   __DATA.__objc_ivar: 0x250
   __DATA.__data: 0x330
-  __DATA.__bss: 0xa8
+  __DATA.__bss: 0xa0
   __DATA.__common: 0x24
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 582
-  Symbols:   1526
+  Symbols:   1525
   CStrings:  1229
 
Symbols:
- systemInfo_isDeveloperBuild.developerBuild
Functions:
~ _systemInfo_isDeveloperBuild : 56 -> 52
~ ___systemInfo_isDeveloperBuild_block_invoke : 16 -> 4
```
