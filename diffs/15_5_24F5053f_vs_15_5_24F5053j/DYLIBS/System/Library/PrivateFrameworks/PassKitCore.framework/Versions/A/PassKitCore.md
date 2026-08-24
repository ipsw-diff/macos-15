## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore`

```diff

-1591.6.2.2.0
-  __TEXT.__text: 0x7d7ee0
+1591.6.3.0.0
+  __TEXT.__text: 0x7d8398
   __TEXT.__auth_stubs: 0x45b0
-  __TEXT.__objc_methlist: 0x67d04
+  __TEXT.__objc_methlist: 0x67d7c
   __TEXT.__const: 0xdac0
-  __TEXT.__cstring: 0x63f25
+  __TEXT.__cstring: 0x63f85
   __TEXT.__swift5_typeref: 0x4d5c
   __TEXT.__swift5_capture: 0x3230
-  __TEXT.__oslogstring: 0x2f0af
+  __TEXT.__oslogstring: 0x2f11a
   __TEXT.__constg_swiftt: 0x48a4
   __TEXT.__swift5_fieldmd: 0x4bc8
   __TEXT.__swift5_reflstr: 0x3e5d

   __TEXT.__swift5_types2: 0x4
   __TEXT.__gcc_except_tab: 0x6f24
   __TEXT.__ustring: 0x1ed6
-  __TEXT.__unwind_info: 0x1a188
+  __TEXT.__unwind_info: 0x1a1b0
   __TEXT.__eh_frame: 0x4724
-  __TEXT.__objc_classname: 0xf2ce
-  __TEXT.__objc_methname: 0xc082f
+  __TEXT.__objc_classname: 0xf2d1
+  __TEXT.__objc_methname: 0xc0915
   __TEXT.__objc_methtype: 0x160bb
-  __TEXT.__objc_stubs: 0x529a0
-  __DATA_CONST.__got: 0x3fc0
-  __DATA_CONST.__const: 0xf368
+  __TEXT.__objc_stubs: 0x529e0
+  __DATA_CONST.__got: 0x3fc8
+  __DATA_CONST.__const: 0xf350
   __DATA_CONST.__objc_classlist: 0x3860
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x4f8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x20f08
+  __DATA_CONST.__objc_selrefs: 0x20f40
   __DATA_CONST.__objc_protorefs: 0x1f8
   __DATA_CONST.__objc_superrefs: 0x2c90
-  __DATA_CONST.__objc_arraydata: 0x30a8
+  __DATA_CONST.__objc_arraydata: 0x3148
   __AUTH_CONST.__auth_got: 0x22e8
-  __AUTH_CONST.__const: 0x26648
-  __AUTH_CONST.__cfstring: 0x6bbc0
-  __AUTH_CONST.__objc_const: 0xbd488
-  __AUTH_CONST.__objc_arrayobj: 0xae0
-  __AUTH_CONST.__objc_dictobj: 0x1d88
+  __AUTH_CONST.__const: 0x26678
+  __AUTH_CONST.__cfstring: 0x6bc60
+  __AUTH_CONST.__objc_const: 0xbd4e8
+  __AUTH_CONST.__objc_arrayobj: 0xaf8
+  __AUTH_CONST.__objc_dictobj: 0x1e28
   __AUTH_CONST.__objc_intobj: 0x1098
   __AUTH_CONST.__objc_doubleobj: 0x2b0
   __AUTH.__objc_data: 0x12420
   __AUTH.__data: 0x33f0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x872c
+  __DATA.__objc_ivar: 0x8730
   __DATA.__data: 0x6e30
   __DATA.__bss: 0x164c8
   __DATA.__common: 0x1c0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 47540
-  Symbols:   80444
-  CStrings:  46844
+  Functions: 47548
+  Symbols:   80457
+  CStrings:  46859
 
Symbols:
+ -[PKAccount(PKSavingsAccountFeatureDescriptor) accountBalanceEventReportingFeatureDescriptor]
+ -[PKAccount(PKSavingsAccountFeatureDescriptor) supportsAccountBalanceEventReportingForLocation:]
+ -[PKAccountLocation app]
+ -[PKAccountLocation copyWithZone:]
+ -[PKAccountLocation description]
+ -[PKAccountLocation page]
+ -[PKAccountLocation setApp:]
+ -[PKAccountLocation setPage:]
+ -[PKSavingsAccountFeatureDescriptor accountLocations]
+ -[PKSavingsAccountFeatureDescriptor setAccountLocations:]
+ _PKSavingsAccountFeatureDescriptorIdentifierAccountBalanceEventReporting
+ __OBJC_$_PROP_LIST_PKAccountLocation
+ ___56-[PKSavingsAccountFeatureDescriptor initWithDictionary:]_block_invoke
+ ___block_descriptor_40_e8_32s_e41_B16?0"PKPassEntitlementsComposerEntry"8l
+ _objc_msgSend$accountBalanceEventReportingFeatureDescriptor
+ _objc_msgSend$accountLocations
- _PKAccountLocationAppFromString
- _PKAccountLocationPageFromString
- ___block_descriptor_32_e41_B16?0"PKPassEntitlementsComposerEntry"8l
CStrings:
+ "Either feature descriptor (%ld) or location (%ld) was nil when checking supported balance access locations"
+ "T@\"NSArray\",C,N,V_accountLocations"
+ "TQ,N,V_app"
+ "TQ,N,V_page"
+ "_accountLocations"
+ "accountBalanceEventReporting"
+ "accountBalanceEventReportingFeatureDescriptor"
+ "accountLocations"
+ "accountLocations: '%@'"
+ "app: '%ld'; "
+ "page: '%ld'; "
+ "setAccountLocations:"
+ "setApp:"
+ "setPage:"
+ "supportsAccountBalanceEventReportingForLocation:"
```
