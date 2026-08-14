## VoiceTrigger

> `/System/Library/PrivateFrameworks/VoiceTrigger.framework/Versions/A/VoiceTrigger`

```diff

-3404.21.1.0.0
-  __TEXT.__text: 0xa2b0c
-  __TEXT.__auth_stubs: 0xea0
+3405.2.1.0.0
+  __TEXT.__text: 0xa2a68
+  __TEXT.__auth_stubs: 0xfa0
   __TEXT.__objc_methlist: 0x87c
-  __TEXT.__const: 0x124c
-  __TEXT.__cstring: 0xc618
+  __TEXT.__const: 0x1291
+  __TEXT.__cstring: 0xcdb7
   __TEXT.__swift5_typeref: 0x102
   __TEXT.__constg_swiftt: 0x104
   __TEXT.__swift5_reflstr: 0xad

   __TEXT.__oslogstring: 0x13cc
   __TEXT.__swift5_assocty: 0x60
   __TEXT.__swift5_proto: 0x18
-  __TEXT.__gcc_except_tab: 0x6a58
+  __TEXT.__gcc_except_tab: 0x67a4
   __TEXT.__ustring: 0xb4
   __TEXT.__dlopen_cstrs: 0xcc
-  __TEXT.__unwind_info: 0x1ed0
+  __TEXT.__unwind_info: 0x1f50
   __TEXT.__eh_frame: 0x148
   __TEXT.__objc_classname: 0x9c
   __TEXT.__objc_methname: 0x1fc8

   __DATA_CONST.__objc_selrefs: 0x8a8
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__objc_arraydata: 0x1d0
-  __AUTH_CONST.__auth_got: 0x768
-  __AUTH_CONST.__const: 0x36e0
+  __AUTH_CONST.__auth_got: 0x7e8
+  __AUTH_CONST.__const: 0x3840
   __AUTH_CONST.__cfstring: 0x1960
   __AUTH_CONST.__objc_const: 0x5f8
   __AUTH_CONST.__objc_intobj: 0x48

   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
+  - /System/Library/PrivateFrameworks/AggregateDictionary.framework/Versions/A/AggregateDictionary
+  - /System/Library/PrivateFrameworks/AppSupport.framework/Versions/A/AppSupport
   - /System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices
+  - /System/Library/PrivateFrameworks/MobileAsset.framework/Versions/A/MobileAsset
   - /System/Library/PrivateFrameworks/RemoteServiceDiscovery.framework/Versions/A/RemoteServiceDiscovery
   - /System/Library/PrivateFrameworks/RemoteXPC.framework/Versions/A/RemoteXPC
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1833
-  Symbols:   3427
-  CStrings:  1581
+  Functions: 1872
+  Symbols:   3496
+  CStrings:  1610
 
Symbols:
+ GCC_except_table1675
+ GCC_except_table1689
+ GCC_except_table1693
+ GCC_except_table1705
+ GCC_except_table1707
+ _BNNSGraphContextDestroy_v2
+ _BNNSGraphContextExecute_v2
+ _BNNSGraphContextMake
+ _BNNSGraphContextSetMessageLogCallback
+ _BNNSGraphContextSetMessageLogMask
+ _BNNSGraphContextSetWeights
+ _BNNSGraphGetArgumentPosition
+ _BNNSGraphGetFunctionCount
+ _BNNSGraphGetFunctionNames
+ _BNNSGraphGetInputCount
+ _BNNSGraphGetInputNames_v2
+ _BNNSGraphGetOutputCount
+ _BNNSGraphGetOutputNames_v2
+ _BNNSGraphGetTensorDescriptor_v2
+ _BNNSNDArrayGetDataSize
+ __ZN19NBNNSIRDistribution14setWeightsFileERK7NString
+ __ZN19NBNNSIRDistribution20determineStateWiringEPKvPKcRK7NString
+ __ZN19NBNNSIRDistribution4readERK7NString
+ __ZN19NBNNSIRDistribution5resetEv
+ __ZN19NBNNSIRDistributionC1Ev
+ __ZN19NBNNSIRDistributionC2Ev
+ __ZN19NBNNSIRDistributionD0Ev
+ __ZN19NBNNSIRDistributionD1Ev
+ __ZN19NBNNSIRDistributionD2Ev
+ __ZN6NArrayI21bnns_graph_argument_tE6resizeERKj
+ __ZN6NArrayI21bnns_graph_argument_tE9fromArrayEPKS0_RKj
+ __ZN6NArrayI21bnns_graph_argument_tED0Ev
+ __ZN6NArrayI21bnns_graph_argument_tED1Ev
+ __ZN6NArrayI21bnns_graph_argument_tEaSERKS1_
+ __ZN6NArrayImE6resizeERKj
+ __ZN6NArrayImE9fromArrayEPKmRKj
+ __ZN6NArrayImED0Ev
+ __ZN6NArrayImED1Ev
+ __ZN6NArrayImEaSERKS0_
+ __ZNK19NBNNSIRDistribution10resetStateEPv
+ __ZNK19NBNNSIRDistribution13numComponentsEv
+ __ZNK19NBNNSIRDistribution14allocateStatePEv
+ __ZNK19NBNNSIRDistribution14componentScoreERKjRK6NArrayIfE
+ __ZNK19NBNNSIRDistribution15deallocateStateEPv
+ __ZNK19NBNNSIRDistribution15scoreCacheTypesEv
+ __ZNK19NBNNSIRDistribution15scoreUsingCacheERKjRK6NArrayIbERKS2_IfE
+ __ZNK19NBNNSIRDistribution16firstComponentIdERKj
+ __ZNK19NBNNSIRDistribution16setComponentMaskERKjR6NArrayIbE
+ __ZNK19NBNNSIRDistribution17fixedPointScalesPEv
+ __ZNK19NBNNSIRDistribution21posteriorWeightedMeanERKjRK6NArrayIfERS3_
+ __ZNK19NBNNSIRDistribution24flipStateOutputsToInputsEPv
+ __ZNK19NBNNSIRDistribution4sizeEv
+ __ZNK19NBNNSIRDistribution5dimenEv
+ __ZNK19NBNNSIRDistribution5scoreERKjRK6NArrayIfE
+ __ZNK19NBNNSIRDistribution7baseGMMEv
+ __ZNK19NBNNSIRDistribution8scoreAllERK6NArrayIfERS1_Pv
+ __ZNK19NBNNSIRDistribution9frameSizeEv
+ __ZNK19NBNNSIRDistribution9numFramesEv
+ __ZTI19NBNNSIRDistribution
+ __ZTI6NArrayI21bnns_graph_argument_tE
+ __ZTI6NArrayImE
+ __ZTS19NBNNSIRDistribution
+ __ZTS6NArrayI21bnns_graph_argument_tE
+ __ZTS6NArrayImE
+ __ZTV19NBNNSIRDistribution
+ __ZTV6NArrayI21bnns_graph_argument_tE
+ __ZTV6NArrayImE
+ __ZZNK19NBNNSIRDistribution8scoreAllERK6NArrayIfERS1_PvEN3$_08__invokeE21BNNSGraphMessageLevelPKcS9_P24bnns_user_message_data_t
+ _getpagesize
CStrings:
+ "-DAPPLEACCEL -DNOZLIB -DNO_BOUNDS_CHECK -DNLOGOFF -DAPPLEACCEL -O3 -DACCELERATE_NEW_LAPACK -DACCELERATE_LAPACK_ILP64 -DUSE_BNNSIR -Wno-vla-cxx-extension -Wno-unknown-warning-option -Wno-deprecated-declarations  -Wno-error=deprecated-declarations -Wno-error=#warnings -Wno-error=nonnull -Wno-error=objc-designated-initializers -Wno-error=deprecated-implementations -Wno-error=documentation -Wno-error=unused-command-line-argument -arch undefined_arch"
+ "BNNSGraphGetInputNames failed"
+ "BNNSGraphGetOutputNames failed"
+ "BNNSGraphGetTensorDescriptor failed"
+ "BNNSIR Sizes >= 2^31"
+ "Currently only support numinputs=numoutputs"
+ "Invalid BNNSIR"
+ "NBNNSIRDistribution::NBNNSIRDistribution() - cannot determine page size for allocation"
+ "NBNNSIRDistribution::baseGMM() - not supported for this distribution type"
+ "NBNNSIRDistribution::componentScore() - not supported for this distribution type"
+ "NBNNSIRDistribution::firstComponentId() - not supported for this distribution type"
+ "NBNNSIRDistribution::fixedPointScalesP() - not supported for this distribution type"
+ "NBNNSIRDistribution::numComponents() - not supported for this distribution type"
+ "NBNNSIRDistribution::posteriorWeightedMean() - not supported for this distribution type"
+ "NBNNSIRDistribution::read() - %s %s"
+ "NBNNSIRDistribution::read() - invalid bnnsir header or wrong version"
+ "NBNNSIRDistribution::read() - missing cookie in %s"
+ "NBNNSIRDistribution::score not implemented yet() - not supported for this distribution type"
+ "NBNNSIRDistribution::scoreAll() - BNNSGraphContextSetWeights fails with error %d"
+ "NBNNSIRDistribution::scoreAll() - BNNSGraphExecute fails with error \"%s\" (%d)"
+ "NBNNSIRDistribution::scoreAll() - BNNSIR not loaded"
+ "NBNNSIRDistribution::scoreAll() - input vector has wrong size (%d, should be %d)"
+ "NBNNSIRDistribution::scoreAll() - output (dist) vector has wrong size (%d, should be %d)"
+ "NBNNSIRDistribution::scoreAll() - state uninitialized"
+ "NBNNSIRDistribution::scoreUsingCache() - not supported for this distribution type"
+ "NBNNSIRDistribution::setComponentMask() - not supported for this distribution type"
+ "Novalib gitrelno_unavailable Release Thu Apr  3 23:39:37 2025"
+ "Thu Apr  3 23:39:37 2025"
+ "Thu Apr  3 23:39:37 PDT 2025"
+ "Unknown"
+ "_out"
+ "input dimension >2 or unsupported layout/stride"
+ "input not float32 type"
+ "more than one external input identified"
+ "more than one external output identified"
+ "no external input identified"
+ "no external output identified"
+ "output dimension >2 or unsupported layout/stride"
+ "output not float32 type"
+ "output tensor wired to a second input"
+ "tensor arg position already set"
+ "tensor has zero size"
- "\n#IMPOSTOR END\n\n"
- "# DNNLb v1.00\n\n\n"
- "#IMPOSTOR v001\n\n"
- "-DAPPLEACCEL -DNOZLIB -DNO_BOUNDS_CHECK -DNLOGOFF -DAPPLEACCEL -O3 -DACCELERATE_NEW_LAPACK -DACCELERATE_LAPACK_ILP64  -Wno-error=deprecated-declarations -Wno-error=#warnings -Wno-error=nonnull -Wno-error=objc-designated-initializers -Wno-error=deprecated-implementations -Wno-error=documentation -Wno-error=unused-command-line-argument -arch undefined_arch"
- "ALL"
- "INVAR"
- "INVSD"
- "LOG"
- "Novalib gitrelno_unavailable Release Tue Mar 18 03:05:58 2025"
- "Tue Mar 18 03:05:58 2025"
- "Tue Mar 18 03:05:58 PDT 2025"
- "]"
- "read_gaussian_models() - BNNSIR format in %s not supported"
```
