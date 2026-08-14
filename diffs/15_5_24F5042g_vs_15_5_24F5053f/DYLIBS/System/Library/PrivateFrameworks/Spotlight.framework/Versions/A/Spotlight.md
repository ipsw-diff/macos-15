## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Versions/A/Spotlight`

```diff

-2333.41.1.3.0
-  __TEXT.__text: 0x55510
+2333.47.1.0.0
+  __TEXT.__text: 0x55630
   __TEXT.__auth_stubs: 0x1010
-  __TEXT.__objc_methlist: 0x3bb4
+  __TEXT.__objc_methlist: 0x3be4
   __TEXT.__const: 0x578
   __TEXT.__cstring: 0x4eec
-  __TEXT.__gcc_except_tab: 0x2224
+  __TEXT.__gcc_except_tab: 0x2238
   __TEXT.__oslogstring: 0xc90
   __TEXT.__ustring: 0x2c
   __TEXT.__unwind_info: 0x10e0
   __TEXT.__eh_frame: 0x60
   __TEXT.__objc_classname: 0x58c
-  __TEXT.__objc_methname: 0xbde8
+  __TEXT.__objc_methname: 0xbe0e
   __TEXT.__objc_methtype: 0x1445
-  __TEXT.__objc_stubs: 0xa480
+  __TEXT.__objc_stubs: 0xa4c0
   __DATA_CONST.__got: 0xb10
   __DATA_CONST.__const: 0xa50
   __DATA_CONST.__objc_classlist: 0x198
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x32d8
+  __DATA_CONST.__objc_selrefs: 0x32e8
   __DATA_CONST.__objc_superrefs: 0x138
   __DATA_CONST.__objc_arraydata: 0x8b0
   __AUTH_CONST.__auth_got: 0x820
   __AUTH_CONST.__const: 0x1628
   __AUTH_CONST.__cfstring: 0x5be0
-  __AUTH_CONST.__objc_const: 0x5a20
+  __AUTH_CONST.__objc_const: 0x5a80
   __AUTH_CONST.__objc_arrayobj: 0x1b0
   __AUTH_CONST.__objc_intobj: 0x6d8
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH.__objc_data: 0xbe0
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x48c
+  __DATA.__objc_ivar: 0x494
   __DATA.__data: 0x6a8
   __DATA.__bss: 0x4a4
   __DATA_DIRTY.__objc_data: 0x410

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1562
-  Symbols:   4488
-  CStrings:  3220
+  Functions: 1566
+  Symbols:   4496
+  CStrings:  3223
 
Symbols:
+ -[SPMetadataQuery isMath]
+ -[SPMetadataQuery setIsMath:]
+ -[SPQueryTask isMath]
+ -[SPQueryTask setIsMath:]
+ OBJC_IVAR_$_SPMetadataQuery._isMath
+ OBJC_IVAR_$_SPQueryTask._isMath
+ _objc_msgSend$isMath
+ _objc_msgSend$setIsMath:
Functions:
~ -[SPCoreSpotlightQuery buildGroupedResults:] : 4864 -> 4876
~ -[SPQueryTask _initQueries] : 780 -> 800
+ -[SPQueryTask setUserQueryString:]
+ -[SPQueryTask corespotlightFinished]
~ +[SPMetadataQuery _topHitQueryParametersForSearchString:options:queryContext:keyboardLanguage:] : 4096 -> 4196
~ -[SPMetadataQuery queryStringForUserQuery:options:queryContext:outFilterQueries:] : 2444 -> 2496
~ -[SPMetadataQuery _prepareQuery] : 3344 -> 3392
+ -[SPMetadataQuery hasTargetApplicationURL]
+ -[SPMetadataQuery queryUnderstandingOutput]
CStrings:
+ "TB,V_isMath"
+ "_isMath"
+ "setIsMath:"
```
