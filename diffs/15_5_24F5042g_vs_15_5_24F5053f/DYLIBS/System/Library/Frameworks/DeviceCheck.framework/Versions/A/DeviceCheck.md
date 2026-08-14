## DeviceCheck

> `/System/Library/Frameworks/DeviceCheck.framework/Versions/A/DeviceCheck`

```diff

-109.3.0.0.0
-  __TEXT.__text: 0xa800
+109.6.0.0.0
+  __TEXT.__text: 0xa8f0
   __TEXT.__auth_stubs: 0x350
-  __TEXT.__objc_methlist: 0x65c
+  __TEXT.__objc_methlist: 0x66c
   __TEXT.__const: 0xb0
   __TEXT.__cstring: 0xa0e
   __TEXT.__gcc_except_tab: 0x480
   __TEXT.__oslogstring: 0x9bc
   __TEXT.__unwind_info: 0x2c8
   __TEXT.__objc_classname: 0xf8
-  __TEXT.__objc_methname: 0xfce
-  __TEXT.__objc_methtype: 0x52e
+  __TEXT.__objc_methname: 0x1004
+  __TEXT.__objc_methtype: 0x53b
   __TEXT.__objc_stubs: 0xc20
   __DATA_CONST.__got: 0x140
   __DATA_CONST.__const: 0xf8

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x468
+  __DATA_CONST.__objc_selrefs: 0x470
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
   __AUTH_CONST.__auth_got: 0x1b8

   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 191
-  Symbols:   509
-  CStrings:  355
+  Functions: 192
+  Symbols:   510
+  CStrings:  356
 
Symbols:
+ -[DCAppAttestController sign:withKey:teamIdentifier:completionHandler:]
+ -[DCAppAttestServicePriv sign:withKey:teamIdentifier:completionHandler:]
+ __71-[DCAppAttestController sign:withKey:teamIdentifier:completionHandler:]_block_invoke
+ ___71-[DCAppAttestController sign:withKey:teamIdentifier:completionHandler:]_block_invoke
+ _objc_msgSend$appAttestationSign:appUUID:keyId:teamId:completion:
+ _objc_msgSend$sign:withKey:teamIdentifier:completionHandler:
- -[DCAppAttestController sign:withKey:completionHandler:]
- __56-[DCAppAttestController sign:withKey:completionHandler:]_block_invoke
- ___56-[DCAppAttestController sign:withKey:completionHandler:]_block_invoke
- _objc_msgSend$appAttestationSign:appUUID:keyId:completion:
- _objc_msgSend$sign:withKey:completionHandler:
CStrings:
+ "appAttestationSign:appUUID:keyId:teamId:completion:"
+ "sign:withKey:teamIdentifier:completionHandler:"
+ "v56@0:8@\"NSData\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@?<v@?@\"NSData\"@\"NSError\">48"
- "appAttestationSign:appUUID:keyId:completion:"
- "v48@0:8@\"NSData\"16@\"NSString\"24@\"NSString\"32@?<v@?@\"NSData\"@\"NSError\">40"
```
