## AppleMediaServicesUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-6.5.5.0.0
-  __TEXT.__text: 0x179b18
-  __TEXT.__auth_stubs: 0x38a0
-  __TEXT.__objc_methlist: 0xee04
+6.5.10.0.0
+  __TEXT.__text: 0x17ad1c
+  __TEXT.__auth_stubs: 0x38b0
+  __TEXT.__objc_methlist: 0xef7c
   __TEXT.__const: 0x7fe4
-  __TEXT.__cstring: 0xb8e4
-  __TEXT.__oslogstring: 0x8675
-  __TEXT.__gcc_except_tab: 0x16ec
-  __TEXT.__dlopen_cstrs: 0x875
+  __TEXT.__cstring: 0xb964
+  __TEXT.__oslogstring: 0x86f5
+  __TEXT.__gcc_except_tab: 0x1728
+  __TEXT.__dlopen_cstrs: 0x8d8
   __TEXT.__swift5_typeref: 0xba6e
   __TEXT.__swift5_reflstr: 0x1e85
   __TEXT.__swift5_assocty: 0xdd8

   __TEXT.__swift_as_entry: 0xe4
   __TEXT.__swift_as_ret: 0x10c
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__unwind_info: 0x6a58
+  __TEXT.__unwind_info: 0x6aa8
   __TEXT.__eh_frame: 0x3a68
-  __TEXT.__objc_classname: 0x2239
-  __TEXT.__objc_methname: 0x22612
-  __TEXT.__objc_methtype: 0x6e64
-  __TEXT.__objc_stubs: 0x17fa0
-  __DATA_CONST.__got: 0x14c8
-  __DATA_CONST.__const: 0x3550
-  __DATA_CONST.__objc_classlist: 0x900
+  __TEXT.__objc_classname: 0x227a
+  __TEXT.__objc_methname: 0x229d6
+  __TEXT.__objc_methtype: 0x7048
+  __TEXT.__objc_stubs: 0x18120
+  __DATA_CONST.__got: 0x14d8
+  __DATA_CONST.__const: 0x3590
+  __DATA_CONST.__objc_classlist: 0x908
   __DATA_CONST.__objc_catlist: 0x90
-  __DATA_CONST.__objc_protolist: 0x318
+  __DATA_CONST.__objc_protolist: 0x320
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7f30
+  __DATA_CONST.__objc_selrefs: 0x7fd8
   __DATA_CONST.__objc_protorefs: 0xf0
-  __DATA_CONST.__objc_superrefs: 0x630
+  __DATA_CONST.__objc_superrefs: 0x638
   __DATA_CONST.__objc_arraydata: 0x310
-  __AUTH_CONST.__auth_got: 0x1c60
+  __AUTH_CONST.__auth_got: 0x1c68
   __AUTH_CONST.__const: 0x5cd8
-  __AUTH_CONST.__cfstring: 0x9e60
-  __AUTH_CONST.__objc_const: 0x1cc68
+  __AUTH_CONST.__cfstring: 0x9f20
+  __AUTH_CONST.__objc_const: 0x1cfc0
   __AUTH_CONST.__objc_intobj: 0x2b8
   __AUTH_CONST.__objc_dictobj: 0x208
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x108
-  __AUTH.__objc_data: 0x5350
+  __AUTH.__objc_data: 0x53a0
   __AUTH.__data: 0x3e80
-  __DATA.__objc_ivar: 0xfb4
-  __DATA.__data: 0x50b8
-  __DATA.__bss: 0x8ef8
+  __DATA.__objc_ivar: 0xfcc
+  __DATA.__data: 0x5118
+  __DATA.__bss: 0x8f08
   __DATA.__common: 0x238
   __DATA_DIRTY.__objc_data: 0x1a40
   - /System/Library/Frameworks/Accessibility.framework/Versions/A/Accessibility

   - /System/iOSSupport/System/Library/PrivateFrameworks/OnBoardingKit.framework/Versions/A/OnBoardingKit
   - /System/iOSSupport/System/Library/PrivateFrameworks/ShareSheet.framework/Versions/A/ShareSheet
   - /System/iOSSupport/System/Library/PrivateFrameworks/UIKitCore.framework/Versions/A/UIKitCore
+  - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 11253
-  Symbols:   13904
-  CStrings:  8548
+  Functions: 11284
+  Symbols:   13965
+  CStrings:  8593
 
Symbols:
+ -[AMSUIWebAppearance clientHandlesDismissability]
+ -[AMSUIWebAppearance setClientHandlesDismissability:]
+ -[AMSUIWebContainerViewController childViewControllerForHomeIndicatorAutoHidden]
+ -[AMSUIWebContainerViewController childViewControllerForStatusBarStyle]
+ -[AMSUIWebContainerViewController pageModel]
+ -[AMSUIWebContainerViewController preferredInterfaceOrientationForPresentation]
+ -[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]
+ -[AMSUIWebContainerViewController setPageModel:]
+ -[AMSUIWebContainerViewController supportedInterfaceOrientations]
+ -[AMSUIWebFlowController navigationControllerPreferredInterfaceOrientationForPresentation:]
+ -[AMSUIWebFlowController navigationControllerSupportedInterfaceOrientations:]
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
+ GCC_except_table49
+ GCC_except_table54
+ OBJC_IVAR_$_AMSUIWebAppearance._clientHandlesDismissability
+ OBJC_IVAR_$_AMSUIWebContainerViewController._pageModel
+ OBJC_IVAR_$_AMSUIWebOpenAuthenticationSession._URL
+ OBJC_IVAR_$_AMSUIWebOpenAuthenticationSession._callback
+ OBJC_IVAR_$_AMSUIWebOpenAuthenticationSession._ephemeral
+ OBJC_IVAR_$_AMSUIWebPageModel._swipeToDismissAction
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_AMSUIWebOpenAuthenticationSession
+ _OBJC_CLASS_$_UIContentUnavailableConfiguration
+ _OBJC_CLASS_$_UIContentUnavailableView
+ _OBJC_METACLASS_$_AMSUIWebOpenAuthenticationSession
+ __46-[AMSUIWebOpenAuthenticationSession runAction]_block_invoke
+ __98-[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]_block_invoke
+ __98-[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]_block_invoke_2
+ __OBJC_$_INSTANCE_METHODS_AMSUIWebOpenAuthenticationSession
+ __OBJC_$_INSTANCE_VARIABLES_AMSUIWebOpenAuthenticationSession
+ __OBJC_$_PROP_LIST_AMSUIWebOpenAuthenticationSession
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AMSUIWebPageProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UINavigationControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UINavigationControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_UINavigationControllerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_AMSUIWebFlowController
+ __OBJC_CLASS_PROTOCOLS_$_AMSUIWebOpenAuthenticationSession
+ __OBJC_CLASS_RO_$_AMSUIWebOpenAuthenticationSession
+ __OBJC_LABEL_PROTOCOL_$_UINavigationControllerDelegate
+ __OBJC_METACLASS_RO_$_AMSUIWebOpenAuthenticationSession
+ __OBJC_PROTOCOL_$_UINavigationControllerDelegate
+ ___34-[AMSUIErrorView setButtonAction:]_block_invoke
+ ___46-[AMSUIWebOpenAuthenticationSession runAction]_block_invoke
+ ___98-[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]_block_invoke
+ ___98-[AMSUIWebContainerViewController replaceContentWithViewController:animated:pageModel:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40r_e27_v24?0"NSURL"8"NSError"16lr40l8s32l8
+ ___block_descriptor_72_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ _objc_msgSend$actionWithHandler:
+ _objc_msgSend$buttonProperties
+ _objc_msgSend$clientHandlesDismissability
+ _objc_msgSend$emptyConfiguration
+ _objc_msgSend$pageModel
+ _objc_msgSend$preferredInterfaceOrientationForPresentation
+ _objc_msgSend$replaceContentWithViewController:animated:pageModel:completion:
+ _objc_msgSend$secondaryText
+ _objc_msgSend$setClientHandlesDismissability:
+ _objc_msgSend$setPageModel:
+ _objc_msgSend$setPrimaryAction:
+ _objc_msgSend$setSecondaryText:
+ _objc_msgSend$supportedInterfaceOrientations
+ _objc_msgSend$swipeToDismissAction
- -[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]
- GCC_except_table31
- GCC_except_table45
- GCC_except_table50
- __88-[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]_block_invoke
- __88-[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]_block_invoke_2
- ___88-[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]_block_invoke
- ___88-[AMSUIWebContainerViewController replaceContentWithViewController:animated:completion:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s_e5_v8?0ls32l8s40l8
- _objc_msgSend$buttonTitle
- _objc_msgSend$replaceContentWithViewController:animated:completion:
CStrings:
+ "%{public}@ Action finished successfully with a URL. url = %{public}@"
+ "%{public}@: [%{public}@] Running swipe to dismiss action"
+ "@\"<UIViewControllerAnimatedTransitioning>\"48@0:8@\"UINavigationController\"16q24@\"UIViewController\"32@\"UIViewController\"40"
+ "@\"<UIViewControllerInteractiveTransitioning>\"32@0:8@\"UINavigationController\"16@\"<UIViewControllerAnimatedTransitioning>\"24"
+ "@\"AMSUIWebAction\""
+ "@\"AMSUIWebAction\"16@0:8"
+ "@\"UIContentUnavailableView\""
+ "@48@0:8@16q24@32@40"
+ "AMSUIWebOpenAuthenticationSession"
+ "No URL Provided"
+ "No callback Provided"
+ "Q24@0:8@\"UINavigationController\"16"
+ "T@\"<AMSUIWebPageProvider>\",&,N,V_pageModel"
+ "T@\"AMSUIWebAction\",&,N,V_swipeToDismissAction"
+ "T@\"AMSUIWebAction\",?,R,N"
+ "T@\"UIContentUnavailableView\",&,N,V_backingView"
+ "TB,N,V_clientHandlesDismissability"
+ "UINavigationControllerDelegate"
+ "WIFI_NETWORK_ERROR_MESSAGE"
+ "WLAN_NETWORK_ERROR_MESSAGE"
+ "_clientHandlesDismissability"
+ "_pageModel"
+ "_swipeToDismissAction"
+ "actionWithHandler:"
+ "buttonProperties"
+ "childViewControllerForHomeIndicatorAutoHidden"
+ "childViewControllerForStatusBarStyle"
+ "clientHandlesDismissability"
+ "emptyConfiguration"
+ "navigationController:animationControllerForOperation:fromViewController:toViewController:"
+ "navigationController:didShowViewController:animated:"
+ "navigationController:interactionControllerForAnimationController:"
+ "navigationController:willShowViewController:animated:"
+ "navigationControllerPreferredInterfaceOrientationForPresentation:"
+ "navigationControllerSupportedInterfaceOrientations:"
+ "pageModel"
+ "preferredInterfaceOrientationForPresentation"
+ "q24@0:8@\"UINavigationController\"16"
+ "replaceContentWithViewController:animated:pageModel:completion:"
+ "setClientHandlesDismissability:"
+ "setPageModel:"
+ "setPrimaryAction:"
+ "setSecondaryText:"
+ "setSwipeToDismissAction:"
+ "swipeToDismissAction"
+ "v36@0:8@\"UINavigationController\"16@\"UIViewController\"24B32"
+ "v44@0:8@16B24@28@?36"
+ "wapi"
- "NETWORK_ERROR_MESSAGE"
- "T@\"_UIContentUnavailableView\",&,N,V_backingView"
- "replaceContentWithViewController:animated:completion:"
```
