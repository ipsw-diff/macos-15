## mediaanalysisd

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/Versions/A/mediaanalysisd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-325.3.1.0.0
-  __TEXT.__text: 0x1a80c4
+325.4.1.0.0
+  __TEXT.__text: 0x1a8568
   __TEXT.__auth_stubs: 0xeb0
   __TEXT.__objc_stubs: 0x12be0
   __TEXT.__objc_methlist: 0x9178
-  __TEXT.__gcc_except_tab: 0x31b64
+  __TEXT.__gcc_except_tab: 0x31c08
   __TEXT.__cstring: 0x13a1e
   __TEXT.__objc_classname: 0x1b92
   __TEXT.__objc_methname: 0x19aee
   __TEXT.__objc_methtype: 0x33fe
   __TEXT.__const: 0x430
-  __TEXT.__oslogstring: 0x21df9
+  __TEXT.__oslogstring: 0x21f2b
   __TEXT.__dlopen_cstrs: 0x3b2
   __TEXT.__unwind_info: 0x5b88
   __DATA_CONST.__auth_got: 0x770

   - /usr/lib/libsqlite3.dylib
   Functions: 3964
   Symbols:   679
-  CStrings:  8806
+  CStrings:  8810
 
Functions:
~ sub_10000cf64 : 2096 -> 2724
~ sub_100078e2c -> sub_1000790a0 : 2296 -> 2480
~ sub_100079724 -> sub_100079a50 : 2712 -> 2884
~ sub_1000b1210 -> sub_1000b15e8 : 2192 -> 2396
CStrings:
+ "%@ Analysis has future version (v%d); discarding existing analysis"
+ "[MergeAnalysis]%@ Analysis A has future version (v%d), use B: %@"
+ "[MergeAnalysis]%@ Analysis B has future version (v%d), use A: %@"
+ "[MergeAnalysis]%@ Both analyses have future versions (A: v%d, B: v%d, current: %d), no valid analysis to use"
```
