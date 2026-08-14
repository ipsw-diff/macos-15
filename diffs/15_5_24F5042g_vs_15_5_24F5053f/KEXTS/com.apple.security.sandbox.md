## com.apple.security.sandbox

> `com.apple.security.sandbox`

```diff

-2401.120.9.0.0
+2401.120.20.0.1
   __TEXT.__os_log: 0x1d47
-  __TEXT.__const: 0x1ef5f
+  __TEXT.__const: 0x1f0df
   __TEXT.__cstring: 0x7626
-  __TEXT_EXEC.__text: 0x45244
+  __TEXT_EXEC.__text: 0x45254
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x2b8
   __DATA.__bss: 0x7f128
Symbols:
+ _send_event_to_sandboxd
- _thread_ustackshot_destroy
Functions:
~ _log_kernel_report_summary -> _send_event_to_sandboxd : 388 -> 628
~ _thread_ustackshot_destroy -> _log_kernel_report_summary : 96 -> 388
~ _sb_event : 3404 -> 2888
```
