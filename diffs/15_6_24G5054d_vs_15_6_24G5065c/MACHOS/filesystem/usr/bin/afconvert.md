## afconvert

> `/usr/bin/afconvert`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-776.600.0.0.0
-  __TEXT.__text: 0x1199c
+776.701.0.0.0
+  __TEXT.__text: 0x119d0
   __TEXT.__auth_stubs: 0x930
   __TEXT.__objc_stubs: 0x80
   __TEXT.__gcc_except_tab: 0xfc8

   __TEXT.__unwind_info: 0x660
   __DATA_CONST.__auth_got: 0x4a8
   __DATA_CONST.__got: 0xf8
-  __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0xfd8
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 258
-  Symbols:   185
+  Symbols:   184
   CStrings:  529
 
Symbols:
+ _AudioFileReadPacketData
- _AudioFileReadPackets
- ___chkstk_darwin
Functions:
~ sub_1000083bc -> sub_10000836c : 1216 -> 1228
~ sub_10000c848 -> sub_10000c804 : 4400 -> 4440
```
