## AppleAVE2FW_H14G.im4p

> `Firmware/ave/AppleAVE2FW_H14G.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xcb440
+  __TEXT.__text: 0xcb790
   __TEXT._rtk_mtab: 0x320
-  __TEXT.__const: 0x1b4e0
-  __TEXT.__cstring: 0x11563
+  __TEXT.__const: 0x1b440
+  __TEXT.__cstring: 0x115c9
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x27f8

   __DATA._rtk_threads: 0x0
   __DATA.__zerofill: 0xc68b8
   Functions: 0
-  Symbols:   1379
-  CStrings:  2117
+  Symbols:   1380
+  CStrings:  2121
 
Symbols:
+ __ZN19CFlowControllerBase19ProcessCmd_PriorityEv
CStrings:
+ "%s %d %lld %d"
+ "%s::%s:%d %lld %d %lld %d"
+ "8002.46.0"
+ "ProcessCmd_Priority"
+ "insize == sizeof(struct sCAveCmdPriority)"
- "8002.41.0"
```
