## ipad13dcp.im4p

> `Firmware/dcp/ipad13dcp.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2bf170
-  __TEXT.__const: 0x3c8e44
+  __TEXT.__text: 0x2bf6ec
+  __TEXT.__const: 0x3c912c
   __TEXT.__chain_starts: 0x5c
-  __TEXT.__cstring: 0x308c0
+  __TEXT.__cstring: 0x3099b
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x64

   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x560
   __OS_LOG.__string: 0x21d97
-  Functions: 6750
+  Functions: 6751
   Symbols:   0
-  CStrings:  6087
+  CStrings:  6090
 
CStrings:
+ "IOMFB removing mode with odd Hactive : %d\n"
+ "Mode: id=%llu %ux%u@%u.%uHz, pEnc=0x%x, type=%u, st=%u, v=%u, cc=%u, pCl=%u, sc=%u\n"
+ "Mode: sType=%u total=%ux%u, hBack=%u, vBack=%u, hFront=%u, vFront=%u, hSync=%u, vSync=%u, apCl=%u, ar=%u, cr=%u\n"
+ "This monitor has timing with vblank=%d us < spec threshold of 300us \n"
- "VFP:%d, VBP: %d, VSYNC_WIDTH: %d, HTOTAL:%d, VTOTAL:%d, pixel clock: %d, linetime: %d (ns)"
```
