## Safari

> `/System/Library/PrivateFrameworks/Safari.framework/Versions/A/Safari`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methname`

```diff

-621.2.3.11.1
-  __TEXT.__text: 0x6e8234
+621.2.4.11.2
+  __TEXT.__text: 0x6e849c
   __TEXT.__auth_stubs: 0x5860
-  __TEXT.__objc_methlist: 0x54a34
-  __TEXT.__gcc_except_tab: 0xc64bc
+  __TEXT.__objc_methlist: 0x54a44
+  __TEXT.__gcc_except_tab: 0xc6508
   __TEXT.__const: 0x5b84
   __TEXT.__ustring: 0x10dbe
   __TEXT.__cstring: 0x49c75
-  __TEXT.__oslogstring: 0x1ec6b
+  __TEXT.__oslogstring: 0x1eccb
   __TEXT.__dlopen_cstrs: 0x468
   __TEXT.__constg_swiftt: 0x684
   __TEXT.__swift5_typeref: 0x3a6e

   __TEXT.__swift5_capture: 0x344
   __TEXT.__swift_as_entry: 0x2c
   __TEXT.__swift_as_ret: 0x20
-  __TEXT.__unwind_info: 0x38530
+  __TEXT.__unwind_info: 0x38538
   __TEXT.__eh_frame: 0xc50
   __TEXT.__objc_classname: 0xb58a
   __TEXT.__objc_methname: 0xfaef3

   __AUTH_CONST.__auth_got: 0x2c48
   __AUTH_CONST.__const: 0x1a680
   __AUTH_CONST.__cfstring: 0x33fa0
-  __AUTH_CONST.__objc_const: 0x7bc50
+  __AUTH_CONST.__objc_const: 0x7bca8
   __AUTH_CONST.__objc_intobj: 0x1200
   __AUTH_CONST.__objc_dictobj: 0x5a0
   __AUTH_CONST.__objc_arrayobj: 0x4e0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 35372
-  Symbols:   77305
-  CStrings:  47135
+  Functions: 35373
+  Symbols:   77307
+  CStrings:  47136
 
Symbols:
+ -[Alert windowDidBecomeKey:]
+ __OBJC_CLASS_PROTOCOLS_$_Alert
Functions:
~ -[Alert beginSheetModalForWindow:completionHandler:] : 280 -> 272
+ -[Alert windowDidBecomeKey:]
~ -[AutoFillLocalAuthenticationOperation _shouldEvaluateAuthenticationPolicyWithSavedAccountMatch:] : 328 -> 368
~ -[AutoFillLocalAuthenticationOperation tab] : 16 -> 52
~ -[AutoFillLocalAuthenticationOperation setTab:] : 12 -> 20
~ -[AutoFillLocalAuthenticationOperation .cxx_destruct] : 140 -> 136
~ -[BrowserUIDelegate webView:createWebViewWithConfiguration:forNavigationAction:windowFeatures:] : 1500 -> 1828
~ __ZN6Safari19FormCredentialSaver21offerToSaveCredentialERKNS_2WK5FrameES4_P8NSStringS6_b34FormCredentialSaverPromptingPolicy34RelatedCredentialsMatchingCriteria43FormCredentialSaverShouldOfferDefaultButtonU13block_pointerFvvE : 4400 -> 4468
~ -[TabBarView _adjustedFrameForButtonAtIndex:selectedButtonIndex:isHidden:] : 676 -> 668
~ -[UnifiedField _shouldTruncateOnLeadingEdge] : 124 -> 144
CStrings:
+ "T@\"BrowserTabViewItem\",W,V_tab"
+ "Will not attempt to save credentials because user opted out of saving credentials when signing in"
- "T@\"BrowserTabViewItem\",&,V_tab"
```
