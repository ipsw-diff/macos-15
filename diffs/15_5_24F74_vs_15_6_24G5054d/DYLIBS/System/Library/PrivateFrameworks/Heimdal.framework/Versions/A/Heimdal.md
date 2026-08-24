## Heimdal

> `/System/Library/PrivateFrameworks/Heimdal.framework/Versions/A/Heimdal`

```diff

-693.100.10.0.0
-  __TEXT.__text: 0xaca8c
+693.140.2.0.0
+  __TEXT.__text: 0xacacc
   __TEXT.__auth_stubs: 0x19e0
-  __TEXT.__const: 0xe88
-  __TEXT.__cstring: 0xfbbd
+  __TEXT.__const: 0xe80
+  __TEXT.__cstring: 0xfbce
   __TEXT.__oslogstring: 0xb
   __TEXT.__gcc_except_tab: 0x2c
   __TEXT.__unwind_info: 0xb20

   - /usr/lib/libresolv.9.dylib
   Functions: 2755
   Symbols:   4525
-  CStrings:  2375
+  CStrings:  2376
 
Functions:
~ _send_kkdcp : 568 -> 616
~ ___send_kkdcp_block_invoke : 324 -> 340
CStrings:
+ "kkdcp : (%s)"
+ "kkdcp: got %d bytes, feeding them back: %s"
- "kkdcp: got %d bytes, feeding them back"
```
