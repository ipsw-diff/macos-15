## libReverseProxyDevice.dylib

> `/usr/lib/libReverseProxyDevice.dylib`

```diff

-102.0.0.0.0
-  __TEXT.__text: 0x43e4
-  __TEXT.__auth_stubs: 0x660
+104.0.0.0.0
+  __TEXT.__text: 0x43fc
+  __TEXT.__auth_stubs: 0x670
   __TEXT.__objc_methlist: 0x2bc
   __TEXT.__const: 0x30
-  __TEXT.__gcc_except_tab: 0xcc
-  __TEXT.__cstring: 0xb63
-  __TEXT.__unwind_info: 0x188
+  __TEXT.__gcc_except_tab: 0xd4
+  __TEXT.__cstring: 0xb77
+  __TEXT.__unwind_info: 0x198
   __TEXT.__objc_classname: 0x61
   __TEXT.__objc_methname: 0x6e2
   __TEXT.__objc_methtype: 0x603

   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x1e0
-  __AUTH_CONST.__auth_got: 0x340
+  __AUTH_CONST.__auth_got: 0x348
   __AUTH_CONST.__const: 0x198
   __AUTH_CONST.__cfstring: 0x820
   __AUTH_CONST.__objc_const: 0x3d8

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 90
-  Symbols:   290
+  Symbols:   292
   CStrings:  248
 
Symbols:
+ GCC_except_table25
+ GCC_except_table28
+ __ZN8RPSocket13EventCallback20invoke_and_delete_fnEPS0_
+ _dispatch_async_f
- GCC_except_table29
- __ZN8RPSocket13EventCallback4sendEv
Functions:
~ __ZN8RPSocket11set_invalidEv : 176 -> 192
~ __ZNK8RPSocket13EventCallback11release_allEv -> __ZN8RPSocket13EventCallback20invoke_and_delete_fnEPS0_ : 104 -> 84
~ __ZN8RPSocket13EventCallback4sendEv -> __ZN8RPSocket13EventCallback6invokeEv : 124 -> 436
~ __ZN8RPSocket13EventCallback6invokeEv -> __ZNK8RPSocket13EventCallback11release_allEv : 436 -> 104
~ __ZN8RPSocket13EventCallback9invoke_fnEPS0_ -> __ZN11RPSocket_fd13event_handlerEPv : 4 -> 188
~ __ZN11RPSocket_fd13event_handlerEPv -> __ZN8RPSocket13EventCallback9invoke_fnEPS0_ : 140 -> 4
```
