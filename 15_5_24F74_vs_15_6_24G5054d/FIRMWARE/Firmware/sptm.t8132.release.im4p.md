## sptm.t8132.release.im4p

> `Firmware/sptm.t8132.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

-392.120.16.0.0
-  __TEXT.__cstring: 0xe865
+392.140.5.0.0
+  __TEXT.__cstring: 0xec2b
   __TEXT.__binname: 0x40
-  __TEXT.__const: 0xb00
+  __TEXT.__const: 0x9f0
   __TEXT.__chain_starts: 0x78
   __DATA_CONST.__const: 0x68c8
   __LATE_CONST.__late_const: 0x5d6c0
-  __TEXT_EXEC.__text: 0x51b84
+  __TEXT_EXEC.__text: 0x51f1c
   __LAST.__pinst: 0x8
   __DATA.__auth_ptr: 0x18
   __DATA.__data: 0x6
   __DATA.__common: 0x9290
-  __DATA.__bss: 0x5c20
+  __DATA.__bss: 0x5d28
   __BOOTDATA.__data: 0x14000
-  Functions: 356
+  Functions: 352
   Symbols:   1
-  CStrings:  1813
+  CStrings:  1835
 
CStrings:
+ "!sptm_add_overflow(bank_page_count, bitmapword_bits - 1, &roundup)"
+ "!sptm_add_overflow(pages_seen, bank_page_count, &pages_seen)"
+ "((uintptr_t)hib_ctx->aop_gapf_lock_reg & ~SPTM_PAGE_MASK) == reg_page"
+ "(end - ptr) >= (bank->bitmapwords * sizeof(bank->bitmap[0]))"
+ "(end - ptr) >= (sizeof(hibernate_bitmap_t))"
+ "(end - ptr) >= (sizeof(hibernate_page_list_t))"
+ "(header != NULL) && (list != NULL)"
+ "Failed to read sptm-gapf-enable-reg property."
+ "Failed to read sptm-gapf-lock-reg property."
+ "arm-io/aop/iop-aop-nub/aop-gapf-filters"
+ "bank->bitmapwords == (roundup / bitmapword_bits)"
+ "bank->first_page > last_page_seen"
+ "bank->last_page >= bank->first_page"
+ "bank_page_count > 0"
+ "hdr_page_list_length >= sizeof(hibernate_page_list_t)"
+ "list->list_size <= hdr_page_list_length"
+ "pages_seen <= list->page_count"
+ "pages_seen == list->page_count"
+ "sptm-gapf-enable-reg"
+ "sptm-gapf-enable-reg property size is incorrect."
+ "sptm-gapf-lock-reg"
+ "sptm-gapf-lock-reg property size is incorrect."
```
