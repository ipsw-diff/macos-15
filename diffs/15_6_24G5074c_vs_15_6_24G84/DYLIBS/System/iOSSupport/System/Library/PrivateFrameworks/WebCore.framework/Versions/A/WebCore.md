## WebCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/WebCore.framework/Versions/A/WebCore`

```diff

-621.3.8.0.0
-  __TEXT.__text: 0x2bcdcd4
+621.3.11.11.3
+  __TEXT.__text: 0x2bcead4
   __TEXT.__auth_stubs: 0xc410
   __TEXT.__objc_methlist: 0x4c7c
-  __TEXT.__const: 0x192378
+  __TEXT.__const: 0x192368
   __TEXT.__gcc_except_tab: 0x196c0
   __TEXT.__swift5_typeref: 0xea
-  __TEXT.__cstring: 0x294576
+  __TEXT.__cstring: 0x294e2c
   __TEXT.__constg_swiftt: 0x3e8
   __TEXT.__swift5_fieldmd: 0x2a0
   __TEXT.__swift5_reflstr: 0xa4

   __DATA_CONST.__jsc_ops: 0x470
   __DATA_CONST.__objc_arraydata: 0x90
   __AUTH_CONST.__auth_got: 0x6228
-  __AUTH_CONST.__const: 0x228e38
+  __AUTH_CONST.__const: 0x228e88
   __AUTH_CONST.__cfstring: 0x65e0
   __AUTH_CONST.__objc_const: 0x7540
   __AUTH_CONST.__objc_arrayobj: 0x90

   __DATA_DIRTY.__objc_data: 0xd70
   __DATA_DIRTY.__data: 0x48b8
   __DATA_DIRTY.__common: 0xa129
-  __DATA_DIRTY.__bss: 0x76e8
+  __DATA_DIRTY.__bss: 0x76f8
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 102029
-  Symbols:   129190
-  CStrings:  29446
+  Functions: 102034
+  Symbols:   129195
+  CStrings:  29448
 
Symbols:
+ __ZN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEED1Ev
+ __ZN3WTF9HashTableIdNS_12KeyValuePairIdNS_17ThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderENS_15NoTaggingTraitsIS4_EEEEEENS_24KeyValuePairKeyExtractorIS8_EENS_11DefaultHashIdEENS_7HashMapIdS7_SC_NS_10HashTraitsIdEENSE_IS7_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESF_LSI_1EE6rehashEjPS8_
+ __ZNK3WTF29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvv
+ __ZTVN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEEE
- __ZGVZN7WebCoreL9loaderMapEvE9loaderMap
- __ZN3WTF7HashMapIdPN7WebCore18HRTFDatabaseLoaderENS_11DefaultHashIdEENS_10HashTraitsIdEENS6_IS3_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0EE3addIS3_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIdNS_12KeyValuePairIdS3_EENS_24KeyValuePairKeyExtractorISH_EES5_NSB_18KeyValuePairTraitsES7_LSA_0EEEdSH_SJ_S5_SK_S7_EEEEOdOT_
- __ZN3WTF9HashTableIdNS_12KeyValuePairIdPN7WebCore18HRTFDatabaseLoaderEEENS_24KeyValuePairKeyExtractorIS5_EENS_11DefaultHashIdEENS_7HashMapIdS4_S9_NS_10HashTraitsIdEENSB_IS4_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0EE18KeyValuePairTraitsESC_LSF_0EE6rehashEjPS5_
- __ZN7WebCore18HRTFDatabaseLoader18loadAsynchronouslyEv
- __ZZN7WebCoreL9loaderMapEvE9loaderMap
CStrings:
+ "void WTF::HashTable<double, WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, WTF::DefaultHash<double>, WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::HashTraits<double>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = double, Value = WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, HashFunctions = WTF::DefaultHash<double>, Traits = WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<double>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::HashMapTranslatorAdapter<WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::IdentityHashTranslator<WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::DefaultHash<double>>>, T = double]"
+ "void WTF::HashTable<double, WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, WTF::DefaultHash<double>, WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::HashTraits<double>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = double, Value = WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, HashFunctions = WTF::DefaultHash<double>, Traits = WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<double>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::IdentityHashTranslator<WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::DefaultHash<double>>, T = double]"
```
