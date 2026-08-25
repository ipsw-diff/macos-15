## LocalAuthentication

> `/System/Library/Frameworks/LocalAuthentication.framework/Versions/A/LocalAuthentication`

```diff

-1656.140.3.0.0
-  __TEXT.__text: 0x3bc34
+1656.140.4.0.0
+  __TEXT.__text: 0x3ac8c
   __TEXT.__auth_stubs: 0x920
-  __TEXT.__objc_methlist: 0x3470
-  __TEXT.__const: 0x2f0
+  __TEXT.__objc_methlist: 0x33e0
+  __TEXT.__const: 0x2e0
   __TEXT.__gcc_except_tab: 0x1330
   __TEXT.__cstring: 0x1b18
   __TEXT.__dlopen_cstrs: 0x177
-  __TEXT.__oslogstring: 0x2cea
+  __TEXT.__oslogstring: 0x2ac8
   __TEXT.__swift5_typeref: 0x6e
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_builtin: 0x14

   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x1368
+  __TEXT.__unwind_info: 0x1348
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_classname: 0x91e
-  __TEXT.__objc_methname: 0x687d
-  __TEXT.__objc_methtype: 0x1e75
-  __TEXT.__objc_stubs: 0x46c0
+  __TEXT.__objc_methname: 0x6765
+  __TEXT.__objc_methtype: 0x1e08
+  __TEXT.__objc_stubs: 0x4640
   __DATA_CONST.__got: 0x4b0
   __DATA_CONST.__const: 0x3a8
   __DATA_CONST.__objc_classlist: 0x240
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1af0
+  __DATA_CONST.__objc_selrefs: 0x1ab0
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x1c8
   __DATA_CONST.__objc_arraydata: 0x18
   __AUTH_CONST.__auth_got: 0x4a0
-  __AUTH_CONST.__const: 0x20e0
+  __AUTH_CONST.__const: 0x1ff0
   __AUTH_CONST.__cfstring: 0x1940
-  __AUTH_CONST.__objc_const: 0x7e50
+  __AUTH_CONST.__objc_const: 0x7e30
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH.__objc_data: 0x1680

   - /usr/lib/swift/libswift_time.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1509
-  Symbols:   3419
-  CStrings:  2019
+  Functions: 1493
+  Symbols:   3394
+  CStrings:  1999
 
Symbols:
+ GCC_except_table104
+ GCC_except_table106
+ GCC_except_table123
+ GCC_except_table127
+ GCC_except_table133
+ GCC_except_table137
+ GCC_except_table183
+ GCC_except_table75
+ GCC_except_table77
+ GCC_except_table81
+ GCC_except_table92
- -[LAClient analyticsAction:dismissing:reply:]
- -[LAClient analyticsMechanism:result:reply:]
- -[LAClient analyticsMechanism:starting:reply:]
- -[LAClient analyticsSessionStarting:dialogID:bundleID:reply:]
- -[LAContext analyticsAction:dismissing:]
- -[LAContext analyticsMechanism:result:]
- -[LAContext analyticsMechanism:starting:]
- -[LAContext analyticsSessionStarting:dialogID:bundleID:]
- GCC_except_table100
- GCC_except_table112
- GCC_except_table114
- GCC_except_table131
- GCC_except_table135
- GCC_except_table141
- GCC_except_table145
- GCC_except_table191
- GCC_except_table83
- GCC_except_table89
- GCC_except_table93
- ___39-[LAContext analyticsMechanism:result:]_block_invoke
- ___40-[LAContext analyticsAction:dismissing:]_block_invoke
- ___41-[LAContext analyticsMechanism:starting:]_block_invoke
- ___44-[LAClient analyticsMechanism:result:reply:]_block_invoke
- ___45-[LAClient analyticsAction:dismissing:reply:]_block_invoke
- ___46-[LAClient analyticsMechanism:starting:reply:]_block_invoke
- ___56-[LAContext analyticsSessionStarting:dialogID:bundleID:]_block_invoke
- ___61-[LAClient analyticsSessionStarting:dialogID:bundleID:reply:]_block_invoke
- ___block_descriptor_53_e8_32s40s_e20_v20?0B8"NSError"12l
- ___block_descriptor_57_e8_32s40s48s_e25_v16?0?<v?B"NSError">8l
- ___block_descriptor_60_e8_32s40s_e20_v20?0B8"NSError"12l
- ___block_descriptor_61_e8_32s40s_e20_v20?0B8"NSError"12l
- ___block_descriptor_68_e8_32s40s48s_e20_v20?0B8"NSError"12l
- _objc_msgSend$analyticsAction:dismissing:reply:
- _objc_msgSend$analyticsMechanism:result:reply:
- _objc_msgSend$analyticsMechanism:starting:reply:
- _objc_msgSend$analyticsSessionStarting:dialogID:bundleID:reply:
CStrings:
- "analyticsAction:%d dismissing:%d on %{public}@ cid:%u"
- "analyticsAction:%d on %{public}@ cid:%u returned %{public}@"
- "analyticsAction:dismissing:"
- "analyticsAction:dismissing:reply:"
- "analyticsMechanism:%d result: %{public}@ on %{public}@ cid:%u returned %{public}@"
- "analyticsMechanism:%d result:%{public}@ on %{public}@ cid:%u"
- "analyticsMechanism:%d starting:%d on %{public}@ cid:%u"
- "analyticsMechanism:%d starting:%d on %{public}@ cid:%u returned %{public}@"
- "analyticsMechanism:result:"
- "analyticsMechanism:result:reply:"
- "analyticsMechanism:starting:"
- "analyticsMechanism:starting:reply:"
- "analyticsSessionStarting:%d dialogID:%{public}@ bundleID:%{private}@ on %{public}@ cid:%u"
- "analyticsSessionStarting:%d on %{public}@ cid:%u returned %{public}@"
- "analyticsSessionStarting:dialogID:bundleID:"
- "analyticsSessionStarting:dialogID:bundleID:reply:"
- "v28@0:8q16B24"
- "v36@0:8B16@20@28"
- "v44@0:8B16@\"NSString\"20@\"NSString\"28@?<v@?B@\"NSError\">36"
- "v44@0:8B16@20@28@?36"
```
