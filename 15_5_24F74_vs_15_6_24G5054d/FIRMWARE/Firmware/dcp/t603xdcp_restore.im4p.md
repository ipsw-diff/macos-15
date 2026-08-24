## t603xdcp_restore.im4p

> `Firmware/dcp/t603xdcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__TEXT.__lcxx_override`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2b949c
-  __TEXT.__const: 0x3a9c34
+  __TEXT.__text: 0x2b9480
+  __TEXT.__const: 0x3a9c74
   __TEXT.__chain_starts: 0x5c
-  __TEXT.__cstring: 0x31147
+  __TEXT.__cstring: 0x31185
   __TEXT.__lcxx_override: 0x64
-  __DATA.__const: 0x33148
-  __DATA.__data: 0x11ef3c
+  __DATA.__const: 0x33170
+  __DATA.__data: 0x11ef34
   __DATA._rtk_patchbay: 0x734
   __DATA.__constructor: 0x8
   __DATA._rtk_tunables: 0x5b0

   __DATA._rtk_data_uuid: 0x40
   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x580
-  __OS_LOG.__string: 0x22020
+  __OS_LOG.__string: 0x21fd1
   Functions: 6715
   Symbols:   0
   CStrings:  6183
CStrings:
+ "A44614"
+ "IOMFB DEBUG PANIC: TE watchdog Int: %d Start: %d Status: %d TE updating: %d FastTE_WAR %d"
+ "IOMFB: %s: swallowed fast update swap ID %d as main display is unplugged \n"
- "IOMFB DEBUG PANIC: TE watchdog Int: %d Start: %d Status: %d"
- "failed to disable MST mode ret=0x%x"
- "willTrainLink"
```
