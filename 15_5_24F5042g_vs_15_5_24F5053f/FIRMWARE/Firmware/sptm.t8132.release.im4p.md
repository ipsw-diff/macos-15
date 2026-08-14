## sptm.t8132.release.im4p

> `Firmware/sptm.t8132.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

-392.120.12.0.0
-  __TEXT.__cstring: 0xe686
+392.120.14.0.0
+  __TEXT.__cstring: 0xe888
   __TEXT.__binname: 0x40
   __TEXT.__const: 0xb00
   __TEXT.__chain_starts: 0x78
   __DATA_CONST.__const: 0x68c8
   __LATE_CONST.__late_const: 0x5d6c0
-  __TEXT_EXEC.__text: 0x519e8
+  __TEXT_EXEC.__text: 0x51b84
   __LAST.__pinst: 0x8
   __DATA.__auth_ptr: 0x18
   __DATA.__data: 0x6

   __BOOTDATA.__data: 0x14000
   Functions: 356
   Symbols:   1
-  CStrings:  1809
+  CStrings:  1814
 
Functions:
~ sub_fffffff0270c0c50 : 7716 -> 7796
~ sub_fffffff0270c2a74 -> sub_fffffff0270c2ac4 : 404 -> 92
~ sub_fffffff0270c2c08 -> sub_fffffff0270c2b20 : 92 -> 1320
~ sub_fffffff0270c2c64 -> sub_fffffff0270c3048 : 396 -> 404
~ sub_fffffff0270c2df0 -> sub_fffffff0270c31dc : 568 -> 396
~ sub_fffffff0270c3028 -> sub_fffffff0270c3368 : 1624 -> 872
~ sub_fffffff0270c3680 -> sub_fffffff0270c36d0 : 7384 -> 7716
~ sub_fffffff0270cd9ac -> sub_fffffff0270cdb48 : 68 -> 72
CStrings:
+ "!sptm_add_overflow(src_paddr, (0), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (2 * sizeof(uint32_t)), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (compressed_size), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "!sptm_add_overflow(src_paddr, (sizeof(uint32_t)), &assert_end_paddr) && assert_end_paddr <= hib_image_end_paddr"
+ "header->image1Size > (uintptr_t)page_list_end_paddr - (uintptr_t)header_paddr"
```
