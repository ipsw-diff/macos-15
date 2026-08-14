## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1284.13.0.0.0
-  __TEXT.__text: 0x86dcc
+1284.15.0.0.0
+  __TEXT.__text: 0x86d4c
   __TEXT.__const: 0x2380
   __TEXT.__cstring: 0x10026
   __TEXT.__unwind_info: 0x4a8
Functions:
~ __ZN10AAREncoder7addFileENSt3__117basic_string_viewIcNS0_11char_traitsIcEEEENS0_4spanISt4byteLm18446744073709551615EEE : 136 -> 140
~ __ZN3lsl6VectorIN10AAREncoder4LinkEE6resizeEy : 148 -> 144
~ ____ZN5dyld423ExternallyViewableState34notifyMonitorOfImageListChangesSimEbjPPK11mach_headerPPKc_block_invoke : 2832 -> 2676
~ __ZN12_GLOBAL__N_19quickSortIPPN12PropertyList4DataEEEvT_S5_ : 336 -> 332
~ _ZNK10AAREncoder10encodeFileERKNS_4FileER10ByteStream.cold.1 : 72 -> 104
CStrings:
+ "1284.15"
- "1284.13"
```
