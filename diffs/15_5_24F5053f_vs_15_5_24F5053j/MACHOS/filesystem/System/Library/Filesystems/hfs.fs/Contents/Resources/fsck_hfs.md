## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/Contents/Resources/fsck_hfs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-683.100.9.0.0
-  __TEXT.__text: 0x2fa60
+683.120.3.0.0
+  __TEXT.__text: 0x2fb1c
   __TEXT.__auth_stubs: 0x780
   __TEXT.__const: 0x112c
-  __TEXT.__cstring: 0x6c5c
+  __TEXT.__cstring: 0x6cab
   __TEXT.__unwind_info: 0x508
   __DATA_CONST.__auth_got: 0x3c0
   __DATA_CONST.__got: 0x50

   - /usr/lib/libSystem.B.dylib
   Functions: 470
   Symbols:   135
-  CStrings:  776
+  CStrings:  778
 
Functions:
~ sub_10002f330 : 1844 -> 2032
CStrings:
+ "\tInvalid block size block_list_header\n"
+ "%s: jnl: %s: open: bad jhdr size (%d) \n"
```
