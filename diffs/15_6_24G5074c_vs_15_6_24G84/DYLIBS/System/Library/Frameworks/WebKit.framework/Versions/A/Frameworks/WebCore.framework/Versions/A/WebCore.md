## WebCore

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebCore.framework/Versions/A/WebCore`

```diff

-621.3.8.0.0
-  __TEXT.__text: 0x2f19ba0
+621.3.11.11.3
+  __TEXT.__text: 0x2f1a1ac
   __TEXT.__auth_stubs: 0xd750
   __TEXT.__objc_methlist: 0x3fd0
   __TEXT.__const: 0x1b1f90
-  __TEXT.__gcc_except_tab: 0x278c4
+  __TEXT.__gcc_except_tab: 0x278d8
   __TEXT.__swift5_typeref: 0xea
-  __TEXT.__cstring: 0x2b71da
+  __TEXT.__cstring: 0x2b7a90
   __TEXT.__constg_swiftt: 0x3e8
   __TEXT.__swift5_fieldmd: 0x2a0
   __TEXT.__swift5_reflstr: 0xa4

   __DATA_CONST.__jsc_ops: 0x260
   __DATA_CONST.__objc_arraydata: 0xa8
   __AUTH_CONST.__auth_got: 0x6bc8
-  __AUTH_CONST.__const: 0x25f590
+  __AUTH_CONST.__const: 0x25f5e0
   __AUTH_CONST.__cfstring: 0x9ea0
   __AUTH_CONST.__objc_const: 0x7a98
   __AUTH_CONST.__objc_intobj: 0x330

   __DATA_DIRTY.__objc_data: 0x13d8
   __DATA_DIRTY.__data: 0x5c98
   __DATA_DIRTY.__common: 0xa2c1
-  __DATA_DIRTY.__bss: 0xaf18
+  __DATA_DIRTY.__bss: 0xaf28
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 125796
-  Symbols:   157633
-  CStrings:  33251
+  Functions: 125801
+  Symbols:   157638
+  CStrings:  33253
 
Symbols:
+ __ZN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEE4callEv
+ __ZN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEED1Ev
+ __ZN3WTF9HashTableIdNS_12KeyValuePairIdNS_17ThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderENS_15NoTaggingTraitsIS4_EEEEEENS_24KeyValuePairKeyExtractorIS8_EENS_11DefaultHashIdEENS_7HashMapIdS7_SC_NS_10HashTraitsIdEENSE_IS7_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EE18KeyValuePairTraitsESF_LSI_1EE6rehashEjPS8_
+ __ZN7WebCore15ScrollerPairMac23updateScrollbarPaintersEv
+ __ZNK3WTF29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvv
+ __ZTVN3WTF6Detail15CallableWrapperIZNKS_29ThreadSafeWeakPtrControlBlock11strongDerefIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EEEvvEUlvE_vJEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZNKS_47ThreadSafeRefCountedAndCanMakeThreadSafeWeakPtrIN7WebCore18HRTFDatabaseLoaderELNS_17DestructionThreadE1EE5derefEvEUlvE_vJEEE
- __ZGVZN7WebCoreL9loaderMapEvE9loaderMap
- __ZN3WTF7HashMapIdPN7WebCore18HRTFDatabaseLoaderENS_11DefaultHashIdEENS_10HashTraitsIdEENS6_IS3_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0EE3addIS3_EENS_18HashTableAddResultINS_17HashTableIteratorINS_9HashTableIdNS_12KeyValuePairIdS3_EENS_24KeyValuePairKeyExtractorISH_EES5_NSB_18KeyValuePairTraitsES7_LSA_0EEEdSH_SJ_S5_SK_S7_EEEEOdOT_
- __ZN3WTF9HashTableIdNS_12KeyValuePairIdPN7WebCore18HRTFDatabaseLoaderEEENS_24KeyValuePairKeyExtractorIS5_EENS_11DefaultHashIdEENS_7HashMapIdS4_S9_NS_10HashTraitsIdEENSB_IS4_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0EE18KeyValuePairTraitsESC_LSF_0EE6rehashEjPS5_
- __ZN7WebCore18HRTFDatabaseLoader18loadAsynchronouslyEv
- __ZN7WebCore37ScrollingTreeScrollingNodeDelegateMac23updateScrollbarPaintersEv
- __ZZN7WebCoreL9loaderMapEvE9loaderMap
CStrings:
+ "void WTF::HashTable<double, WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, WTF::DefaultHash<double>, WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::HashTraits<double>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = double, Value = WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, HashFunctions = WTF::DefaultHash<double>, Traits = WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<double>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::HashMapTranslatorAdapter<WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::IdentityHashTranslator<WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::DefaultHash<double>>>, T = double]"
+ "void WTF::HashTable<double, WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, WTF::DefaultHash<double>, WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::HashTraits<double>, WTF::ShouldValidateKey::Yes>::checkKey(const T &) [Key = double, Value = WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>>, HashFunctions = WTF::DefaultHash<double>, Traits = WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<double>, shouldValidateKey = WTF::ShouldValidateKey::Yes, HashTranslator = WTF::IdentityHashTranslator<WTF::HashMap<double, WTF::ThreadSafeWeakPtr<WebCore::HRTFDatabaseLoader>>::KeyValuePairTraits, WTF::DefaultHash<double>>, T = double]"
```
