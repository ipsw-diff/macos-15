## WorkflowUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/WorkflowUI.framework/Versions/A/WorkflowUI`

```diff

-3607.0.2.0.0
-  __TEXT.__text: 0x29db4c
+3609.0.0.0.0
+  __TEXT.__text: 0x29de04
   __TEXT.__auth_stubs: 0x5cb0
-  __TEXT.__objc_methlist: 0x9b34
-  __TEXT.__const: 0x139a8
+  __TEXT.__objc_methlist: 0x9b4c
+  __TEXT.__const: 0x13cc8
   __TEXT.__dlopen_cstrs: 0x196
-  __TEXT.__cstring: 0xdbc6
+  __TEXT.__cstring: 0xdc17
   __TEXT.__constg_swiftt: 0x8efc
   __TEXT.__swift5_typeref: 0x24afc
   __TEXT.__swift5_reflstr: 0x5113

   __TEXT.__swift5_proto: 0xb40
   __TEXT.__swift5_types: 0x70c
   __TEXT.__swift_as_entry: 0x108
-  __TEXT.__oslogstring: 0x1cda
+  __TEXT.__oslogstring: 0x1d4c
   __TEXT.__swift5_protos: 0x84
   __TEXT.__swift_as_ret: 0x100
   __TEXT.__swift5_mpenum: 0x250
-  __TEXT.__gcc_except_tab: 0x558
+  __TEXT.__gcc_except_tab: 0x55c
   __TEXT.__ustring: 0x2d4
-  __TEXT.__unwind_info: 0xa410
+  __TEXT.__unwind_info: 0xa418
   __TEXT.__eh_frame: 0x58cc
   __TEXT.__objc_classname: 0x1973
-  __TEXT.__objc_methname: 0x190b8
+  __TEXT.__objc_methname: 0x19128
   __TEXT.__objc_methtype: 0x5ec6
-  __TEXT.__objc_stubs: 0xda20
+  __TEXT.__objc_stubs: 0xda60
   __DATA_CONST.__got: 0x2280
-  __DATA_CONST.__const: 0x1ba8
+  __DATA_CONST.__const: 0x1bd0
   __DATA_CONST.__objc_classlist: 0x788
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x478
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6458
+  __DATA_CONST.__objc_selrefs: 0x6468
   __DATA_CONST.__objc_protorefs: 0x1b0
   __DATA_CONST.__objc_superrefs: 0x360
   __DATA_CONST.__objc_arraydata: 0x1a8
   __AUTH_CONST.__auth_got: 0x2e68
-  __AUTH_CONST.__const: 0xf7f0
+  __AUTH_CONST.__const: 0xf810
   __AUTH_CONST.__cfstring: 0x37e0
   __AUTH_CONST.__objc_const: 0x146b0
   __AUTH_CONST.__objc_intobj: 0x4f8

   __AUTH.__objc_data: 0x7848
   __AUTH.__data: 0x6b00
   __DATA.__objc_ivar: 0x5d8
-  __DATA.__data: 0xb168
+  __DATA.__data: 0xadc8
   __DATA.__bss: 0x16d50
   __DATA.__common: 0x240
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 17211
-  Symbols:   11127
-  CStrings:  6454
+  Functions: 17214
+  Symbols:   11133
+  CStrings:  6460
 
Symbols:
+ -[WFCreateAutomationCoordinator cleanUpAbandonedTriggerIfNecessary]
+ -[WFCreateAutomationCoordinator dealloc]
+ -[WFCreateAutomationCoordinator setUnfinishedTriggerIdentifier:]
+ -[WFCreateAutomationCoordinator unfinishedTriggerIdentifier]
+ GCC_except_table1864
+ GCC_except_table1871
+ GCC_except_table1875
+ GCC_except_table1906
+ GCC_except_table2038
+ OBJC_IVAR_$_WFCreateAutomationCoordinator._unfinishedTriggerIdentifier
+ ___67-[WFCreateAutomationCoordinator cleanUpAbandonedTriggerIfNecessary]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e20_v20?0B8"NSError"12lw40l8s32l8
+ _objc_msgSend$cleanUpAbandonedTriggerIfNecessary
+ _objc_msgSend$setUnfinishedTriggerIdentifier:
+ _objc_msgSend$unfinishedTriggerIdentifier
- -[WFCreateAutomationCoordinator setTriggerIdentifier:]
- -[WFCreateAutomationCoordinator triggerIdentifier]
- GCC_except_table1862
- GCC_except_table1869
- GCC_except_table1873
- GCC_except_table1903
- GCC_except_table2035
- OBJC_IVAR_$_WFCreateAutomationCoordinator._triggerIdentifier
- _objc_msgSend$setTriggerIdentifier:
CStrings:
+ "%s Attempted to finish trigger creation but trigger identifier was nil"
+ "%s Failed to delete configured trigger: %@"
+ "-[WFCreateAutomationCoordinator cleanUpAbandonedTriggerIfNecessary]_block_invoke"
+ "T@\"NSString\",&,N,V_unfinishedTriggerIdentifier"
+ "_unfinishedTriggerIdentifier"
+ "cleanUpAbandonedTriggerIfNecessary"
+ "setUnfinishedTriggerIdentifier:"
+ "unfinishedTriggerIdentifier"
- "T@\"NSString\",&,N,V_triggerIdentifier"
- "setTriggerIdentifier:"
```
