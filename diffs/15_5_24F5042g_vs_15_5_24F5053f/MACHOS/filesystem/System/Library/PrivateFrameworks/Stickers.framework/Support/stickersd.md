## stickersd

> `/System/Library/PrivateFrameworks/Stickers.framework/Support/stickersd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-35.306.0.0.0
-  __TEXT.__text: 0xe550
-  __TEXT.__auth_stubs: 0xbd0
+35.307.0.0.0
+  __TEXT.__text: 0xe618
+  __TEXT.__auth_stubs: 0xbe0
   __TEXT.__objc_stubs: 0x40
   __TEXT.__objc_methlist: 0x3d4
   __TEXT.__const: 0x484
-  __TEXT.__cstring: 0x74a
+  __TEXT.__cstring: 0x8be
   __TEXT.__oslogstring: 0xbb3
   __TEXT.__swift5_typeref: 0x263
   __TEXT.__objc_methname: 0x5e7

   __TEXT.__swift_as_entry: 0x1c
   __TEXT.__swift_as_ret: 0x14
   __TEXT.__unwind_info: 0x348
-  __TEXT.__eh_frame: 0x278
-  __DATA_CONST.__auth_got: 0x5f0
+  __TEXT.__eh_frame: 0x280
+  __DATA_CONST.__auth_got: 0x5f8
   __DATA_CONST.__got: 0x1c8
   __DATA_CONST.__auth_ptr: 0x148
   __DATA_CONST.__const: 0x570

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 259
-  Symbols:   300
-  CStrings:  206
+  Symbols:   301
+  CStrings:  211
 
Symbols:
+ _os_transaction_create
Functions:
~ sub_10000ab64 : 2660 -> 2696
~ sub_10000b758 -> sub_10000b77c : 532 -> 560
~ sub_10000be7c -> sub_10000bebc : 1208 -> 1236
~ sub_10000df00 -> sub_10000df5c : 3552 -> 3660
CStrings:
+ "com.apple.stickersd.StickerIndexingClient.provideDataForBundleID"
+ "com.apple.stickersd.StickerIndexingClient.provideDataForManagedRepresentation"
+ "com.apple.stickersd.StickerIndexingClient.provideDataForStickerRepresentation"
+ "com.apple.stickersd.StickerIndexingClient.reindexAllItems"
+ "com.apple.stickersd.StickerIndexingClient.reindexItems"
```
