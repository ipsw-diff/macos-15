## IPConfiguration

> `/System/Library/SystemConfiguration/IPConfiguration.bundle/Contents/MacOS/IPConfiguration`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-494.120.6.0.0
-  __TEXT.__text: 0x5aee4
-  __TEXT.__auth_stubs: 0x1060
+494.140.4.0.0
+  __TEXT.__text: 0x5b378
+  __TEXT.__auth_stubs: 0x1080
   __TEXT.__const: 0x2f0
-  __TEXT.__cstring: 0x3d3d
-  __TEXT.__oslogstring: 0x64ed
-  __TEXT.__unwind_info: 0xb78
-  __DATA_CONST.__auth_got: 0x830
+  __TEXT.__cstring: 0x3d95
+  __TEXT.__oslogstring: 0x6503
+  __TEXT.__unwind_info: 0xb90
+  __DATA_CONST.__auth_got: 0x840
   __DATA_CONST.__got: 0x3c8
   __DATA_CONST.__auth_ptr: 0xf8
   __DATA_CONST.__const: 0x1d90
-  __DATA_CONST.__cfstring: 0x2920
+  __DATA_CONST.__cfstring: 0x2960
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__data: 0x110
-  __DATA.__bss: 0x200
+  __DATA.__bss: 0x1f8
   __DATA.__common: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration
   - /System/Library/PrivateFrameworks/IO80211.framework/Versions/A/IO80211
   - /System/Library/PrivateFrameworks/IPConfiguration.framework/Versions/A/IPConfiguration

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1003
-  Symbols:   498
-  CStrings:  1683
+  Functions: 1006
+  Symbols:   500
+  CStrings:  1686
 
Symbols:
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
CStrings:
+ "%s: close socket %d failed, %s"
+ "HideWiFiInfo"
+ "Will NOT "
+ "[%s] %sTransmit %d byte packet\n%@"
+ "[%s] %sTransmit %d byte packet dest %d.%d.%d.%d scope %d\n%@"
+ "[%s] %sTransmit %d byte packet xid 0x%lx to %d.%d.%d.%d [scope=%d]"
+ "com.apple.IPConfiguration.get-information"
+ "com.apple.IPConfigurationService"
- "BSSID %shidden"
- "HideBSSID"
- "[%s] Transmit %d byte packet\n%@"
- "[%s] Transmit %d byte packet dest %d.%d.%d.%d scope %d\n%@"
- "[%s] Transmit %d byte packet xid 0x%lx to %d.%d.%d.%d [scope=%d]"
```
