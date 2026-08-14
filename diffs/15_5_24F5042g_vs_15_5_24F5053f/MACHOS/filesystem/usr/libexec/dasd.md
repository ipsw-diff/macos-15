## dasd

> `/usr/libexec/dasd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1856.120.8.0.0
-  __TEXT.__text: 0xe1e40
+1856.120.11.0.0
+  __TEXT.__text: 0xe1eb4
   __TEXT.__auth_stubs: 0xf50
   __TEXT.__objc_stubs: 0x11de0
   __TEXT.__objc_methlist: 0xd5a8
   __TEXT.__const: 0x5b8
   __TEXT.__objc_methname: 0x1e1c7
-  __TEXT.__cstring: 0xa55f
+  __TEXT.__cstring: 0xa5ad
   __TEXT.__oslogstring: 0xbf8e
   __TEXT.__objc_classname: 0x13bf
   __TEXT.__objc_methtype: 0x2536

   __DATA_CONST.__got: 0x7a8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x2f08
-  __DATA_CONST.__cfstring: 0xb220
+  __DATA_CONST.__cfstring: 0xb280
   __DATA_CONST.__objc_classlist: 0x520
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x138

   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x470
   __DATA_CONST.__objc_intobj: 0xcd8
-  __DATA_CONST.__objc_arraydata: 0xe8
+  __DATA_CONST.__objc_arraydata: 0x100
   __DATA_CONST.__objc_arrayobj: 0x78
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_dictobj: 0xc8

   - /usr/lib/libperfcheck.dylib
   Functions: 5343
   Symbols:   508
-  CStrings:  8008
+  CStrings:  8011
 
Functions:
~ sub_1000160cc : 168 -> 180
~ sub_1000b2620 -> sub_1000b262c : 2308 -> 2412
CStrings:
+ "com.apple.backupd.cellular"
+ "com.apple.backupd.onBattery"
+ "com.apple.backupd.wifi"
```
