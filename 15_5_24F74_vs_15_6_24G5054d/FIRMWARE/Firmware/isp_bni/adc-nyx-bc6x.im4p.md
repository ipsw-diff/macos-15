## adc-nyx-bc6x.im4p

> `Firmware/isp_bni/adc-nyx-bc6x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.text_env`
- `__TEXT._rtk_mtab`
- `__TEXT.__data_copy`
- `__DATA.__data`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x80365c
+  __TEXT.__text: 0x8036ac
   __TEXT.__const: 0x1fd554
   __TEXT.text_env: 0x28718
   __TEXT._rtk_mtab: 0x2b8
-  __TEXT.__cstring: 0xdd2f8
+  __TEXT.__cstring: 0xdd348
   __TEXT.__data_copy: 0x180000
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
-  __DATA.__const: 0x37e08
+  __DATA.__const: 0x37e10
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xd83a8
   __DATA._rtk_power: 0x368

   __DATA.__zerofill: 0xf42020
   Functions: 0
   Symbols:   0
-  CStrings:  24520
+  CStrings:  24521
 
CStrings:
+ "%s reset contextSwitchTag %d\n"
+ "02:25:46"
+ "pCmd->numBuses <= (sizeof(pCmd->busBase)/sizeof(pCmd->busBase[0]))"
- "21:21:28"
- "SPMI bus %u base %zu\n"
```
