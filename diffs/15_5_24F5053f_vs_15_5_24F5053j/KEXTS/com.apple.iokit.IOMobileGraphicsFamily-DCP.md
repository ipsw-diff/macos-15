## com.apple.iokit.IOMobileGraphicsFamily-DCP

> `com.apple.iokit.IOMobileGraphicsFamily-DCP`

```diff

-399.27.3.0.0
-  __TEXT.__cstring: 0x40a1
+399.27.5.0.0
+  __TEXT.__cstring: 0x3ffc
   __TEXT.__const: 0x2f28
-  __TEXT_EXEC.__text: 0x222b0
+  __TEXT_EXEC.__text: 0x2228c
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xe0
   __DATA.__common: 0x26d0

   __DATA_CONST.__kalloc_type: 0x800
   Functions: 685
   Symbols:   1293
-  CStrings:  370
+  CStrings:  366
 
Symbols:
+ __ZZ21notify_event_callbackP8OSObjectP20IOSurfaceSharedEventyyE21kalloc_type_view_5743
+ __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_4484
+ __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_4532
+ __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_4538
+ __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_4567
+ __ZZN21IOMobileFramebufferAP17shared_event_waitEPN5IOMFB2AP11SharedEventEP9IOSurfaceP18IOMFBSwapIORequestjjbE21kalloc_type_view_5786
+ __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_1599
+ __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_1619
- __ZZ21notify_event_callbackP8OSObjectP20IOSurfaceSharedEventyyE21kalloc_type_view_5734
- __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_4475
- __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_4523
- __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_4529
- __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_4558
- __ZZN21IOMobileFramebufferAP17shared_event_waitEPN5IOMFB2AP11SharedEventEP9IOSurfaceP18IOMFBSwapIORequestjjbE21kalloc_type_view_5777
- __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_1590
- __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_1610
Functions:
~ __ZN21IOMobileFramebufferAP19get_clamshell_stateEb : 240 -> 204
CStrings:
+ "%s set fAPClamshellState to %d \n"
+ "get_clamshell_state"
- "get_clamshell_state fAPClamshellState %d from_kernel %d fReceivedClamshellStateFromSkyLight %d \n"
- "property doesnt Exists \n"
- "propertyExists \n"
- "propertyHas default Value \n"
- "propertyHas false Value \n"
- "propertyHas true Value \n"
```
