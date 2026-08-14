## SoftwareUpdateMacController

> `/System/Library/PrivateFrameworks/SoftwareUpdateMacController.framework/Versions/A/SoftwareUpdateMacController`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-223.100.6.0.0
-  __TEXT.__text: 0xaa39c
+223.120.2.0.0
+  __TEXT.__text: 0xaa414
   __TEXT.__auth_stubs: 0x340
-  __TEXT.__objc_methlist: 0x5474
+  __TEXT.__objc_methlist: 0x5484
   __TEXT.__const: 0x180
-  __TEXT.__cstring: 0x13c72
+  __TEXT.__cstring: 0x13c9a
   __TEXT.__oslogstring: 0x11779
   __TEXT.__gcc_except_tab: 0x6c4
   __TEXT.__unwind_info: 0xe30
   __TEXT.__objc_classname: 0x56c
-  __TEXT.__objc_methname: 0x12d9c
+  __TEXT.__objc_methname: 0x12e29
   __TEXT.__objc_methtype: 0x11a7
-  __TEXT.__objc_stubs: 0xc160
+  __TEXT.__objc_stubs: 0xc1a0
   __DATA_CONST.__got: 0x588
   __DATA_CONST.__const: 0x16b8
   __DATA_CONST.__objc_classlist: 0x100
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3900
+  __DATA_CONST.__objc_selrefs: 0x3910
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0xb0
   __DATA_CONST.__objc_arraydata: 0x10
   __AUTH_CONST.__auth_got: 0x1b0
   __AUTH_CONST.__const: 0x11e0
-  __AUTH_CONST.__cfstring: 0xe360
-  __AUTH_CONST.__objc_const: 0x8c40
+  __AUTH_CONST.__cfstring: 0xe380
+  __AUTH_CONST.__objc_const: 0x8c70
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0xa00
-  __DATA.__objc_ivar: 0x720
+  __DATA.__objc_ivar: 0x724
   __DATA.__data: 0x660
   __DATA.__bss: 0x50
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/SoftwareUpdateCoreSupport.framework/Versions/A/SoftwareUpdateCoreSupport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2042
-  Symbols:   5239
-  CStrings:  5655
+  Functions: 2043
+  Symbols:   5243
+  CStrings:  5660
 
Symbols:
+ -[SUMacControllerDescriptor documentationEncodedUIBundlePath]
+ OBJC_IVAR_$_SUMacControllerDescriptor._documentationEncodedUIBundlePath
+ _objc_msgSend$documentationEncodedUIBundlePath
+ _objc_msgSend$encodedUIBundlePath
Functions:
~ -[SUMacControllerDescriptor _initializeWithSUCoreDescriptor:updateUUID:initializationMethod:] : 2716 -> 2720
~ -[SUMacControllerDescriptor _initializeWithTargetRestoreVersion:targetBuildVersion:targetProductVersion:updateUUID:] : 1392 -> 1396
~ -[SUMacControllerDescriptor assignDocumentation:] : 1304 -> 1348
~ -[SUMacControllerDescriptor description] : 5748 -> 5796
+ -[SUMacControllerDescriptor associatedDocumentation]
~ -[SUMacControllerDescriptor .cxx_destruct] : 1076 -> 1088
CStrings:
+ "  documentationEncodedUIBundlePath: %@\n"
+ "T@\"NSString\",R,&,N,V_documentationEncodedUIBundlePath"
+ "_documentationEncodedUIBundlePath"
+ "documentationEncodedUIBundlePath"
+ "encodedUIBundlePath"
```
