## DPSubmissionService

> `/System/Library/PrivateFrameworks/DifferentialPrivacy.framework/XPCServices/DPSubmissionService.xpc/Contents/MacOS/DPSubmissionService`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-659.120.3.0.0
-  __TEXT.__text: 0x544d8
-  __TEXT.__auth_stubs: 0xe90
-  __TEXT.__objc_stubs: 0x3020
-  __TEXT.__objc_methlist: 0x13ac
+659.120.7.0.3
+  __TEXT.__text: 0x53ab4
+  __TEXT.__auth_stubs: 0xe80
+  __TEXT.__objc_stubs: 0x2fa0
+  __TEXT.__objc_methlist: 0x132c
   __TEXT.__const: 0x2818
-  __TEXT.__cstring: 0x2b30
-  __TEXT.__objc_methname: 0x3c06
-  __TEXT.__objc_classname: 0x331
-  __TEXT.__objc_methtype: 0xa39
-  __TEXT.__oslogstring: 0x12b7
-  __TEXT.__gcc_except_tab: 0x238
+  __TEXT.__cstring: 0x2a90
+  __TEXT.__objc_methname: 0x3b1d
+  __TEXT.__objc_classname: 0x31a
+  __TEXT.__objc_methtype: 0xa1a
+  __TEXT.__oslogstring: 0x127e
+  __TEXT.__gcc_except_tab: 0x234
   __TEXT.__swift5_typeref: 0x88e
   __TEXT.__swift5_fieldmd: 0x1490
   __TEXT.__constg_swiftt: 0xd88

   __TEXT.__swift5_assocty: 0x5b8
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x1e08
+  __TEXT.__unwind_info: 0x1df0
   __TEXT.__eh_frame: 0x4158
-  __DATA_CONST.__auth_got: 0x758
-  __DATA_CONST.__got: 0x520
+  __DATA_CONST.__auth_got: 0x750
+  __DATA_CONST.__got: 0x508
   __DATA_CONST.__auth_ptr: 0x2a8
-  __DATA_CONST.__const: 0x2e50
-  __DATA_CONST.__cfstring: 0x17a0
+  __DATA_CONST.__const: 0x2e30
+  __DATA_CONST.__cfstring: 0x1720
   __DATA_CONST.__objc_classlist: 0x110
-  __DATA_CONST.__objc_catlist: 0x10
+  __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8

   __DATA_CONST.__objc_arraydata: 0x68
   __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA.__objc_const: 0x25a0
-  __DATA.__objc_selrefs: 0xe60
-  __DATA.__objc_ivar: 0x104
+  __DATA.__objc_const: 0x2500
+  __DATA.__objc_selrefs: 0xe38
+  __DATA.__objc_ivar: 0xfc
   __DATA.__objc_data: 0xe78
   __DATA.__data: 0x23d0
-  __DATA.__bss: 0x59d0
+  __DATA.__bss: 0x59c0
   __DATA.__common: 0x140
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2425
-  Symbols:   329
-  CStrings:  1134
+  Functions: 2413
+  Symbols:   325
+  CStrings:  1118
 
Symbols:
- __DPMetadataIsV2
- _kDPMetadataDediscoTaskConfigFeatures
- _kDPMetadataDediscoTaskConfigFeaturesOHTTP
- _kDPMetadataDediscoTaskConfigFeaturesPAT
CStrings:
+ "%@_%@.pat"
+ "Fetched %lu tokens"
+ "Missing issue URL. Skipping token fetching"
+ "No file found in path %@ to retrieve token"
+ "Token count: %lu; %@"
+ "donateTokenCountToBitacoraForDirPath:"
+ "fetchMultipleChallengeTokenPair"
+ "initWithIssuer:redemptionContext:"
+ "randomFile"
+ "randomToken"
+ "saveTokens:toFileInPath:"
+ "tokensFilePrefix"
- "  aggregators: %@\n"
- "%@Tokens_%@.pat"
- "B40@0:8@16@24@32"
- "DPSubmissionService"
- "Fetched %lu tokens for aggregator %@."
- "Incorrect data type for %@.%@ - expect dictionary"
- "Incorrect data type for %@.%@.%@ - expect boolean"
- "Missing aggregator list or issue URL. Skipping token fetching"
- "No file found in path %@ to retrieve token for aggregator %@."
- "Origin info length exceeds 64KB."
- "Q32@0:8@16@24"
- "T@\"NSArray\",R,C,N,V_aggregators"
- "T@\"NSString\",R,C,N,V_origin"
- "Token count for %@: %lu; %@"
- "_aggregators"
- "_origin"
- "aggregators"
- "allKeys"
- "defaultValueForKey:"
- "donateTokenCountToBitacoraForAggregator:dirPath:"
- "fetchMultipleChallengeTokenPairForAggregator:"
- "getHelperServerName"
- "initWithIssuer:origin:redemptionContext:"
- "isFeatureEnabled:withError:"
- "origin"
- "randomFileForAggregator:"
- "randomTokenForAggregator:"
- "saveTokens:toFileInPath:forAggregator:"
```
