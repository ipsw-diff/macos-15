## WebCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/WebCore.framework/Versions/A/WebCore`

```diff

-621.3.6.1.0
-  __TEXT.__text: 0x2bcd874
-  __TEXT.__auth_stubs: 0xc400
+621.3.7.0.0
+  __TEXT.__text: 0x2bcdb94
+  __TEXT.__auth_stubs: 0xc410
   __TEXT.__objc_methlist: 0x4c7c
   __TEXT.__const: 0x192378
   __TEXT.__gcc_except_tab: 0x196c0

   __DATA_CONST.__objc_superrefs: 0x1f8
   __DATA_CONST.__jsc_ops: 0x470
   __DATA_CONST.__objc_arraydata: 0x90
-  __AUTH_CONST.__auth_got: 0x6220
+  __AUTH_CONST.__auth_got: 0x6228
   __AUTH_CONST.__const: 0x228e38
   __AUTH_CONST.__cfstring: 0x65e0
   __AUTH_CONST.__objc_const: 0x7540

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 102028
-  Symbols:   129188
+  Functions: 102029
+  Symbols:   129190
   CStrings:  29446
 
Symbols:
+ __ZN7WebCore8SWServer32addHandlerIfHasControlledClientsEON3WTF17CompletionHandlerIFvvEEE
+ _nw_parameters_set_source_application_by_bundle_id
Functions:
~ __ZN3JSC8JSObject17putDirectInternalILNS0_7PutModeE1EEEN3WTF12ASCIILiteralERNS_2VMENS_12PropertyNameENS_7JSValueEjRNS_15PutPropertySlotE : 4732 -> 4760
~ __ZN3JSC9Structure3addILNS0_9ShouldPinE1EZNS_8JSObject35prepareToPutDirectWithoutTransitionERNS_2VMENS_12PropertyNameEjNS_11StructureIDEPS0_EUlRKNS_24GCSafeConcurrentJSLockerEiiE_EEiS5_S6_jRKT0_ : 888 -> 920
~ __ZN7WebCore11FrameLoader19prefetchDNSIfNeededERKN3WTF3URLE : 640 -> 644
~ __ZN7WebCore20DNSResolveQueueCFNet16performDNSLookupERKN3WTF6StringEONS1_3RefINS0_24CompletionHandlerWrapperENS1_12RawPtrTraitsIS6_EENS1_21DefaultRefDerefTraitsIS6_EEEE : 768 -> 904
~ __ZN7WebCore8SWServer6createERNS_16SWServerDelegateEON3WTF9UniqueRefINS_13SWOriginStoreEEEbONS3_6StringEN3PAL9SessionIDEbbNSt3__18optionalIjEENS_26ServiceWorkerIsInspectableE : 960 -> 964
~ __ZN7WebCore8SWServerD2Ev : 3528 -> 3632
~ __ZN7WebCore8SWServer21whenImportIsCompletedEON3WTF17CompletionHandlerIFvvEEE : 108 -> 112
~ __ZN7WebCore8SWServer29unregisterServiceWorkerClientERKNS_12ClientOriginENS_16ProcessQualifiedIN3WTF4UUIDEEE : 4464 -> 4704
~ __ZN7WebCore8SWServer13getAllOriginsEON3WTF17CompletionHandlerIFvONS1_7HashSetINS_12ClientOriginENS1_11DefaultHashIS4_EENS1_10HashTraitsIS4_EENS1_15HashTableTraitsELNS1_17ShouldValidateKeyE1EEEEEE : 408 -> 412
~ __ZN7WebCore8SWServer18processPushMessageEONSt3__18optionalIN3WTF6VectorIhLm0ENS3_15CrashOnOverflowELm16ENS3_10FastMallocEEEEEONS2_INS_19NotificationPayloadEEEONS3_3URLEONS3_17CompletionHandlerIFvbSC_EEE : 1032 -> 1036
~ __ZN7WebCore8SWServer24processNotificationEventEONS_16NotificationDataENS_21NotificationEventTypeEON3WTF17CompletionHandlerIFvbEEE : 1020 -> 1024
+ __ZN7WebCore8SWServer32addHandlerIfHasControlledClientsEON3WTF17CompletionHandlerIFvvEEE
~ __ZN3WTF6Detail15CallableWrapperIZN7WebCore8SWServer26validateRegistrationDomainENS2_17RegistrableDomainENS2_20ServiceWorkerJobTypeEbONS_17CompletionHandlerIFvbEEEE3$_0vJONS_7HashSetIS4_NS_11DefaultHashIS4_EENS_10HashTraitsIS4_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1EEEEE4callESJ_ : 500 -> 484
```
