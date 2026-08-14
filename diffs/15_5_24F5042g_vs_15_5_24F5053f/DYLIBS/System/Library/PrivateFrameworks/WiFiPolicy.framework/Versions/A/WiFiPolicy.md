## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/Versions/A/WiFiPolicy`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`

```diff

-925.31.0.0.0
-  __TEXT.__text: 0xc3c3c
+925.32.0.0.0
+  __TEXT.__text: 0xc3c5c
   __TEXT.__auth_stubs: 0x12d0
   __TEXT.__objc_methlist: 0x110d0
   __TEXT.__const: 0x628
   __TEXT.__cstring: 0x1b4f7
-  __TEXT.__oslogstring: 0x3559
+  __TEXT.__oslogstring: 0x355d
   __TEXT.__gcc_except_tab: 0x17a0
   __TEXT.__unwind_info: 0x20d8
   __TEXT.__objc_classname: 0x1379
Functions:
~ -[WiFiUsageMonitor faultEventDetected:] : 368 -> 408
~ +[WiFiUsageSession isDriverUnavailabilityReasonVoluntary:subReason:orReasonString:] : 112 -> 104
CStrings:
+ "%s: fault event %@(%@) detected on interface %@"
+ "B32@0:8i16i20@24"
- "%s: fault event %@ detected on interface %@"
- "B40@0:8q16q24@32"
```
