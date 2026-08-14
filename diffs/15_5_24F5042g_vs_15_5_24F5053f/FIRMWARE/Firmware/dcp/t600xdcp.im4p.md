## t600xdcp.im4p

> `Firmware/dcp/t600xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x305860
-  __TEXT.__const: 0x3ca654
+  __TEXT.__text: 0x305ddc
+  __TEXT.__const: 0x3ca90c
   __TEXT.__chain_starts: 0x4c
-  __TEXT.__cstring: 0x30c9c
+  __TEXT.__cstring: 0x30d77
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x64
-  __DATA.__const: 0x31718
-  __DATA.__data: 0x129f5c
+  __DATA.__const: 0x316f8
+  __DATA.__data: 0x129f64
   __DATA._rtk_patchbay: 0x734
   __DATA.__constructor: 0x8
   __DATA._rtk_tunables: 0x1e8

   __DATA.__gxf_data: 0x10
   __DATA._rtk_mtab: 0x430
   __OS_LOG.__string: 0x2138f
-  Functions: 6796
+  Functions: 6797
   Symbols:   0
-  CStrings:  6121
+  CStrings:  6124
 
CStrings:
+ "IOMFB removing mode with odd Hactive : %d\n"
+ "Mode: id=%llu %ux%u@%u.%uHz, pEnc=0x%x, type=%u, st=%u, v=%u, cc=%u, pCl=%u, sc=%u\n"
+ "Mode: sType=%u total=%ux%u, hBack=%u, vBack=%u, hFront=%u, vFront=%u, hSync=%u, vSync=%u, apCl=%u, ar=%u, cr=%u\n"
+ "This monitor has timing with vblank=%d us < spec threshold of 300us \n"
- "VFP:%d, VBP: %d, VSYNC_WIDTH: %d, HTOTAL:%d, VTOTAL:%d, pixel clock: %d, linetime: %d (ns)"
```
