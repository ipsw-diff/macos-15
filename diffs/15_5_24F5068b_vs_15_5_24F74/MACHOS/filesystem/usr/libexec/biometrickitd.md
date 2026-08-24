## biometrickitd

> `/usr/libexec/biometrickitd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 10185.100.20.0.0
-  __TEXT.__text: 0xd1d94
+  __TEXT.__text: 0xd2170
   __TEXT.__auth_stubs: 0x1930
   __TEXT.__objc_stubs: 0x8000
   __TEXT.__objc_methlist: 0x4334
-  __TEXT.__cstring: 0x8246
+  __TEXT.__cstring: 0x82e6
   __TEXT.__objc_methname: 0xe4fc
   __TEXT.__objc_classname: 0x266
   __TEXT.__objc_methtype: 0x10fa

   __DATA_CONST.__got: 0x450
   __DATA_CONST.__auth_ptr: 0x250
   __DATA_CONST.__const: 0x3038
-  __DATA_CONST.__cfstring: 0x5d40
+  __DATA_CONST.__cfstring: 0x5e80
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 4104
   Symbols:   636
-  CStrings:  4057
+  CStrings:  4066
 
Functions:
~ sub_100001c78 : 1204 -> 1216
~ sub_100004ba4 -> sub_100004bb0 : 4 -> 664
~ sub_100004df4 -> sub_100005094 : 164 -> 240
~ sub_1000050d0 -> sub_1000053bc : 1204 -> 1256
~ sub_1000056a8 -> sub_1000059c8 : 1248 -> 1436
~ sub_1000096f8 -> sub_100009ad4 : 872 -> 608
~ sub_100009b88 -> sub_100009e5c : 316 -> 384
~ sub_100009cc4 -> sub_100009fdc : 328 -> 396
~ sub_100009f10 -> sub_10000a26c : 196 -> 224
~ sub_10000a50c -> sub_10000a884 : 276 -> 324
~ sub_10000a620 -> sub_10000a9c8 : 1776 -> 1828
CStrings:
+ "BioLog: Topology"
+ "Coordinates:  [%i,%i,%i]%s"
+ "Image added as node %u"
+ "Image not added"
+ "Image replaced node %u"
+ "Node placement: [%i,%i,%i,%i,%i,%i,["
+ "Parent: %i"
+ "[%i,%i,%i,%i,%i]"
+ "],%i,%i,%i,%i,%i,0x%04x]"
+ "^-1"
- "00000000-SEED-SEED-SEED-000000000000"
```
