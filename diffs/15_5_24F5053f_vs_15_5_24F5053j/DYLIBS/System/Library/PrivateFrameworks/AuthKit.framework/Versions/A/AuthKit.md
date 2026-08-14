## AuthKit

> `/System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit`

```diff

-493.462.0.0.0
-  __TEXT.__text: 0x1f2b68
+493.463.1.0.0
+  __TEXT.__text: 0x1f3318
   __TEXT.__auth_stubs: 0xc00
-  __TEXT.__objc_methlist: 0xce04
+  __TEXT.__objc_methlist: 0xcebc
   __TEXT.__const: 0x46811
-  __TEXT.__cstring: 0xdbf7
-  __TEXT.__oslogstring: 0xff78
+  __TEXT.__cstring: 0xdc44
+  __TEXT.__oslogstring: 0xffb8
   __TEXT.__gcc_except_tab: 0x54ec
   __TEXT.__ustring: 0x1b8
   __TEXT.__dlopen_cstrs: 0xb4
-  __TEXT.__unwind_info: 0x3d60
+  __TEXT.__unwind_info: 0x3d88
   __TEXT.__eh_frame: 0xb8
-  __TEXT.__objc_classname: 0x1a5b
-  __TEXT.__objc_methname: 0x1fe42
+  __TEXT.__objc_classname: 0x1a75
+  __TEXT.__objc_methname: 0x1ff0e
   __TEXT.__objc_methtype: 0x439d
-  __TEXT.__objc_stubs: 0xdb80
-  __DATA_CONST.__got: 0x870
-  __DATA_CONST.__const: 0x4598
-  __DATA_CONST.__objc_classlist: 0x5b0
+  __TEXT.__objc_stubs: 0xdc00
+  __DATA_CONST.__got: 0x878
+  __DATA_CONST.__const: 0x45a8
+  __DATA_CONST.__objc_classlist: 0x5b8
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x1e8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x68b8
+  __DATA_CONST.__objc_selrefs: 0x68e0
   __DATA_CONST.__objc_protorefs: 0xd8
   __DATA_CONST.__objc_superrefs: 0x3a0
   __DATA_CONST.__objc_arraydata: 0x1c0
   __AUTH_CONST.__auth_got: 0x610
   __AUTH_CONST.__const: 0xc0a0
-  __AUTH_CONST.__cfstring: 0xe660
-  __AUTH_CONST.__objc_const: 0x22fc8
+  __AUTH_CONST.__cfstring: 0xe6e0
+  __AUTH_CONST.__objc_const: 0x231d8
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_dictobj: 0x2a8
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH.__objc_data: 0x38e0
-  __DATA.__objc_ivar: 0xf20
+  __AUTH.__objc_data: 0x3930
+  __DATA.__objc_ivar: 0xf28
   __DATA.__data: 0x1868
   __DATA.__bss: 0x7f8
   __DATA.__common: 0xa18

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6013
-  Symbols:   11591
-  CStrings:  8430
+  Functions: 6028
+  Symbols:   11622
+  CStrings:  8443
 
Symbols:
+ +[AKAttestationResponseData supportsSecureCoding]
+ -[AKAnisetteProvisioningController handleAttestationResponseWithResponseData:completion:]
+ -[AKAttestationResponseData .cxx_destruct]
+ -[AKAttestationResponseData copyWithZone:]
+ -[AKAttestationResponseData description]
+ -[AKAttestationResponseData encodeWithCoder:]
+ -[AKAttestationResponseData headersFromServer]
+ -[AKAttestationResponseData initWithCoder:]
+ -[AKAttestationResponseData setHeadersFromServer:]
+ -[AKAttestationResponseData setStatus:]
+ -[AKAttestationResponseData status]
+ -[AKURLBag isIDSBAADisabled]
+ -[NSError(AuthKit) ak_errorsHeaderStringWithMessage]
+ OBJC_IVAR_$_AKAttestationResponseData._headersFromServer
+ OBJC_IVAR_$_AKAttestationResponseData._status
+ _AKHTTPResponseHeaderServerTimeKey
+ _OBJC_CLASS_$_AKAttestationResponseData
+ _OBJC_METACLASS_$_AKAttestationResponseData
+ __OBJC_$_CLASS_METHODS_AKAttestationResponseData
+ __OBJC_$_CLASS_PROP_LIST_AKAttestationResponseData
+ __OBJC_$_INSTANCE_METHODS_AKAttestationResponseData
+ __OBJC_$_INSTANCE_VARIABLES_AKAttestationResponseData
+ __OBJC_$_PROP_LIST_AKAttestationResponseData
+ __OBJC_CLASS_PROTOCOLS_$_AKAttestationResponseData
+ __OBJC_CLASS_RO_$_AKAttestationResponseData
+ __OBJC_METACLASS_RO_$_AKAttestationResponseData
+ ___52-[NSError(AuthKit) ak_errorsHeaderStringWithMessage]_block_invoke
+ _objc_msgSend$headersFromServer
+ _objc_msgSend$setHeadersFromServer:
+ _objc_msgSend$setStatus:
+ _objc_msgSend$status
CStrings:
+ "%@:%ld:[%@]"
+ "<%@: %p> status: %li, headers:%@"
+ "AKAttestationResponseData"
+ "Handling attestation response - %@"
+ "T@\"NSDictionary\",&,N,V_headersFromServer"
+ "Unhandled status code (%ld)."
+ "_headersFromServer"
+ "ak_errorsHeaderStringWithMessage"
+ "disableIDSBAA"
+ "handleAttestationResponseWithResponseData:completion:"
+ "headersFromServer"
+ "isIDSBAADisabled"
+ "setHeadersFromServer:"
```
