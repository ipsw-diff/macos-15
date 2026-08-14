## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/Versions/A/APFS`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-2332.120.27.0.0
-  __TEXT.__text: 0x57200
+2332.120.29.0.0
+  __TEXT.__text: 0x571f8
   __TEXT.__auth_stubs: 0xcf0
   __TEXT.__const: 0x8120
   __TEXT.__cstring: 0xef01
Functions:
~ _create_synthetic_elements_on_volume_group : 1044 -> 1032
~ _bitmap_count_bits : 300 -> 296
~ create_synthetic_elements_on_volume_group.cold.4 : 152 -> 172
~ create_synthetic_elements_on_volume_group.cold.5 : 164 -> 152
CStrings:
+ "2332.120.29"
- "2332.120.27"
```
