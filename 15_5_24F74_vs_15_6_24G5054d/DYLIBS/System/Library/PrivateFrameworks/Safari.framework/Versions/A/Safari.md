## Safari

> `/System/Library/PrivateFrameworks/Safari.framework/Versions/A/Safari`

```diff

-621.2.5.11.8
-  __TEXT.__text: 0x6e8460
-  __TEXT.__auth_stubs: 0x5860
-  __TEXT.__objc_methlist: 0x54a44
-  __TEXT.__gcc_except_tab: 0xc6500
-  __TEXT.__const: 0x5b84
+621.3.6.1.0
+  __TEXT.__text: 0x6e9258
+  __TEXT.__auth_stubs: 0x5850
+  __TEXT.__objc_methlist: 0x54af4
+  __TEXT.__gcc_except_tab: 0xc66d8
+  __TEXT.__const: 0x5c54
   __TEXT.__ustring: 0x10dbe
-  __TEXT.__cstring: 0x49c75
-  __TEXT.__oslogstring: 0x1eccb
+  __TEXT.__cstring: 0x49ca5
+  __TEXT.__oslogstring: 0x1ed2b
   __TEXT.__dlopen_cstrs: 0x468
   __TEXT.__constg_swiftt: 0x684
   __TEXT.__swift5_typeref: 0x3a6e

   __TEXT.__swift5_capture: 0x344
   __TEXT.__swift_as_entry: 0x2c
   __TEXT.__swift_as_ret: 0x20
-  __TEXT.__unwind_info: 0x38538
+  __TEXT.__unwind_info: 0x38588
   __TEXT.__eh_frame: 0xc50
-  __TEXT.__objc_classname: 0xb58a
-  __TEXT.__objc_methname: 0xfaef3
-  __TEXT.__objc_methtype: 0x22535
-  __TEXT.__objc_stubs: 0x96160
+  __TEXT.__objc_classname: 0xb5bc
+  __TEXT.__objc_methname: 0xfb2ba
+  __TEXT.__objc_methtype: 0x225ee
+  __TEXT.__objc_stubs: 0x962e0
   __DATA_CONST.__got: 0x3a68
   __DATA_CONST.__const: 0x4320
   __DATA_CONST.__objc_classlist: 0x1fa0
   __DATA_CONST.__objc_catlist: 0x300
   __DATA_CONST.__objc_nlcatlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x1090
+  __DATA_CONST.__objc_protolist: 0x1098
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2f6a0
+  __DATA_CONST.__objc_selrefs: 0x2f718
   __DATA_CONST.__objc_protorefs: 0x200
   __DATA_CONST.__objc_superrefs: 0x1828
   __DATA_CONST.__objc_arraydata: 0xad8
-  __AUTH_CONST.__auth_got: 0x2c48
+  __AUTH_CONST.__auth_got: 0x2c40
   __AUTH_CONST.__const: 0x1a680
   __AUTH_CONST.__cfstring: 0x33fa0
-  __AUTH_CONST.__objc_const: 0x7bca8
+  __AUTH_CONST.__objc_const: 0x7be30
   __AUTH_CONST.__objc_intobj: 0x1200
   __AUTH_CONST.__objc_dictobj: 0x5a0
   __AUTH_CONST.__objc_arrayobj: 0x4e0

   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH.__objc_data: 0xedb8
   __AUTH.__data: 0xa70
-  __DATA.__objc_ivar: 0x5ebc
-  __DATA.__data: 0xd2b8
+  __DATA.__objc_ivar: 0x5ed8
+  __DATA.__data: 0xd258
   __DATA.__bss: 0x2e50
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x4f60

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 35373
-  Symbols:   77307
-  CStrings:  47136
+  Functions: 35386
+  Symbols:   77342
+  CStrings:  47166
 
Symbols:
+ -[BrowserContainerViewController installTabDialogView:andDimmingView:placement:tabDialogViewController:completionHandler:]
+ -[BrowserContainerViewController transplantTabDialogView:andDimmingView:placement:tabDialogViewController:]
+ -[DeveloperPreferences _webDriverSecurePreferencesDidUpdate:]
+ -[DownloadProgressEntry initWithWKDownload:navigatedWebView:suggestedFilename:mayOpenWhenDone:shouldAvoidPersistingIdentifyingInformation:profileIdentifier:]
+ -[DownloadProgressEntry navigatedWebView]
+ -[DownloadsManager pendingDownloadNavigatedWebViewForOriginatingWebView:]
+ -[DownloadsManager setPendingDownloadNavigatedWebView:forOriginatingWebView:]
+ -[SearchProvidersController userVisibleQueryFromSearchURL:allowQueryThatLooksLikeURL:]
+ -[TabDialogInstaller _commonDialogLayoutConstraintsUsingOffset:]
+ -[TabDialogInstaller _dialogPlacementConstraintsForPlacement:verticalOffset:additionalOffsetToAvoidClickJacking:]
+ -[TabDialogInstaller installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:tabDialogViewController:completionHandler:]
+ -[TabDialogInstaller tabDialogViewControllerDidShowDialog:]
+ -[TabDialogInstaller updateLayoutConstraintsIfNeeded]
+ -[TabDialogViewController presentationDelegate]
+ -[TabDialogViewController setPresentationDelegate:]
+ -[TabDialogViewController viewDidLayout]
+ -[UnifiedField usesActiveAppearance]
+ GCC_except_table392
+ OBJC_IVAR_$_DownloadProgressEntry._navigatedWebView
+ OBJC_IVAR_$_DownloadsManager._pendingDownloadOriginatingWebViewsToNavigatedWebViews
+ OBJC_IVAR_$_TabDialogInstaller._dialogPlacementConstraints
+ OBJC_IVAR_$_TabDialogInstaller._tabDialogVerticalPlacement
+ OBJC_IVAR_$_TabDialogInstaller._tabDialogViewController
+ OBJC_IVAR_$_TabDialogInstaller._verticalOffset
+ OBJC_IVAR_$_TabDialogViewController._presentationDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TabDialogViewControllerPresentationDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TabDialogViewControllerPresentationDelegate
+ __OBJC_$_PROTOCOL_REFS_TabDialogViewControllerPresentationDelegate
+ __OBJC_CLASS_PROTOCOLS_$_TabDialogInstaller
+ __OBJC_LABEL_PROTOCOL_$_TabDialogViewControllerPresentationDelegate
+ __OBJC_PROTOCOL_$_TabDialogViewControllerPresentationDelegate
+ ___122-[BrowserContainerViewController installTabDialogView:andDimmingView:placement:tabDialogViewController:completionHandler:]_block_invoke
+ ___149-[TabDialogInstaller installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:tabDialogViewController:completionHandler:]_block_invoke
+ _objc_msgSend$_commonDialogLayoutConstraintsUsingOffset:
+ _objc_msgSend$_dialogPlacementConstraintsForPlacement:verticalOffset:additionalOffsetToAvoidClickJacking:
+ _objc_msgSend$_isContentExtensionRedirect
+ _objc_msgSend$_navigationInitiatingFrame
+ _objc_msgSend$disableSafariNavIntent
+ _objc_msgSend$initWithEffectiveBundleIdentifier:delegate:onQueue:
+ _objc_msgSend$initWithUser:password:site:creationDate:customTitle:groupName:requestedHost:
+ _objc_msgSend$initWithWKDownload:navigatedWebView:suggestedFilename:mayOpenWhenDone:shouldAvoidPersistingIdentifyingInformation:profileIdentifier:
+ _objc_msgSend$installTabDialogView:andDimmingView:placement:tabDialogViewController:completionHandler:
+ _objc_msgSend$installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:tabDialogViewController:completionHandler:
+ _objc_msgSend$lastMouseClickPosition
+ _objc_msgSend$navigatedWebView
+ _objc_msgSend$setPendingDownloadNavigatedWebView:forOriginatingWebView:
+ _objc_msgSend$setPresentationDelegate:
+ _objc_msgSend$tabDialogViewControllerDidShowDialog:
+ _objc_msgSend$transplantTabDialogView:andDimmingView:placement:tabDialogViewController:
+ _objc_msgSend$updateLayoutConstraintsIfNeeded
+ _objc_msgSend$userVisibleQueryFromSearchURL:allowQueryThatLooksLikeURL:
+ _objc_msgSend$usesActiveAppearance
- -[BrowserContainerViewController installTabDialogView:andDimmingView:placement:completionHandler:]
- -[BrowserContainerViewController transplantTabDialogView:andDimmingView:placement:]
- -[DownloadProgressEntry initWithWKDownload:suggestedFilename:mayOpenWhenDone:shouldAvoidPersistingIdentifyingInformation:profileIdentifier:]
- -[TabDialogInstaller installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:completionHandler:]
- GCC_except_table329
- GCC_except_table367
- GCC_except_table404
- _CTParagraphStyleGetCompositionLanguageForLanguage
- ___125-[TabDialogInstaller installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:completionHandler:]_block_invoke
- ___98-[BrowserContainerViewController installTabDialogView:andDimmingView:placement:completionHandler:]_block_invoke
- _objc_msgSend$initWithEffectiveBundlePath:delegate:onQueue:
- _objc_msgSend$initWithUser:password:site:creationDate:customTitle:groupName:
- _objc_msgSend$initWithWKDownload:suggestedFilename:mayOpenWhenDone:shouldAvoidPersistingIdentifyingInformation:profileIdentifier:
- _objc_msgSend$installTabDialogView:andDimmingView:placement:completionHandler:
- _objc_msgSend$installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:completionHandler:
- _objc_msgSend$tabTitle
- _objc_msgSend$transplantTabDialogView:andDimmingView:placement:
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.6.Internal.sdk/usr/local/include/wtf/HashTable.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.6.Internal.sdk/usr/local/include/wtf/RefCounted.h"
+ "@\"<TabDialogViewControllerPresentationDelegate>\""
+ "@40@0:8q16d24d32"
+ "Got notification that WebDriver preferences changed, updating Allow Remote Automation checkbox."
+ "T@\"<TabDialogViewControllerPresentationDelegate>\",W,N,V_presentationDelegate"
+ "T@\"WKWebView\",R,W,N,V_navigatedWebView"
+ "TabDialogViewControllerPresentationDelegate"
+ "_commonDialogLayoutConstraintsUsingOffset:"
+ "_dialogPlacementConstraints"
+ "_dialogPlacementConstraintsForPlacement:verticalOffset:additionalOffsetToAvoidClickJacking:"
+ "_isContentExtensionRedirect"
+ "_navigatedWebView"
+ "_navigationInitiatingFrame"
+ "_pendingDownloadOriginatingWebViewsToNavigatedWebViews"
+ "_presentationDelegate"
+ "_tabDialogVerticalPlacement"
+ "_verticalOffset"
+ "_webDriverSecurePreferencesDidUpdate:"
+ "disableSafariNavIntent"
+ "initWithEffectiveBundleIdentifier:delegate:onQueue:"
+ "initWithUser:password:site:creationDate:customTitle:groupName:requestedHost:"
+ "initWithWKDownload:navigatedWebView:suggestedFilename:mayOpenWhenDone:shouldAvoidPersistingIdentifyingInformation:profileIdentifier:"
+ "installTabDialogView:andDimmingView:placement:tabDialogViewController:completionHandler:"
+ "installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:tabDialogViewController:completionHandler:"
+ "navigatedWebView"
+ "pendingDownloadNavigatedWebViewForOriginatingWebView:"
+ "presentationDelegate"
+ "setPendingDownloadNavigatedWebView:forOriginatingWebView:"
+ "setPresentationDelegate:"
+ "tabDialogViewControllerDidShowDialog:"
+ "transplantTabDialogView:andDimmingView:placement:tabDialogViewController:"
+ "updateLayoutConstraintsIfNeeded"
+ "userVisibleQueryFromSearchURL:allowQueryThatLooksLikeURL:"
+ "usesActiveAppearance"
+ "v24@0:8@\"TabDialogViewController\"16"
+ "v48@0:8@\"NSView<TabDialogView>\"16@\"DimmingView\"24q32@\"TabDialogViewController\"40"
+ "v56@0:8@\"NSView<TabDialogView>\"16@\"DimmingView\"24q32@\"TabDialogViewController\"40@?<v@?>48"
+ "v56@0:8@16@24q32@40@?48"
+ "v72@0:8@16@24q32d40@?48@56@?64"
+ "\xf0\x81"
+ "\xf0\xc1a"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.5.Internal.sdk/usr/local/include/wtf/HashTable.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.5.Internal.sdk/usr/local/include/wtf/RefCounted.h"
- "initWithEffectiveBundlePath:delegate:onQueue:"
- "initWithUser:password:site:creationDate:customTitle:groupName:"
- "initWithWKDownload:suggestedFilename:mayOpenWhenDone:shouldAvoidPersistingIdentifyingInformation:profileIdentifier:"
- "installTabDialogView:andDimmingView:placement:completionHandler:"
- "installTabDialogView:andDimmingView:placement:verticalOffset:preInstallationCallback:completionHandler:"
- "transplantTabDialogView:andDimmingView:placement:"
- "v40@0:8@\"NSView<TabDialogView>\"16@\"DimmingView\"24q32"
- "v48@0:8@\"NSView<TabDialogView>\"16@\"DimmingView\"24q32@?<v@?>40"
- "v64@0:8@16@24q32d40@?48@?56"
- "\xf0q"
```
