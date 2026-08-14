## libRPAC.dylib

> `/usr/lib/libRPAC.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__AUTH_CONST.__interpose`
- `__DATA.__objc_selrefs`

```diff

-84.0.0.0.0
-  __TEXT.__text: 0x8e1ac
+88.0.0.0.0
+  __TEXT.__text: 0x8e278
   __TEXT.__auth_stubs: 0x790
   __TEXT.__objc_stubs: 0x1a0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x4a0f
+  __TEXT.__cstring: 0x49ee
   __TEXT.__gcc_except_tab: 0x44
   __TEXT.__const: 0x1d60
   __TEXT.__objc_methname: 0x13b
   __TEXT.__oslogstring: 0x1d
   __TEXT.__objc_classname: 0x1
-  __TEXT.__unwind_info: 0x288
+  __TEXT.__unwind_info: 0x298
   __DATA_CONST.__auth_got: 0x3e0
   __DATA_CONST.__got: 0x80
   __DATA_CONST.__auth_ptr: 0x10

   __DATA_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__interpose: 0x90
   __DATA.__objc_selrefs: 0x88
-  __DATA.__data: 0x7c8
+  __DATA.__data: 0x7c4
   __DATA.__common: 0x800e8
-  __DATA.__bss: 0x580630
+  __DATA.__bss: 0x580430
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 194
-  Symbols:   508
+  Functions: 197
+  Symbols:   510
   CStrings:  538
 
Symbols:
+ _lockLockInDispatchLockMap
+ _lockLockInNSCondtionLockMap
+ _unlockLockInDispatchLockMap
+ _unlockLockInNSConditionLockMap
- __ZL18max_primitive_maps
- deletePrimitiveEntry
CStrings:
+ "Inversion detection for %s\n"
+ "SemaphoreWaitingAGPCLogType"
+ "semaphorewaitingagpclogtype"
- "DispatchSemaphoreWaitingOnMainThreadAGPCLogType"
- "deletePrimitiveEntry"
- "dispatchsemaphorewaitingonmainthreadagpclogtype"
```
