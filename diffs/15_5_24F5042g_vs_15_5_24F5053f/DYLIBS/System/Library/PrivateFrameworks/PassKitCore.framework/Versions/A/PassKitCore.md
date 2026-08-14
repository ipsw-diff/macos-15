## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore`

```diff

-1591.5.17.3.0
-  __TEXT.__text: 0x7d749c
+1591.6.2.2.0
+  __TEXT.__text: 0x7d7ee0
   __TEXT.__auth_stubs: 0x45b0
-  __TEXT.__objc_methlist: 0x67c64
+  __TEXT.__objc_methlist: 0x67d04
   __TEXT.__const: 0xdac0
-  __TEXT.__cstring: 0x63e96
+  __TEXT.__cstring: 0x63f25
   __TEXT.__swift5_typeref: 0x4d5c
   __TEXT.__swift5_capture: 0x3230
-  __TEXT.__oslogstring: 0x2f092
+  __TEXT.__oslogstring: 0x2f0af
   __TEXT.__constg_swiftt: 0x48a4
   __TEXT.__swift5_fieldmd: 0x4bc8
   __TEXT.__swift5_reflstr: 0x3e5d

   __TEXT.__swift5_protos: 0x40
   __TEXT.__swift5_mpenum: 0xf0
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x6f34
+  __TEXT.__gcc_except_tab: 0x6f24
   __TEXT.__ustring: 0x1ed6
-  __TEXT.__unwind_info: 0x1a170
+  __TEXT.__unwind_info: 0x1a188
   __TEXT.__eh_frame: 0x4724
-  __TEXT.__objc_classname: 0xf2bc
-  __TEXT.__objc_methname: 0xc06a1
-  __TEXT.__objc_methtype: 0x16075
-  __TEXT.__objc_stubs: 0x52940
+  __TEXT.__objc_classname: 0xf2ce
+  __TEXT.__objc_methname: 0xc082f
+  __TEXT.__objc_methtype: 0x160bb
+  __TEXT.__objc_stubs: 0x529a0
   __DATA_CONST.__got: 0x3fc0
-  __DATA_CONST.__const: 0xf318
-  __DATA_CONST.__objc_classlist: 0x3858
+  __DATA_CONST.__const: 0xf368
+  __DATA_CONST.__objc_classlist: 0x3860
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x4f8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x20ec8
+  __DATA_CONST.__objc_selrefs: 0x20f08
   __DATA_CONST.__objc_protorefs: 0x1f8
-  __DATA_CONST.__objc_superrefs: 0x2c88
+  __DATA_CONST.__objc_superrefs: 0x2c90
   __DATA_CONST.__objc_arraydata: 0x30a8
   __AUTH_CONST.__auth_got: 0x22e8
-  __AUTH_CONST.__const: 0x26698
-  __AUTH_CONST.__cfstring: 0x6bb00
-  __AUTH_CONST.__objc_const: 0xbd3b0
+  __AUTH_CONST.__const: 0x26648
+  __AUTH_CONST.__cfstring: 0x6bbc0
+  __AUTH_CONST.__objc_const: 0xbd488
   __AUTH_CONST.__objc_arrayobj: 0xae0
   __AUTH_CONST.__objc_dictobj: 0x1d88
   __AUTH_CONST.__objc_intobj: 0x1098
   __AUTH_CONST.__objc_doubleobj: 0x2b0
-  __AUTH.__objc_data: 0x123d0
+  __AUTH.__objc_data: 0x12420
   __AUTH.__data: 0x33f0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x8728
+  __DATA.__objc_ivar: 0x872c
   __DATA.__data: 0x6e30
-  __DATA.__bss: 0x164d8
+  __DATA.__bss: 0x164c8
   __DATA.__common: 0x1c0
   __DATA_DIRTY.__objc_data: 0x12070
   __DATA_DIRTY.__data: 0x40

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 47525
-  Symbols:   80407
-  CStrings:  46829
+  Functions: 47540
+  Symbols:   80444
+  CStrings:  46844
 
Symbols:
+ +[PKAccountLocation supportsSecureCoding]
+ +[PKContactlessInterfaceSession _copyDevicePrimaryContactlessAccessControlForSecureElementPass:]
+ +[PKContactlessInterfaceSession _useSTSForDevicePrimaryContactlessAccessControlForSecureElementPass:]
+ +[PKContactlessInterfaceSession copyAccessControlForPaymentApplication:subcredential:onSecureElementPass:]
+ +[PKPaymentSession STSCredentialForPaymentApplication:subcredential:onSecureElementPass:]
+ +[PKPaymentSession _STSCredentialTypeForPaymentApplication:subcredential:onSecureElementPass:STSCredential:]
+ +[PKPaymentSession useSTSForPaymentApplication:subcredential:onSecureElementPass:]
+ -[PKAccountDeviceEventReporter reportEventIfNecessary:location:completion:]
+ -[PKAccountLocation encodeWithCoder:]
+ -[PKAccountLocation initWithApp:page:]
+ -[PKAccountLocation initWithCoder:]
+ -[PKAccountLocation initWithDictionary:]
+ -[PKAccountLocation isEqual:]
+ -[PKPushProvisioningTarget _jsonRepresentationWithSanitization:]
+ -[PKPushProvisioningTarget sanitizedJSONRepresentation]
+ GCC_except_table59
+ GCC_except_table85
+ OBJC_IVAR_$_PKAccountLocation._app
+ OBJC_IVAR_$_PKAccountLocation._page
+ _OBJC_CLASS_$_PKAccountLocation
+ _OBJC_METACLASS_$_PKAccountLocation
+ _PKAccountLocationAppFromString
+ _PKAccountLocationAppKey
+ _PKAccountLocationAppSettingsString
+ _PKAccountLocationAppWalletString
+ _PKAccountLocationAppWalletWatchString
+ _PKAccountLocationPageAppleCardDashboardString
+ _PKAccountLocationPageAppleCardRewardsAndOffersString
+ _PKAccountLocationPageFromString
+ _PKAccountLocationPageKey
+ _PKAccountLocationPageSavingsDashboardString
+ _PKAccountLocationPageSavingsDetailsString
+ _PKAccountLocationPageWalletAndApplePaySettingsString
+ _PKPRemoteCredentialTransferTypeIsCopyable
+ __OBJC_$_CLASS_METHODS_PKAccountLocation
+ __OBJC_$_CLASS_PROP_LIST_PKAccountLocation
+ __OBJC_$_INSTANCE_METHODS_PKAccountLocation
+ __OBJC_$_INSTANCE_VARIABLES_PKAccountLocation
+ __OBJC_CLASS_PROTOCOLS_$_PKAccountLocation
+ __OBJC_CLASS_RO_$_PKAccountLocation
+ __OBJC_METACLASS_RO_$_PKAccountLocation
+ _objc_msgSend$STSCredentialForPaymentApplication:subcredential:onSecureElementPass:
+ _objc_msgSend$_jsonRepresentationWithSanitization:
+ _objc_msgSend$copyAccessControl
+ _objc_msgSend$initWithApp:page:
+ _objc_msgSend$reportEventIfNecessary:location:completion:
+ _objc_msgSend$useSTSForPaymentApplication:subcredential:onSecureElementPass:
- -[PKPaymentProvisioningController allowCarKeyTransfer]
- -[PKPaymentProvisioningController setAllowCarKeyTransfer:]
- GCC_except_table118
- GCC_except_table74
- OBJC_IVAR_$_PKPaymentProvisioningController._allowCarKeyTransfer
- ___131-[PKDiscoveryDataSource displayedDiscoveryItem:isWelcomeCard:afterSwipingToCard:multipleStoryCardsAvailable:callToAction:cardSize:]_block_invoke
- ___block_descriptor_48_e8_32s40w_e46_v24?0"PKDiscoveryArticleLayout"8"NSError"16l
- _objc_msgSend$hasHitMaxViewCount
- _objc_msgSend$reportEventIfNecessary:completion:
- _objc_msgSend$setAllowCarKeyTransfer:
CStrings:
+ "Invalid credentials count for STS session: (n: %lu)"
+ "PKAccountLocation"
+ "Remote credential missing identifier"
+ "STSCredentialForPaymentApplication:subcredential:onSecureElementPass:"
+ "^{__SecAccessControl=}24@0:8@16"
+ "^{__SecAccessControl=}40@0:8@16@24@32"
+ "_app"
+ "_copyDevicePrimaryContactlessAccessControlForSecureElementPass:"
+ "_jsonRepresentationWithSanitization:"
+ "_useSTSForDevicePrimaryContactlessAccessControlForSecureElementPass:"
+ "appleCardDashboard"
+ "appleCardRewardsAndOffers"
+ "copyAccessControl"
+ "copyAccessControlForPaymentApplication:subcredential:onSecureElementPass:"
+ "initWithApp:page:"
+ "reportEventIfNecessary:location:completion:"
+ "sanitizedJSONRepresentation"
+ "savingsDashboard"
+ "useSTSForPaymentApplication:subcredential:onSecureElementPass:"
+ "walletWatch"
- "Invalid credentials count for STS session: (t: %lu, n: %lu)"
- "TB,N,V_allowCarKeyTransfer"
- "_allowCarKeyTransfer"
- "allowCarKeyTransfer"
- "setAllowCarKeyTransfer:"
```
