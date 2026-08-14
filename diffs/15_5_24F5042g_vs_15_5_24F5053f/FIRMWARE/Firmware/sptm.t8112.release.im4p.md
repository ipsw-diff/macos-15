## sptm.t8112.release.im4p

> `Firmware/sptm.t8112.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__auth_ptr`

```diff

-392.120.12.0.0
-  __TEXT.__cstring: 0xd790
+392.120.14.0.0
+  __TEXT.__cstring: 0xd992
   __TEXT.__binname: 0x40
   __TEXT.__const: 0xb00
   __TEXT.__chain_starts: 0x74
   __DATA_CONST.__const: 0x6498
   __LATE_CONST.__late_const: 0x5d610
-  __TEXT_EXEC.__text: 0x4c518
+  __TEXT_EXEC.__text: 0x4c68c
   __LAST.__pinst: 0x8
   __DATA.__auth_ptr: 0x18
   __DATA.__data: 0x6

   __BOOTDATA.__data: 0x14000
   Functions: 334
   Symbols:   1
-  CStrings:  1684
+  CStrings:  1689
 
Functions:
~ sub_fffffff027081068 : 44812 -> 44852
~ sub_fffffff02708c098 -> sub_fffffff02708c0c0 : 328 -> 320
~ sub_fffffff02708f1b8 -> sub_fffffff02708f1d8 : 6400 -> 6368
~ sub_fffffff0270bc45c : 7716 -> 7796
~ sub_fffffff0270be280 -> sub_fffffff0270be2d0 : 404 -> 92
~ sub_fffffff0270be414 -> sub_fffffff0270be32c : 92 -> 1320
~ sub_fffffff0270be470 -> sub_fffffff0270be854 : 308 -> 404
~ sub_fffffff0270be5a4 -> sub_fffffff0270be9e8 : 568 -> 308
~ sub_fffffff0270be7dc -> sub_fffffff0270beb1c : 1624 -> 872
~ sub_fffffff0270beee4 -> sub_fffffff0270bef34 : 4844 -> 5136
~ sub_fffffff0270c84dc -> sub_fffffff0270c8650 : 68 -> 64
CStrings:
+ "!sptm_add_overflow(src_paddr, (0), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (2 * sizeof(uint32_t)), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (compressed_size), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (sizeof(uint32_t)), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "header->image1Size > (uintptr_t)page_list_end_paddr - (uintptr_t)header_paddr"
```
