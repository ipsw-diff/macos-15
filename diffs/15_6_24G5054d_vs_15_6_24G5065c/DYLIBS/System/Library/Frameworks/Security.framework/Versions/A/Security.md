## Security

> `/System/Library/Frameworks/Security.framework/Versions/A/Security`

```diff

-61439.140.8.0.0
-  __TEXT.__text: 0x344c14
+61439.140.10.0.0
+  __TEXT.__text: 0x343d18
   __TEXT.__auth_stubs: 0x4c80
   __TEXT.__objc_methlist: 0x6008
   __TEXT.__const: 0x16685
   __TEXT.__dlopen_cstrs: 0x2e7
   __TEXT.__cstring: 0x28900
-  __TEXT.__oslogstring: 0x2055c
-  __TEXT.__gcc_except_tab: 0x2fc38
+  __TEXT.__oslogstring: 0x2058a
+  __TEXT.__gcc_except_tab: 0x2faac
   __TEXT.__ustring: 0x40a
   __TEXT.__dof_codesign: 0x2617
   __TEXT.__dof_syspolicy: 0xc27

   - /usr/lib/libz.1.dylib
   Functions: 12354
   Symbols:   25350
-  CStrings:  12334
+  CStrings:  12335
 
Functions:
~ __ZN8Security14SecPointerBaseC2EPNS_11SecCFObjectE : 108 -> 132
~ __ZN8Security11SecCFObject6handleEb : 120 -> 140
~ __ZN8Security14SecPointerBaseD2Ev : 88 -> 104
~ __ZN8Security12KeychainCore8KeychainC2ERKNS_10CssmClient2DbE : 784 -> 740
~ __ZN8Security14SecPointerBaseC2ERKS0_ : 104 -> 128
~ __ZN8Security12KeychainCore12KeychainImpl18defaultCredentialsEv : 4852 -> 4800
~ __ZN8Security12KeychainCore12KCCursorImpl4nextERNS0_4ItemE : 7628 -> 7656
~ __ZN8Security12KeychainCore12KeychainImpl4itemEjRNS_10CssmClient14DbUniqueRecordE : 1404 -> 1360
~ __ZN8Security14SecPointerBaseaSERKS0_ : 144 -> 168
~ _SecPolicySearchCreate : 744 -> 692
~ __ZN8Security14SecPointerBase6assignEPNS_11SecCFObjectE : 152 -> 188
~ __ZN8Security12KeychainCore5Trust8evaluateEb : 20420 -> 21084
~ __ZN8Security12KeychainCore12CCallbackMgr7consumeEjjRKNS_8CssmDataE : 2344 -> 2308
~ __ZN8Security12KeychainCore12KeychainImpl4itemERKNS0_10PrimaryKeyE : 1452 -> 1408
~ __ZN8Security11CodeSigning7SecCode15autoLocateGuestEPK14__CFDictionaryj : 484 -> 496
~ _SecCodeCopySelf : 608 -> 580
~ _SecCodeCopyGuestWithAttributes : 592 -> 536
~ _SecCodeCreateWithPID : 636 -> 608
~ _SecCodeCreateWithAuditToken : 684 -> 656
~ _SecCodeSignerCreate : 732 -> 676
~ __ZN8Security11CodeSigning13SecStaticCode20isAppleDeveloperCertEPK9__CFArray : 1160 -> 1108
~ ____ZN8Security11CodeSigning13SecStaticCode14reportProgressEj_block_invoke : 224 -> 196
~ __ZN8Security11CodeSigning13SecStaticCode16validateResourceEPK14__CFDictionaryNSt3__112basic_stringIcNS5_11char_traitsIcEENS5_9allocatorIcEEEEbRNS1_17ValidationContextEjj : 6736 -> 6632
~ __ZN8Security11CodeSigning13SecStaticCode14staticValidateEjPKNS0_14SecRequirementE : 4196 -> 4140
~ __ZN8Security11CodeSigning13SecStaticCode23visitOtherArchitecturesEU13block_pointerFvPS1_E : 1384 -> 1332
~ __ZN8Security11CodeSigning13SecStaticCode22staticValidateResourceENSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEjPKNS0_14SecRequirementE : 4460 -> 4408
~ ____ZN8Security11CodeSigning13SecStaticCode22staticValidateResourceENSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEjPKNS0_14SecRequirementE_block_invoke : 1288 -> 1240
~ __ZN8Security11CodeSigning10KernelCode13identifyGuestEPNS0_7SecCodeEPPK8__CFData : 1424 -> 1320
~ __ZN8Security11CodeSigning11FileDiskRep19defaultRequirementsEPKNS_12ArchitectureERKNS0_7DiskRep14SigningContextE : 1104 -> 1056
~ __ZN8Security11CodeSigning12PolicyEngine12evaluateCodeEPK7__CFURLjyPK14__CFDictionaryPS5_b : 3636 -> 3544
~ __ZN8Security11CodeSigning12PolicyEngine15normalizeTargetERNS_5CFRefIPKvEEjRNS_12CFDictionaryEPNSt3__112basic_stringIcNS9_11char_traitsIcEENS9_9allocatorIcEEEE : 1168 -> 1092
~ _SecCodeSignerRemoteCreate : 1076 -> 1024
~ ____ZN8Security11CodeSigning13SecCodeSigner6Signer14buildResourcesENSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEES9_PK14__CFDictionary_block_invoke_2 : 2460 -> 2404
~ __ZN8Security12KeychainCore3ACL5parseERKNS_9TypedListE : 2148 -> 2064
~ __ZN8Security12KeychainCore6AccessC1Ev : 496 -> 392
~ __ZN8Security12KeychainCore6Access12makeStandardERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEERKNS2_6vectorINS_10SecPointerINS0_18TrustedApplicationEEENS6_ISE_EEEERKNS_19AclAuthorizationSetESL_ : 1672 -> 1524
~ __ZN8Security12KeychainCore6AccessC2ERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE : 528 -> 428
~ __ZN8Security12KeychainCore8KCCursorC2ERKNSt3__16vectorINS0_8KeychainENS2_9allocatorIS4_EEEE12SecItemClassPK24SecKeychainAttributeListjj : 852 -> 808
~ __ZN8Security12KeychainCore11Certificate14findInKeychainERKNSt3__16vectorINS0_8KeychainENS2_9allocatorIS4_EEEE : 372 -> 380
~ __ZN8Security12KeychainCore25IdentityCursorPolicyAndID21findPreferredIdentityEv : 752 -> 700
~ __ZN8Security12KeychainCore25IdentityCursorPolicyAndID4nextERNS_10SecPointerINS0_8IdentityEEE : 1768 -> 1680
~ __ZN8Security12KeychainCore14IdentityCursor4nextERNS_10SecPointerINS0_8IdentityEEE : 1196 -> 1144
~ __ZN8Security12KeychainCore8ItemImpl15removeIntegrityERNS_10CssmClient9AclBearerEPKNS_17AccessCredentialsE : 408 -> 356
~ __ZN8Security12KeychainCore8ItemImpl12setIntegrityERNS_10CssmClient9AclBearerEb : 336 -> 284
~ __ZN8Security12KeychainCore8ItemImpl20getCurrentAttributesEv : 920 -> 932
~ __ZN8Security12KeychainCore8ItemImpl6copyToERKNS0_8KeychainEPNS0_6AccessE : 1988 -> 1880
~ __ZN8Security12KeychainCore8ItemImplC2ERS1_ : 752 -> 772
~ __ZN8Security12KeychainCore8ItemImpl8doChangeENS0_8KeychainEjU13block_pointerFvvE : 1960 -> 1856
~ __ZN8Security12KeychainCore8ItemImpl15addWithCopyInfoERNS0_8KeychainEb : 2068 -> 2084
~ __ZN8Security12KeychainCore8ItemImplC2E12SecItemClassjjPKvb : 684 -> 692
~ __ZN8Security12KeychainCore8ItemImplC2E12SecItemClassP24SecKeychainAttributeListjPKv : 740 -> 748
~ __ZN8Security12KeychainCore4ItemC1E12SecItemClassjjPKvb : 304 -> 252
~ __ZN8Security12KeychainCore4ItemC1E12SecItemClassP24SecKeychainAttributeListjPKv : 256 -> 204
~ __ZNK8Security12KeychainCore7KeyItemcvPKvEv : 272 -> 232
~ __ZN8Security12KeychainCore8KCCursorC2ERKNSt3__16vectorINS0_8KeychainENS2_9allocatorIS4_EEEEPK24SecKeychainAttributeList : 904 -> 860
~ _SecACLCreateFromSimpleContents : 820 -> 768
~ __ZL15setApplicationsPN8Security12KeychainCore3ACLEPK9__CFArray : 300 -> 248
~ _SecAccessCreate : 1168 -> 1116
~ _SecAccessCreateFromOwnerAndACL : 664 -> 612
~ _SecCertificateCreateItemImplInstance : 304 -> 252
~ _SecCertificateSetPreference : 3188 -> 3204
~ _SecIdentityCreateWithCertificate : 768 -> 716
~ _SecIdentityCreate : 668 -> 564
~ _SecIdentitySetPreference : 3596 -> 3612
~ _SecIdentityCopySystemIdentity : 1372 -> 1320
~ _SecIdentitySearchCreate : 660 -> 608
~ _SecIdentitySearchCreateWithAttributes : 644 -> 592
~ _SecIdentitySearchCreateWithPolicy : 836 -> 788
~ __ZL23SecCDSAKeyCopyPublicKeyP8__SecKey : 1796 -> 1744
~ __ZL17SecCDSAKeyDestroyP8__SecKey : 536 -> 568
~ _SecKeyCreatePair : 7356 -> 7092
~ _SecKeyImportPair : 5708 -> 5448
~ __ZL28SecKeyGenerateWithAttributesP24SecKeychainAttributeListP13__SecKeychainjjyjjP11__SecAccessPP8__SecKey : 4264 -> 4108
~ _SecKeychainAddInternetPassword : 1112 -> 1128
~ _SecKeychainAddGenericPassword : 896 -> 912
~ _SecKeychainRemoveFromSearchList : 648 -> 596
~ _SecKeychainCreateWithBlob : 1240 -> 1248
~ _SecKeychainItemCreateFromContent : 804 -> 820
~ _SecKeychainItemCopyAccess : 900 -> 848
~ _SecKeychainItemCopyFromPersistentReference : 2464 -> 2420
~ _SecKeychainItemSetExtendedAttribute : 1812 -> 1764
~ _SecKeychainItemCopyAllExtendedAttributes : 1748 -> 1696
~ _SecGenericPasswordCreate : 1032 -> 980
~ __ZL17tsCopyCertsCommonPK9cssm_dataPKcjbbbbPPK9__CFArray : 1100 -> 996
~ ___SecTrustSettingsCopyCertificates_block_invoke_2 : 1980 -> 1876
~ _SecTrustedApplicationCreateFromPath : 1196 -> 1144
~ _SecTrustedApplicationCreateFromRequirement : 620 -> 572
~ _SecTrustedApplicationCreateApplicationGroup : 1704 -> 1648
~ __ZN8Security12KeychainCore14StorageManager13getSearchListERNSt3__16vectorINS0_8KeychainENS2_9allocatorIS4_EEEE : 1192 -> 1036
~ __ZN8Security12KeychainCore14StorageManager15defaultKeychainEv : 480 -> 452
~ __ZN8Security12KeychainCore14StorageManager11convertListERNSt3__16vectorINS0_8KeychainENS2_9allocatorIS4_EEEERKNS3_INS_14DLDbIdentifierENS5_IS9_EEEE : 432 -> 380
~ __ZN8Security12KeychainCore14StorageManager18optionalSearchListEPKvRNSt3__16vectorINS0_8KeychainENS4_9allocatorIS6_EEEE : 388 -> 336
~ __ZN8Security12KeychainCore14StorageManager5loginEjPKvjS3_b : 14524 -> 14472
~ __ZN8Security12KeychainCore14StorageManager13resetKeychainEh : 2812 -> 2720
~ __ZN8Security14SecPointerBase4copyEPNS_11SecCFObjectE : 88 -> 124
CStrings:
+ "failed to add certificate %p to keychain \"%s\""
```
