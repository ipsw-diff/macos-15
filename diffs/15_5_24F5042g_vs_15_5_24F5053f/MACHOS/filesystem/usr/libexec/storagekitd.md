## storagekitd

> `/usr/libexec/storagekitd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-934.120.1.0.0
-  __TEXT.__text: 0x193ef8
-  __TEXT.__auth_stubs: 0x2e40
+934.120.4.0.0
+  __TEXT.__text: 0x194038
+  __TEXT.__auth_stubs: 0x2e60
   __TEXT.__objc_stubs: 0xee60
   __TEXT.__objc_methlist: 0x805c
   __TEXT.__const: 0xc88
-  __TEXT.__objc_methname: 0x15884
+  __TEXT.__objc_methname: 0x15868
   __TEXT.__oslogstring: 0x624c
   __TEXT.__objc_classname: 0xd8a
-  __TEXT.__objc_methtype: 0x634b
+  __TEXT.__objc_methtype: 0x6348
   __TEXT.__gcc_except_tab: 0x287c
-  __TEXT.__cstring: 0x6813a
+  __TEXT.__cstring: 0x68166
   __TEXT.__unwind_info: 0x28b0
   __TEXT.__eh_frame: 0x1a8
-  __DATA_CONST.__auth_got: 0x1730
+  __DATA_CONST.__auth_got: 0x1740
   __DATA_CONST.__got: 0xb38
   __DATA_CONST.__auth_ptr: 0xa8
   __DATA_CONST.__const: 0x2b20
-  __DATA_CONST.__cfstring: 0x3f760
+  __DATA_CONST.__cfstring: 0x3f7a0
   __DATA_CONST.__objc_classlist: 0x428
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0xb0

   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3603
-  Symbols:   1110
-  CStrings:  14534
+  Functions: 3604
+  Symbols:   1112
+  CStrings:  14537
 
Symbols:
+ _fstatfs_ext
+ _statfs_ext
CStrings:
+ "-[DMToolBootPreference copyFileFromPath:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:atomic:]"
+ "-[DMToolBootPreference copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:atomic:]"
+ "Cannot convert path to UTF8"
+ "Cannot resolve path %@"
+ "Cannot resolve path for key %@"
+ "_DMrealPathForDictionary"
+ "copyFileFromPath:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:atomic:"
+ "copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:atomic:"
+ "i80@0:8@16@24@32B40B44B48^{DMUDSPrivRec=Qq[150c]}52Q60Q68B76"
- "-[DMToolBootPreference copyFileFromPath:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:allowSymlinks:atomic:]"
- "-[DMToolBootPreference copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:allowSymlinks:atomic:]"
- "Cannot convert mount point to UTF8"
- "copyFileFromPath:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:allowSymlinks:atomic:"
- "copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:allowSymlinks:atomic:"
- "i84@0:8@16@24@32B40B44B48^{DMUDSPrivRec=Qq[150c]}52Q60Q68B76B80"
```
