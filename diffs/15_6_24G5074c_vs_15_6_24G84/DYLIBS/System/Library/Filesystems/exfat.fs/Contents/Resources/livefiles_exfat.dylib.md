## livefiles_exfat.dylib

> `/System/Library/Filesystems/exfat.fs/Contents/Resources/livefiles_exfat.dylib`

```diff

-488.120.2.0.0
-  __TEXT.__text: 0x1c3e4
+488.140.1.0.1
+  __TEXT.__text: 0x1c3f8
   __TEXT.__auth_stubs: 0x420
   __TEXT.__const: 0x4b50
   __TEXT.__oslogstring: 0x486c
   __TEXT.__cstring: 0x6be
-  __TEXT.__unwind_info: 0x240
+  __TEXT.__unwind_info: 0x248
   __TEXT.__objc_methname: 0x137
   __TEXT.__objc_stubs: 0x100
   __DATA_CONST.__got: 0x18

   - /System/Library/PrivateFrameworks/LiveFS.framework/Versions/A/LiveFS
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 177
-  Symbols:   281
+  Functions: 178
+  Symbols:   282
   CStrings:  441
 
Symbols:
+ _DIROPS_MarkNodeAsDeleted
Functions:
~ _EXFAT_Rename : 4292 -> 4272
+ _DIROPS_MarkNodeAsDeleted
```
