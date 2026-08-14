## NotesShared

> `/System/Library/PrivateFrameworks/NotesShared.framework/Versions/A/NotesShared`

```diff

-2998.52.0.0.0
-  __TEXT.__text: 0x366c68
+2998.55.0.0.0
+  __TEXT.__text: 0x367370
   __TEXT.__auth_stubs: 0x4d80
-  __TEXT.__objc_methlist: 0x172d8
-  __TEXT.__const: 0xb5e0
-  __TEXT.__cstring: 0x19bbf
-  __TEXT.__oslogstring: 0x1af4c
-  __TEXT.__gcc_except_tab: 0xfb58
+  __TEXT.__objc_methlist: 0x17310
+  __TEXT.__const: 0xb5b0
+  __TEXT.__cstring: 0x19c1f
+  __TEXT.__oslogstring: 0x1b08c
+  __TEXT.__gcc_except_tab: 0xfb78
   __TEXT.__dlopen_cstrs: 0x2b8
   __TEXT.__ustring: 0x38e
   __TEXT.__constg_swiftt: 0x2e30
-  __TEXT.__swift5_typeref: 0x3e6d
+  __TEXT.__swift5_typeref: 0x3e7d
   __TEXT.__swift5_builtin: 0x1cc
-  __TEXT.__swift5_reflstr: 0x1c48
-  __TEXT.__swift5_fieldmd: 0x292c
+  __TEXT.__swift5_reflstr: 0x1cd8
+  __TEXT.__swift5_fieldmd: 0x2974
   __TEXT.__swift5_assocty: 0x838
   __TEXT.__swift5_capture: 0x1518
-  __TEXT.__swift5_proto: 0x968
+  __TEXT.__swift5_proto: 0x964
   __TEXT.__swift5_types: 0x344
   __TEXT.__swift_as_entry: 0x1a8
   __TEXT.__swift_as_ret: 0x1d8
   __TEXT.__swift5_protos: 0x54
   __TEXT.__swift5_mpenum: 0x74
-  __TEXT.__unwind_info: 0xee80
-  __TEXT.__eh_frame: 0x9334
-  __TEXT.__objc_classname: 0x2124
-  __TEXT.__objc_methname: 0x3414a
-  __TEXT.__objc_methtype: 0x4b72
-  __TEXT.__objc_stubs: 0x257a0
+  __TEXT.__unwind_info: 0xee90
+  __TEXT.__eh_frame: 0x936c
+  __TEXT.__objc_classname: 0x2126
+  __TEXT.__objc_methname: 0x34275
+  __TEXT.__objc_methtype: 0x4b58
+  __TEXT.__objc_stubs: 0x25800
   __DATA_CONST.__got: 0x20d0
   __DATA_CONST.__const: 0x1e30
   __DATA_CONST.__objc_classlist: 0x9f8
   __DATA_CONST.__objc_catlist: 0x118
   __DATA_CONST.__objc_protolist: 0x210
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc148
+  __DATA_CONST.__objc_selrefs: 0xc168
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0x6d0
   __DATA_CONST.__objc_arraydata: 0x1f0
   __AUTH_CONST.__auth_got: 0x26d8
   __AUTH_CONST.__const: 0x102b0
-  __AUTH_CONST.__cfstring: 0xee20
-  __AUTH_CONST.__objc_const: 0x20950
+  __AUTH_CONST.__cfstring: 0xee40
+  __AUTH_CONST.__objc_const: 0x209e0
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_intobj: 0x408
   __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x60d8
   __AUTH.__data: 0x1dc8
-  __DATA.__objc_ivar: 0xd1c
-  __DATA.__data: 0x5818
+  __DATA.__objc_ivar: 0xd28
+  __DATA.__data: 0x5808
   __DATA.__objc_stublist: 0x20
-  __DATA.__bss: 0x12830
+  __DATA.__bss: 0x127c0
   __DATA.__common: 0x330
   __DATA_DIRTY.__objc_data: 0xa00
   __DATA_DIRTY.__bss: 0xa0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 17960
-  Symbols:   22295
-  CStrings:  13733
+  Functions: 17972
+  Symbols:   22308
+  CStrings:  13748
 
Symbols:
+ -[ICCloudConfiguration searchSubstringMatchingEnabled]
+ -[ICSearchSuggestionsQuery filterQueries]
+ -[ICSearchSuggestionsQuery initWithSearchString:additionalLiteralSearchString:searchTokens:filterQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:]
+ -[ICSearchSuggestionsQuery literalSearchString]
+ -[ICSearchSuggestionsQuery setFilterQueries:]
+ -[ICSearchSuggestionsQuery setLiteralSearchString:]
+ -[ICSearchSuggestionsQuery setUserSearchString:]
+ -[ICSearchSuggestionsQuery userSearchString]
+ OBJC_IVAR_$_ICCloudConfiguration._searchSubstringMatchingEnabled
+ OBJC_IVAR_$_ICSearchSuggestionsQuery._filterQueries
+ OBJC_IVAR_$_ICSearchSuggestionsQuery._literalSearchString
+ OBJC_IVAR_$_ICSearchSuggestionsQuery._userSearchString
+ __35+[ICNoteContext clearSharedContext]_block_invoke
+ _objc_msgSend$initWithSearchString:additionalLiteralSearchString:searchTokens:filterQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:
+ _objc_msgSend$literalSearchString
+ _objc_msgSend$searchSubstringMatchingEnabled
+ _objc_msgSend$setAdditionalQueries:
+ _objc_msgSend$userSearchString
+ _sharedContextReferenceCount
+ _symbolic SS11errorString_t
- -[ICSearchSuggestionsQuery additionalQueries]
- -[ICSearchSuggestionsQuery initWithSearchString:searchTokens:additionalQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:]
- -[ICSearchSuggestionsQuery setAdditionalQueries:]
- OBJC_IVAR_$_ICSearchSuggestionsQuery._additionalQueries
- _associated conformance 11NotesShared20SummarizationManagerC0C5ErrorOSHAASQ
- _objc_msgSend$additionalQueries
- _objc_msgSend$initWithSearchString:searchTokens:additionalQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:
CStrings:
+ "-[ICSearchSuggestionsQuery initWithSearchString:additionalLiteralSearchString:searchTokens:filterQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:]"
+ "T@\"NSArray\",&,N,V_filterQueries"
+ "T@\"NSString\",&,N,V_literalSearchString"
+ "T@\"NSString\",&,N,V_userSearchString"
+ "TB,R,N,V_searchSubstringMatchingEnabled"
+ "Trying to create a cloud configuration with no searchSubstringMatchingEnabled value"
+ "_filterQueries"
+ "_literalSearchString"
+ "_searchSubstringMatchingEnabled"
+ "_userSearchString"
+ "clearSharedContext :: Canceling all ICCloudContext operations"
+ "clearSharedContext :: Clearing sharedContext"
+ "clearSharedContext :: sharedContextReferenceCount = %ld"
+ "initWithSearchString:additionalLiteralSearchString:searchTokens:filterQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:"
+ "literalSearchString"
+ "nosign.badge.clock"
+ "searchSubstringMatchingEnabled"
+ "setLiteralSearchString:"
+ "setUserSearchString:"
+ "startSharedContextWithOptions: :: sharedContextReferenceCount = %ld"
+ "userSearchString"
- "-[ICSearchSuggestionsQuery initWithSearchString:searchTokens:additionalQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:]"
- "@60@0:8@16@24@32@40B48@52"
- "T@\"NSArray\",&,N,V_additionalQueries"
- "_additionalQueries"
- "additionalQueries"
- "initWithSearchString:searchTokens:additionalQueries:rankingQueriesDefinition:modernResultsOnly:suggestionsResponder:"
```
