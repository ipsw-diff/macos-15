## CMIOBaseUnits

> `/System/Library/Frameworks/CoreMediaIO.framework/Versions/Current/Resources/BaseUnits/CMIOBaseUnits.bundle/Contents/MacOS/CMIOBaseUnits`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

 5590.122.2.0.1
-  __TEXT.__text: 0x10dca8
-  __TEXT.__auth_stubs: 0x1fa0
+  __TEXT.__text: 0x10df70
+  __TEXT.__auth_stubs: 0x1fb0
   __TEXT.__objc_stubs: 0x1060
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x1a0
-  __TEXT.__cstring: 0x9750
+  __TEXT.__cstring: 0x97f8
   __TEXT.__const: 0x133e
-  __TEXT.__oslogstring: 0x193c3
-  __TEXT.__gcc_except_tab: 0xb944
+  __TEXT.__oslogstring: 0x19410
+  __TEXT.__gcc_except_tab: 0xb948
   __TEXT.__objc_classname: 0x4d
-  __TEXT.__objc_methname: 0x1144
+  __TEXT.__objc_methname: 0x115b
   __TEXT.__objc_methtype: 0x3de
   __TEXT.__dlopen_cstrs: 0xa0
   __TEXT.__unwind_info: 0x2cd8
   __TEXT.__eh_frame: 0x50
-  __DATA_CONST.__auth_got: 0xfe0
+  __DATA_CONST.__auth_got: 0xfe8
   __DATA_CONST.__got: 0x728
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0x7d08
-  __DATA_CONST.__cfstring: 0x2500
+  __DATA_CONST.__cfstring: 0x25e0
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__objc_intobj: 0x108
   __DATA_CONST.__objc_arraydata: 0xa0
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA.__objc_const: 0x9d8
+  __DATA.__objc_const: 0x9f8
   __DATA.__objc_selrefs: 0x438
-  __DATA.__objc_ivar: 0xec
+  __DATA.__objc_ivar: 0xf0
   __DATA.__objc_data: 0x140
   __DATA.__data: 0x40
   __DATA.__bss: 0x3bc

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 3519
-  Symbols:   775
-  CStrings:  2795
+  Symbols:   776
+  CStrings:  2805
 
Symbols:
+ _CFPreferencesGetAppBooleanValue
Functions:
~ sub_29f78 : 1780 -> 1996
~ sub_2a66c -> sub_2a744 : 308 -> 512
~ sub_2b3c0 -> sub_2b564 : 3640 -> 3652
~ sub_2c718 -> sub_2c8c8 : 5096 -> 5236
~ sub_3dd58 -> sub_3df94 : 1576 -> 1664
~ sub_95a04 -> sub_95c98 : 5852 -> 5904
CStrings:
+ "%s:%d:%s effect quality override %d"
+ "%s:%d:%s effect quality override %d %llu"
+ "AEAverage"
+ "AETarget"
+ "CMIO_Unit_Helpers_PortraitBlur.EffectQualityOverride"
+ "CMIO_Unit_Helpers_PortraitBlur.facesForReactions"
+ "DebugMetadataSEI"
+ "_effectQualityOverride"
+ "com.apple.coremedia"
+ "debug_sei"
```
