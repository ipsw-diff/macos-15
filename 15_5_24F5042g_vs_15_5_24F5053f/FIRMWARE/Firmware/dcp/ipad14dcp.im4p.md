## ipad14dcp.im4p

> `Firmware/dcp/ipad14dcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__TEXT.__lcxx_override`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2dd4b0
-  __TEXT.__const: 0x3c9d6c
+  __TEXT.__text: 0x2dda2c
+  __TEXT.__const: 0x3c9fec
   __TEXT.__chain_starts: 0x54
-  __TEXT.__cstring: 0x31081
+  __TEXT.__cstring: 0x3115c
   __TEXT.__lcxx_override: 0x64
-  __DATA.__const: 0x321d8
+  __DATA.__const: 0x321e8
   __DATA.__data: 0x14d304
   __DATA._rtk_patchbay: 0x734
   __DATA.__constructor: 0x8

   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x6a0
   __OS_LOG.__string: 0x21f96
-  Functions: 6804
+  Functions: 6805
   Symbols:   0
-  CStrings:  6146
+  CStrings:  6149
 
CStrings:
+ "IOMFB removing mode with odd Hactive : %d\n"
+ "Mode: id=%llu %ux%u@%u.%uHz, pEnc=0x%x, type=%u, st=%u, v=%u, cc=%u, pCl=%u, sc=%u\n"
+ "Mode: sType=%u total=%ux%u, hBack=%u, vBack=%u, hFront=%u, vFront=%u, hSync=%u, vSync=%u, apCl=%u, ar=%u, cr=%u\n"
+ "This monitor has timing with vblank=%d us < spec threshold of 300us \n"
- "VFP:%d, VBP: %d, VSYNC_WIDTH: %d, HTOTAL:%d, VTOTAL:%d, pixel clock: %d, linetime: %d (ns)"
```
