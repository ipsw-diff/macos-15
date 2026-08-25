## afplay

> `/usr/bin/afplay`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

-776.600.0.0.0
-  __TEXT.__text: 0x3840
+776.701.0.0.0
+  __TEXT.__text: 0x3844
   __TEXT.__auth_stubs: 0x460
   __TEXT.__objc_stubs: 0x80
   __TEXT.__const: 0x81
Symbols:
+ _AudioFileReadPacketData
- _AudioFileReadPackets
Functions:
~ sub_100002c38 : 456 -> 460
```
