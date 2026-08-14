## AppKit

> `/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-2575.60.2.0.0
-  __TEXT.__text: 0xeefb84
+2575.60.3.1.0
+  __TEXT.__text: 0xef006c
   __TEXT.__auth_stubs: 0xfd80
-  __TEXT.__objc_methlist: 0xcab38
+  __TEXT.__objc_methlist: 0xcab50
   __TEXT.__const: 0x1d388
   __TEXT.__dlopen_cstrs: 0xe9d
   __TEXT.__cstring: 0xc3947

   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift_as_entry: 0xd4
   __TEXT.__swift_as_ret: 0xa4
-  __TEXT.__gcc_except_tab: 0xa565c
+  __TEXT.__gcc_except_tab: 0xa5678
   __TEXT.__ustring: 0x15ea
   __TEXT.__dof_NSTrackin: 0x7e7
   __TEXT.__dof_NSApplica: 0x809
   __TEXT.__dof_NSAccessi: 0x1eb
-  __TEXT.__unwind_info: 0x536b8
+  __TEXT.__unwind_info: 0x536d8
   __TEXT.__eh_frame: 0x5b18
   __TEXT.__objc_classname: 0x15673
-  __TEXT.__objc_methname: 0x153d31
+  __TEXT.__objc_methname: 0x153d7c
   __TEXT.__objc_methtype: 0x3f096
-  __TEXT.__objc_stubs: 0xfbba0
+  __TEXT.__objc_stubs: 0xfbbe0
   __DATA_CONST.__got: 0x4f10
   __DATA_CONST.__const: 0xa1a0
   __DATA_CONST.__objc_classlist: 0x4798

   __DATA_CONST.__objc_catlist: 0x1e0
   __DATA_CONST.__objc_protolist: 0xf90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4caf0
+  __DATA_CONST.__objc_selrefs: 0x4cb00
   __DATA_CONST.__objc_protorefs: 0x558
   __DATA_CONST.__objc_superrefs: 0x3cd0
   __DATA_CONST.__objc_arraydata: 0x4050
   __AUTH_CONST.__auth_got: 0x7ed8
-  __AUTH_CONST.__const: 0x360a0
+  __AUTH_CONST.__const: 0x360c0
   __AUTH_CONST.__cfstring: 0x976c0
   __AUTH_CONST.__objc_const: 0xf2f60
   __AUTH_CONST.__objc_intobj: 0x2d00

   __DATA_DIRTY.__objc_data: 0x22970
   __DATA_DIRTY.__data: 0xab8
   __DATA_DIRTY.__common: 0x1e0
-  __DATA_DIRTY.__bss: 0x4c30
+  __DATA_DIRTY.__bss: 0x4c40
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accessibility.framework/Versions/A/Accessibility
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 87301
-  Symbols:   147610
-  CStrings:  83057
+  Functions: 87306
+  Symbols:   147617
+  CStrings:  83059
 
Symbols:
+ -[NSSpellChecker _clearCurrentMarkedTextForClient:replacementRange:]
+ -[NSTextInputContext(CatalystSupport) _isRTISourceSession]
+ ___34-[NSCorrectionPanel _handleEvent:]_block_invoke_2
+ ___block_descriptor_64_e8_32b40w48w_e36_v16?0"NSCorrectionPanelSelection"8l
+ ___copy_helper_block_e8_32b40w48w
+ ___destroy_helper_block_e8_32b40w48w
+ _objc_msgSend$_clearCurrentMarkedTextForClient:replacementRange:
+ _objc_msgSend$_isRTISourceSession
+ _objc_msgSend$setUnmarkIfNecessary:
- ___block_descriptor_72_e8_32o40o48o56b_e18_v16?0"NSString"8l
- _objc_msgSend$unmarkIfNecessary
CStrings:
+ "_clearCurrentMarkedTextForClient:replacementRange:"
+ "_isRTISourceSession"
+ "dismissing submenu %p"
+ "setUnmarkIfNecessary:"
+ "trackedImpl set to %p"
- "dismissing submenu %@"
- "trackedImpl set to %@"
- "unmarkIfNecessary"
```
