## CoreDuet

> `/System/Library/PrivateFrameworks/CoreDuet.framework/Versions/A/CoreDuet`

```diff

-1892.20.1.0.0
-  __TEXT.__text: 0x1a2c98
-  __TEXT.__auth_stubs: 0x12c0
+1892.21.0.0.0
+  __TEXT.__text: 0x1a2e5c
+  __TEXT.__auth_stubs: 0x12d0
   __TEXT.__objc_methlist: 0x11414
-  __TEXT.__cstring: 0x150e3
+  __TEXT.__cstring: 0x15115
   __TEXT.__const: 0x5a0
   __TEXT.__oslogstring: 0x178e0
   __TEXT.__gcc_except_tab: 0x7890
   __TEXT.__dlopen_cstrs: 0xb6
   __TEXT.__unwind_info: 0x5300
   __TEXT.__objc_classname: 0x2b1a
-  __TEXT.__objc_methname: 0x257b4
+  __TEXT.__objc_methname: 0x2581a
   __TEXT.__objc_methtype: 0x60c8
-  __TEXT.__objc_stubs: 0x164e0
-  __DATA_CONST.__got: 0x10e8
+  __TEXT.__objc_stubs: 0x16540
+  __DATA_CONST.__got: 0x10f8
   __DATA_CONST.__const: 0xe98
   __DATA_CONST.__objc_classlist: 0xbe8
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x218
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7e08
+  __DATA_CONST.__objc_selrefs: 0x7e20
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0x658
   __DATA_CONST.__objc_arraydata: 0x698
-  __AUTH_CONST.__auth_got: 0x970
+  __AUTH_CONST.__auth_got: 0x978
   __AUTH_CONST.__const: 0x4d70
   __AUTH_CONST.__cfstring: 0x12da0
   __AUTH_CONST.__objc_const: 0x220b0

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 8551
-  Symbols:   16164
-  CStrings:  10961
+  Symbols:   16170
+  CStrings:  10964
 
Symbols:
+ _OBJC_CLASS_$_LSApplicationExtensionRecord
+ _OBJC_CLASS_$_LSExtensionPointRecord
+ _dyld_get_active_platform
+ _objc_msgSend$containingBundleRecord
+ _objc_msgSend$enumeratorWithExtensionPointRecord:options:
+ _objc_msgSend$initWithIdentifier:platform:error:
Functions:
~ -[_CDInteractionStore deleteInteractionsWithBundleId:error:] : 232 -> 236
~ __CDTargetBundleIdForBundleId : 244 -> 692
CStrings:
+ "bundleId == %@ OR targetBundleId == %@ OR targetBundleId == %@"
+ "containingBundleRecord"
+ "deleteInteractionsWithBundleId:%@ andTargetBundleIds:%@,%@"
+ "enumeratorWithExtensionPointRecord:options:"
+ "initWithIdentifier:platform:error:"
- "bundleId == %@ OR targetBundleId = %@"
- "deleteInteractionsWithBundleId:%@"
```
