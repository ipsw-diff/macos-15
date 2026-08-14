## libdispatch.dylib

> `/usr/lib/system/libdispatch.dylib`

```diff

-1521.120.2.0.0
-  __TEXT.__text: 0x3bdcc
+1521.120.4.0.0
+  __TEXT.__text: 0x3bdf8
   __TEXT.__auth_stubs: 0xbe0
   __TEXT.__objc_methlist: 0x684
   __TEXT.__const: 0x748

   - /usr/lib/system/libsystem_platform.dylib
   - /usr/lib/system/libsystem_pthread.dylib
   - /usr/lib/system/libunwind.dylib
-  Functions: 1368
-  Symbols:   2066
+  Functions: 1369
+  Symbols:   2067
   CStrings:  616
 
Symbols:
+ __dispatch_event_update_all_deferred
Functions:
~ __dispatch_mach_send_drain : 1088 -> 1108
+ __dispatch_event_update_all_deferred
```
