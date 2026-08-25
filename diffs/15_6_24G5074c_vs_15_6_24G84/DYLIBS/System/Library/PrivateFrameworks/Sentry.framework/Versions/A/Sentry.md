## Sentry

> `/System/Library/PrivateFrameworks/Sentry.framework/Versions/A/Sentry`

```diff

 1.20.42.0.0
-  __TEXT.__text: 0x1e0a4
+  __TEXT.__text: 0x1e1b8
   __TEXT.__auth_stubs: 0x720
   __TEXT.__objc_methlist: 0x1778
   __TEXT.__const: 0x174
-  __TEXT.__cstring: 0x1e7e
-  __TEXT.__oslogstring: 0x2f8f
-  __TEXT.__gcc_except_tab: 0x524
+  __TEXT.__cstring: 0x1ea0
+  __TEXT.__oslogstring: 0x2fad
+  __TEXT.__gcc_except_tab: 0x540
   __TEXT.__unwind_info: 0x730
   __TEXT.__objc_classname: 0x386
   __TEXT.__objc_methname: 0x4951

   __DATA_CONST.__objc_arraydata: 0xa8
   __AUTH_CONST.__auth_got: 0x3a0
   __AUTH_CONST.__const: 0xb60
-  __AUTH_CONST.__cfstring: 0x1e60
+  __AUTH_CONST.__cfstring: 0x1e80
   __AUTH_CONST.__objc_const: 0x31f0
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_arrayobj: 0x18

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
-  Functions: 759
+  Functions: 760
   Symbols:   1803
-  CStrings:  1448
+  CStrings:  1450
 
Symbols:
+ GCC_except_table239
- GCC_except_table238
Functions:
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:] : 2476 -> 2692
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.3 : 144 -> 60
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.4 : 60 -> 144
~ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.8 : 108 -> 60
+ -[STYSpecialAppLaunchSignpostMonitorHelper handleInterval:].cold.9
CStrings:
+ "App launch threshold enforced"
+ "ApplicationFirstFramePresentation"
```
