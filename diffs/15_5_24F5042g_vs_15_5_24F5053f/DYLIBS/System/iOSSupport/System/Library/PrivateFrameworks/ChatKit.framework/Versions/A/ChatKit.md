## ChatKit

> `/System/iOSSupport/System/Library/PrivateFrameworks/ChatKit.framework/Versions/A/ChatKit`

```diff

-1402.600.4.0.0
-  __TEXT.__text: 0x852b68
-  __TEXT.__auth_stubs: 0x8180
+1402.600.22.0.0
+  __TEXT.__text: 0x8551d0
+  __TEXT.__auth_stubs: 0x8190
   __TEXT.__delay_stubs: 0x58
-  __TEXT.__delay_helper: 0x16c
-  __TEXT.__objc_methlist: 0x6890c
-  __TEXT.__const: 0x19d24
-  __TEXT.__gcc_except_tab: 0x259a8
-  __TEXT.__cstring: 0x3ee49
-  __TEXT.__oslogstring: 0x3d30b
+  __TEXT.__delay_helper: 0x234
+  __TEXT.__objc_methlist: 0x68a04
+  __TEXT.__const: 0x19d94
+  __TEXT.__gcc_except_tab: 0x25b7c
+  __TEXT.__cstring: 0x3ee99
+  __TEXT.__oslogstring: 0x3d62b
   __TEXT.__dlopen_cstrs: 0x6d9
   __TEXT.__ustring: 0x17c
   __TEXT.__swift5_typeref: 0x21714

   __TEXT.__swift_as_ret: 0x160
   __TEXT.__swift5_protos: 0x7c
   __TEXT.__swift5_mpenum: 0x24
-  __TEXT.__unwind_info: 0x23958
+  __TEXT.__unwind_info: 0x239f8
   __TEXT.__eh_frame: 0x5170
   __TEXT.__objc_classname: 0xacec
-  __TEXT.__objc_methname: 0xf8339
-  __TEXT.__objc_methtype: 0x2196f
-  __TEXT.__objc_stubs: 0x9a820
-  __DATA_CONST.__got: 0x5d08
+  __TEXT.__objc_methname: 0xf89ac
+  __TEXT.__objc_methtype: 0x219bb
+  __TEXT.__objc_stubs: 0x9ad80
+  __DATA_CONST.__got: 0x5da0
   __DATA_CONST.__const: 0xd5c8
   __DATA_CONST.__objc_classlist: 0x26a0
   __DATA_CONST.__objc_catlist: 0x4e0
   __DATA_CONST.__objc_protolist: 0x1120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x32010
+  __DATA_CONST.__objc_selrefs: 0x32138
   __DATA_CONST.__objc_protorefs: 0x370
-  __DATA_CONST.__objc_superrefs: 0x1920
+  __DATA_CONST.__objc_superrefs: 0x1928
   __DATA_CONST.__objc_arraydata: 0xf68
-  __AUTH_CONST.__auth_got: 0x40e0
+  __AUTH_CONST.__auth_got: 0x40e8
   __AUTH_CONST.__const: 0x24480
-  __AUTH_CONST.__cfstring: 0x232c0
-  __AUTH_CONST.__objc_const: 0x89f48
+  __AUTH_CONST.__cfstring: 0x23300
+  __AUTH_CONST.__objc_const: 0x89ff8
   __AUTH_CONST.__objc_intobj: 0xf48
   __AUTH_CONST.__objc_arrayobj: 0xe40
   __AUTH_CONST.__objc_doubleobj: 0x8d0

   __AUTH_CONST.__objc_dictobj: 0x168
   __AUTH.__objc_data: 0x208a8
   __AUTH.__data: 0x91a0
-  __DATA.__objc_ivar: 0x4850
-  __DATA.__data: 0x16518
+  __DATA.__objc_ivar: 0x485c
+  __DATA.__data: 0x16528
   __DATA.__objc_stublist: 0x10
   __DATA.__bss: 0x1ef48
   __DATA.__common: 0x9f8

   - /System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices
   - /System/Library/PrivateFrameworks/AudioToolboxCore.framework/Versions/A/AudioToolboxCore
   - /System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit
+  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/Versions/A/BiomeLibrary
   - /System/Library/PrivateFrameworks/BiomeStreams.framework/Versions/A/BiomeStreams
   - /System/Library/PrivateFrameworks/CMPhoto.framework/Versions/A/CMPhoto
   - /System/Library/PrivateFrameworks/CloudDocs.framework/Versions/A/CloudDocs

   - /System/iOSSupport/System/Library/PrivateFrameworks/IMSharedUI.framework/Versions/A/IMSharedUI
   - /System/iOSSupport/System/Library/PrivateFrameworks/IMSharedUtilities.framework/Versions/A/IMSharedUtilities
   - /System/iOSSupport/System/Library/PrivateFrameworks/IMTranscoding.framework/Versions/A/IMTranscoding
+  - /System/iOSSupport/System/Library/PrivateFrameworks/ManagedConfiguration.framework/Versions/A/ManagedConfiguration
   - /System/iOSSupport/System/Library/PrivateFrameworks/MessagesSupport.framework/Versions/A/MessagesSupport
   - /System/iOSSupport/System/Library/PrivateFrameworks/OnBoardingKit.framework/Versions/A/OnBoardingKit
   - /System/iOSSupport/System/Library/PrivateFrameworks/PhotosPlayer.framework/Versions/A/PhotosPlayer

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 54154
-  Symbols:   83750
-  CStrings:  48953
+  Functions: 54177
+  Symbols:   83844
+  CStrings:  49019
 
Symbols:
+ +[CKApplicationState applicationDidResume:]
+ +[CKApplicationState applicationDidSuspend:]
+ -[CKBigEmojiBalloonView .cxx_destruct]
+ -[CKBigEmojiBalloonView initWithFrame:]
+ -[CKBigEmojiBalloonView insetMask]
+ -[CKBigEmojiBalloonView isScheduled]
+ -[CKBigEmojiBalloonView layoutSubviews]
+ -[CKBigEmojiBalloonView prepareForReuse]
+ -[CKBigEmojiBalloonView sendLaterMaskInsets]
+ -[CKBigEmojiBalloonView setInsetMask:]
+ -[CKBigEmojiBalloonView setScheduled:]
+ -[CKBigEmojiBalloonView(CKMessagePartChatItem) configureForMessagePart:]
+ -[CKSearchAnalytics _buildType:]
+ -[CKSearchAnalytics _dimensionContext]
+ -[CKSearchAnalytics _invalidateSessionIDIfNeeded]
+ -[CKSearchAnalytics _logEvent:]
+ -[CKSearchAnalytics _logSearchButtonInteractionWithVisualComponentType:mode:]
+ -[CKSearchAnalytics _sectionTypeForContentType:]
+ -[CKSearchAnalytics _seeAllPageTypeForContentType:]
+ -[CKSearchAnalytics _tokenTypeForSearchFilterContentType:]
+ -[CKSearchAnalytics eventStream]
+ -[CKSearchAnalytics logUserInputChanged:input:tokens:]
+ -[CKSearchViewController _logResultsDidChange]
+ OBJC_IVAR_$_CKBigEmojiBalloonView._insetMask
+ OBJC_IVAR_$_CKBigEmojiBalloonView._scheduled
+ OBJC_IVAR_$_CKSearchAnalytics._eventStream
+ _BiomeLibrary
+ _IMServiceCapabilityDisplayUnknownSenderLinks
+ _OBJC_CLASS_$_BMMessagesSearchEvent
+ _OBJC_CLASS_$_BMMessagesSearchEventDimensionContext
+ _OBJC_CLASS_$_BMMessagesSearchEventInputDetected
+ _OBJC_CLASS_$_BMMessagesSearchEventPageAttribute
+ _OBJC_CLASS_$_BMMessagesSearchEventResultAttribute
+ _OBJC_CLASS_$_BMMessagesSearchEventResultReceived
+ _OBJC_CLASS_$_BMMessagesSearchEventSearchViewAppeared
+ _OBJC_CLASS_$_BMMessagesSearchEventSearchViewContext
+ _OBJC_CLASS_$_BMMessagesSearchEventSearchViewDisappeared
+ _OBJC_CLASS_$_BMMessagesSearchEventSectionAttribute
+ _OBJC_CLASS_$_BMMessagesSearchEventSessionIdResetContext
+ _OBJC_CLASS_$_BMMessagesSearchEventSessionIdResetEnded
+ _OBJC_CLASS_$_BMMessagesSearchEventSessionIdResetStarted
+ _OBJC_CLASS_$_BMMessagesSearchEventToken
+ _OBJC_CLASS_$_BMMessagesSearchEventUserInteractionDetected
+ _OBJC_CLASS_$_BMMessagesSearchEventVisualComponent
+ _OBJC_CLASS_$_GEOCountryConfiguration
+ _OBJC_CLASS_$_MCProfileConnection
+ __OBJC_$_INSTANCE_METHODS_CKBigEmojiBalloonView(CKMessagePartChatItem)
+ __OBJC_$_INSTANCE_VARIABLES_CKBigEmojiBalloonView
+ __OBJC_$_PROP_LIST_CKBigEmojiBalloonView
+ ___31-[CKSearchAnalytics _logEvent:]_block_invoke
+ ___44-[CKSearchViewController _searchImmediately]_block_invoke
+ _dlopenHelper$GeoServices
+ _dlopenHelperFlag$GeoServices
+ _gotLoadHelper_x8$_OBJC_CLASS_$_GEOCountryConfiguration
+ _objc_msgSend$Event
+ _objc_msgSend$Messages
+ _objc_msgSend$Search
+ _objc_msgSend$_buildType:
+ _objc_msgSend$_dimensionContext
+ _objc_msgSend$_incrementQueryID
+ _objc_msgSend$_invalidateSessionIDIfNeeded
+ _objc_msgSend$_logEvent:
+ _objc_msgSend$_logResultsDidChange
+ _objc_msgSend$_logSearchButtonInteractionWithVisualComponentType:mode:
+ _objc_msgSend$_productType
+ _objc_msgSend$_sectionTypeForContentType:
+ _objc_msgSend$_seeAllPageTypeForContentType:
+ _objc_msgSend$_tokenTypeForSearchFilterContentType:
+ _objc_msgSend$eventStream
+ _objc_msgSend$initWithComponentType:resultAttribute:sectionAttribute:pageAttribute:
+ _objc_msgSend$initWithDimensionContext:inputDetected:userInteractionDetected:displayContext:searchViewContext:resultReceived:messagesAppViewContext:sessionIdResetContext:
+ _objc_msgSend$initWithIsInSearchView:
+ _objc_msgSend$initWithMillisecondsSinceSessionStarted:sessionId:queryId:appeared:disappeared:
+ _objc_msgSend$initWithMillisecondsSinceSessionStarted:sessionId:queryId:isZkw:token:
+ _objc_msgSend$initWithMillisecondsSinceSessionStarted:sessionId:queryId:noResultReceived:totalConversations:totalTokens:totalMessages:totalLinks:totalPhotos:totalLocation:totalAttachments:totalWallet:totalCollaboration:totalHighlights:
+ _objc_msgSend$initWithMillisecondsSinceSessionStarted:sessionId:queryId:started:ended:
+ _objc_msgSend$initWithMillisecondsSinceSessionStarted:sessionId:queryId:visualComponent:interactionType:
+ _objc_msgSend$initWithPageType:
+ _objc_msgSend$initWithResultPositionIndex:
+ _objc_msgSend$initWithSearchViewAppearedReason:
+ _objc_msgSend$initWithSearchViewDisappearedReason:
+ _objc_msgSend$initWithSectionType:
+ _objc_msgSend$initWithSessionStartTimestampInSeconds:sessionId:systemLocale:currentCountry:build:osType:productType:buildType:isLiveOn:
+ _objc_msgSend$initWithTokenType:wordCount:charCount:
+ _objc_msgSend$insetMask
+ _objc_msgSend$isDiagnosticSubmissionAllowed
+ _objc_msgSend$logUserInputChanged:input:tokens:
+ _objc_msgSend$millisecondsSinceSessionStarted
+ _objc_msgSend$previousPresentationReason
+ _objc_msgSend$queryIDString
+ _objc_msgSend$searchAnalyticsEnabled
+ _objc_msgSend$sendLaterMaskInsets
+ _objc_msgSend$sessionStartTimestampInSeconds
+ _objc_msgSend$setInsetMask:
+ _objc_msgSend$setPreviousPresentationReason:
+ _objc_msgSend$sharedConfiguration
+ _objc_msgSend$sharedConnection
- +[CKApplicationState applicationWillResume:]
- +[CKApplicationState applicationWillSuspend:]
- __OBJC_$_INSTANCE_METHODS_CKBigEmojiBalloonView
CStrings:
+ "/System/Library/PrivateFrameworks/GeoServices.framework/Versions/A/GeoServices"
+ "@\"BMStream\""
+ "Event"
+ "Invalidating sessionID"
+ "Logging disabled per D&U, clearing session state if present"
+ "Logging event: %@"
+ "Not incrementing queryID on input changed received, didInvalidate %@ or previous presentation was search %@"
+ "Not notifying imagent of successful preview generation, transfer GUID %@ preview is null %@"
+ "QueryID not persisted, invalidating"
+ "Request to log dismissal with reason %lu"
+ "Request to log presentation with reason %lu"
+ "Request to log results received"
+ "Request to log search button interaction"
+ "Request to log search result interaction"
+ "Request to log show all interaction"
+ "Request to log user input changed"
+ "Request to log user input ignored, current mode is Show All!"
+ "SessionID TTL not persisted, invalidating"
+ "SessionID TTL rolled, invalidating"
+ "SessionID not persisted, invalidating"
+ "T@\"BMStream\",R,N,V_eventStream"
+ "T@\"CKBalloonImageView\",&,N,V_insetMask"
+ "_buildType:"
+ "_dimensionContext"
+ "_eventStream"
+ "_insetMask"
+ "_invalidateSessionIDIfNeeded"
+ "_logEvent:"
+ "_logResultsDidChange"
+ "_logSearchButtonInteractionWithVisualComponentType:mode:"
+ "_sectionTypeForContentType:"
+ "_seeAllPageTypeForContentType:"
+ "_tokenTypeForSearchFilterContentType:"
+ "applicationDidResume:"
+ "applicationDidSuspend:"
+ "eventStream"
+ "i20@0:8B16"
+ "i24@0:8Q16"
+ "i24@0:8q16"
+ "iOS"
+ "initWithComponentType:resultAttribute:sectionAttribute:pageAttribute:"
+ "initWithDimensionContext:inputDetected:userInteractionDetected:displayContext:searchViewContext:resultReceived:messagesAppViewContext:sessionIdResetContext:"
+ "initWithIsInSearchView:"
+ "initWithMillisecondsSinceSessionStarted:sessionId:queryId:appeared:disappeared:"
+ "initWithMillisecondsSinceSessionStarted:sessionId:queryId:isZkw:token:"
+ "initWithMillisecondsSinceSessionStarted:sessionId:queryId:noResultReceived:totalConversations:totalTokens:totalMessages:totalLinks:totalPhotos:totalLocation:totalAttachments:totalWallet:totalCollaboration:totalHighlights:"
+ "initWithMillisecondsSinceSessionStarted:sessionId:queryId:started:ended:"
+ "initWithMillisecondsSinceSessionStarted:sessionId:queryId:visualComponent:interactionType:"
+ "initWithPageType:"
+ "initWithResultPositionIndex:"
+ "initWithSearchViewAppearedReason:"
+ "initWithSearchViewDisappearedReason:"
+ "initWithSectionType:"
+ "initWithSessionStartTimestampInSeconds:sessionId:systemLocale:currentCountry:build:osType:productType:buildType:isLiveOn:"
+ "initWithTokenType:wordCount:charCount:"
+ "insetMask"
+ "isDiagnosticSubmissionAllowed"
+ "logUserInputChanged:input:tokens:"
+ "macOS"
+ "sendLaterMaskInsets"
+ "session is valid"
+ "setInsetMask:"
+ "sharedConfiguration"
+ "sharedConnection"
+ "v28@0:8i16Q20"
+ "v40@0:8Q16@24@32"
```
