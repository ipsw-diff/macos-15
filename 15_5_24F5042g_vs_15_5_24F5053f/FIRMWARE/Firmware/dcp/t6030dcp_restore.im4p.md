## t6030dcp_restore.im4p

> `Firmware/dcp/t6030dcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__lcxx_override`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2b5680
-  __TEXT.__const: 0x3a8ab4
+  __TEXT.__text: 0x2b5c18
+  __TEXT.__const: 0x3a8ce4
   __TEXT.__chain_starts: 0x50
-  __TEXT.__cstring: 0x30f16
+  __TEXT.__cstring: 0x30ff1
   __TEXT.__lcxx_override: 0x64
   __DATA.__const: 0x316f0
   __DATA.__data: 0x11dca8

   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x580
   __OS_LOG.__string: 0x22003
-  Functions: 6697
+  Functions: 6698
   Symbols:   0
-  CStrings:  6171
+  CStrings:  6174
 
CStrings:
+ "IOMFB removing mode with odd Hactive : %d\n"
+ "Mode: id=%llu %ux%u@%u.%uHz, pEnc=0x%x, type=%u, st=%u, v=%u, cc=%u, pCl=%u, sc=%u\n"
+ "Mode: sType=%u total=%ux%u, hBack=%u, vBack=%u, hFront=%u, vFront=%u, hSync=%u, vSync=%u, apCl=%u, ar=%u, cr=%u\n"
+ "This monitor has timing with vblank=%d us < spec threshold of 300us \n"
- "VFP:%d, VBP: %d, VSYNC_WIDTH: %d, HTOTAL:%d, VTOTAL:%d, pixel clock: %d, linetime: %d (ns)"
```
