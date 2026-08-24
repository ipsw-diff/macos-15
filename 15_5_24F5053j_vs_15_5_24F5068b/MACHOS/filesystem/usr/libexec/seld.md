## seld

> `/usr/libexec/seld`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-355.3.0.0.0
-  __TEXT.__text: 0x3cde0
+355.4.0.0.0
+  __TEXT.__text: 0x3c750
   __TEXT.__auth_stubs: 0x720
-  __TEXT.__objc_stubs: 0x3320
+  __TEXT.__objc_stubs: 0x3360
   __TEXT.__objc_methlist: 0xef4
   __TEXT.__const: 0x1c0
   __TEXT.__gcc_except_tab: 0x1708
-  __TEXT.__objc_methname: 0x3eaf
-  __TEXT.__cstring: 0x674d
+  __TEXT.__objc_methname: 0x3ee2
+  __TEXT.__cstring: 0x6731
   __TEXT.__oslogstring: 0x4f16
   __TEXT.__objc_classname: 0x254
   __TEXT.__objc_methtype: 0xc97
-  __TEXT.__unwind_info: 0x638
+  __TEXT.__unwind_info: 0x650
   __DATA_CONST.__auth_got: 0x3a0
-  __DATA_CONST.__got: 0x220
+  __DATA_CONST.__got: 0x228
   __DATA_CONST.__const: 0xb00
-  __DATA_CONST.__cfstring: 0x1e20
+  __DATA_CONST.__cfstring: 0x1de0
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_dictobj: 0xa0
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x1e18
-  __DATA.__objc_selrefs: 0x1130
+  __DATA.__objc_selrefs: 0x1140
   __DATA.__objc_ivar: 0x1cc
   __DATA.__objc_data: 0x370
   __DATA.__data: 0x4e0

   - /usr/lib/libnfshared.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 388
-  Symbols:   194
+  Symbols:   195
   CStrings:  1553
 
Symbols:
+ _OBJC_CLASS_$_NFXPCConnectionUserInfoDictionary
Functions:
~ sub_10001dfa0 : 1836 -> 1812
~ sub_10001e6f8 -> sub_10001e6e0 : 664 -> 600
~ sub_10001f320 -> sub_10001f2c8 : 724 -> 660
~ sub_10001f5f4 -> sub_10001f55c : 596 -> 532
~ sub_1000247f4 -> sub_10002471c : 848 -> 792
~ sub_100024b44 -> sub_100024a34 : 2192 -> 2128
~ sub_100025b00 -> sub_1000259b0 : 880 -> 816
~ sub_100025e70 -> sub_100025ce0 : 572 -> 500
~ sub_100026944 -> sub_10002676c : 880 -> 816
~ sub_100026cb4 -> sub_100026a9c : 572 -> 500
~ sub_100027fe0 -> sub_100027d80 : 804 -> 748
~ sub_100028304 -> sub_10002806c : 5372 -> 5308
~ sub_100029800 -> sub_100029528 : 756 -> 668
~ sub_100029af4 -> sub_1000297c4 : 1192 -> 1128
~ sub_10002a4e8 -> sub_10002a178 : 756 -> 668
~ sub_10002a7dc -> sub_10002a414 : 784 -> 712
~ sub_10002b88c -> sub_10002b47c : 756 -> 668
~ sub_10002bb80 -> sub_10002b718 : 704 -> 632
~ sub_10002be50 -> sub_10002b9a0 : 756 -> 668
~ sub_10002c144 -> sub_10002bc3c : 704 -> 632
~ sub_10002c414 -> sub_10002bec4 : 756 -> 668
~ sub_10002c708 -> sub_10002c160 : 704 -> 632
~ sub_10002c9d8 -> sub_10002c3e8 : 756 -> 668
~ sub_10002cccc -> sub_10002c684 : 868 -> 796
CStrings:
+ "NF_clientName"
+ "initWithServiceWhitelist:clientName:"
- "ClientName"
- "ServiceWhitelist"
```
