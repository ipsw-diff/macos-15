## SpotlightEmbedding

> `/System/Library/PrivateFrameworks/SpotlightEmbedding.framework/Versions/A/SpotlightEmbedding`

```diff

-2333.41.1.3.0
-  __TEXT.__text: 0x4738
-  __TEXT.__auth_stubs: 0x240
-  __TEXT.__objc_methlist: 0x2bc
-  __TEXT.__const: 0xa8
-  __TEXT.__cstring: 0x3b6
-  __TEXT.__gcc_except_tab: 0x14c
-  __TEXT.__oslogstring: 0x446
-  __TEXT.__unwind_info: 0x168
-  __TEXT.__objc_classname: 0x4d
-  __TEXT.__objc_methname: 0xa14
-  __TEXT.__objc_methtype: 0x1b2
-  __TEXT.__objc_stubs: 0xb20
-  __DATA_CONST.__got: 0xc0
-  __DATA_CONST.__const: 0x68
-  __DATA_CONST.__objc_classlist: 0x20
+2333.47.1.0.0
+  __TEXT.__text: 0x5d5c
+  __TEXT.__auth_stubs: 0x2f0
+  __TEXT.__objc_methlist: 0x36c
+  __TEXT.__const: 0xc8
+  __TEXT.__cstring: 0x4c5
+  __TEXT.__gcc_except_tab: 0x230
+  __TEXT.__oslogstring: 0x5bd
+  __TEXT.__unwind_info: 0x198
+  __TEXT.__objc_classname: 0x67
+  __TEXT.__objc_methname: 0xc96
+  __TEXT.__objc_methtype: 0x1c7
+  __TEXT.__objc_stubs: 0xec0
+  __DATA_CONST.__got: 0x110
+  __DATA_CONST.__const: 0x88
+  __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x350
-  __DATA_CONST.__objc_superrefs: 0x20
-  __AUTH_CONST.__auth_got: 0x130
-  __AUTH_CONST.__const: 0x280
-  __AUTH_CONST.__cfstring: 0x320
-  __AUTH_CONST.__objc_const: 0x520
+  __DATA_CONST.__objc_selrefs: 0x448
+  __DATA_CONST.__objc_superrefs: 0x28
+  __DATA_CONST.__objc_arraydata: 0x10
+  __AUTH_CONST.__auth_got: 0x188
+  __AUTH_CONST.__const: 0x2c0
+  __AUTH_CONST.__cfstring: 0x480
+  __AUTH_CONST.__objc_const: 0x610
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH.__objc_data: 0x140
-  __DATA.__objc_ivar: 0x3c
-  __DATA.__bss: 0x50
+  __AUTH_CONST.__objc_doubleobj: 0x10
+  __AUTH_CONST.__objc_dictobj: 0x28
+  __AUTH_CONST.__objc_floatobj: 0x10
+  __AUTH.__objc_data: 0x190
+  __DATA.__objc_ivar: 0x44
+  __DATA.__bss: 0x70
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreSpotlight.framework/Versions/A/CoreSpotlight
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /System/Library/PrivateFrameworks/MediaAnalysisServices.framework/Versions/A/MediaAnalysisServices
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 94
-  Symbols:   315
-  CStrings:  221
+  - /usr/lib/libtailspin.dylib
+  Functions: 112
+  Symbols:   398
+  CStrings:  279
 
Symbols:
+ +[SPEmbeddingTailspinDumper lockFilePath]
+ +[SPEmbeddingTailspinDumper log]
+ +[SPEmbeddingTailspinDumper sharedInstance]
+ +[SPEmbeddingTailspinDumper tailspinDirectory]
+ +[SPEmbeddingTailspinDumper tailspinPrefix]
+ -[SPEmbeddingTailspinDumper .cxx_destruct]
+ -[SPEmbeddingTailspinDumper canDump]
+ -[SPEmbeddingTailspinDumper cleanupOldDumps]
+ -[SPEmbeddingTailspinDumper dumpTailspinSync:]
+ -[SPEmbeddingTailspinDumper dump]
+ -[SPEmbeddingTailspinDumper init]
+ -[SPEmbeddingTailspinDumper latestDumpDate]
+ -[SPEmbeddingTailspinDumper setLatestDumpDate:]
+ GCC_except_table13
+ OBJC_IVAR_$_SPEmbeddingTailspinDumper._dumpQueue
+ OBJC_IVAR_$_SPEmbeddingTailspinDumper._latestDumpDate
+ _CFPreferencesGetAppBooleanValue
+ _NSFileModificationDate
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_CLASS_$_NSConstantDoubleNumber
+ _OBJC_CLASS_$_NSConstantFloatNumber
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSFileManager
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_SPEmbeddingTailspinDumper
+ _OBJC_METACLASS_$_SPEmbeddingTailspinDumper
+ _TSPDumpOptions_Symbolicate
+ __OBJC_$_CLASS_METHODS_SPEmbeddingTailspinDumper
+ __OBJC_$_INSTANCE_METHODS_SPEmbeddingTailspinDumper
+ __OBJC_$_INSTANCE_VARIABLES_SPEmbeddingTailspinDumper
+ __OBJC_$_PROP_LIST_SPEmbeddingTailspinDumper
+ __OBJC_CLASS_RO_$_SPEmbeddingTailspinDumper
+ __OBJC_METACLASS_RO_$_SPEmbeddingTailspinDumper
+ ___32+[SPEmbeddingTailspinDumper log]_block_invoke
+ ___33-[SPEmbeddingTailspinDumper dump]_block_invoke
+ ___43+[SPEmbeddingTailspinDumper sharedInstance]_block_invoke
+ ___44-[SPEmbeddingTailspinDumper cleanupOldDumps]_block_invoke
+ ___block_descriptor_32_e39_q24?0"NSDictionary"8"NSDictionary"16l
+ ___kCFBooleanFalse
+ __block_literal_global
+ _close
+ _flock
+ _isAppleInternalInstall
+ _kCFPreferencesAnyApplication
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_exception_rethrow
+ _objc_msgSend$array
+ _objc_msgSend$attributesOfItemAtPath:error:
+ _objc_msgSend$canDump
+ _objc_msgSend$cleanupOldDumps
+ _objc_msgSend$compare:
+ _objc_msgSend$contentsOfDirectoryAtPath:error:
+ _objc_msgSend$createDirectoryAtPath:withIntermediateDirectories:attributes:error:
+ _objc_msgSend$currentLocale
+ _objc_msgSend$date
+ _objc_msgSend$defaultManager
+ _objc_msgSend$dump
+ _objc_msgSend$dumpTailspinSync:
+ _objc_msgSend$fileExistsAtPath:
+ _objc_msgSend$fileSystemRepresentation
+ _objc_msgSend$hasSuffix:
+ _objc_msgSend$languageCode
+ _objc_msgSend$lockFilePath
+ _objc_msgSend$objectForKeyedSubscript:
+ _objc_msgSend$processInfo
+ _objc_msgSend$processName
+ _objc_msgSend$removeItemAtPath:error:
+ _objc_msgSend$setDateFormat:
+ _objc_msgSend$sortUsingComparator:
+ _objc_msgSend$stringByAppendingPathComponent:
+ _objc_msgSend$stringByExpandingTildeInPath
+ _objc_msgSend$stringFromDate:
+ _objc_msgSend$tailspinDirectory
+ _objc_msgSend$tailspinPrefix
+ _objc_msgSend$timeIntervalSinceDate:
+ _objc_terminate
+ _open
+ _tailspin_dump_output_with_options_sync
+ _unlink
+ sharedInstance.sharedInstance
CStrings:
+ "%@%@%@"
+ "%@_"
+ ".tailspin"
+ "@\"NSDate\""
+ "A recent tailspin exists. Skipping dump."
+ "B20@0:8i16"
+ "Failed to capture tailspin at %@"
+ "Failed to create tailsipin directory: %@"
+ "Failed to open tailspin file at %@"
+ "Failed to remove old tailspin file at %@: %@"
+ "Failed to remove outdated dump file at %@: %@"
+ "SPEmbeddingTailspinDumper"
+ "SpotlightEmbeddingGenTimeoutTailspin"
+ "T@\"NSDate\",&,N,V_latestDumpDate"
+ "Tailspin"
+ "Tailspin captured at %@"
+ "Unable to acquire tailspin lock on file %@"
+ "Unable to open tailspin lock file at %@"
+ "[qid=%ld] Result marked as safe by CLIP Safety Model with confidence score : %f (threshold:%f language:%@)"
+ "[qid=%ld] Result marked as unsafe by CLIP Safety Models with confidence score : %f (threshold:%f language:%@)"
+ "_dumpQueue"
+ "_latestDumpDate"
+ "array"
+ "attributesOfItemAtPath:error:"
+ "canDump"
+ "cleanupOldDumps"
+ "com.apple.SpotlightEmbedding.tailspinDump"
+ "compare:"
+ "contentsOfDirectoryAtPath:error:"
+ "createDirectoryAtPath:withIntermediateDirectories:attributes:error:"
+ "currentLocale"
+ "date"
+ "defaultManager"
+ "dump"
+ "dumpTailspinSync:"
+ "fileExistsAtPath:"
+ "fileSystemRepresentation"
+ "hasSuffix:"
+ "languageCode"
+ "latestDumpDate"
+ "lockFilePath"
+ "objectForKeyedSubscript:"
+ "path"
+ "processInfo"
+ "processName"
+ "q24@?0@\"NSDictionary\"8@\"NSDictionary\"16"
+ "removeItemAtPath:error:"
+ "setDateFormat:"
+ "setLatestDumpDate:"
+ "sortUsingComparator:"
+ "stringByAppendingPathComponent:"
+ "stringByExpandingTildeInPath"
+ "stringFromDate:"
+ "tailspin.lock"
+ "tailspinDirectory"
+ "tailspinPrefix"
+ "timeIntervalSinceDate:"
+ "yyyyMMdd_HHmmss"
+ "zh"
+ "~/Library/Logs/CrashReporter/DiagnosticLogs/Search"
- "[qid=%ld] Result marked as safe by CLIP Safety Model with confidence score : %f"
- "[qid=%ld] Result marked as unsafe by CLIP Safety Model with confidence score : %f"
```
