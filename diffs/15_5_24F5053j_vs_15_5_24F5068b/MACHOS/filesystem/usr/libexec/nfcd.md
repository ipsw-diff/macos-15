## nfcd

> `/usr/libexec/nfcd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-355.3.0.0.0
-  __TEXT.__text: 0x1e8bbc
+355.4.0.0.0
+  __TEXT.__text: 0x1e7af0
   __TEXT.__auth_stubs: 0x1350
-  __TEXT.__objc_stubs: 0xa300
+  __TEXT.__objc_stubs: 0xa340
   __TEXT.__objc_methlist: 0x7300
   __TEXT.__const: 0x1090
   __TEXT.__dlopen_cstrs: 0x70
   __TEXT.__oslogstring: 0x1cc7b
-  __TEXT.__cstring: 0x257aa
+  __TEXT.__cstring: 0x25799
   __TEXT.__objc_classname: 0x1461
-  __TEXT.__objc_methname: 0x13093
+  __TEXT.__objc_methname: 0x130c6
   __TEXT.__objc_methtype: 0x3c7e
-  __TEXT.__gcc_except_tab: 0x5698
-  __TEXT.__unwind_info: 0x2678
+  __TEXT.__gcc_except_tab: 0x56a4
+  __TEXT.__unwind_info: 0x2670
   __DATA_CONST.__auth_got: 0x9b8
-  __DATA_CONST.__got: 0x378
+  __DATA_CONST.__got: 0x380
   __DATA_CONST.__const: 0x5260
-  __DATA_CONST.__cfstring: 0xe820
+  __DATA_CONST.__cfstring: 0xe800
   __DATA_CONST.__objc_classlist: 0x468
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x278

   __DATA_CONST.__objc_protorefs: 0x140
   __DATA_CONST.__objc_superrefs: 0x2f8
   __DATA_CONST.__objc_intobj: 0x55f8
-  __DATA_CONST.__objc_arraydata: 0x1a10
+  __DATA_CONST.__objc_arraydata: 0x1a08
   __DATA_CONST.__objc_arrayobj: 0x120
   __DATA_CONST.__objc_dictobj: 0xbe0
   __DATA.__objc_const: 0xefa8
-  __DATA.__objc_selrefs: 0x4558
+  __DATA.__objc_selrefs: 0x4568
   __DATA.__objc_ivar: 0xc28
   __DATA.__objc_data: 0x2c10
   __DATA.__data: 0x1df0

   - /usr/lib/libnfshared.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 3272
-  Symbols:   430
-  CStrings:  8039
+  Symbols:   431
+  CStrings:  8040
 
Symbols:
+ _OBJC_CLASS_$_NFXPCConnectionUserInfoDictionary
Functions:
~ sub_100022c94 : 2288 -> 2264
~ sub_100067b24 -> sub_100067b0c : 1116 -> 1052
~ sub_1000827c8 -> sub_100082770 : 172 -> 132
~ sub_1000abfac -> sub_1000abf2c : 444 -> 408
~ sub_1000ac80c -> sub_1000ac768 : 252 -> 220
~ sub_1000ac908 -> sub_1000ac844 : 312 -> 280
~ sub_1000bd0b4 -> sub_1000bcfd0 : 932 -> 820
~ sub_1000bd7d0 -> sub_1000bd67c : 1044 -> 976
~ sub_1000bdbe4 -> sub_1000bda4c : 696 -> 620
~ sub_1000bdf98 -> sub_1000bddb4 : 1368 -> 1304
~ sub_1000be6a0 -> sub_1000be47c : 1156 -> 988
~ sub_1000c5d84 -> sub_1000c5ab8 : 1320 -> 1248
~ sub_1000c6fa0 -> sub_1000c6c8c : 4024 -> 4100
~ sub_1000d12d4 -> sub_1000d100c : 3540 -> 3320
~ sub_1000d20a8 -> sub_1000d1d04 : 2656 -> 2488
~ sub_1000d32e4 -> sub_1000d2e98 : 3780 -> 3548
~ sub_1000d4964 -> sub_1000d4430 : 3744 -> 3500
~ sub_1000d5fc0 -> sub_1000d5998 : 3036 -> 2844
~ sub_1000d6fe4 -> sub_1000d68fc : 4044 -> 3776
~ sub_1000d89c8 -> sub_1000d81d4 : 1168 -> 1116
~ sub_1000d92ec -> sub_1000d8ac4 : 4616 -> 4516
~ sub_1000da878 -> sub_1000d9fec : 2656 -> 2488
~ sub_1000dba68 -> sub_1000db134 : 2476 -> 2272
~ sub_1000dcba4 -> sub_1000dc1a4 : 3084 -> 2812
~ sub_1000dd7ec -> sub_1000dccdc : 6032 -> 5696
~ sub_1000df1c4 -> sub_1000de564 : 3652 -> 3380
~ sub_1000e0044 -> sub_1000df2d4 : 2364 -> 2180
~ sub_1000e09bc -> sub_1000dfb94 : 1616 -> 1452
~ sub_1000e1048 -> sub_1000e017c : 2720 -> 2552
~ sub_1000e1c0c -> sub_1000e0c98 : 900 -> 804
~ sub_1000e2088 -> sub_1000e10b4 : 880 -> 792
~ sub_1000ee120 -> sub_1000ed0f4 : 596 -> 564
~ sub_10013a880 -> sub_100139834 : 5464 -> 5432
~ sub_1001ac014 -> sub_1001aafa8 : 1260 -> 1164
CStrings:
+ "NFCD built from (B&I) Stockholm_Base-355.4"
+ "NF_clientName"
+ "initWithServiceWhitelist:clientName:"
- "NFCD built from (B&I) Stockholm_Base-355.3"
- "ServiceWhitelist"
```
