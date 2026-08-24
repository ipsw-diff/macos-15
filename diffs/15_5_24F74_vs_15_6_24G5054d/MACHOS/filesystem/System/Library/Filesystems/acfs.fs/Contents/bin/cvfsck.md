## cvfsck

> `/System/Library/Filesystems/acfs.fs/Contents/bin/cvfsck`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-782.120.2.0.0
+782.140.2.0.0
   __TEXT.__text: 0x989ac
   __TEXT.__auth_stubs: 0x1070
-  __TEXT.__const: 0xc610
-  __TEXT.__cstring: 0x2cbb1
+  __TEXT.__const: 0xc618
+  __TEXT.__cstring: 0x2cc9c
   __TEXT.__unwind_info: 0x1660
   __DATA_CONST.__auth_got: 0x838
   __DATA_CONST.__got: 0x98
```
