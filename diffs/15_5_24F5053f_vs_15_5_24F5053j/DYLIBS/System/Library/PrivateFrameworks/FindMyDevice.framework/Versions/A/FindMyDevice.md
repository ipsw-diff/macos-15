## FindMyDevice

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/Versions/A/FindMyDevice`

```diff

-438.25.2.11.7
-  __TEXT.__text: 0x12ea8
-  __TEXT.__auth_stubs: 0x2e0
-  __TEXT.__objc_methlist: 0x1654
-  __TEXT.__cstring: 0x3576
+438.25.2.11.16
+  __TEXT.__text: 0x133a0
+  __TEXT.__auth_stubs: 0x2f0
+  __TEXT.__objc_methlist: 0x1704
+  __TEXT.__cstring: 0x35b5
   __TEXT.__const: 0xb0
   __TEXT.__gcc_except_tab: 0x2c4
   __TEXT.__oslogstring: 0x1126
-  __TEXT.__unwind_info: 0x4c0
-  __TEXT.__objc_classname: 0x3df
-  __TEXT.__objc_methname: 0x314f
-  __TEXT.__objc_methtype: 0xa11
-  __TEXT.__objc_stubs: 0x22c0
-  __DATA_CONST.__got: 0x100
+  __TEXT.__unwind_info: 0x4d8
+  __TEXT.__objc_classname: 0x3f2
+  __TEXT.__objc_methname: 0x326a
+  __TEXT.__objc_methtype: 0xa2e
+  __TEXT.__objc_stubs: 0x2340
+  __DATA_CONST.__got: 0x108
   __DATA_CONST.__const: 0xc40
-  __DATA_CONST.__objc_classlist: 0xa8
+  __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc20
+  __DATA_CONST.__objc_selrefs: 0xc48
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x90
-  __AUTH_CONST.__auth_got: 0x180
+  __DATA_CONST.__objc_superrefs: 0x98
+  __AUTH_CONST.__auth_got: 0x188
   __AUTH_CONST.__const: 0x960
   __AUTH_CONST.__cfstring: 0x3920
-  __AUTH_CONST.__objc_const: 0x3da0
+  __AUTH_CONST.__objc_const: 0x3fd0
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH.__objc_data: 0x690
-  __DATA.__objc_ivar: 0x148
+  __AUTH.__objc_data: 0x6e0
+  __DATA.__objc_ivar: 0x158
   __DATA.__data: 0x858
   __DATA.__common: 0x10
   __DATA.__bss: 0x130

   - /System/Library/Frameworks/LocalAuthentication.framework/Versions/A/LocalAuthentication
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/FMCoreLite.framework/Versions/A/FMCoreLite
+  - /System/Library/PrivateFrameworks/InternationalSupport.framework/Versions/A/InternationalSupport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 576
-  Symbols:   1754
-  CStrings:  1294
+  Functions: 589
+  Symbols:   1787
+  CStrings:  1308
 
Symbols:
+ +[FMDFMIPAccountInfo supportsSecureCoding]
+ -[FMDFMIPAccountInfo .cxx_destruct]
+ -[FMDFMIPAccountInfo dsid]
+ -[FMDFMIPAccountInfo encodeWithCoder:]
+ -[FMDFMIPAccountInfo initWithCoder:]
+ -[FMDFMIPAccountInfo initWithUserName:dsid:oneTimeRemoveAuthToken:serverURL:]
+ -[FMDFMIPAccountInfo oneTimeRemoveAuthToken]
+ -[FMDFMIPAccountInfo serverURL]
+ -[FMDFMIPAccountInfo setDsid:]
+ -[FMDFMIPAccountInfo setOneTimeRemoveAuthToken:]
+ -[FMDFMIPAccountInfo setServerURL:]
+ -[FMDFMIPAccountInfo setUsername:]
+ -[FMDFMIPAccountInfo username]
+ OBJC_IVAR_$_FMDFMIPAccountInfo._dsid
+ OBJC_IVAR_$_FMDFMIPAccountInfo._oneTimeRemoveAuthToken
+ OBJC_IVAR_$_FMDFMIPAccountInfo._serverURL
+ OBJC_IVAR_$_FMDFMIPAccountInfo._username
+ _FMNSXPCConnectionConfigurationSharedConfigurationServiceName
+ _OBJC_CLASS_$_FMDFMIPAccountInfo
+ _OBJC_CLASS_$_NSURL
+ _OBJC_METACLASS_$_FMDFMIPAccountInfo
+ __OBJC_$_CLASS_METHODS_FMDFMIPAccountInfo
+ __OBJC_$_CLASS_PROP_LIST_FMDFMIPAccountInfo
+ __OBJC_$_INSTANCE_METHODS_FMDFMIPAccountInfo
+ __OBJC_$_INSTANCE_VARIABLES_FMDFMIPAccountInfo
+ __OBJC_$_PROP_LIST_FMDFMIPAccountInfo
+ __OBJC_CLASS_PROTOCOLS_$_FMDFMIPAccountInfo
+ __OBJC_CLASS_RO_$_FMDFMIPAccountInfo
+ __OBJC_METACLASS_RO_$_FMDFMIPAccountInfo
+ _objc_msgSend$oneTimeRemoveAuthToken
+ _objc_msgSend$serverURL
+ _objc_msgSend$setOneTimeRemoveAuthToken:
+ _objc_msgSend$setServerURL:
+ _objc_setProperty_atomic_copy
- _kFMDTnLStatusKey
CStrings:
+ "@\"NSURL\""
+ "@48@0:8@16@24@32@40"
+ "FMDFMIPAccountInfo"
+ "T@\"NSString\",C,N,V_dsid"
+ "T@\"NSString\",C,N,V_oneTimeRemoveAuthToken"
+ "T@\"NSString\",C,N,V_username"
+ "T@\"NSURL\",C,V_serverURL"
+ "_oneTimeRemoveAuthToken"
+ "_serverURL"
+ "com.apple.icloud.FindMyDevice.FindMyDeviceSharedConfigurationXPCService"
+ "initWithUserName:dsid:oneTimeRemoveAuthToken:serverURL:"
+ "oneTimeRemoveAuthToken"
+ "serverURL"
+ "setOneTimeRemoveAuthToken:"
+ "setServerURL:"
- "tlStatus"
```
