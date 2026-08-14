## AppleAVE2FW_H13D.im4p

> `Firmware/ave/AppleAVE2FW_H13D.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_power`

```diff

-  __TEXT.__text: 0xe6020
+  __TEXT.__text: 0xe6360
   __TEXT._rtk_mtab: 0x2b8
-  __TEXT.__const: 0x1ebd8
-  __TEXT.__cstring: 0x12df0
+  __TEXT.__const: 0x1ed38
+  __TEXT.__cstring: 0x12e56
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x2950

   __DATA._rtk_threads: 0x0
   __DATA.__zerofill: 0xd03d8
   Functions: 0
-  Symbols:   1461
-  CStrings:  2283
+  Symbols:   1462
+  CStrings:  2287
 
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
