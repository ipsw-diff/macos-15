## ipconfig

> `/usr/sbin/ipconfig`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-494.120.6.0.0
-  __TEXT.__text: 0xa3b0
+494.140.4.0.0
+  __TEXT.__text: 0xa464
   __TEXT.__auth_stubs: 0x730
   __TEXT.__const: 0xe8
-  __TEXT.__cstring: 0x2e0f
+  __TEXT.__cstring: 0x2e84
   __TEXT.__oslogstring: 0x64
   __TEXT.__unwind_info: 0x220
   __DATA_CONST.__auth_got: 0x398

   - /usr/lib/libSystem.B.dylib
   Functions: 151
   Symbols:   157
-  CStrings:  727
+  CStrings:  730
 
Functions:
~ sub_1000012b4 : 236 -> 296
~ sub_1000013a0 -> sub_1000013dc : 332 -> 392
~ sub_1000014ec -> sub_100001564 : 484 -> 544
CStrings:
+ "HideWiFiInfo"
+ "failed to set hide WiFi info\n"
+ "ipconfig_get_packet(%s) failed: %s\n"
+ "ipconfig_get_ra(%s) failed: %s\n"
+ "ipconfig_get_v6_packet(%s) failed: %s\n"
+ "setHideWiFiInfo"
- "HideBSSID"
- "failed to set hide BSSID\n"
- "setHideBSSID"
```
