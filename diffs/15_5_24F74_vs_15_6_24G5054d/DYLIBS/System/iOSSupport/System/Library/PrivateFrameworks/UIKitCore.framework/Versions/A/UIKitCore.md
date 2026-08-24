## UIKitCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/UIKitCore.framework/Versions/A/UIKitCore`

```diff

-8506.0.0.0.0
-  __TEXT.__text: 0x14fbc80
+8603.0.0.0.0
+  __TEXT.__text: 0x14fc1ec
   __TEXT.__auth_stubs: 0x99f0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x172b48
-  __TEXT.__const: 0x1f4e0
+  __TEXT.__const: 0x1fa40
   __TEXT.__dlopen_cstrs: 0x21e1
-  __TEXT.__cstring: 0xcd5b6
+  __TEXT.__cstring: 0xcd5f4
   __TEXT.__swift5_typeref: 0x9dee
   __TEXT.__swift5_capture: 0x65cc
   __TEXT.__swift5_reflstr: 0x60a7

   __TEXT.__swift5_protos: 0x134
   __TEXT.__swift5_proto: 0xfcc
   __TEXT.__swift5_types: 0xa50
-  __TEXT.__oslogstring: 0x3d629
+  __TEXT.__oslogstring: 0x3d6a0
   __TEXT.__swift_as_entry: 0x160
   __TEXT.__swift_as_ret: 0x11c
   __TEXT.__swift5_mpenum: 0xd0
   __TEXT.__gcc_except_tab: 0x202ec
   __TEXT.__ustring: 0x226e
-  __TEXT.__unwind_info: 0x58008
-  __TEXT.__eh_frame: 0x5304
+  __TEXT.__unwind_info: 0x58010
+  __TEXT.__eh_frame: 0x532c
   __TEXT.__objc_classname: 0x2cff7
   __TEXT.__objc_methname: 0x2ded04
   __TEXT.__objc_methtype: 0x6cdbf

   __DATA_CONST.__objc_selrefs: 0x8aa30
   __DATA_CONST.__objc_protorefs: 0x830
   __DATA_CONST.__objc_superrefs: 0x6880
-  __DATA_CONST.__objc_arraydata: 0x36f0
+  __DATA_CONST.__objc_arraydata: 0x3718
   __AUTH_CONST.__auth_got: 0x4d10
   __AUTH_CONST.__const: 0x337f0
-  __AUTH_CONST.__cfstring: 0x9cd80
+  __AUTH_CONST.__cfstring: 0x9cde0
   __AUTH_CONST.__objc_const: 0x212c28
-  __AUTH_CONST.__objc_arrayobj: 0x26d0
+  __AUTH_CONST.__objc_arrayobj: 0x26e8
   __AUTH_CONST.__objc_doubleobj: 0xe00
   __AUTH_CONST.__objc_intobj: 0x44e8
   __AUTH_CONST.__objc_dictobj: 0x5f0
   __AUTH.__objc_data: 0x4f2d8
-  __AUTH.__data: 0x54b8
+  __AUTH.__data: 0x54a8
   __DATA.__objc_ivar: 0xed68
   __DATA.__uikit_ip: 0xa58
-  __DATA.__data: 0x255b8
+  __DATA.__data: 0x25098
   __DATA.__uikit_ipl: 0x10
   __DATA.__bss: 0x21af0
   __DATA.__common: 0xf30

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 145142
-  Symbols:   255600
-  CStrings:  141419
+  Functions: 145143
+  Symbols:   255601
+  CStrings:  141422
 
Symbols:
+ _verifyClient.didReport
Functions:
+ sub_1b44d958c
- sub_1b43a5708
- sub_1b4407368
+ sub_1b453c06c
- sub_1b4408510
+ sub_1b45da234
+ sub_1b46b3644
~ -[UIAlertControllerStackManager _hideStackedAlertControllers] : 436 -> 540
~ -[UIAlertControllerStackManager _showHiddenStackedAlertControllers] : 544 -> 780
~ -[UIAlertControllerStackManager _addAlertControllerToStack:] : 208 -> 316
~ -[UIAlertControllerStackManager _removeAlertControllerFromStack:] : 208 -> 316
~ -[UIAlertControllerStackManager _willShowAlertController:] : 204 -> 320
~ -[UIAlertControllerStackManager _didHideAlertController:] : 204 -> 320
~ +[UIKeyboardViewController _verifyClient] : 4 -> 352
~ -[UIPointerLockState _preferredPointerLockStatusUpdated] : 612 -> 708
~ +[_UISmartReplyFeedbackManager showReportConcernUI] : 80 -> 8
~ -[UIKBAutofillController showASPInTextField:isRightToLeft:] : 728 -> 768
~ -[UIKeyboardEmojiAndStickerCollectionView touchesBegan:withEvent:] : 576 -> 584
CStrings:
+ "Unknown UIKeyboardViewController client (bundleID=%@)"
+ "Verify UIKeyboardViewController client (bundleID=%@, isKnown=%s)"
+ "com.apple.ContactsUI.MonogramPosterExtension"
+ "com.apple.QuickboardViewService"
- "FeedbackFCSBehavior"
```
