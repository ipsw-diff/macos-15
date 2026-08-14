## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-1425.42.0.0.0
-  __TEXT.__text: 0x2ad3ec
+1425.43.0.0.0
+  __TEXT.__text: 0x2ad67c
   __TEXT.__auth_stubs: 0x24e0
   __TEXT.__init_offsets: 0x1c0
-  __TEXT.__cstring: 0x7e1d7
+  __TEXT.__cstring: 0x7e256
   __TEXT.__const: 0x3d0b0
   __TEXT.__unwind_info: 0x5db0
   __TEXT.__eh_frame: 0x38

   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/System/Library/PrivateFrameworks/OLYHALDriverKit.framework/OLYHALDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 13063
-  Symbols:   11455
-  CStrings:  12648
+  Functions: 13068
+  Symbols:   11457
+  CStrings:  12651
 
Symbols:
+ __ZN22AppleBCMWLANChipMemory10readFlags3Ev
+ __ZN27AppleBCMWLANChipManagerPCIe19setDARUpdateAllowedEb
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1425.43\""
+ "AppleBCMWLANV3_driverkit-1425.43"
+ "Apr  3 2025 23:24:34"
+ "[dk] %s@%d:DAR Based trap supported\n"
+ "[dk] %s@%d:Host initiated DAR based trap timed out\n"
+ "[dk] %s@%d:deviceSharedFlags3 = 0x%x\n"
- "\"AppleBCMWLANV3_driverkit-1425.42\""
- "AppleBCMWLANV3_driverkit-1425.42"
- "Mar 21 2025 21:17:37"
```
