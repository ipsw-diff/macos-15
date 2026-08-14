## AppleAVE2FW_H13G.im4p

> `Firmware/ave/AppleAVE2FW_H13G.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xc8900
+  __TEXT.__text: 0xc8c40
   __TEXT._rtk_mtab: 0x308
-  __TEXT.__const: 0x1afb0
-  __TEXT.__cstring: 0x112f9
+  __TEXT.__const: 0x1ae70
+  __TEXT.__cstring: 0x1135f
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x2588

   __DATA._rtk_threads: 0x0
   __DATA.__zerofill: 0xc68b8
   Functions: 0
-  Symbols:   1333
-  CStrings:  2086
+  Symbols:   1334
+  CStrings:  2090
 
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
