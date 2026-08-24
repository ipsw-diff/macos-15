## adc-eris-j129.im4p

> `Firmware/isp_bni/adc-eris-j129.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.text_env`
- `__TEXT._rtk_mtab`
- `__TEXT.__data_copy`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA._rtk_smp_main`

```diff

-  __TEXT.__text: 0x7b7f3c
+  __TEXT.__text: 0x7b7fe8
   __TEXT.__const: 0x1f0644
   __TEXT.text_env: 0x5dba8
   __TEXT._rtk_mtab: 0x2b8
-  __TEXT.__cstring: 0xf0b58
+  __TEXT.__cstring: 0xf0ba8
   __TEXT.__data_copy: 0x190000
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
-  __DATA.__const: 0x39c68
+  __DATA.__const: 0x39c70
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xdb1b0
   __DATA._rtk_power: 0x3a8

   __DATA.__zerofill: 0x337f20
   Functions: 0
   Symbols:   0
-  CStrings:  26676
+  CStrings:  26677
 
CStrings:
+ "%s reset contextSwitchTag %d\n"
+ "02:24:51"
+ "pCmd->numBuses <= (sizeof(pCmd->busBase)/sizeof(pCmd->busBase[0]))"
- "21:20:41"
- "SPMI bus %u base %zu\n"
```
