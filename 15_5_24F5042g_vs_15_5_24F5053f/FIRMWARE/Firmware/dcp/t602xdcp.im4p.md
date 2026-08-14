## t602xdcp.im4p

> `Firmware/dcp/t602xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__TEXT.__lcxx_override`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2cafac
-  __TEXT.__const: 0x3a88f4
+  __TEXT.__text: 0x2cb540
+  __TEXT.__const: 0x3a8af4
   __TEXT.__chain_starts: 0x50
-  __TEXT.__cstring: 0x31397
+  __TEXT.__cstring: 0x31472
   __TEXT.__lcxx_override: 0x64
   __DATA.__const: 0x31078
   __DATA.__data: 0x118ca4

   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x448
   __OS_LOG.__string: 0x21681
-  Functions: 6692
+  Functions: 6693
   Symbols:   0
-  CStrings:  6175
+  CStrings:  6178
 
CStrings:
+ "IOMFB removing mode with odd Hactive : %d\n"
+ "Mode: id=%llu %ux%u@%u.%uHz, pEnc=0x%x, type=%u, st=%u, v=%u, cc=%u, pCl=%u, sc=%u\n"
+ "Mode: sType=%u total=%ux%u, hBack=%u, vBack=%u, hFront=%u, vFront=%u, hSync=%u, vSync=%u, apCl=%u, ar=%u, cr=%u\n"
+ "This monitor has timing with vblank=%d us < spec threshold of 300us \n"
- "VFP:%d, VBP: %d, VSYNC_WIDTH: %d, HTOTAL:%d, VTOTAL:%d, pixel clock: %d, linetime: %d (ns)"
```
