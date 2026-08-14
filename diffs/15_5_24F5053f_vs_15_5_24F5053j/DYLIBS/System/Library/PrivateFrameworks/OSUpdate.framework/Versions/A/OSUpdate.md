## OSUpdate

> `/System/Library/PrivateFrameworks/OSUpdate.framework/Versions/A/OSUpdate`

```diff

-2078.120.12.0.0
-  __TEXT.__text: 0x8e608
+2078.120.19.0.3
+  __TEXT.__text: 0x8ebf0
   __TEXT.__auth_stubs: 0xab0
-  __TEXT.__objc_methlist: 0x6e44
+  __TEXT.__objc_methlist: 0x6e9c
   __TEXT.__const: 0x191
-  __TEXT.__cstring: 0x64c1
-  __TEXT.__oslogstring: 0xbe6c
-  __TEXT.__gcc_except_tab: 0x2028
+  __TEXT.__cstring: 0x6540
+  __TEXT.__oslogstring: 0xbf2d
+  __TEXT.__gcc_except_tab: 0x204c
   __TEXT.__ustring: 0xc
-  __TEXT.__unwind_info: 0x1d00
-  __TEXT.__objc_classname: 0x81b
-  __TEXT.__objc_methname: 0x150ee
+  __TEXT.__unwind_info: 0x1d10
+  __TEXT.__objc_classname: 0x81c
+  __TEXT.__objc_methname: 0x151b8
   __TEXT.__objc_methtype: 0x20a4
-  __TEXT.__objc_stubs: 0xe360
+  __TEXT.__objc_stubs: 0xe3e0
   __DATA_CONST.__got: 0x9d8
   __DATA_CONST.__const: 0xc48
   __DATA_CONST.__objc_classlist: 0x220
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4520
+  __DATA_CONST.__objc_selrefs: 0x4548
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x3f8
   __AUTH_CONST.__auth_got: 0x568
   __AUTH_CONST.__const: 0x2730
   __AUTH_CONST.__cfstring: 0x52e0
-  __AUTH_CONST.__objc_const: 0x8928
+  __AUTH_CONST.__objc_const: 0x8988
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH.__objc_data: 0xaf0
-  __DATA.__objc_ivar: 0x654
+  __DATA.__objc_ivar: 0x65c
   __DATA.__data: 0x612
   __DATA.__bss: 0x90
   __DATA_DIRTY.__objc_data: 0xa50

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbootpolicy.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2909
-  Symbols:   6482
-  CStrings:  5158
+  Functions: 2919
+  Symbols:   6497
+  CStrings:  5171
 
Symbols:
+ +[SUOSUUtilities shouldShutDownForPendingBridgeOSUpdate]
+ -[SUOSUMajorProductStubImpl encodedUIBundlePath]
+ -[SUOSUProduct encodedUIBundlePath]
+ -[SUOSUProduct setEncodedUIBundlePath:]
+ -[SUOSUProductStub encodedUIBundlePath]
+ -[SUOSUProductStub setEncodedUIBundlePath:]
+ -[SUOSUProductStubImpl encodedUIBundlePath]
+ OBJC_IVAR_$_SUOSUProduct._encodedUIBundlePath
+ OBJC_IVAR_$_SUOSUProductStub._encodedUIBundlePath
+ __56+[SUOSUUtilities shouldShutDownForPendingBridgeOSUpdate]_block_invoke
+ ___56+[SUOSUUtilities shouldShutDownForPendingBridgeOSUpdate]_block_invoke
+ _objc_msgSend$documentationEncodedUIBundlePath
+ _objc_msgSend$encodedUIBundleOverridePath
+ _objc_msgSend$encodedUIBundlePath
+ _objc_msgSend$shouldShutDownForPendingBridgeOSUpdate
CStrings:
+ "%@: Overriding Encoded UI Bundle Path to %@ for %@"
+ "%s: BridgeOS update pending, should shut down!"
+ "%s: Error retrieving BOSSUC updateState: %s"
+ "%s: Error retrieving BOSSUC updateState: timed out"
+ "+[SUOSUUtilities shouldShutDownForPendingBridgeOSUpdate]"
+ "+[SUOSUUtilities shouldShutDownForPendingBridgeOSUpdate]_block_invoke"
+ "T@\"NSString\",&,V_encodedUIBundlePath"
+ "_encodedUIBundlePath"
+ "documentationEncodedUIBundlePath"
+ "encodedUIBundleOverridePath"
+ "encodedUIBundlePath"
+ "setEncodedUIBundlePath:"
+ "shouldShutDownForPendingBridgeOSUpdate"
```
