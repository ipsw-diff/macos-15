## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/Versions/A/FileProvider`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-2882.140.18.0.0
-  __TEXT.__text: 0x14a284
+2882.140.28.0.0
+  __TEXT.__text: 0x14a5b0
   __TEXT.__auth_stubs: 0x1da0
   __TEXT.__objc_methlist: 0xdf1c
   __TEXT.__const: 0x85e

   __DATA_CONST.__objc_superrefs: 0x518
   __DATA_CONST.__objc_arraydata: 0xaa0
   __AUTH_CONST.__auth_got: 0xee0
-  __AUTH_CONST.__const: 0x6a88
+  __AUTH_CONST.__const: 0x6a58
   __AUTH_CONST.__cfstring: 0x11140
   __AUTH_CONST.__objc_const: 0x22fa8
   __AUTH_CONST.__objc_intobj: 0x108

   - /usr/lib/swift/libswift_time.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 7168
+  Functions: 7169
   Symbols:   13700
   CStrings:  9464
 
Symbols:
+ ___block_descriptor_72_e8_32bs_e8_i12?0i8l
+ _fpfs_set_download_quarantine
- ___block_descriptor_56_e8_32bs_e8_i12?0i8l
- ___block_descriptor_60_e8_32bs_e8_i12?0i8l
Functions:
+ _fpfs_set_download_quarantine
~ _fpfs_set_metadata : 208 -> 228
~ ___fpfs_set_metadata_block_invoke : 24 -> 28
~ _fpfs_fset_metadata : 1456 -> 1984
~ _dataless_fault_header_decode : 120 -> 148
~ _fpfs_parse_cmpfs_xattr : 368 -> 392
~ __fset_dataless_cmpfs_xattr : 328 -> 340
~ ___fpfs_create_dataless_fault_at_block_invoke : 200 -> 208
~ _fpfs_update_dataless_fault : 92 -> 100
~ _fpfs_update_dataless_fault_at : 204 -> 224
~ ___fpfs_update_dataless_fault_at_block_invoke : 20 -> 24
~ _fpfs_materialize : 2028 -> 2044
~ _fpfs_evict : 1792 -> 1808
CStrings:
+ "2882.140.28"
- "2882.140.18"
```
