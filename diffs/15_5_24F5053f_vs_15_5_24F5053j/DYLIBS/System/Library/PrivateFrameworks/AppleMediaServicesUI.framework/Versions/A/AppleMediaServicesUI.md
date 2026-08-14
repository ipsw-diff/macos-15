## AppleMediaServicesUI

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-6.5.5.0.0
-  __TEXT.__text: 0x17a050
-  __TEXT.__auth_stubs: 0x3200
-  __TEXT.__objc_methlist: 0xd2ec
+6.5.10.0.0
+  __TEXT.__text: 0x17af2c
+  __TEXT.__auth_stubs: 0x3210
+  __TEXT.__objc_methlist: 0xd3cc
   __TEXT.__const: 0x8384
-  __TEXT.__gcc_except_tab: 0x12d0
-  __TEXT.__oslogstring: 0x79a5
-  __TEXT.__cstring: 0xbcc4
-  __TEXT.__dlopen_cstrs: 0x7f8
+  __TEXT.__gcc_except_tab: 0x1310
+  __TEXT.__oslogstring: 0x79e5
+  __TEXT.__cstring: 0xbd54
+  __TEXT.__dlopen_cstrs: 0x85b
   __TEXT.__swift5_typeref: 0xb906
   __TEXT.__swift5_reflstr: 0x21c5
   __TEXT.__swift5_assocty: 0xe18

   __TEXT.__swift_as_ret: 0x114
   __TEXT.__swift5_protos: 0x2c
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__unwind_info: 0x6750
+  __TEXT.__unwind_info: 0x6788
   __TEXT.__eh_frame: 0x3afc
-  __TEXT.__objc_classname: 0x1d3a
-  __TEXT.__objc_methname: 0x1ca2f
-  __TEXT.__objc_methtype: 0x5aea
-  __TEXT.__objc_stubs: 0x14140
+  __TEXT.__objc_classname: 0x1d5c
+  __TEXT.__objc_methname: 0x1cb86
+  __TEXT.__objc_methtype: 0x5b29
+  __TEXT.__objc_stubs: 0x141a0
   __DATA_CONST.__got: 0x1308
-  __DATA_CONST.__const: 0x1168
-  __DATA_CONST.__objc_classlist: 0x850
+  __DATA_CONST.__const: 0x1180
+  __DATA_CONST.__objc_classlist: 0x858
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x298
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6c88
+  __DATA_CONST.__objc_selrefs: 0x6cb8
   __DATA_CONST.__objc_protorefs: 0xe0
-  __DATA_CONST.__objc_superrefs: 0x5b0
+  __DATA_CONST.__objc_superrefs: 0x5b8
   __DATA_CONST.__objc_arraydata: 0x318
-  __AUTH_CONST.__auth_got: 0x1910
-  __AUTH_CONST.__const: 0x8880
-  __AUTH_CONST.__cfstring: 0x9620
-  __AUTH_CONST.__objc_const: 0x1a4e8
+  __AUTH_CONST.__auth_got: 0x1918
+  __AUTH_CONST.__const: 0x88b0
+  __AUTH_CONST.__cfstring: 0x96e0
+  __AUTH_CONST.__objc_const: 0x1a7a0
   __AUTH_CONST.__objc_intobj: 0x258
   __AUTH_CONST.__objc_dictobj: 0x280
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x120
-  __AUTH.__objc_data: 0x4a08
+  __AUTH.__objc_data: 0x4a58
   __AUTH.__data: 0x4558
-  __DATA.__objc_ivar: 0xe7c
+  __DATA.__objc_ivar: 0xe94
   __DATA.__data: 0x4c70
-  __DATA.__bss: 0x9340
+  __DATA.__bss: 0x9360
   __DATA.__common: 0x248
   __DATA_DIRTY.__objc_data: 0x1ae0
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /System/Library/PrivateFrameworks/PassKitMacHelperTemp.framework/Versions/A/PassKitMacHelperTemp
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
+  - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 10897
-  Symbols:   12474
-  CStrings:  7645
+  Functions: 10921
+  Symbols:   12512
+  CStrings:  7667
 
Symbols:
+ -[AMSUIWebAppearance clientHandlesDismissability]
+ -[AMSUIWebAppearance setClientHandlesDismissability:]
+ -[AMSUIWebContainerViewController pageModel]
+ -[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]
+ -[AMSUIWebContainerViewController setPageModel:]
+ -[AMSUIWebOpenAuthenticationSession .cxx_destruct]
+ -[AMSUIWebOpenAuthenticationSession URL]
+ -[AMSUIWebOpenAuthenticationSession callback]
+ -[AMSUIWebOpenAuthenticationSession ephemeral]
+ -[AMSUIWebOpenAuthenticationSession initWithJSObject:context:]
+ -[AMSUIWebOpenAuthenticationSession presentationAnchorForWebAuthenticationSession:]
+ -[AMSUIWebOpenAuthenticationSession runAction]
+ -[AMSUIWebOpenAuthenticationSession setCallback:]
+ -[AMSUIWebOpenAuthenticationSession setEphemeral:]
+ -[AMSUIWebOpenAuthenticationSession setURL:]
+ -[AMSUIWebPageModel setSwipeToDismissAction:]
+ -[AMSUIWebPageModel swipeToDismissAction]
+ OBJC_IVAR_$_AMSUIWebAppearance._clientHandlesDismissability
+ OBJC_IVAR_$_AMSUIWebContainerViewController._pageModel
+ OBJC_IVAR_$_AMSUIWebOpenAuthenticationSession._URL
+ OBJC_IVAR_$_AMSUIWebOpenAuthenticationSession._callback
+ OBJC_IVAR_$_AMSUIWebOpenAuthenticationSession._ephemeral
+ OBJC_IVAR_$_AMSUIWebPageModel._swipeToDismissAction
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_AMSUIWebOpenAuthenticationSession
+ _OBJC_METACLASS_$_AMSUIWebOpenAuthenticationSession
+ __46-[AMSUIWebOpenAuthenticationSession runAction]_block_invoke
+ __98-[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_AMSUIWebOpenAuthenticationSession
+ __OBJC_$_INSTANCE_VARIABLES_AMSUIWebOpenAuthenticationSession
+ __OBJC_$_PROP_LIST_AMSUIWebOpenAuthenticationSession
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AMSUIWebPageProvider
+ __OBJC_CLASS_PROTOCOLS_$_AMSUIWebOpenAuthenticationSession
+ __OBJC_CLASS_RO_$_AMSUIWebOpenAuthenticationSession
+ __OBJC_METACLASS_RO_$_AMSUIWebOpenAuthenticationSession
+ ___46-[AMSUIWebOpenAuthenticationSession runAction]_block_invoke
+ ___98-[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]_block_invoke
+ ___98-[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40r_e27_v24?0"NSURL"8"NSError"16l
+ _objc_msgSend$clientHandlesDismissability
+ _objc_msgSend$replaceContentWithViewController:animated:pageModel:completion:
+ _objc_msgSend$setClientHandlesDismissability:
+ _objc_msgSend$setPageModel:
- -[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]
- __88-[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]_block_invoke
- ___88-[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]_block_invoke
- ___88-[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]_block_invoke_2
- _objc_msgSend$replaceContentWithViewController:animated:completion:
CStrings:
+ "%{public}@ Action finished successfully with a URL. url = %{public}@"
+ "@\"AMSUIWebAction\""
+ "@\"AMSUIWebAction\"16@0:8"
+ "AMSUIWebOpenAuthenticationSession"
+ "No URL Provided"
+ "No callback Provided"
+ "T@\"<AMSUIWebPageProvider>\",&,V_pageModel"
+ "T@\"AMSUIWebAction\",&,V_swipeToDismissAction"
+ "T@\"AMSUIWebAction\",?,R"
+ "TB,V_clientHandlesDismissability"
+ "WIFI_NETWORK_ERROR_MESSAGE"
+ "WLAN_NETWORK_ERROR_MESSAGE"
+ "_clientHandlesDismissability"
+ "_pageModel"
+ "_swipeToDismissAction"
+ "clientHandlesDismissability"
+ "pageModel"
+ "replaceContentWithViewController:animated:pageModel:completion:"
+ "setClientHandlesDismissability:"
+ "setPageModel:"
+ "setSwipeToDismissAction:"
+ "swipeToDismissAction"
+ "v44@0:8@16B24@28@?36"
+ "wapi"
- "NETWORK_ERROR_MESSAGE"
- "replaceContentWithViewController:animated:completion:"
```
