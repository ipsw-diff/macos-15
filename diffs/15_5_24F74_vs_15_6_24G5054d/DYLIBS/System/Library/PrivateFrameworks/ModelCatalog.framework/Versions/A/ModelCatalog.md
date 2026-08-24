## ModelCatalog

> `/System/Library/PrivateFrameworks/ModelCatalog.framework/Versions/A/ModelCatalog`

```diff

-162.762.0.0.0
-  __TEXT.__text: 0x1b0c84
-  __TEXT.__auth_stubs: 0x1900
-  __TEXT.__objc_methlist: 0x72c
-  __TEXT.__const: 0x2bd34
-  __TEXT.__cstring: 0x1ae49
-  __TEXT.__swift5_typeref: 0x64c4
-  __TEXT.__oslogstring: 0x1eed
-  __TEXT.__constg_swiftt: 0x6b38
-  __TEXT.__swift5_reflstr: 0x28c7
-  __TEXT.__swift5_fieldmd: 0x10f88
+162.772.0.0.0
+  __TEXT.__text: 0x1b47e8
+  __TEXT.__auth_stubs: 0x1940
+  __TEXT.__objc_methlist: 0x738
+  __TEXT.__const: 0x2c244
+  __TEXT.__cstring: 0x1ad69
+  __TEXT.__swift5_typeref: 0x6542
+  __TEXT.__oslogstring: 0x1f0d
+  __TEXT.__constg_swiftt: 0x6ba0
+  __TEXT.__swift5_reflstr: 0x28d7
+  __TEXT.__swift5_fieldmd: 0x1100c
   __TEXT.__swift5_builtin: 0xb4
-  __TEXT.__swift5_proto: 0x34c4
-  __TEXT.__swift5_types: 0xb30
-  __TEXT.__swift5_capture: 0x5630
-  __TEXT.__swift_as_entry: 0x13c
-  __TEXT.__swift_as_ret: 0x10c
-  __TEXT.__swift5_assocty: 0x3718
+  __TEXT.__swift5_proto: 0x34e0
+  __TEXT.__swift5_types: 0xb3c
+  __TEXT.__swift5_capture: 0x5694
+  __TEXT.__swift_as_entry: 0x144
+  __TEXT.__swift_as_ret: 0x114
+  __TEXT.__swift5_assocty: 0x3730
   __TEXT.__swift5_protos: 0xfc
   __TEXT.__swift5_mpenum: 0x44
-  __TEXT.__unwind_info: 0x9c40
-  __TEXT.__eh_frame: 0xd648
+  __TEXT.__unwind_info: 0x9d58
+  __TEXT.__eh_frame: 0xd7f0
   __TEXT.__objc_classname: 0x39
-  __TEXT.__objc_methname: 0xda4
+  __TEXT.__objc_methname: 0xdcb
   __TEXT.__objc_methtype: 0x100
-  __DATA_CONST.__got: 0x3c8
+  __DATA_CONST.__got: 0x3d8
   __DATA_CONST.__const: 0x300
   __DATA_CONST.__objc_classlist: 0x90
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x450
+  __DATA_CONST.__objc_selrefs: 0x458
   __DATA_CONST.__objc_protorefs: 0x30
-  __AUTH_CONST.__auth_got: 0xc80
-  __AUTH_CONST.__const: 0x4d400
-  __AUTH_CONST.__objc_const: 0x1368
+  __AUTH_CONST.__auth_got: 0xca0
+  __AUTH_CONST.__const: 0x4d0d0
+  __AUTH_CONST.__objc_const: 0x1370
   __AUTH.__objc_data: 0x940
-  __AUTH.__data: 0x2e40
-  __DATA.__data: 0x74d8
+  __AUTH.__data: 0x2ee0
+  __DATA.__data: 0x71c8
   __DATA.__common: 0x98
-  __DATA.__bss: 0x68100
+  __DATA.__bss: 0x68480
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CryptoKit.framework/Versions/A/CryptoKit
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 22381
+  Functions: 22475
   Symbols:   218
-  CStrings:  2048
+  CStrings:  2051
 
CStrings:
+ "    WITH EligibilityInfo AS ( SELECT isAppleIntelligenceToggleEnabled, region, languages_json, json_extract(appleIntelligenceUseCase_json, \"$.waitlistStatus\") AS afm_waitlistStatus, json_extract(appleIntelligenceUseCase_json, \"$.isDeviceEligible\") AS afm_deviceEligible FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ) SELECT  json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, json_each(languages_json) WHERE afm_deviceEligible = true AND (isAppleIntelligenceToggleEnabled = true OR bm_gmBypass(\"afm\") = true OR bm_gmBypass(\"adm\") = true)"
+ "    WITH EligibilityInfo AS ( SELECT region, languages_json FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ) SELECT  json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, json_each(languages_json) WHERE bm_mobileGestalt(\"deviceSupportsGenerativeModelSystems\") = true"
+ "    WITH EligibilityInfo AS ( SELECT region, languages_json FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ), ValidANEArchitectures AS ( SELECT json_array(\"h13\", \"h13g\", \"h14\", \"h14g\", \"h14c\", \"h15\", \"h15g\", \"h15c\", \"h16\", \"h16g\", \"h17\", \"h14g.n301\", \"h18\") AS valid_values ) SELECT  json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, ValidANEArchitectures, json_each(languages_json) WHERE bm_aneDeviceInfo(\"aneArchitectureType\") IN ( SELECT value FROM json_each(ValidANEArchitectures.valid_values) )"
+ "calling safetyFailures"
+ "safetyFailuresWithUserIdentifier:with:"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
+ "v28@0:8I16@?20"
+ "v28@0:8I16@?<v@?@\"NSData\"@\"NSError\">20"
- "    WITH EligibilityInfo AS ( SELECT isAppleIntelligenceToggleEnabled, region, languages_json, json_extract(appleIntelligenceUseCase_json, \"$.waitlistStatus\") AS afm_waitlistStatus, json_extract(appleIntelligenceUseCase_json, \"$.isDeviceEligible\") AS afm_deviceEligible FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ) SELECT CASE WHEN region = 1 THEN true ELSE false END AS isMainlandChina, json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, json_each(languages_json) WHERE afm_deviceEligible = true AND (isAppleIntelligenceToggleEnabled = true OR bm_gmBypass(\"afm\") = true OR bm_gmBypass(\"adm\") = true)"
- "    WITH EligibilityInfo AS ( SELECT region, languages_json FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ) SELECT CASE WHEN region = 1 THEN true ELSE false END AS isMainlandChina, json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, json_each(languages_json) WHERE bm_mobileGestalt(\"deviceSupportsGenerativeModelSystems\") = true"
- "    WITH EligibilityInfo AS ( SELECT region, languages_json FROM \"AppleIntelligence.Availability\" ORDER BY eventTimestamp DESC LIMIT 1 ), ValidANEArchitectures AS ( SELECT json_array(\"h13\", \"h13g\", \"h14\", \"h14g\", \"h14c\", \"h15\", \"h15g\", \"h15c\", \"h16\", \"h16g\", \"h17\", \"h14g.n301\", \"h18\") AS valid_values ) SELECT CASE WHEN region = 1 THEN true ELSE false END AS isMainlandChina, json_each.value AS language, NULL AS expirationDate FROM EligibilityInfo, ValidANEArchitectures, json_each(languages_json) WHERE bm_aneDeviceInfo(\"aneArchitectureType\") IN ( SELECT value FROM json_each(ValidANEArchitectures.valid_values) )"
- "com.apple.fm.language.instruct_3b.text_summarizer.draft.generic"
- "com.apple.fm.language.instruct_3b.text_summarizer.generic"
```
