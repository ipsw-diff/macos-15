## AppleAVE2FW_H16S.im4p

> `Firmware/ave/AppleAVE2FW_H16S.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xf37c8
+  __TEXT.__text: 0xf3b58
   __TEXT._rtk_mtab: 0x2d0
-  __TEXT.__const: 0x23284
-  __TEXT.__cstring: 0x14113
+  __TEXT.__const: 0x233cc
+  __TEXT.__cstring: 0x14179
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x2a20

   __DATA._rtk_threads: 0x0
   __DATA.__zerofill: 0xc9318
   Functions: 0
-  Symbols:   1537
-  CStrings:  2419
+  Symbols:   1538
+  CStrings:  2423
 
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
