## CoreUtils

> `/System/Library/PrivateFrameworks/CoreUtils.framework/Versions/A/CoreUtils`

```diff

-780.12.0.0.0
-  __TEXT.__text: 0x11cef0
+780.14.0.0.0
+  __TEXT.__text: 0x11d000
   __TEXT.__auth_stubs: 0x2af0
-  __TEXT.__objc_methlist: 0x9e60
-  __TEXT.__cstring: 0x21774
-  __TEXT.__const: 0x2340
+  __TEXT.__objc_methlist: 0x9e80
+  __TEXT.__cstring: 0x21783
+  __TEXT.__const: 0x2350
   __TEXT.__gcc_except_tab: 0x1d28
   __TEXT.__oslogstring: 0xdef
   __TEXT.__unwind_info: 0x3950
   __TEXT.__eh_frame: 0x50
-  __TEXT.__objc_classname: 0xcde
-  __TEXT.__objc_methname: 0x162b7
-  __TEXT.__objc_methtype: 0x44e3
-  __TEXT.__objc_stubs: 0xa400
+  __TEXT.__objc_classname: 0xcdf
+  __TEXT.__objc_methname: 0x16333
+  __TEXT.__objc_methtype: 0x44fb
+  __TEXT.__objc_stubs: 0xa420
   __DATA_CONST.__got: 0x640
   __DATA_CONST.__const: 0x1490
   __DATA_CONST.__objc_classlist: 0x360
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x150
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4e68
+  __DATA_CONST.__objc_selrefs: 0x4e80
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x248
   __DATA_CONST.__objc_arraydata: 0x8
   __AUTH_CONST.__auth_got: 0x1588
   __AUTH_CONST.__const: 0x38f0
   __AUTH_CONST.__cfstring: 0x3fa0
-  __AUTH_CONST.__objc_const: 0x13ad0
+  __AUTH_CONST.__objc_const: 0x13b00
   __AUTH_CONST.__objc_intobj: 0x180
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH.__objc_data: 0x5f0
   __AUTH.__data: 0x1f0
-  __DATA.__objc_ivar: 0x14e8
+  __DATA.__objc_ivar: 0x14ec
   __DATA.__data: 0x3130
   __DATA.__bss: 0xf70
   __DATA.__common: 0x2a

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5718
-  Symbols:   11374
-  CStrings:  9358
+  Functions: 5722
+  Symbols:   11380
+  CStrings:  9364
 
Symbols:
+ -[CUPairingSession extraFlags]
+ -[CUPairingSession setExtraFlags:]
+ -[CUVoiceSession _speakText:flags:languageCode:volume:completion:]
+ -[CUVoiceSession speakText:flags:languageCode:volume:completionHandler:]
+ GCC_except_table2976
+ GCC_except_table2977
+ GCC_except_table3036
+ GCC_except_table3107
+ GCC_except_table3111
+ GCC_except_table3155
+ GCC_except_table3158
+ GCC_except_table3161
+ GCC_except_table3435
+ GCC_except_table3863
+ GCC_except_table4131
+ GCC_except_table4139
+ GCC_except_table4147
+ GCC_except_table4299
+ GCC_except_table4303
+ GCC_except_table4305
+ GCC_except_table4307
+ GCC_except_table4330
+ GCC_except_table4415
+ GCC_except_table4417
+ GCC_except_table4419
+ GCC_except_table4421
+ GCC_except_table4423
+ GCC_except_table4425
+ GCC_except_table4429
+ GCC_except_table4431
+ GCC_except_table4443
+ GCC_except_table4455
+ GCC_except_table4462
+ GCC_except_table4463
+ GCC_except_table4464
+ GCC_except_table4474
+ GCC_except_table4484
+ GCC_except_table4498
+ GCC_except_table4502
+ GCC_except_table4504
+ GCC_except_table4506
+ GCC_except_table5140
+ GCC_except_table5145
+ GCC_except_table5149
+ GCC_except_table5216
+ GCC_except_table5226
+ GCC_except_table5235
+ GCC_except_table5243
+ GCC_except_table5567
+ GCC_except_table5568
+ GCC_except_table5581
+ OBJC_IVAR_$_CUPairingSession._extraFlags
+ _PairingSessionSetExtraFlags
+ ___72-[CUVoiceSession speakText:flags:languageCode:volume:completionHandler:]_block_invoke
+ ___block_descriptor_76_e8_32s40s48s56bs_e5_v8?0l
+ _objc_msgSend$_speakText:flags:languageCode:volume:completion:
+ _objc_msgSend$speakText:flags:languageCode:volume:completionHandler:
- -[CUVoiceSession _speakText:flags:volume:completion:]
- GCC_except_table2974
- GCC_except_table2975
- GCC_except_table3034
- GCC_except_table3105
- GCC_except_table3109
- GCC_except_table3153
- GCC_except_table3156
- GCC_except_table3157
- GCC_except_table3433
- GCC_except_table3861
- GCC_except_table4128
- GCC_except_table4136
- GCC_except_table4144
- GCC_except_table4296
- GCC_except_table4300
- GCC_except_table4302
- GCC_except_table4304
- GCC_except_table4327
- GCC_except_table4411
- GCC_except_table4412
- GCC_except_table4413
- GCC_except_table4418
- GCC_except_table4420
- GCC_except_table4422
- GCC_except_table4426
- GCC_except_table4428
- GCC_except_table4440
- GCC_except_table4447
- GCC_except_table4449
- GCC_except_table4454
- GCC_except_table4458
- GCC_except_table4469
- GCC_except_table4471
- GCC_except_table4479
- GCC_except_table4480
- GCC_except_table4487
- GCC_except_table4501
- GCC_except_table5137
- GCC_except_table5142
- GCC_except_table5146
- GCC_except_table5212
- GCC_except_table5222
- GCC_except_table5231
- GCC_except_table5239
- GCC_except_table5563
- GCC_except_table5564
- GCC_except_table5577
- ___59-[CUVoiceSession speakText:flags:volume:completionHandler:]_block_invoke
- ___block_descriptor_68_e8_32s40s48bs_e5_v8?0l
- _objc_msgSend$_speakText:flags:volume:completion:
CStrings:
+ "Activate: sessionType=%s, flags=%@, extraFlags=%@, pinType=%s, fixedPIN=%s"
+ "TQ,N,V_extraFlags"
+ "_extraFlags"
+ "_speakText:flags:languageCode:volume:completion:"
+ "extraFlags"
+ "setExtraFlags:"
+ "speakText:flags:languageCode:volume:completionHandler:"
+ "v52@0:8@16I24@28d36@?44"
- "Activate: sessionType=%s, flags=%@, pinType=%s, fixedPIN=%s"
- "_speakText:flags:volume:completion:"
```
