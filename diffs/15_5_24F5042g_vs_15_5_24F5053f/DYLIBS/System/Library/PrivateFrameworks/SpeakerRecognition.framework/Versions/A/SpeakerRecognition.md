## SpeakerRecognition

> `/System/Library/PrivateFrameworks/SpeakerRecognition.framework/Versions/A/SpeakerRecognition`

```diff

-3405.20.3.0.0
-  __TEXT.__text: 0x88628
+3405.26.1.4.2
+  __TEXT.__text: 0x8edac
   __TEXT.__auth_stubs: 0x10f0
-  __TEXT.__objc_methlist: 0x5d58
+  __TEXT.__objc_methlist: 0x61d0
   __TEXT.__const: 0x478
-  __TEXT.__cstring: 0xed7f
+  __TEXT.__cstring: 0xf485
   __TEXT.__swift5_typeref: 0xe4
   __TEXT.__constg_swiftt: 0x2f4
   __TEXT.__swift5_fieldmd: 0x118
   __TEXT.__swift5_reflstr: 0x18a
   __TEXT.__swift5_types: 0xc
-  __TEXT.__gcc_except_tab: 0x2504
-  __TEXT.__oslogstring: 0xbbb9
-  __TEXT.__unwind_info: 0x1730
-  __TEXT.__objc_classname: 0xd73
-  __TEXT.__objc_methname: 0x108ae
-  __TEXT.__objc_methtype: 0x2389
-  __TEXT.__objc_stubs: 0x9880
-  __DATA_CONST.__got: 0x980
+  __TEXT.__gcc_except_tab: 0x270c
+  __TEXT.__oslogstring: 0xbdac
+  __TEXT.__unwind_info: 0x17c8
+  __TEXT.__objc_classname: 0xd9d
+  __TEXT.__objc_methname: 0x10aa0
+  __TEXT.__objc_methtype: 0x23cf
+  __TEXT.__objc_stubs: 0x9a00
+  __DATA_CONST.__got: 0x998
   __DATA_CONST.__const: 0x788
-  __DATA_CONST.__objc_classlist: 0x2b0
+  __DATA_CONST.__objc_classlist: 0x2b8
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3790
+  __DATA_CONST.__objc_selrefs: 0x3808
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x1e0
+  __DATA_CONST.__objc_superrefs: 0x1f0
   __DATA_CONST.__objc_arraydata: 0x370
   __AUTH_CONST.__auth_got: 0x890
-  __AUTH_CONST.__const: 0x1b80
-  __AUTH_CONST.__cfstring: 0x5220
-  __AUTH_CONST.__objc_const: 0x9dc8
+  __AUTH_CONST.__const: 0x1bb0
+  __AUTH_CONST.__cfstring: 0x5240
+  __AUTH_CONST.__objc_const: 0xa5f8
   __AUTH_CONST.__objc_dictobj: 0x898
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH.__objc_data: 0x1e90
+  __AUTH.__objc_data: 0x1ee0
   __AUTH.__data: 0x50
-  __DATA.__objc_ivar: 0x73c
+  __DATA.__objc_ivar: 0x7d4
   __DATA.__data: 0xfa0
   __DATA.__bss: 0x130
   __DATA.__common: 0x88

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2225
-  Symbols:   5475
-  CStrings:  5099
+  Functions: 2327
+  Symbols:   5639
+  CStrings:  5159
 
Symbols:
+ -[SSRVoiceProfileRetrainerPSRExclave .cxx_destruct]
+ -[SSRVoiceProfileRetrainerPSRExclave _composeSpeakerConfusionWithScores:forProfiles:]
+ -[SSRVoiceProfileRetrainerPSRExclave _logSpeakerConfusion:forProfileArray:withPrependString:]
+ -[SSRVoiceProfileRetrainerPSRExclave _logSpeakerConfusionWithExplicitScores:withImplicitScores:withPurgeUtterances:forProfile:forConfigVersion:]
+ -[SSRVoiceProfileRetrainerPSRExclave _processAudioFile:]
+ -[SSRVoiceProfileRetrainerPSRExclave _processSpeakerVector:withSize:withScorers:processedAudioDurationMs:]
+ -[SSRVoiceProfileRetrainerPSRExclave addUtterances:withPolicy:withCompletion:]
+ -[SSRVoiceProfileRetrainerPSRExclave asset]
+ -[SSRVoiceProfileRetrainerPSRExclave bestTriggerScore]
+ -[SSRVoiceProfileRetrainerPSRExclave comparativeModels]
+ -[SSRVoiceProfileRetrainerPSRExclave configFilePath]
+ -[SSRVoiceProfileRetrainerPSRExclave configVersion]
+ -[SSRVoiceProfileRetrainerPSRExclave ctx]
+ -[SSRVoiceProfileRetrainerPSRExclave currUttLengthInMs]
+ -[SSRVoiceProfileRetrainerPSRExclave dealloc]
+ -[SSRVoiceProfileRetrainerPSRExclave description]
+ -[SSRVoiceProfileRetrainerPSRExclave implicitTrainingRequired]
+ -[SSRVoiceProfileRetrainerPSRExclave initWithVoiceRetrainingContext:]
+ -[SSRVoiceProfileRetrainerPSRExclave initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:]
+ -[SSRVoiceProfileRetrainerPSRExclave maximumSpeakerVectors]
+ -[SSRVoiceProfileRetrainerPSRExclave modelFilePath]
+ -[SSRVoiceProfileRetrainerPSRExclave needsRetrainingWithAudioFiles:]
+ -[SSRVoiceProfileRetrainerPSRExclave processedAudioDurationMs]
+ -[SSRVoiceProfileRetrainerPSRExclave psrModelFilePath]
+ -[SSRVoiceProfileRetrainerPSRExclave psrScorer]
+ -[SSRVoiceProfileRetrainerPSRExclave purgeConfusionInformationWithPolicy:]
+ -[SSRVoiceProfileRetrainerPSRExclave purgeLastSpeakerEmbedding]
+ -[SSRVoiceProfileRetrainerPSRExclave queue]
+ -[SSRVoiceProfileRetrainerPSRExclave resetModelForRetraining]
+ -[SSRVoiceProfileRetrainerPSRExclave resourceFilePath]
+ -[SSRVoiceProfileRetrainerPSRExclave retrainerType]
+ -[SSRVoiceProfileRetrainerPSRExclave setAsset:]
+ -[SSRVoiceProfileRetrainerPSRExclave setBestTriggerScore:]
+ -[SSRVoiceProfileRetrainerPSRExclave setComparativeModels:]
+ -[SSRVoiceProfileRetrainerPSRExclave setConfigFilePath:]
+ -[SSRVoiceProfileRetrainerPSRExclave setConfigVersion:]
+ -[SSRVoiceProfileRetrainerPSRExclave setCtx:]
+ -[SSRVoiceProfileRetrainerPSRExclave setCurrUttLengthInMs:]
+ -[SSRVoiceProfileRetrainerPSRExclave setMaximumSpeakerVectors:]
+ -[SSRVoiceProfileRetrainerPSRExclave setProcessedAudioDurationMs:]
+ -[SSRVoiceProfileRetrainerPSRExclave setPsrModelFilePath:]
+ -[SSRVoiceProfileRetrainerPSRExclave setPsrScorer:]
+ -[SSRVoiceProfileRetrainerPSRExclave setQueue:]
+ -[SSRVoiceProfileRetrainerPSRExclave setResourceFilePath:]
+ -[SSRVoiceProfileRetrainerPSRExclave setSpIdType:]
+ -[SSRVoiceProfileRetrainerPSRExclave setSpeakerRecognitionConfig:]
+ -[SSRVoiceProfileRetrainerPSRExclave setSpeakerVector:]
+ -[SSRVoiceProfileRetrainerPSRExclave setSpeakerVectorSize:]
+ -[SSRVoiceProfileRetrainerPSRExclave setVoiceProfile:]
+ -[SSRVoiceProfileRetrainerPSRExclave spIdType]
+ -[SSRVoiceProfileRetrainerPSRExclave speakerRecognitionConfig]
+ -[SSRVoiceProfileRetrainerPSRExclave speakerVectorSize]
+ -[SSRVoiceProfileRetrainerPSRExclave speakerVector]
+ -[SSRVoiceProfileRetrainerPSRExclave voiceProfile]
+ -[SSRVoiceProfileRetrainerSATExclave .cxx_destruct]
+ -[SSRVoiceProfileRetrainerSATExclave _processAudioFile:]
+ -[SSRVoiceProfileRetrainerSATExclave _processSpeakerVector:withSize:withScorers:processedAudioDurationMs:]
+ -[SSRVoiceProfileRetrainerSATExclave asset]
+ -[SSRVoiceProfileRetrainerSATExclave bestTriggerScore]
+ -[SSRVoiceProfileRetrainerSATExclave comparativeModels]
+ -[SSRVoiceProfileRetrainerSATExclave configFilePath]
+ -[SSRVoiceProfileRetrainerSATExclave configVersion]
+ -[SSRVoiceProfileRetrainerSATExclave ctx]
+ -[SSRVoiceProfileRetrainerSATExclave currUttLengthInMs]
+ -[SSRVoiceProfileRetrainerSATExclave dealloc]
+ -[SSRVoiceProfileRetrainerSATExclave description]
+ -[SSRVoiceProfileRetrainerSATExclave maximumSpeakerVectors]
+ -[SSRVoiceProfileRetrainerSATExclave processedAudioDurationMs]
+ -[SSRVoiceProfileRetrainerSATExclave queue]
+ -[SSRVoiceProfileRetrainerSATExclave resourceFilePath]
+ -[SSRVoiceProfileRetrainerSATExclave satModelFilePath]
+ -[SSRVoiceProfileRetrainerSATExclave satScorer]
+ -[SSRVoiceProfileRetrainerSATExclave setAsset:]
+ -[SSRVoiceProfileRetrainerSATExclave setBestTriggerScore:]
+ -[SSRVoiceProfileRetrainerSATExclave setComparativeModels:]
+ -[SSRVoiceProfileRetrainerSATExclave setConfigFilePath:]
+ -[SSRVoiceProfileRetrainerSATExclave setConfigVersion:]
+ -[SSRVoiceProfileRetrainerSATExclave setCtx:]
+ -[SSRVoiceProfileRetrainerSATExclave setCurrUttLengthInMs:]
+ -[SSRVoiceProfileRetrainerSATExclave setMaximumSpeakerVectors:]
+ -[SSRVoiceProfileRetrainerSATExclave setProcessedAudioDurationMs:]
+ -[SSRVoiceProfileRetrainerSATExclave setQueue:]
+ -[SSRVoiceProfileRetrainerSATExclave setResourceFilePath:]
+ -[SSRVoiceProfileRetrainerSATExclave setSatModelFilePath:]
+ -[SSRVoiceProfileRetrainerSATExclave setSatScorer:]
+ -[SSRVoiceProfileRetrainerSATExclave setSpIdType:]
+ -[SSRVoiceProfileRetrainerSATExclave setSpeakerRecognitionConfig:]
+ -[SSRVoiceProfileRetrainerSATExclave setSpeakerVector:]
+ -[SSRVoiceProfileRetrainerSATExclave setSpeakerVectorSize:]
+ -[SSRVoiceProfileRetrainerSATExclave setVoiceProfile:]
+ -[SSRVoiceProfileRetrainerSATExclave spIdType]
+ -[SSRVoiceProfileRetrainerSATExclave speakerRecognitionConfig]
+ -[SSRVoiceProfileRetrainerSATExclave speakerVectorSize]
+ -[SSRVoiceProfileRetrainerSATExclave speakerVector]
+ -[SSRVoiceProfileRetrainerSATExclave voiceProfile]
+ GCC_except_table1045
+ GCC_except_table1070
+ GCC_except_table1126
+ GCC_except_table1130
+ GCC_except_table1148
+ GCC_except_table1233
+ GCC_except_table1234
+ GCC_except_table1236
+ GCC_except_table1254
+ GCC_except_table1258
+ GCC_except_table1267
+ GCC_except_table1334
+ GCC_except_table1340
+ GCC_except_table1347
+ GCC_except_table1376
+ GCC_except_table1389
+ GCC_except_table1434
+ GCC_except_table1449
+ GCC_except_table1464
+ GCC_except_table1470
+ GCC_except_table1539
+ GCC_except_table1648
+ GCC_except_table1663
+ GCC_except_table1675
+ GCC_except_table1685
+ GCC_except_table1690
+ GCC_except_table1707
+ GCC_except_table1711
+ GCC_except_table1720
+ GCC_except_table1735
+ GCC_except_table1810
+ GCC_except_table1814
+ GCC_except_table1853
+ GCC_except_table1888
+ GCC_except_table1953
+ GCC_except_table1964
+ GCC_except_table1973
+ GCC_except_table1984
+ GCC_except_table1994
+ GCC_except_table2011
+ GCC_except_table504
+ GCC_except_table508
+ GCC_except_table523
+ GCC_except_table537
+ GCC_except_table609
+ GCC_except_table617
+ GCC_except_table619
+ GCC_except_table623
+ GCC_except_table709
+ GCC_except_table791
+ GCC_except_table831
+ GCC_except_table838
+ GCC_except_table868
+ GCC_except_table871
+ GCC_except_table945
+ GCC_except_table946
+ GCC_except_table949
+ GCC_except_table952
+ GCC_except_table953
+ GCC_except_table954
+ GCC_except_table955
+ GCC_except_table956
+ GCC_except_table957
+ GCC_except_table958
+ GCC_except_table959
+ GCC_except_table960
+ GCC_except_table962
+ GCC_except_table963
+ GCC_except_table965
+ GCC_except_table968
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._asset
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._bestTriggerScore
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._comparativeModels
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._configFilePath
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._configVersion
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._ctx
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._currUttLengthInMs
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._maximumSpeakerVectors
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._novDetector
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._processedAudioDurationMs
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._psrModelFilePath
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._psrScorer
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._queue
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._resourceFilePath
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._spIdType
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._speakerRecognitionConfig
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._speakerVector
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._speakerVectorSize
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerPSRExclave._voiceProfile
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._asset
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._bestTriggerScore
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._comparativeModels
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._configFilePath
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._configVersion
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._ctx
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._currUttLengthInMs
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._maximumSpeakerVectors
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._novDetector
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._processedAudioDurationMs
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._queue
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._resourceFilePath
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._satModelFilePath
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._satScorer
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._spIdType
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._speakerRecognitionConfig
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._speakerVector
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._speakerVectorSize
+ OBJC_IVAR_$_SSRVoiceProfileRetrainerSATExclave._voiceProfile
+ _OBJC_CLASS_$_SSRVoiceProfileRetrainerPSRExclave
+ _OBJC_CLASS_$_SecureSpeakerRecognitionConfigDecoder
+ _OBJC_METACLASS_$_SSRVoiceProfileRetrainerPSRExclave
+ __OBJC_$_INSTANCE_METHODS_SSRVoiceProfileRetrainerPSRExclave
+ __OBJC_$_INSTANCE_VARIABLES_SSRVoiceProfileRetrainerPSRExclave
+ __OBJC_$_INSTANCE_VARIABLES_SSRVoiceProfileRetrainerSATExclave
+ __OBJC_$_PROP_LIST_SSRVoiceProfileRetrainerPSRExclave
+ __OBJC_CLASS_PROTOCOLS_$_SSRVoiceProfileRetrainerPSRExclave
+ __OBJC_CLASS_RO_$_SSRVoiceProfileRetrainerPSRExclave
+ __OBJC_METACLASS_RO_$_SSRVoiceProfileRetrainerPSRExclave
+ ___112-[SSRVoiceProfileRetrainerPSRExclave initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:]_block_invoke
+ ___112-[SSRVoiceProfileRetrainerSATExclave initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:]_block_invoke
+ ___56-[SSRVoiceProfileRetrainerPSRExclave _processAudioFile:]_block_invoke
+ ___56-[SSRVoiceProfileRetrainerSATExclave _processAudioFile:]_block_invoke
+ ___93-[SSRVoiceProfileRetrainerPSRExclave _logSpeakerConfusion:forProfileArray:withPrependString:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48r_e27_v40?0^v8Q16Q24"NSError"32l
+ ___block_descriptor_56_e8_32s40s48r_e31_v32?0"NSMutableArray"8Q16^B24l
+ _objc_msgSend$_fetchSecureAssetForCommunalDevice:
+ _objc_msgSend$_fetchSecureAssetForNonCommunalDevice:
+ _objc_msgSend$_processAudioFile:
+ _objc_msgSend$activateSecureSession:
+ _objc_msgSend$decode:
+ _objc_msgSend$initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:
+ _objc_msgSend$maxEnrollmentUtterances
+ _objc_msgSend$psrConfigString
+ _objc_msgSend$psrMemoryIndex
+ _objc_msgSend$satConfigString
+ _objc_msgSend$satMemoryIndex
+ _objc_msgSend$secureProfileModelFilePath
+ _objc_msgSend$supportsSystemDaemon
- -[SSRVTUITrainingManager fetchSpeechId]
- GCC_except_table1013
- GCC_except_table1069
- GCC_except_table1073
- GCC_except_table1091
- GCC_except_table1176
- GCC_except_table1177
- GCC_except_table1179
- GCC_except_table1197
- GCC_except_table1201
- GCC_except_table1210
- GCC_except_table1220
- GCC_except_table1226
- GCC_except_table1290
- GCC_except_table1319
- GCC_except_table1332
- GCC_except_table1362
- GCC_except_table1368
- GCC_except_table1437
- GCC_except_table1546
- GCC_except_table1561
- GCC_except_table1573
- GCC_except_table1583
- GCC_except_table1588
- GCC_except_table1605
- GCC_except_table1609
- GCC_except_table1618
- GCC_except_table1633
- GCC_except_table1708
- GCC_except_table1712
- GCC_except_table1751
- GCC_except_table1786
- GCC_except_table1851
- GCC_except_table1862
- GCC_except_table1871
- GCC_except_table1882
- GCC_except_table1892
- GCC_except_table1909
- GCC_except_table478
- GCC_except_table550
- GCC_except_table558
- GCC_except_table560
- GCC_except_table564
- GCC_except_table650
- GCC_except_table734
- GCC_except_table774
- GCC_except_table781
- GCC_except_table811
- GCC_except_table814
- GCC_except_table888
- GCC_except_table889
- GCC_except_table892
- GCC_except_table895
- GCC_except_table896
- GCC_except_table897
- GCC_except_table898
- GCC_except_table899
- GCC_except_table900
- GCC_except_table901
- GCC_except_table902
- GCC_except_table903
- GCC_except_table905
- GCC_except_table906
- GCC_except_table908
- GCC_except_table911
- GCC_except_table988
- ___39-[SSRVTUITrainingManager fetchSpeechId]_block_invoke
- ___block_descriptor_40_e8_32s_e31_v24?0"AFAccount"8"NSError"16l
- _objc_msgSend$setSpeechIdForDonationLogging:
CStrings:
+ "%s ERR: Cannot create SAT nd detector"
+ "%s Failed to initialize nov detector with error %s"
+ "%s PSRModel Retraining asset is nil! - Skipping"
+ "%s SATModel Retraining asset is nil! - Skipping"
+ "%s Secure Speaker detector config is nil"
+ "%s Secure Speaker detector config is nil - Skipping"
+ "%s Secure Speaker detector failed to create nov detector."
+ "%s Secure Speaker detector memory index is nil - Skipping"
+ "%s SecureAsset is nil"
+ "%s SpeakerVector: %{private}@ [dimension=%ld]"
+ "%s Successfully created nov detector"
+ "-[SSRVoiceProfileRetrainerFactory voiceRetrainersWithContext:]"
+ "-[SSRVoiceProfileRetrainerPSRExclave _logSpeakerConfusionWithExplicitScores:withImplicitScores:withPurgeUtterances:forProfile:forConfigVersion:]"
+ "-[SSRVoiceProfileRetrainerPSRExclave _processAudioFile:]"
+ "-[SSRVoiceProfileRetrainerPSRExclave _processAudioFile:]_block_invoke"
+ "-[SSRVoiceProfileRetrainerPSRExclave addUtterances:withPolicy:withCompletion:]"
+ "-[SSRVoiceProfileRetrainerPSRExclave dealloc]"
+ "-[SSRVoiceProfileRetrainerPSRExclave implicitTrainingRequired]"
+ "-[SSRVoiceProfileRetrainerPSRExclave initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:]"
+ "-[SSRVoiceProfileRetrainerPSRExclave initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:]_block_invoke"
+ "-[SSRVoiceProfileRetrainerPSRExclave needsRetrainingWithAudioFiles:]"
+ "-[SSRVoiceProfileRetrainerPSRExclave purgeConfusionInformationWithPolicy:]"
+ "-[SSRVoiceProfileRetrainerPSRExclave purgeLastSpeakerEmbedding]"
+ "-[SSRVoiceProfileRetrainerPSRExclave resetModelForRetraining]"
+ "-[SSRVoiceProfileRetrainerSATExclave _processAudioFile:]"
+ "-[SSRVoiceProfileRetrainerSATExclave _processAudioFile:]_block_invoke"
+ "-[SSRVoiceProfileRetrainerSATExclave addUtterances:withPolicy:withCompletion:]"
+ "-[SSRVoiceProfileRetrainerSATExclave dealloc]"
+ "-[SSRVoiceProfileRetrainerSATExclave implicitTrainingRequired]"
+ "-[SSRVoiceProfileRetrainerSATExclave initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:]"
+ "-[SSRVoiceProfileRetrainerSATExclave initWithVoiceRetrainingContext:secureAsset:secureSpeakerRecognitionConfig:]_block_invoke"
+ "-[SSRVoiceProfileRetrainerSATExclave needsRetrainingWithAudioFiles:]"
+ "-[SSRVoiceProfileRetrainerSATExclave purgeLastSpeakerEmbedding]"
+ "-[SSRVoiceProfileRetrainerSATExclave resetModelForRetraining]"
+ "@\"SSRVoiceProfileRetrainingContext\""
+ "@\"SecureSpeakerRecognitionConfig\""
+ "SSRVoiceProfileRetrainerPSRExclave"
+ "T@\"SSRVoiceProfileRetrainingContext\",&,V_ctx"
+ "T@\"SecureAsset\",&,V_asset"
+ "T@\"SecureSpeakerRecognitionConfig\",&,N,V_speakerRecognitionConfig"
+ "TQ,N,V_maximumSpeakerVectors"
+ "Tf,N,V_bestTriggerScore"
+ "_ctx"
+ "_novDetector"
+ "_processAudioFile:"
+ "_speakerRecognitionConfig"
+ "activateSecureSession:"
+ "bestTriggerScore"
+ "com.apple.corespeech.speakerretrain.secure.psrq"
+ "com.apple.corespeech.speakerretrain.secure.satq"
+ "ctx"
+ "decode:"
+ "maximumSpeakerVectors"
+ "psrConfigString"
+ "psrMemoryIndex"
+ "satConfigString"
+ "satMemoryIndex"
+ "setBestTriggerScore:"
+ "setCtx:"
+ "setMaximumSpeakerVectors:"
+ "setSpeakerRecognitionConfig:"
+ "speakerRecognitionConfig"
+ "supportsSystemDaemon"
+ "{%@:%@:%@:%@}"
- "-[SSRVTUITrainingManager fetchSpeechId]"
- "-[SSRVTUITrainingManager fetchSpeechId]_block_invoke"
- "fetchSpeechId"
- "setSpeechIdForDonationLogging:"
```
