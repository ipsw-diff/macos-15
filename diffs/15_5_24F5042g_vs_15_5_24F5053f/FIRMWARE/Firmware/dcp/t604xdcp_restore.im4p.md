## t604xdcp_restore.im4p

> `Firmware/dcp/t604xdcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__TEXT.__lcxx_override`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2d5d94
-  __TEXT.__const: 0x3b7ba4
+  __TEXT.__text: 0x2d5f28
+  __TEXT.__const: 0x3b7ee4
   __TEXT.__chain_starts: 0x5c
-  __TEXT.__cstring: 0x3270a
+  __TEXT.__cstring: 0x327e5
   __TEXT.__lcxx_override: 0x64
-  __DATA.__const: 0x35c80
+  __DATA.__const: 0x35c90
   __DATA.__data: 0x11fd70
   __DATA._rtk_patchbay: 0x734
   __DATA.__constructor: 0x8

   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x5a0
   __OS_LOG.__string: 0x2243a
-  Functions: 6894
+  Functions: 6892
   Symbols:   0
-  CStrings:  6355
+  CStrings:  6358
 
CStrings:
+ "IOMFB removing mode with odd Hactive : %d\n"
+ "Mode: id=%llu %ux%u@%u.%uHz, pEnc=0x%x, type=%u, st=%u, v=%u, cc=%u, pCl=%u, sc=%u\n"
+ "Mode: sType=%u total=%ux%u, hBack=%u, vBack=%u, hFront=%u, vFront=%u, hSync=%u, vSync=%u, apCl=%u, ar=%u, cr=%u\n"
+ "This monitor has timing with vblank=%d us < spec threshold of 300us \n"
- "VFP:%d, VBP: %d, VSYNC_WIDTH: %d, HTOTAL:%d, VTOTAL:%d, pixel clock: %d, linetime: %d (ns)"
```
