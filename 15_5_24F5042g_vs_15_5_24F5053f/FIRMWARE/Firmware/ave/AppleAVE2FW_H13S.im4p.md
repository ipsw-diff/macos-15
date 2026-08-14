## AppleAVE2FW_H13S.im4p

> `Firmware/ave/AppleAVE2FW_H13S.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xcb4d0
+  __TEXT.__text: 0xcb810
   __TEXT._rtk_mtab: 0x308
-  __TEXT.__const: 0x1e560
-  __TEXT.__cstring: 0x113c7
+  __TEXT.__const: 0x1e5e0
+  __TEXT.__cstring: 0x1142d
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x27f8

   __DATA._rtk_threads: 0x0
   __DATA.__zerofill: 0xc68b8
   Functions: 0
-  Symbols:   1370
-  CStrings:  2110
+  Symbols:   1371
+  CStrings:  2114
 
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
