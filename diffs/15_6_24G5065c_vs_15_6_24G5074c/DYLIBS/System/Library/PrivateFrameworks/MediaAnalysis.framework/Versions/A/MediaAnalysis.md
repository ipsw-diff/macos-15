## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/Versions/A/MediaAnalysis`

```diff

-325.3.1.0.0
-  __TEXT.__text: 0x3abbf0
+325.4.1.0.0
+  __TEXT.__text: 0x3abcfc
   __TEXT.__auth_stubs: 0x30d0
   __TEXT.__objc_methlist: 0x1a698
   __TEXT.__const: 0x14640
-  __TEXT.__gcc_except_tab: 0x55084
+  __TEXT.__gcc_except_tab: 0x5509c
   __TEXT.__cstring: 0x18d05
-  __TEXT.__oslogstring: 0x23e8b
+  __TEXT.__oslogstring: 0x23eeb
   __TEXT.__dlopen_cstrs: 0x3e7
   __TEXT.__ustring: 0x40
   __TEXT.__swift5_typeref: 0x94

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 12183
+  Functions: 12184
   Symbols:   27728
-  CStrings:  16285
+  CStrings:  16286
 
Functions:
~ +[MADComputeSyncPayloadResults fullAnalysisResultsFromAnalysisProto:asset:payloadData:] : 1348 -> 1500
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB8ne190102EPS4_ : 112 -> 120
+ +[MADComputeSyncPayloadResults fullAnalysisResultsFromAnalysisProto:asset:payloadData:].cold.1
CStrings:
+ "[ComputeSyncPayload][%@] Full analysis results from compute sync has future version (v%d)"
```
