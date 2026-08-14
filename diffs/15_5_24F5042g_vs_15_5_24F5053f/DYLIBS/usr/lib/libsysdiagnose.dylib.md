## libsysdiagnose.dylib

> `/usr/lib/libsysdiagnose.dylib`

```diff

-1438.120.5.0.0
-  __TEXT.__text: 0x3478
+1438.120.8.0.0
+  __TEXT.__text: 0x35a4
   __TEXT.__auth_stubs: 0x380
   __TEXT.__objc_methlist: 0xe0
+  __TEXT.__oslogstring: 0x1f8
+  __TEXT.__cstring: 0x562
   __TEXT.__const: 0x38
   __TEXT.__gcc_except_tab: 0x60
-  __TEXT.__cstring: 0x563
-  __TEXT.__oslogstring: 0x1d4
   __TEXT.__unwind_info: 0x108
   __TEXT.__objc_classname: 0xf
-  __TEXT.__objc_methname: 0x6c3
+  __TEXT.__objc_methname: 0x701
   __TEXT.__objc_methtype: 0xd9
-  __TEXT.__objc_stubs: 0x700
-  __DATA_CONST.__got: 0xd8
+  __TEXT.__objc_stubs: 0x760
+  __DATA_CONST.__got: 0xe0
   __DATA_CONST.__const: 0xe0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x208
+  __DATA_CONST.__objc_selrefs: 0x220
   __AUTH_CONST.__auth_got: 0x1d0
   __AUTH_CONST.__const: 0x180
   __AUTH_CONST.__cfstring: 0x540

   __DATA_DIRTY.__objc_data: 0x50
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/PrivateFrameworks/OSAnalytics.framework/Versions/A/OSAnalytics
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 46
-  Symbols:   229
-  CStrings:  156
+  Functions: 48
+  Symbols:   235
+  CStrings:  160
 
Symbols:
+ _OBJC_CLASS_$_OSASystemConfiguration
+ _appendToCrashlogsDir
+ _objc_msgSend$pathSubmission
+ _objc_msgSend$sharedInstance
+ _objc_msgSend$stringByAppendingPathComponent:
+ appendToCrashlogsDir
Functions:
+ _appendToCrashlogsDir
~ +[Libsysdiagnose getSysdiagnoseCrashLog] : 1096 -> 1124
+ appendToCrashlogsDir.cold.1
CStrings:
+ "/Library/Logs/DiagnosticReports"
+ "OSAnalytics returned nil crash path"
+ "pathSubmission"
+ "sharedInstance"
+ "stringByAppendingPathComponent:"
- "/Library/Logs/DiagnosticReports/"
```
