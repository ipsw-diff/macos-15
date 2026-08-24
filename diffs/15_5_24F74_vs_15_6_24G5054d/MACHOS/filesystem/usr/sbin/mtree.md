## mtree

> `/usr/sbin/mtree`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-457.120.3.0.0
-  __TEXT.__text: 0x8dd8
+457.140.3.0.0
+  __TEXT.__text: 0x8e50
   __TEXT.__auth_stubs: 0x7a0
   __TEXT.__const: 0x6f7
-  __TEXT.__cstring: 0x15bc
+  __TEXT.__cstring: 0x15bd
   __TEXT.__unwind_info: 0x198
   __TEXT.__eh_frame: 0x40
   __DATA_CONST.__auth_got: 0x3d0

   __DATA_CONST.__cfstring: 0x20
   __DATA.__data: 0x300
   __DATA.__bss: 0x830
-  __DATA.__common: 0x4f8
+  __DATA.__common: 0x500
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /usr/lib/libSystem.B.dylib
   Functions: 139
Functions:
~ sub_1000055f4 : 2188 -> 2228
~ sub_100007884 -> sub_1000078ac : 984 -> 1044
~ sub_100007c5c -> sub_100007cc0 : 1180 -> 1200
CStrings:
+ "cdef:iK:k:LnPp:qrs:UuvwxX:m:F:t:E:SD"
- "cdef:iK:k:LnPp:qrs:UuwxX:m:F:t:E:SD"
```
