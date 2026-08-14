## t603xdcp.im4p

> `Firmware/dcp/t603xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__lcxx_override`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2bb7b8
-  __TEXT.__const: 0x3a99ec
+  __TEXT.__text: 0x2bbd50
+  __TEXT.__const: 0x3a9c1c
   __TEXT.__chain_starts: 0x5c
-  __TEXT.__cstring: 0x3106c
+  __TEXT.__cstring: 0x31147
   __TEXT.__lcxx_override: 0x64
   __DATA.__const: 0x33148
   __DATA.__data: 0x11ef34

   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x580
   __OS_LOG.__string: 0x22020
-  Functions: 6710
+  Functions: 6711
   Symbols:   0
-  CStrings:  6180
+  CStrings:  6183
 
CStrings:
+ "IOMFB removing mode with odd Hactive : %d\n"
+ "Mode: id=%llu %ux%u@%u.%uHz, pEnc=0x%x, type=%u, st=%u, v=%u, cc=%u, pCl=%u, sc=%u\n"
+ "Mode: sType=%u total=%ux%u, hBack=%u, vBack=%u, hFront=%u, vFront=%u, hSync=%u, vSync=%u, apCl=%u, ar=%u, cr=%u\n"
+ "This monitor has timing with vblank=%d us < spec threshold of 300us \n"
- "VFP:%d, VBP: %d, VSYNC_WIDTH: %d, HTOTAL:%d, VTOTAL:%d, pixel clock: %d, linetime: %d (ns)"
```
