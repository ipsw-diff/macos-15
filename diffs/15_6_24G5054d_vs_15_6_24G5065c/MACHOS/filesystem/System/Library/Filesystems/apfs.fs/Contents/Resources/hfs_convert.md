## hfs_convert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.8.0.1
+2332.140.11.0.0
   __TEXT.__text: 0xbaa70
   __TEXT.__auth_stubs: 0x11b0
   __TEXT.__objc_stubs: 0x80
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x1b642
+  __TEXT.__cstring: 0x1b63f
   __TEXT.__const: 0xa960
   __TEXT.__objc_methname: 0x48
   __TEXT.__unwind_info: 0xc28
CStrings:
+ "2332.140.11"
- "2332.140.8.0.1"
```
