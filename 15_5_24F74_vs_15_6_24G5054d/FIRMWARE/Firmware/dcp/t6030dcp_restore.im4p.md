## t6030dcp_restore.im4p

> `Firmware/dcp/t6030dcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__TEXT.__lcxx_override`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2b5d34
-  __TEXT.__const: 0x3a8cf4
+  __TEXT.__text: 0x2b5d18
+  __TEXT.__const: 0x3a8d24
   __TEXT.__chain_starts: 0x50
-  __TEXT.__cstring: 0x30ff1
+  __TEXT.__cstring: 0x3102f
   __TEXT.__lcxx_override: 0x64
-  __DATA.__const: 0x316f0
-  __DATA.__data: 0x11dcb0
+  __DATA.__const: 0x31718
+  __DATA.__data: 0x11dca8
   __DATA._rtk_patchbay: 0x734
   __DATA.__constructor: 0x8
   __DATA._rtk_tunables: 0x5b0

   __DATA._rtk_data_uuid: 0x40
   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x580
-  __OS_LOG.__string: 0x22003
+  __OS_LOG.__string: 0x21fb4
   Functions: 6699
   Symbols:   0
   CStrings:  6174
CStrings:
+ "A44614"
+ "IOMFB DEBUG PANIC: TE watchdog Int: %d Start: %d Status: %d TE updating: %d FastTE_WAR %d"
+ "IOMFB: %s: swallowed fast update swap ID %d as main display is unplugged \n"
- "IOMFB DEBUG PANIC: TE watchdog Int: %d Start: %d Status: %d"
- "failed to disable MST mode ret=0x%x"
- "willTrainLink"
```
