## libAppletTranslationLibrary.dylib

> `/usr/lib/libAppletTranslationLibrary.dylib`

```diff

-55.1.0.0.0
-  __TEXT.__text: 0xb9928
+55.2.0.0.0
+  __TEXT.__text: 0xbac58
   __TEXT.__auth_stubs: 0x1290
-  __TEXT.__objc_methlist: 0x24d8
+  __TEXT.__objc_methlist: 0x2518
   __TEXT.__const: 0x28d4
-  __TEXT.__cstring: 0x8865
-  __TEXT.__oslogstring: 0x53f7
+  __TEXT.__cstring: 0x8895
+  __TEXT.__oslogstring: 0x5437
   __TEXT.__gcc_except_tab: 0x1890
   __TEXT.__swift5_typeref: 0x907
   __TEXT.__constg_swiftt: 0x84c

   __TEXT.__swift5_mpenum: 0x44
   __TEXT.__ustring: 0xa
   __TEXT.__swift5_protos: 0xc
-  __TEXT.__unwind_info: 0x1740
+  __TEXT.__unwind_info: 0x1750
   __TEXT.__eh_frame: 0x1944
   __TEXT.__objc_classname: 0x413
-  __TEXT.__objc_methname: 0x4c30
+  __TEXT.__objc_methname: 0x4d0d
   __TEXT.__objc_methtype: 0xf45
-  __TEXT.__objc_stubs: 0x48c0
+  __TEXT.__objc_stubs: 0x4980
   __DATA_CONST.__got: 0x390
-  __DATA_CONST.__const: 0x828
+  __DATA_CONST.__const: 0x860
   __DATA_CONST.__objc_classlist: 0x1d0
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1410
+  __DATA_CONST.__objc_selrefs: 0x1440
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_arraydata: 0x1b10
   __AUTH_CONST.__auth_got: 0x960
   __AUTH_CONST.__const: 0x2a78
-  __AUTH_CONST.__cfstring: 0x9640
+  __AUTH_CONST.__cfstring: 0x96c0
   __AUTH_CONST.__objc_const: 0x37a8
   __AUTH_CONST.__objc_intobj: 0xb88
   __AUTH_CONST.__objc_arrayobj: 0x420

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1886
-  Symbols:   2814
-  CStrings:  2802
+  Functions: 1891
+  Symbols:   2825
+  CStrings:  2814
 
Symbols:
+ +[KramerMappings calculateTopupTransactionSN:withDifferentiator:withIpeId:]
+ +[KramerMappings convertTopupsToHistory:]
+ +[KramerMappings getMergedHistory:withDirectory:withIpeList:]
+ +[KramerMappings mergeTransitAndTopupHistory:withTopupHistory:]
+ +[KramerVCReader getTopupCredits:withIpeId:]
+ _objc_msgSend$calculateTopupTransactionSN:withDifferentiator:withIpeId:
+ _objc_msgSend$convertTopupsToHistory:
+ _objc_msgSend$getMergedHistory:withDirectory:withIpeList:
+ _objc_msgSend$getTopupCredits:withIpeId:
+ _objc_msgSend$mergeTransitAndTopupHistory:withTopupHistory:
+ _objc_msgSend$removeObjectsInArray:
CStrings:
+ "030000"
+ "Merged history: %@"
+ "Unexpected Enter / Exit Indicatorcode: %u (expected for topup transactions)"
+ "VGIpePointer"
+ "VGTopupCredit"
+ "VGTopups"
+ "calculateTopupTransactionSN:withDifferentiator:withIpeId:"
+ "convertTopupsToHistory:"
+ "getMergedHistory:withDirectory:withIpeList:"
+ "getTopupCredits:withIpeId:"
+ "historyEntries %@"
+ "mergeTransitAndTopupHistory:withTopupHistory:"
+ "removeObjectsInArray:"
- "Unexpected Enter / Exit Indicatorcode: %u"
```
