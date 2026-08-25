## Safari

> `/System/Library/PrivateFrameworks/Safari.framework/Versions/A/Safari`

```diff

-621.3.8.0.0
-  __TEXT.__text: 0x6eaafc
+621.3.11.11.3
+  __TEXT.__text: 0x6eace0
   __TEXT.__auth_stubs: 0x5850
-  __TEXT.__objc_methlist: 0x54b5c
-  __TEXT.__gcc_except_tab: 0xc6ab8
+  __TEXT.__objc_methlist: 0x54b64
+  __TEXT.__gcc_except_tab: 0xc6b00
   __TEXT.__const: 0x5c44
   __TEXT.__ustring: 0x10dbe
   __TEXT.__cstring: 0x49ce5
-  __TEXT.__oslogstring: 0x1f0eb
+  __TEXT.__oslogstring: 0x1f15b
   __TEXT.__dlopen_cstrs: 0x468
   __TEXT.__constg_swiftt: 0x684
   __TEXT.__swift5_typeref: 0x3a6e

   __TEXT.__unwind_info: 0x38600
   __TEXT.__eh_frame: 0xc50
   __TEXT.__objc_classname: 0xb5bc
-  __TEXT.__objc_methname: 0xfb49d
+  __TEXT.__objc_methname: 0xfb4bb
   __TEXT.__objc_methtype: 0x225ee
-  __TEXT.__objc_stubs: 0x96440
+  __TEXT.__objc_stubs: 0x96460
   __DATA_CONST.__got: 0x3a68
   __DATA_CONST.__const: 0x4348
   __DATA_CONST.__objc_classlist: 0x1fa0

   __DATA_CONST.__objc_nlcatlist: 0x8
   __DATA_CONST.__objc_protolist: 0x1098
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2f770
+  __DATA_CONST.__objc_selrefs: 0x2f778
   __DATA_CONST.__objc_protorefs: 0x200
   __DATA_CONST.__objc_superrefs: 0x1828
   __DATA_CONST.__objc_arraydata: 0xad8
   __AUTH_CONST.__auth_got: 0x2c40
   __AUTH_CONST.__const: 0x1a6a0
   __AUTH_CONST.__cfstring: 0x33fe0
-  __AUTH_CONST.__objc_const: 0x7be50
-  __AUTH_CONST.__objc_intobj: 0x1200
+  __AUTH_CONST.__objc_const: 0x7be60
+  __AUTH_CONST.__objc_intobj: 0x11e8
   __AUTH_CONST.__objc_dictobj: 0x5a0
   __AUTH_CONST.__objc_arrayobj: 0x4e0
   __AUTH_CONST.__objc_doubleobj: 0x2c0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 35403
-  Symbols:   77381
-  CStrings:  47196
+  Functions: 35405
+  Symbols:   77384
+  CStrings:  47199
 
Symbols:
+ -[BrowserViewController hasFullScreenWindowController]
+ GCC_except_table1236
+ GCC_except_table1252
+ GCC_except_table1254
+ GCC_except_table1284
+ GCC_except_table1298
+ GCC_except_table1305
+ GCC_except_table1308
+ GCC_except_table1329
+ GCC_except_table1332
+ GCC_except_table1336
+ GCC_except_table1613
+ GCC_except_table1622
+ GCC_except_table1626
+ GCC_except_table1629
+ GCC_except_table1631
+ GCC_except_table1641
+ _objc_msgSend$hasFullScreenWindowController
- GCC_except_table1235
- GCC_except_table1237
- GCC_except_table1253
- GCC_except_table1277
- GCC_except_table1286
- GCC_except_table1318
- GCC_except_table1330
- GCC_except_table1333
- GCC_except_table1338
- GCC_except_table1621
- GCC_except_table1625
- GCC_except_table1628
- GCC_except_table1630
- GCC_except_table1640
- ___90-[AppController _browserStateFromCurrentSessionIgnoringPrivateWindows:encryptionProvider:]_block_invoke_4
Functions:
~ -[AppController _browserStateFromCurrentSessionIgnoringPrivateWindows:encryptionProvider:] : 1412 -> 1760
+ -[BrowserViewController hasFullScreenWindowController]
~ -[BrowserWindowController validateMenuItem:] : 5716 -> 5760
~ -[BrowserWindowController updateWindowStateIncludingTabStates:] : 1296 -> 1328
~ __ZN6Safari35UnifiedFieldCompletionListGenerator35didReceiveSearchSuggestionsResponseEP37WebSearchSuggestionsFetcherControllerP24WBSOpenSearchURLTemplateP35WBSSearchSuggestionsFetcherResponse : 796 -> 764
~ __ZN6Safari35UnifiedFieldCompletionListGenerator32supportsPrefixNavigationalIntentEv : 336 -> 332
~ __ZN6Safari35UnifiedFieldCompletionListGenerator49previousNavigationalIntentShouldBlockSearchResultEP21WBSParsecSearchResult : 288 -> 300
+ -[BrowserWindowController updateWindowStateIncludingTabStates:].cold.1
CStrings:
+ "Could not save nil window state"
+ "Pinned tabs to save for profileIdentifier = %@ : (%lu pinned tabs) %{sensitive}@"
+ "hasFullScreenWindowController"
```
