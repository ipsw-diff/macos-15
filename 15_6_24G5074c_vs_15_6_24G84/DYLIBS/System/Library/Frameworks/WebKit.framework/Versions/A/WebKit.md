## WebKit

> `/System/Library/Frameworks/WebKit.framework/Versions/A/WebKit`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-621.3.8.0.0
-  __TEXT.__text: 0xfda768
+621.3.11.11.3
+  __TEXT.__text: 0xfda7c8
   __TEXT.__auth_stubs: 0x180c0
   __TEXT.__objc_methlist: 0x12cd4
   __TEXT.__const: 0x35c0

   __TEXT.__constg_swiftt: 0x28
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__cstring: 0x30d04e
+  __TEXT.__cstring: 0x30d054
   __TEXT.__swift_as_entry: 0x18
   __TEXT.__swift_as_ret: 0x10
-  __TEXT.__gcc_except_tab: 0x5da40
+  __TEXT.__gcc_except_tab: 0x5da4c
   __TEXT.__oslogstring: 0x42600
   __TEXT.__ustring: 0xb00
   __TEXT.__unwind_info: 0x26148
Symbols:
+ __ZN6WebKit12WebPageProxy11loadRequestEON7WebCore15ResourceRequestENS1_28ShouldOpenExternalURLsPolicyENS1_24IsPerformingHTTPFallbackEONSt3__110unique_ptrINS_20NavigationActionDataENS6_14default_deleteIS8_EEEEPN3API6ObjectEb
- __ZN6WebKit12WebPageProxy11loadRequestEON7WebCore15ResourceRequestENS1_28ShouldOpenExternalURLsPolicyENS1_24IsPerformingHTTPFallbackEONSt3__110unique_ptrINS_20NavigationActionDataENS6_14default_deleteIS8_EEEEPN3API6ObjectE
Functions:
~ _WKPageLoadURLRequest : 220 -> 224
~ _WKPageLoadURL : 328 -> 332
~ __ZN3IPC13ArgumentCoderIN7WebCore21ShareableBitmapHandleEvE6decodeERNS_7DecoderE : 1740 -> 1752
~ _WKPageLoadURLRequestReturningNavigation : 452 -> 456
~ -[WKBrowsingContextController loadRequest:userData:] : 132 -> 136
~ -[WKWebView loadRequest:] : 432 -> 436
~ -[WKWebView(WKPrivate) _loadRequest:shouldOpenExternalURLsPolicy:] : 412 -> 416
~ __ZN6WebKit30RedirectSOAuthorizationSession16completeInternalERKN7WebCore16ResourceResponseEP6NSData : 1584 -> 1588
~ -[WKInspectorViewController webView:decidePolicyForNavigationAction:decisionHandler:] : 440 -> 444
~ __ZN6WebKit12WebPageProxy11loadRequestEON7WebCore15ResourceRequestENS1_28ShouldOpenExternalURLsPolicyENS1_24IsPerformingHTTPFallbackEONSt3__110unique_ptrINS_20NavigationActionDataENS6_14default_deleteIS8_EEEEPN3API6ObjectE -> __ZN6WebKit12WebPageProxy11loadRequestEON7WebCore15ResourceRequestENS1_28ShouldOpenExternalURLsPolicyENS1_24IsPerformingHTTPFallbackEONSt3__110unique_ptrINS_20NavigationActionDataENS6_14default_deleteIS8_EEEEPN3API6ObjectEb : 1068 -> 1072
~ __ZN6WebKit12WebPageProxy23restoreFromSessionStateENS_12SessionStateEb : 780 -> 784
~ __ZN6WebKit12WebPageProxy36didFailProvisionalLoadForFrameSharedEON3WTF3RefINS_15WebProcessProxyENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEERNS_13WebFrameProxyEONS_13FrameInfoDataEON7WebCore15ResourceRequestENSt3__18optionalINS1_23ObjectIdentifierGenericINSE_24NavigationIdentifierTypeENS1_38ObjectIdentifierMainThreadAccessTraitsIyEEyEEEERKNS1_6StringERKNSE_13ResourceErrorENSE_19WillContinueLoadingERKNS_8UserDataENSE_27WillInternallyHandleFailureE : 4812 -> 4816
~ __ZN6WebKit12WebPageProxy32tryReloadAfterProcessTerminationEv : 700 -> 704
~ __ZN3WTF6Detail15CallableWrapperIZZN6WebKit12WebPageProxy31decidePolicyForNavigationActionEONS_3RefINS2_15WebProcessProxyENS_12RawPtrTraitsIS5_EENS_21DefaultRefDerefTraitsIS5_EEEERNS2_13WebFrameProxyEONS2_20NavigationActionDataEONS_17CompletionHandlerIFvONS2_14PolicyDecisionEEEEEN3$_0clEN7WebCore12PolicyActionEPN3API15WebsitePoliciesENS2_28ProcessSwapRequestedByClientEONS_6RefPtrINS2_15BrowsingWarningENS6_ISU_EENS8_ISU_EEEENSt3__18optionalINS2_26NavigatingToAppBoundDomainEEENS2_24WasNavigationInterceptedEEUlOT_E_vJONSZ_7variantIJNS2_18ContinueUnsafeLoadENS_3URLEEEEEE4callES1B_ : 384 -> 388
~ __ZN3WTF6Detail15CallableWrapperIZN6WebKit12WebPageProxy13createNewPageERN3IPC10ConnectionEON7WebCore14WindowFeaturesEONS2_20NavigationActionDataEONS_17CompletionHandlerIFvNSt3__18optionalINS_23ObjectIdentifierGenericINS7_18PageIdentifierTypeENS_38ObjectIdentifierMainThreadAccessTraitsIyEEyEEEENSE_INS2_25WebPageCreationParametersEEEEEEE3$_0vJONS_6RefPtrIS3_NS_12RawPtrTraitsIS3_EENS_21DefaultRefDerefTraitsIS3_EEEEEE4callESX_ : 2260 -> 2268
~ _WKPageLoadURLWithShouldOpenExternalURLsPolicy : 360 -> 364
~ _WKPageLoadURLWithUserData : 372 -> 376
~ _WKPageLoadURLRequestWithUserData : 272 -> 276
~ __ZN6WebKit25RemoteWebInspectorUIProxy10initializeEON3WTF3RefIN3API14DebuggableInfoENS1_12RawPtrTraitsIS4_EENS1_21DefaultRefDerefTraitsIS4_EEEERKNS1_6StringE : 888 -> 892
~ __ZN6WebKit19WebInspectorUIProxy26openLocalInspectorFrontendEv : 1536 -> 1540
~ __ZN6WebKit20WebAutomationSession23navigateBrowsingContextERKN3WTF6StringES4_ONSt3__18optionalIN9Inspector8Protocol10Automation16PageLoadStrategyEEEONS6_IdEEONS1_3RefINS7_34AutomationBackendDispatcherHandler31NavigateBrowsingContextCallbackENS1_12RawPtrTraitsISH_EENS1_21DefaultRefDerefTraitsISH_EEEE : 492 -> 496
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10410: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10418: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10510: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10513: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10539: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10542: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10575: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10621: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10644: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10739: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10755: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10771: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10787: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10815: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10831: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 11887: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 12106: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 12326: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13099: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13965: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13974: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13983: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14053: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14124: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14125: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14139: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14140: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14157: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14158: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14166: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14183: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14184: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14213: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14216: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14261: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14262: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14276: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14277: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 15444: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 8916: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 8917: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 8924: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9198: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9490: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9495: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9534: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9546: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9547: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9627: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9667: Invalid message dispatched %{public}s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9894: Invalid message dispatched %{public}s"
+ "20621.3.11.11.3"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10408: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10416: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10508: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10511: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10537: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10540: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10573: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10619: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10640: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10737: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10753: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10769: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10785: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10813: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 10829: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 11885: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 12104: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 12324: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13097: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13961: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13970: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 13979: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14051: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14122: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14123: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14137: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14138: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14155: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14156: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14164: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14180: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14181: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14211: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14214: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14259: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14260: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14274: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 14275: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 15442: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 8913: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 8914: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 8922: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9196: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9488: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9493: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9532: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9544: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9545: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9625: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9665: Invalid message dispatched %{public}s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/WebKit/Source/WebKit/UIProcess/WebPageProxy.cpp 9892: Invalid message dispatched %{public}s"
- "20621.3.8"
```
