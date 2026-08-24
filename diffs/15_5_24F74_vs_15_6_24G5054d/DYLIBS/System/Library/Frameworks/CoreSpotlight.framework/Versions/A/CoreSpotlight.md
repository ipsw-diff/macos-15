## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/Versions/A/CoreSpotlight`

```diff

-2333.50.1.0.0
-  __TEXT.__text: 0xe10dc
+2333.55.0.0.0
+  __TEXT.__text: 0xe0fec
   __TEXT.__auth_stubs: 0x1ee0
   __TEXT.__objc_methlist: 0xc868
-  __TEXT.__const: 0xbb2
+  __TEXT.__const: 0xbfe
   __TEXT.__gcc_except_tab: 0x2ff8
-  __TEXT.__cstring: 0x120e2
+  __TEXT.__cstring: 0x12052
   __TEXT.__oslogstring: 0x6d05
   __TEXT.__dlopen_cstrs: 0x365
   __TEXT.__ustring: 0x3c

   __TEXT.__unwind_info: 0x3508
   __TEXT.__eh_frame: 0x1e8
   __TEXT.__objc_classname: 0x100d
-  __TEXT.__objc_methname: 0x1d4e8
-  __TEXT.__objc_methtype: 0x20fa
-  __TEXT.__objc_stubs: 0xfe80
+  __TEXT.__objc_methname: 0x1d4dd
+  __TEXT.__objc_methtype: 0x20e5
+  __TEXT.__objc_stubs: 0xfe60
   __DATA_CONST.__got: 0x7b8
   __DATA_CONST.__const: 0x35a8
   __DATA_CONST.__objc_classlist: 0x468

   __DATA_CONST.__objc_arraydata: 0xb98
   __AUTH_CONST.__auth_got: 0xf80
   __AUTH_CONST.__const: 0x36e8
-  __AUTH_CONST.__cfstring: 0x11480
+  __AUTH_CONST.__cfstring: 0x11440
   __AUTH_CONST.__objc_const: 0x12648
   __AUTH_CONST.__objc_intobj: 0x768
   __AUTH_CONST.__objc_doubleobj: 0x90

   __AUTH.__objc_data: 0x1590
   __AUTH.__data: 0x3a0
   __DATA.__objc_ivar: 0xbb0
-  __DATA.__data: 0xa30
+  __DATA.__data: 0x9e8
   __DATA.__bss: 0x1320
   __DATA.__common: 0xc
   __DATA_DIRTY.__objc_data: 0x1680

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 5541
-  Symbols:   11311
-  CStrings:  8848
+  Symbols:   11310
+  CStrings:  8845
 
Symbols:
+ +[CSUserQuery skipTextSemanticSearchForSearchString:queryContext:skipReason:]
+ _objc_msgSend$skipTextSemanticSearchForSearchString:queryContext:skipReason:
- +[CSUserQuery skipTextSemanticSearchForSearchString:tokenCount:queryContext:skipReason:]
- _objc_msgSend$containsCJK
- _objc_msgSend$skipTextSemanticSearchForSearchString:tokenCount:queryContext:skipReason:
Functions:
~ +[CSUserQuery skipTextSemanticSearchForSearchString:tokenCount:queryContext:skipReason:] -> +[CSUserQuery skipTextSemanticSearchForSearchString:queryContext:skipReason:] : 496 -> 356
~ +[CSUserQuery parseResultWithSearchString:parseOptions:queryContext:isZKW:] : 9400 -> 9300
CStrings:
+ "skipTextSemanticSearchForSearchString:queryContext:skipReason:"
- "B48@0:8@16@24@32^@40"
- "kMDUserQueryDictionaryQueryTokenCountKey"
- "query does not match length criteria (tokenCount: %u, normalizedQueryLength: %lu, containsCJK: %d)"
- "skipTextSemanticSearchForSearchString:tokenCount:queryContext:skipReason:"
```
