## AppleProResHWEncoder

> `/System/Library/Video/Plug-Ins/AppleProResHWEncoder.bundle/Contents/MacOS/AppleProResHWEncoder`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-475.2.0.0.0
-  __TEXT.__text: 0x1ce60
+475.6.0.0.0
+  __TEXT.__text: 0x1cd14
   __TEXT.__auth_stubs: 0xa70
-  __TEXT.__const: 0x741b0
+  __TEXT.__const: 0x74190
   __TEXT.__cstring: 0x11e3
   __TEXT.__gcc_except_tab: 0x308
   __TEXT.__oslogstring: 0x2d90
   __TEXT.__unwind_info: 0x3c8
   __DATA_CONST.__auth_got: 0x540
-  __DATA_CONST.__got: 0x228
+  __DATA_CONST.__got: 0x220
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0x188
   __DATA_CONST.__cfstring: 0x240

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   Functions: 411
-  Symbols:   243
+  Symbols:   242
   CStrings:  327
 
Symbols:
- _kVTCompressionPropertyKey_AverageBitRate
Functions:
~ _ProResEncoder_CreateInstance : 1600 -> 1572
~ sub_fe18 -> sub_fdfc : 1268 -> 1236
~ sub_1030c -> sub_102d0 : 2588 -> 2512
~ sub_1180c -> sub_11784 : 4752 -> 4556
```
