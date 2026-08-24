## AppKit

> `/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit`

```diff

-2575.60.3.1.0
-  __TEXT.__text: 0xef006c
+2575.60.5.0.0
+  __TEXT.__text: 0xef0244
   __TEXT.__auth_stubs: 0xfd80
-  __TEXT.__objc_methlist: 0xcab50
+  __TEXT.__objc_methlist: 0xcab60
   __TEXT.__const: 0x1d388
   __TEXT.__dlopen_cstrs: 0xe9d
   __TEXT.__cstring: 0xc3947

   __TEXT.__swift5_builtin: 0x5c8
   __TEXT.__swift5_capture: 0x1f10
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__oslogstring: 0x1a5f3
+  __TEXT.__oslogstring: 0x1a614
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift_as_entry: 0xd4
   __TEXT.__swift_as_ret: 0xa4
-  __TEXT.__gcc_except_tab: 0xa5678
+  __TEXT.__gcc_except_tab: 0xa56cc
   __TEXT.__ustring: 0x15ea
   __TEXT.__dof_NSTrackin: 0x7e7
   __TEXT.__dof_NSApplica: 0x809
   __TEXT.__dof_NSAccessi: 0x1eb
-  __TEXT.__unwind_info: 0x536d8
+  __TEXT.__unwind_info: 0x536e0
   __TEXT.__eh_frame: 0x5b18
   __TEXT.__objc_classname: 0x15673
-  __TEXT.__objc_methname: 0x153d7c
+  __TEXT.__objc_methname: 0x153da3
   __TEXT.__objc_methtype: 0x3f096
-  __TEXT.__objc_stubs: 0xfbbe0
+  __TEXT.__objc_stubs: 0xfbc00
   __DATA_CONST.__got: 0x4f10
   __DATA_CONST.__const: 0xa1a0
   __DATA_CONST.__objc_classlist: 0x4798

   __DATA_CONST.__objc_catlist: 0x1e0
   __DATA_CONST.__objc_protolist: 0xf90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4cb00
+  __DATA_CONST.__objc_selrefs: 0x4cb08
   __DATA_CONST.__objc_protorefs: 0x558
   __DATA_CONST.__objc_superrefs: 0x3cd0
   __DATA_CONST.__objc_arraydata: 0x4050

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 87306
-  Symbols:   147617
-  CStrings:  83059
+  Functions: 87307
+  Symbols:   147619
+  CStrings:  83061
 
Symbols:
+ -[NSCocoaMenuImpl notifySuperOfSubmenuDismissalIfNeeded:]
+ _objc_msgSend$notifySuperOfSubmenuDismissalIfNeeded:
Functions:
~ -[NSCocoaMenuImpl dismissAnimated:completion:] : 228 -> 232
~ -[NSCocoaMenuImpl _dismissCoalescingSubmenus:animated:] : 1128 -> 1032
+ -[NSCocoaMenuImpl notifySuperOfSubmenuDismissalIfNeeded:]
~ -[NSCorrectionPanel _handleEvent:] : 1476 -> 1488
~ -[NSMenuBarWindowManager windowOnDisplay:creatingIfNeeded:withImpl:] : 356 -> 560
~ ___56-[NSMenuBarPresentationInstance _appendMenuBarSettings:]_block_invoke : 708 -> 720
CStrings:
+ "Submenu %p was already dismissed"
+ "notifySuperOfSubmenuDismissalIfNeeded:"
```
