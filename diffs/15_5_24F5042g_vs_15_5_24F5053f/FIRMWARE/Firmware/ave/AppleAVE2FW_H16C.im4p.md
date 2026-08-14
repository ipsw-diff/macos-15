## AppleAVE2FW_H16C.im4p

> `Firmware/ave/AppleAVE2FW_H16C.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xf3868
+  __TEXT.__text: 0xf3bf8
   __TEXT._rtk_mtab: 0x2d0
-  __TEXT.__const: 0x23294
-  __TEXT.__cstring: 0x1412c
+  __TEXT.__const: 0x233dc
+  __TEXT.__cstring: 0x14192
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x2a20

   __DATA._rtk_threads: 0x0
   __DATA.__zerofill: 0xcbd58
   Functions: 0
-  Symbols:   1538
-  CStrings:  2420
+  Symbols:   1539
+  CStrings:  2424
 
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
