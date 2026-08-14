## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/Versions/A/CoreSpotlight`

```diff

-2333.41.1.3.0
-  __TEXT.__text: 0xe1010
+2333.47.1.0.0
+  __TEXT.__text: 0xe10dc
   __TEXT.__auth_stubs: 0x1ee0
   __TEXT.__objc_methlist: 0xc868
   __TEXT.__const: 0xbb2
   __TEXT.__gcc_except_tab: 0x2ff8
-  __TEXT.__cstring: 0x12092
+  __TEXT.__cstring: 0x120e2
   __TEXT.__oslogstring: 0x6d05
   __TEXT.__dlopen_cstrs: 0x365
   __TEXT.__ustring: 0x3c

   __TEXT.__unwind_info: 0x3508
   __TEXT.__eh_frame: 0x1e8
   __TEXT.__objc_classname: 0x100d
-  __TEXT.__objc_methname: 0x1d511
+  __TEXT.__objc_methname: 0x1d4e8
   __TEXT.__objc_methtype: 0x20fa
   __TEXT.__objc_stubs: 0xfe80
   __DATA_CONST.__got: 0x7b8
-  __DATA_CONST.__const: 0x3598
+  __DATA_CONST.__const: 0x35a8
   __DATA_CONST.__objc_classlist: 0x468
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x80

   __DATA_CONST.__objc_arraydata: 0xb98
   __AUTH_CONST.__auth_got: 0xf80
   __AUTH_CONST.__const: 0x36e8
-  __AUTH_CONST.__cfstring: 0x11420
+  __AUTH_CONST.__cfstring: 0x11480
   __AUTH_CONST.__objc_const: 0x12648
   __AUTH_CONST.__objc_intobj: 0x768
   __AUTH_CONST.__objc_doubleobj: 0x90

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 5541
-  Symbols:   11309
-  CStrings:  8845
+  Symbols:   11311
+  CStrings:  8848
 
Symbols:
+ _MDItemDerivedIsMe
+ _MDItemDerivedIsMeTextContentMatch
+ _objc_msgSend$rankingConfigurationWithMeContact:emailAddresses:phoneFavorites:vipList:clientBundle:spotlightQuery:userQuery:tokenString:queryKind:flags:keyboardLanguage:
- _objc_msgSend$rankingConfigurationWithMeContact:emailAddresses:phoneFavorites:vipList:clientBundle:isScopedSearch:isAdvancedSyntax:spotlightQuery:userQuery:tokenString:queryKind:isPeopleSearch:keyboardLanguage:
Functions:
~ -[CSSearchQuery(TopHitRanking) setupTopHitQueryContextForClientBundleId:] : 7372 -> 7380
~ -[CSUserQuery queryStringWithQueryContext:searchString:options:] : 12156 -> 12328
~ -[CSSearchableIndex _issueCommand:completionHandler:] : 432 -> 456
CStrings:
+ "(%@) || (%@)"
+ "_kMDItemDerivedIsMe"
+ "_kMDItemDerivedIsMeTextContentMatch"
+ "rankingConfigurationWithMeContact:emailAddresses:phoneFavorites:vipList:clientBundle:spotlightQuery:userQuery:tokenString:queryKind:flags:keyboardLanguage:"
- "rankingConfigurationWithMeContact:emailAddresses:phoneFavorites:vipList:clientBundle:isScopedSearch:isAdvancedSyntax:spotlightQuery:userQuery:tokenString:queryKind:isPeopleSearch:keyboardLanguage:"
```
