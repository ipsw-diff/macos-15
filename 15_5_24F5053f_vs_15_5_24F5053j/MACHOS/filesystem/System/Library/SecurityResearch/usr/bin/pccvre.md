## pccvre

> `/System/Library/SecurityResearch/usr/bin/pccvre`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__oslogstring`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-199.120.6.0.0
-  __TEXT.__text: 0x1bd5e8
-  __TEXT.__auth_stubs: 0x2ea0
+199.120.7.0.0
+  __TEXT.__text: 0x1bd998
+  __TEXT.__auth_stubs: 0x2ed0
   __TEXT.__objc_methlist: 0x184
-  __TEXT.__const: 0x11078
-  __TEXT.__cstring: 0x8b11
-  __TEXT.__swift5_typeref: 0x3320
-  __TEXT.__constg_swiftt: 0x37fc
+  __TEXT.__const: 0x11248
+  __TEXT.__cstring: 0x8d11
+  __TEXT.__swift5_typeref: 0x3362
+  __TEXT.__constg_swiftt: 0x3848
   __TEXT.__swift5_builtin: 0x1cc
   __TEXT.__swift5_mpenum: 0x84
-  __TEXT.__swift5_reflstr: 0x2c5d
-  __TEXT.__swift5_fieldmd: 0x4adc
+  __TEXT.__swift5_reflstr: 0x2d0d
+  __TEXT.__swift5_fieldmd: 0x4b74
   __TEXT.__swift5_assocty: 0x5c8
-  __TEXT.__swift5_proto: 0x10fc
-  __TEXT.__swift5_types: 0x518
+  __TEXT.__swift5_proto: 0x111c
+  __TEXT.__swift5_types: 0x520
   __TEXT.__objc_classname: 0x59
   __TEXT.__objc_methname: 0x895
   __TEXT.__objc_methtype: 0x16c

   __TEXT.__oslogstring: 0x1aee
   __TEXT.__swift_as_entry: 0x1ac
   __TEXT.__swift_as_ret: 0x1c0
-  __TEXT.__swift5_capture: 0x534
+  __TEXT.__swift5_capture: 0x294
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x5970
-  __TEXT.__eh_frame: 0xa234
-  __DATA_CONST.__auth_got: 0x1750
+  __TEXT.__unwind_info: 0x5928
+  __TEXT.__eh_frame: 0xa2dc
+  __DATA_CONST.__auth_got: 0x1768
   __DATA_CONST.__got: 0x8c8
   __DATA_CONST.__auth_ptr: 0xf08
-  __DATA_CONST.__const: 0x8998
+  __DATA_CONST.__const: 0x8088
   __DATA_CONST.__cfstring: 0x19c0
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x50

   __DATA.__objc_const: 0x1558
   __DATA.__objc_selrefs: 0x320
   __DATA.__objc_data: 0x390
-  __DATA.__data: 0x97c0
-  __DATA.__bss: 0x217d0
-  __DATA.__common: 0xbd0
+  __DATA.__data: 0x98c8
+  __DATA.__bss: 0x21bd0
+  __DATA.__common: 0xbf8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CryptoKit.framework/Versions/A/CryptoKit
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftCryptoTokenKit.dylib
   - /usr/lib/swift/libswiftDarwin.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 7077
-  Symbols:   1275
-  CStrings:  1355
+  Functions: 7027
+  Symbols:   1279
+  CStrings:  1365
 
Symbols:
+ _$s22ArgumentParserInternal0A0V12wrappedValue7parsing4help10completionACySayqd__GGAH_AA0A20ArrayParsingStrategyVAA0A4HelpVSgAA14CompletionKindVSgtcAHRszAA013ExpressibleByA0Rd__lufC
+ _$s22ArgumentParserInternal0A20ArrayParsingStrategyV21captureForPassthroughACvgZ
+ _$ss22_stringCompareInternal____9expectingSbs11_StringGutsV_SnySiGAdEs01_E16ComparisonResultOtF
+ __swift_FORCE_LOAD_$_swiftCryptoTokenKit
CStrings:
+ "--tools-directory"
+ "/usr/bin/pccvre-helper"
+ "Alternate path to 'pccvre-helper' command."
+ "Invoke an app-specific instance command."
+ "The PCC release of the instance does not support this command."
+ "Warning:\nThe PCC release of the instance might be incompatible with this command.\nPlease use `pccvre instance invoke inference-request` instead.\n"
+ "helper not found"
+ "instanceInferenceRequestV1"
+ "passthroughAguments"
+ "pccvre-helper features failed with exit code "
```
