## libnetquality.dylib

> `/usr/lib/libnetquality.dylib`

```diff

-147.120.5.0.0
-  __TEXT.__text: 0x1a37c
+147.120.6.0.0
+  __TEXT.__text: 0x1a7d8
   __TEXT.__auth_stubs: 0x9b0
-  __TEXT.__objc_methlist: 0x168c
-  __TEXT.__const: 0x180
+  __TEXT.__objc_methlist: 0x169c
+  __TEXT.__const: 0x190
   __TEXT.__gcc_except_tab: 0x514
-  __TEXT.__cstring: 0x2290
-  __TEXT.__oslogstring: 0x1625
-  __TEXT.__unwind_info: 0x510
+  __TEXT.__cstring: 0x235a
+  __TEXT.__oslogstring: 0x162a
+  __TEXT.__unwind_info: 0x518
   __TEXT.__objc_classname: 0x315
   __TEXT.__objc_methname: 0x3e3a
   __TEXT.__objc_methtype: 0xc57

   __DATA_CONST.__objc_arraydata: 0x58
   __AUTH_CONST.__auth_got: 0x4e8
   __AUTH_CONST.__const: 0x580
-  __AUTH_CONST.__cfstring: 0x18e0
+  __AUTH_CONST.__cfstring: 0x1900
   __AUTH_CONST.__objc_const: 0x36b0
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_floatobj: 0x10

   - /System/Library/PrivateFrameworks/Rapport.framework/Versions/A/Rapport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 574
-  Symbols:   1614
-  CStrings:  1303
+  Functions: 577
+  Symbols:   1616
+  CStrings:  1305
 
Symbols:
+ -[UploadThroughputDelegate URLSession:dataTask:didReceiveResponse:completionHandler:]
+ _NetworkQualityErrorMeasurementTransferredNoBytes
CStrings:
+ "%s:%u - server response without test_endpoint specified"
+ "-[UploadThroughputDelegate URLSession:dataTask:didReceiveResponse:completionHandler:]"
+ "Request got 200, but transferred no bytes on throughput measurement connection. Is the server configured correctly?"
- "%s:%u - server response without test_endpoint spec"
```
