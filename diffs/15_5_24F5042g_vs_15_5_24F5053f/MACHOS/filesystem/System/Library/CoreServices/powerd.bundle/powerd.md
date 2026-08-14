## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1754.100.38.0.0
-  __TEXT.__text: 0x5d860
+1754.120.2.0.0
+  __TEXT.__text: 0x5d940
   __TEXT.__auth_stubs: 0x1c90
   __TEXT.__objc_stubs: 0x3580
   __TEXT.__objc_methlist: 0x169c

   __TEXT.__gcc_except_tab: 0x358
   __TEXT.__cstring: 0x6f18
   __TEXT.__objc_methname: 0x4af4
-  __TEXT.__oslogstring: 0x9206
+  __TEXT.__oslogstring: 0x922e
   __TEXT.__objc_classname: 0x1a4
   __TEXT.__objc_methtype: 0x533
   __TEXT.__dlopen_cstrs: 0x104

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x50
-  __DATA_CONST.__objc_intobj: 0x1e0
+  __DATA_CONST.__objc_intobj: 0x210
   __DATA_CONST.__objc_arraydata: 0x160
   __DATA_CONST.__objc_dictobj: 0xc8
   __DATA_CONST.__objc_doubleobj: 0x10

   - /usr/lib/libsystemstats.dylib
   Functions: 1882
   Symbols:   566
-  CStrings:  3161
+  CStrings:  3162
 
Functions:
~ sub_10003fed0 : 2340 -> 2564
CStrings:
+ "Value for key %@ is not a NSNumber type"
```
