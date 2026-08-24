## com.apple.nke.webcontentfilter

> `com.apple.nke.webcontentfilter`

```diff

-63.3.2.0.0
-  __TEXT.__cstring: 0x1393
+63.4.0.0.0
+  __TEXT.__cstring: 0x13bc
   __TEXT.__const: 0x8
-  __TEXT_EXEC.__text: 0x1bd4
+  __TEXT_EXEC.__text: 0x1c64
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x10c
-  __DATA.__bss: 0x69
+  __DATA.__bss: 0x71
   __DATA_CONST.__auth_got: 0x140
   __DATA_CONST.__got: 0x8
   __DATA_CONST.__const: 0x120
   Functions: 45
-  Symbols:   108
-  CStrings:  157
+  Symbols:   109
+  CStrings:  158
 
Symbols:
+ _gHolyControlOptionsMutex
Functions:
~ _HolyInquisition_start : 1056 -> 1092
~ _HolyInquisition_stop : 460 -> 484
~ _holy_control_getopt_cb : 236 -> 272
~ _holy_cookie_set_original_addr : 48 -> 96
CStrings:
+ "Cannot allocate gHolyControlOptionsMutex"
```
