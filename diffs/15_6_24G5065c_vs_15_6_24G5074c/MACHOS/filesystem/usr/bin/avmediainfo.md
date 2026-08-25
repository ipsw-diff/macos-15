## avmediainfo

> `/usr/bin/avmediainfo`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

-2340.10.1.0.0
-  __TEXT.__text: 0x5920
+2340.12.2.0.0
+  __TEXT.__text: 0x57f0
   __TEXT.__auth_stubs: 0x3a0
   __TEXT.__objc_stubs: 0x14a0
   __TEXT.__objc_methlist: 0x2e4

   __TEXT.__objc_methname: 0xdf2
   __TEXT.__objc_classname: 0x1e
   __TEXT.__objc_methtype: 0x14a
-  __TEXT.__cstring: 0x1c71
+  __TEXT.__cstring: 0x1bf0
   __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__auth_got: 0x1d8
   __DATA_CONST.__got: 0x260

   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 71
+  Functions: 69
   Symbols:   142
-  CStrings:  519
+  CStrings:  512
 
Symbols:
+ _FigSignalErrorAt
- _FigSignalErrorAt3
CStrings:
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "(Fig)"
- "-1"
- "FigDebugPlatform.h"
- "FigRunCommandWithArguments"
- "allocation failed"
- "invalid argv"
```
