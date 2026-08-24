## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/fsck_apfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.120.31.0.2
+2332.140.8.0.1
   __TEXT.__text: 0x4c8fc
   __TEXT.__auth_stubs: 0x930
-  __TEXT.__cstring: 0x1891a
-  __TEXT.__const: 0x8104
+  __TEXT.__cstring: 0x18919
+  __TEXT.__const: 0x84a4
   __TEXT.__unwind_info: 0xa28
   __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x68
CStrings:
+ "2332.140.8.0.1"
- "2332.120.31.0.2"
```
