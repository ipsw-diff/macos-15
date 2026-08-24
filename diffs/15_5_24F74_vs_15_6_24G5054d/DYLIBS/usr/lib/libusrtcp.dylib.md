## libusrtcp.dylib

> `/usr/lib/libusrtcp.dylib`

```diff

-4277.121.5.0.0
-  __TEXT.__text: 0x5e478
-  __TEXT.__auth_stubs: 0xf90
+4277.140.27.0.0
+  __TEXT.__text: 0x5e774
+  __TEXT.__auth_stubs: 0xfc0
   __TEXT.__const: 0x234
-  __TEXT.__oslogstring: 0xe62f
-  __TEXT.__cstring: 0x19a0
+  __TEXT.__oslogstring: 0xe698
+  __TEXT.__cstring: 0x19e0
   __TEXT.__unwind_info: 0x428
-  __DATA_CONST.__got: 0xa0
-  __DATA_CONST.__const: 0x2f0
-  __AUTH_CONST.__auth_got: 0x7c8
-  __AUTH_CONST.__const: 0x248
+  __DATA_CONST.__got: 0xa8
+  __DATA_CONST.__const: 0x310
+  __AUTH_CONST.__auth_got: 0x7e0
+  __AUTH_CONST.__const: 0x268
   __AUTH.__data: 0xd0
   __DATA.__data: 0x34
-  __DATA.__bss: 0x7d0
+  __DATA.__bss: 0x7e0
   __DATA_DIRTY.__data: 0x2a0
   __DATA_DIRTY.__bss: 0x10
   - /System/Library/Frameworks/Network.framework/Versions/A/Network
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 335
-  Symbols:   651
-  CStrings:  1108
+  Functions: 336
+  Symbols:   658
+  CStrings:  1114
 
Symbols:
+ ___user_tcp_init_all_block_invoke
+ _g_tcp_nw_assert_context
+ _nw_context_assert_queue
+ _nw_context_get_identifier
+ _nw_setting_tcp_nw_assert_context
+ _nw_tcp_access_context
+ _os_variant_has_internal_diagnostics
+ user_tcp_init_all.onceToken
- _tcp_init
CStrings:
+ "%{public}s g_tcp_nw_assert_context is %s value %lld"
+ "%{public}s globals: %p nw_context: %p identifier: %s"
+ "com.apple.network.tcp"
+ "false"
+ "true"
+ "user_tcp_init_all_block_invoke"
```
