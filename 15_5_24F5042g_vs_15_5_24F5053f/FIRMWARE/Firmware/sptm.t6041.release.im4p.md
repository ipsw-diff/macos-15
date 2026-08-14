## sptm.t6041.release.im4p

> `Firmware/sptm.t6041.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

-392.120.12.0.0
-  __TEXT.__cstring: 0xe638
+392.120.14.0.0
+  __TEXT.__cstring: 0xe83a
   __TEXT.__binname: 0x40
   __TEXT.__const: 0xb00
   __TEXT.__chain_starts: 0x78
   __DATA_CONST.__const: 0x68c8
   __LATE_CONST.__late_const: 0x5d750
-  __TEXT_EXEC.__text: 0x50b84
+  __TEXT_EXEC.__text: 0x50d20
   __LAST.__pinst: 0x8
   __DATA.__auth_ptr: 0x18
   __DATA.__data: 0x6

   __BOOTDATA.__data: 0x14000
   Functions: 355
   Symbols:   1
-  CStrings:  1806
+  CStrings:  1811
 
Functions:
~ sub_fffffff0270bfdec : 7716 -> 7796
~ sub_fffffff0270c1c10 -> sub_fffffff0270c1c60 : 404 -> 92
~ sub_fffffff0270c1da4 -> sub_fffffff0270c1cbc : 92 -> 1320
~ sub_fffffff0270c1e00 -> sub_fffffff0270c21e4 : 396 -> 404
~ sub_fffffff0270c1f8c -> sub_fffffff0270c2378 : 568 -> 396
~ sub_fffffff0270c21c4 -> sub_fffffff0270c2504 : 1624 -> 872
~ sub_fffffff0270c281c -> sub_fffffff0270c286c : 7384 -> 7716
~ sub_fffffff0270ccb48 -> sub_fffffff0270ccce4 : 72 -> 60
CStrings:
+ "!sptm_add_overflow(src_paddr, (0), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (2 * sizeof(uint32_t)), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (compressed_size), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (sizeof(uint32_t)), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "header->image1Size > (uintptr_t)page_list_end_paddr - (uintptr_t)header_paddr"
```
