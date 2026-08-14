## UIKitCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/UIKitCore.framework/Versions/A/UIKitCore`

```diff

-8502.0.0.0.0
-  __TEXT.__text: 0x14fb2cc
+8504.0.0.0.0
+  __TEXT.__text: 0x14fbad4
   __TEXT.__auth_stubs: 0x99f0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x172b18
+  __TEXT.__objc_methlist: 0x172b48
   __TEXT.__const: 0x1f4e0
   __TEXT.__dlopen_cstrs: 0x21e1
-  __TEXT.__cstring: 0xcd5a7
+  __TEXT.__cstring: 0xcd5e1
   __TEXT.__swift5_typeref: 0x9dee
   __TEXT.__swift5_capture: 0x65cc
   __TEXT.__swift5_reflstr: 0x60a7

   __TEXT.__swift5_protos: 0x134
   __TEXT.__swift5_proto: 0xfcc
   __TEXT.__swift5_types: 0xa50
-  __TEXT.__oslogstring: 0x3d63e
+  __TEXT.__oslogstring: 0x3d671
   __TEXT.__swift_as_entry: 0x160
   __TEXT.__swift_as_ret: 0x11c
   __TEXT.__swift5_mpenum: 0xd0
-  __TEXT.__gcc_except_tab: 0x202d8
+  __TEXT.__gcc_except_tab: 0x202ec
   __TEXT.__ustring: 0x226e
-  __TEXT.__unwind_info: 0x57fd8
-  __TEXT.__eh_frame: 0x530c
+  __TEXT.__unwind_info: 0x58008
+  __TEXT.__eh_frame: 0x5304
   __TEXT.__objc_classname: 0x2cff7
-  __TEXT.__objc_methname: 0x2deb2b
-  __TEXT.__objc_methtype: 0x6cdc1
-  __TEXT.__objc_stubs: 0x1c72c0
+  __TEXT.__objc_methname: 0x2ded04
+  __TEXT.__objc_methtype: 0x6cdd6
+  __TEXT.__objc_stubs: 0x1c7360
   __DATA_CONST.__got: 0x6210
-  __DATA_CONST.__const: 0x342e8
+  __DATA_CONST.__const: 0x34310
   __DATA_CONST.__objc_classlist: 0x92f0
   __DATA_CONST.__objc_nlclslist: 0x8
   __DATA_CONST.__objc_catlist: 0x328
   __DATA_CONST.__objc_protolist: 0x2938
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8aa08
+  __DATA_CONST.__objc_selrefs: 0x8aa30
   __DATA_CONST.__objc_protorefs: 0x830
   __DATA_CONST.__objc_superrefs: 0x6880
   __DATA_CONST.__objc_arraydata: 0x3718
   __AUTH_CONST.__auth_got: 0x4d10
   __AUTH_CONST.__const: 0x337d0
-  __AUTH_CONST.__cfstring: 0x9cdc0
-  __AUTH_CONST.__objc_const: 0x212bf8
+  __AUTH_CONST.__cfstring: 0x9cde0
+  __AUTH_CONST.__objc_const: 0x212c28
   __AUTH_CONST.__objc_arrayobj: 0x26e8
   __AUTH_CONST.__objc_doubleobj: 0xe00
   __AUTH_CONST.__objc_intobj: 0x44e8
   __AUTH_CONST.__objc_dictobj: 0x5f0
   __AUTH.__objc_data: 0x4f2d8
   __AUTH.__data: 0x54b8
-  __DATA.__objc_ivar: 0xedb4
+  __DATA.__objc_ivar: 0xedb8
   __DATA.__uikit_ip: 0xa58
   __DATA.__data: 0x255b8
   __DATA.__uikit_ipl: 0x10

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 145134
-  Symbols:   255584
-  CStrings:  141409
+  Functions: 145140
+  Symbols:   255597
+  CStrings:  141418
 
Symbols:
+ -[UIWritingToolsCoordinator _fetchPreviewAndSendPrepareForInsertionWithSubrangeIndex:maximumSubrangeIndex:contextID:completion:]
+ -[UIWritingToolsCoordinator _hasStoredTargetedPreviewForInsertionInContextID:previewSubrangeIndex:]
+ -[UIWritingToolsCoordinator _sendFinishRemoveAnimationForNextSubrangeIndex:maximumSubrangeIndex:contextID:completion:]
+ -[_UIContainerWindowPortalInteraction setShouldAdjustZPositionToMatchAncestorViewContainer:]
+ -[_UIContainerWindowPortalInteraction shouldAdjustZPositionToMatchAncestorViewContainer]
+ GCC_except_table159
+ OBJC_IVAR_$__UIContainerWindowPortalInteraction._shouldAdjustZPositionToMatchAncestorViewContainer
+ ___118-[UIWritingToolsCoordinator _sendFinishRemoveAnimationForNextSubrangeIndex:maximumSubrangeIndex:contextID:completion:]_block_invoke
+ ___128-[UIWritingToolsCoordinator _fetchPreviewAndSendPrepareForInsertionWithSubrangeIndex:maximumSubrangeIndex:contextID:completion:]_block_invoke
+ ___128-[UIWritingToolsCoordinator _fetchPreviewAndSendPrepareForInsertionWithSubrangeIndex:maximumSubrangeIndex:contextID:completion:]_block_invoke_2
+ ___block_descriptor_137_e8_32s40s48s56s64s72s80s88bs96w_e28_v16?0"NSAttributedString"8lw96l8s32l8s40l8s48l8s56l8s64l8s72l8s88l8s80l8
+ ___block_descriptor_72_e8_32s40bs48w_e5_v8?0lw48l8s40l8s32l8
+ ___block_descriptor_72_e8_32s40bs48w_e8_v12?0B8lw48l8s40l8s32l8
+ _objc_msgSend$_fetchPreviewAndSendPrepareForInsertionWithSubrangeIndex:maximumSubrangeIndex:contextID:completion:
+ _objc_msgSend$_sendDelegatePrepareForTextAnimation:subrangeIndex:contextID:completion:
+ _objc_msgSend$_sendDelegateTargetedPreviewOfActiveRangeForTextAnimation:previewSubrangeIndex:contextID:completion:
+ _objc_msgSend$_sendFinishRemoveAnimationForNextSubrangeIndex:maximumSubrangeIndex:contextID:completion:
+ _objc_msgSend$setShouldAdjustZPositionToMatchAncestorViewContainer:
- -[UIKeyboardImpl resetSmartReplyFeedbackUIIfAlreadyShown]
- GCC_except_table161
- ___143-[UIWritingToolsCoordinator _updateTextViewAndTrackerWithIncomingCompositionSessionState:forDelivery:animationParameters:contextID:completion:]_block_invoke_3
- ___block_descriptor_138_e8_32s40s48s56s64s72s80s88bs96w_e28_v16?0"NSAttributedString"8lw96l8s32l8s40l8s48l8s56l8s64l8s72l8s88l8s80l8
- ___block_descriptor_97_e8_32s40s48s56s64bs72w_e17_v16?0"NSArray"8lw72l8s32l8s40l8s48l8s64l8s56l8
CStrings:
+ "%@ - Sending delegate finish for %@ with range={%lu, %lu}"
+ "%@ - Sending delegate prepare for %@ with range={%lu, %lu}"
+ "%@ - Sending delegate preview request for %@ with range={%lu, %lu}"
+ "%@ - Sending delegate replaceRange {%lu, %lu} with text of length %lu. Animating? %@"
+ "TB,N,V_shouldAdjustZPositionToMatchAncestorViewContainer"
+ "_fetchPreviewAndSendPrepareForInsertionWithSubrangeIndex:maximumSubrangeIndex:contextID:completion:"
+ "_hasStoredTargetedPreviewForInsertionInContextID:previewSubrangeIndex:"
+ "_sendFinishRemoveAnimationForNextSubrangeIndex:maximumSubrangeIndex:contextID:completion:"
+ "_shouldAdjustZPositionToMatchAncestorViewContainer"
+ "predictionBarDebounceTimeIntervalExpired with marked text"
+ "resetOnKeyboardCandidatesCleared ignored; long form = %d"
+ "setShouldAdjustZPositionToMatchAncestorViewContainer:"
+ "shouldAdjustZPositionToMatchAncestorViewContainer"
+ "v48@0:8Q16Q24@32@?40"
- "Sending delegate finish for %@ with range={%lu, %lu}"
- "Sending delegate prepare for %@ with range={%lu, %lu}"
- "Sending delegate preview request for %@ with range={%lu, %lu}"
- "Sending delegate replaceRange {%lu, %lu} with text of length %lu"
- "resetOnKeyboardCandidatesCleared ignored"
```
