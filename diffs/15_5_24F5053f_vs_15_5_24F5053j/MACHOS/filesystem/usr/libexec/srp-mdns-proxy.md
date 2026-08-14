## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2600.120.6.0.0
-  __TEXT.__text: 0x756c4
+2600.120.11.0.1
+  __TEXT.__text: 0x757ac
   __TEXT.__auth_stubs: 0x1230
   __TEXT.__const: 0x20b
-  __TEXT.__cstring: 0x6e73
-  __TEXT.__oslogstring: 0xf71a
+  __TEXT.__cstring: 0x6e65
+  __TEXT.__oslogstring: 0xf7a0
   __TEXT.__objc_classname: 0x1
   __TEXT.__unwind_info: 0x500
   __TEXT.__eh_frame: 0xb4

   - /usr/lib/libobjc.A.dylib
   Functions: 395
   Symbols:   948
-  CStrings:  2091
+  CStrings:  2090
 
Functions:
~ _cti_internal_rloc16_reply_callback : 428 -> 676
~ _thread_device_shutdown : 208 -> 192
CStrings:
+ "%{public}s: [CX%d] canceling connection %p after successful response"
+ "%{public}s: [CX%d] got invalid RLOC16 value: 0x%llX is too large"
+ "22:13:41"
+ "Apr 13 2025"
+ "Thread:RLOC16"
- "\n"
- "18:55:58"
- "Apr  6 2025"
- "OtCtlCmd"
- "otctl_cmd"
- "rloc16"
```
