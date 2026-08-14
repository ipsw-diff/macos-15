## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_vol_converter`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.120.29.0.0
-  __TEXT.__text: 0x59220
+2332.120.31.0.2
+  __TEXT.__text: 0x592a0
   __TEXT.__auth_stubs: 0x9d0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x1271b
+  __TEXT.__cstring: 0x12780
   __TEXT.__const: 0x320
-  __TEXT.__gcc_except_tab: 0x5a0
+  __TEXT.__gcc_except_tab: 0x5a4
   __TEXT.__unwind_info: 0xbf0
   __DATA_CONST.__auth_got: 0x4f0
   __DATA_CONST.__got: 0x70

   - /usr/lib/libutil.dylib
   Functions: 865
   Symbols:   181
-  CStrings:  1639
+  CStrings:  1640
 
Functions:
~ sub_10000a680 : 2972 -> 2976
~ sub_1000109d0 -> sub_1000109d4 : 3780 -> 3896
~ sub_10002e4a0 -> sub_10002e518 : 496 -> 504
CStrings:
+ "%s:%u Warn: Volume has %llu snapshots, would continue with manually recalculated extentRef tree\n"
+ "2332.120.31.0.2"
- "2332.120.29"
```
