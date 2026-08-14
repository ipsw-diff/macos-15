## SiriInstrumentation

> `/System/Library/PrivateFrameworks/SiriInstrumentation.framework/Versions/A/SiriInstrumentation`

```diff

-3405.16.1.0.0
-  __TEXT.__text: 0xa187ec
+3405.21.1.0.0
+  __TEXT.__text: 0xa20b50
   __TEXT.__auth_stubs: 0xf00
-  __TEXT.__objc_methlist: 0xccef4
-  __TEXT.__const: 0x115b0
-  __TEXT.__cstring: 0x765e6
-  __TEXT.__constg_swiftt: 0x6180
-  __TEXT.__swift5_typeref: 0x1846
-  __TEXT.__swift5_builtin: 0x3868
+  __TEXT.__objc_methlist: 0xcd864
+  __TEXT.__const: 0x11770
+  __TEXT.__cstring: 0x76e87
+  __TEXT.__constg_swiftt: 0x6220
+  __TEXT.__swift5_typeref: 0x1864
+  __TEXT.__swift5_builtin: 0x38cc
   __TEXT.__swift5_reflstr: 0x214
   __TEXT.__swift5_assocty: 0x120
-  __TEXT.__swift5_proto: 0xe84
-  __TEXT.__swift5_types: 0xb98
+  __TEXT.__swift5_proto: 0xe98
+  __TEXT.__swift5_types: 0xbac
   __TEXT.__swift5_fieldmd: 0x3e8
   __TEXT.__oslogstring: 0x95
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__unwind_info: 0x294d0
+  __TEXT.__unwind_info: 0x296c0
   __TEXT.__eh_frame: 0x1f98
-  __TEXT.__objc_classname: 0x150c5
-  __TEXT.__objc_methname: 0x11a084
-  __TEXT.__objc_methtype: 0x26fa8
-  __TEXT.__objc_stubs: 0x66d60
-  __DATA_CONST.__got: 0x4b38
-  __DATA_CONST.__const: 0x33300
-  __DATA_CONST.__objc_classlist: 0x4a08
+  __TEXT.__objc_classname: 0x1525e
+  __TEXT.__objc_methname: 0x11b3fb
+  __TEXT.__objc_methtype: 0x27232
+  __TEXT.__objc_stubs: 0x672a0
+  __DATA_CONST.__got: 0x4b78
+  __DATA_CONST.__const: 0x33680
+  __DATA_CONST.__objc_classlist: 0x4a48
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x352a8
+  __DATA_CONST.__objc_selrefs: 0x35538
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x72c8
+  __DATA_CONST.__objc_superrefs: 0x7330
   __AUTH_CONST.__auth_got: 0x788
-  __AUTH_CONST.__const: 0x20ac0
-  __AUTH_CONST.__cfstring: 0x66ce0
-  __AUTH_CONST.__objc_const: 0x115ad0
+  __AUTH_CONST.__const: 0x20b60
+  __AUTH_CONST.__cfstring: 0x67360
+  __AUTH_CONST.__objc_const: 0x1167e0
   __AUTH_CONST.__objc_intobj: 0xb70
-  __AUTH.__objc_data: 0x2c8a0
+  __AUTH.__objc_data: 0x2cb20
   __AUTH.__data: 0x338
-  __DATA.__objc_ivar: 0xdcf0
-  __DATA.__data: 0x21e8
-  __DATA.__bss: 0x18180
+  __DATA.__objc_ivar: 0xdd8c
+  __DATA.__data: 0x2210
+  __DATA.__bss: 0x18400
   __DATA.__common: 0x50
   __DATA_DIRTY.__objc_data: 0x1e00
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 74241
-  Symbols:   116288
-  CStrings:  57689
+  Functions: 74459
+  Symbols:   116637
+  CStrings:  57875
 
Symbols:
+ -[FLOWSchemaFLOWDomainContext deleteSafariContext]
+ -[FLOWSchemaFLOWDomainContext hasSafariContext]
+ -[FLOWSchemaFLOWDomainContext safariContext]
+ -[FLOWSchemaFLOWDomainContext setHasSafariContext:]
+ -[FLOWSchemaFLOWDomainContext setSafariContext:]
+ -[FLOWSchemaFLOWSafariContext deleteTaskType]
+ -[FLOWSchemaFLOWSafariContext dictionaryRepresentation]
+ -[FLOWSchemaFLOWSafariContext hasTaskType]
+ -[FLOWSchemaFLOWSafariContext hash]
+ -[FLOWSchemaFLOWSafariContext initWithDictionary:]
+ -[FLOWSchemaFLOWSafariContext initWithJSON:]
+ -[FLOWSchemaFLOWSafariContext isEqual:]
+ -[FLOWSchemaFLOWSafariContext jsonData]
+ -[FLOWSchemaFLOWSafariContext readFrom:]
+ -[FLOWSchemaFLOWSafariContext setHasTaskType:]
+ -[FLOWSchemaFLOWSafariContext setTaskType:]
+ -[FLOWSchemaFLOWSafariContext taskType]
+ -[FLOWSchemaFLOWSafariContext writeTo:]
+ -[FLOWSchemaFLOWSafariContext(SensitiveConditions) suppressMessageUnderConditions]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions addClientProcessAssetAvailabilityStatus:]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions assetSetStatusEventTimestampInSecondsSince1970]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions clearClientProcessAssetAvailabilityStatus]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions clientProcessAssetAvailabilityStatusAtIndex:]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions clientProcessAssetAvailabilityStatusCount]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions clientProcessAssetAvailabilityStatus]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions deleteAssetSetStatusEventTimestampInSecondsSince1970]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions deleteClientProcessAssetAvailabilityStatus]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions hasAssetSetStatusEventTimestampInSecondsSince1970]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions setAssetSetStatusEventTimestampInSecondsSince1970:]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions setClientProcessAssetAvailabilityStatus:]
+ -[ODDSiriSchemaODDAssetSetStatusDimensions setHasAssetSetStatusEventTimestampInSecondsSince1970:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus .cxx_destruct]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus deleteGmsAssetAvailabilityStatus]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus dictionaryRepresentation]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus gmsAssetAvailabilityStatus]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus hasGmsAssetAvailabilityStatus]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus hash]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus initWithDictionary:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus initWithJSON:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus isEqual:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus jsonData]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus readFrom:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus setGmsAssetAvailabilityStatus:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus setHasGmsAssetAvailabilityStatus:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus writeTo:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus(SensitiveConditions) applySensitiveConditionsPolicy:]
+ -[ODDSiriSchemaODDClientProcessAssetAvailabilityStatus(SensitiveConditions) suppressMessageUnderConditions]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus deleteStatusMessage]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus deleteTimestampInSecondsSince1970]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus dictionaryRepresentation]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus hasStatusMessage]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus hasTimestampInSecondsSince1970]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus hash]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus initWithDictionary:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus initWithJSON:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus isEqual:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus jsonData]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus readFrom:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus setHasStatusMessage:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus setHasTimestampInSecondsSince1970:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus setStatusMessage:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus setTimestampInSecondsSince1970:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus statusMessage]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus timestampInSecondsSince1970]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus writeTo:]
+ -[ODDSiriSchemaODDGmsAssetAvailabilityStatus(SensitiveConditions) suppressMessageUnderConditions]
+ -[ORCHSchemaORCHClientEvent deleteUserSessionState]
+ -[ORCHSchemaORCHClientEvent hasUserSessionState]
+ -[ORCHSchemaORCHClientEvent setHasUserSessionState:]
+ -[ORCHSchemaORCHClientEvent setUserSessionState:]
+ -[ORCHSchemaORCHClientEvent userSessionState]
+ -[ORCHSchemaORCHMUXUserSessionState accessLevel]
+ -[ORCHSchemaORCHMUXUserSessionState deleteAccessLevel]
+ -[ORCHSchemaORCHMUXUserSessionState deleteIsEndOfRequest]
+ -[ORCHSchemaORCHMUXUserSessionState deleteState]
+ -[ORCHSchemaORCHMUXUserSessionState dictionaryRepresentation]
+ -[ORCHSchemaORCHMUXUserSessionState hasAccessLevel]
+ -[ORCHSchemaORCHMUXUserSessionState hasIsEndOfRequest]
+ -[ORCHSchemaORCHMUXUserSessionState hasState]
+ -[ORCHSchemaORCHMUXUserSessionState hash]
+ -[ORCHSchemaORCHMUXUserSessionState initWithDictionary:]
+ -[ORCHSchemaORCHMUXUserSessionState initWithJSON:]
+ -[ORCHSchemaORCHMUXUserSessionState isEndOfRequest]
+ -[ORCHSchemaORCHMUXUserSessionState isEqual:]
+ -[ORCHSchemaORCHMUXUserSessionState jsonData]
+ -[ORCHSchemaORCHMUXUserSessionState readFrom:]
+ -[ORCHSchemaORCHMUXUserSessionState setAccessLevel:]
+ -[ORCHSchemaORCHMUXUserSessionState setHasAccessLevel:]
+ -[ORCHSchemaORCHMUXUserSessionState setHasIsEndOfRequest:]
+ -[ORCHSchemaORCHMUXUserSessionState setHasState:]
+ -[ORCHSchemaORCHMUXUserSessionState setIsEndOfRequest:]
+ -[ORCHSchemaORCHMUXUserSessionState setState:]
+ -[ORCHSchemaORCHMUXUserSessionState state]
+ -[ORCHSchemaORCHMUXUserSessionState writeTo:]
+ -[ORCHSchemaORCHMUXUserSessionState(SensitiveConditions) suppressMessageUnderConditions]
+ -[POMMESSchemaPOMMESClientEvent deletePommesKnowledgeFallbackConfirmationOutcomeReceived]
+ -[POMMESSchemaPOMMESClientEvent deletePommesKnowledgeFallbackOffered]
+ -[POMMESSchemaPOMMESClientEvent deletePommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown]
+ -[POMMESSchemaPOMMESClientEvent deletePommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived]
+ -[POMMESSchemaPOMMESClientEvent hasPommesKnowledgeFallbackConfirmationOutcomeReceived]
+ -[POMMESSchemaPOMMESClientEvent hasPommesKnowledgeFallbackOffered]
+ -[POMMESSchemaPOMMESClientEvent hasPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown]
+ -[POMMESSchemaPOMMESClientEvent hasPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived]
+ -[POMMESSchemaPOMMESClientEvent pommesKnowledgeFallbackConfirmationOutcomeReceived]
+ -[POMMESSchemaPOMMESClientEvent pommesKnowledgeFallbackOffered]
+ -[POMMESSchemaPOMMESClientEvent pommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown]
+ -[POMMESSchemaPOMMESClientEvent pommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived]
+ -[POMMESSchemaPOMMESClientEvent setHasPommesKnowledgeFallbackConfirmationOutcomeReceived:]
+ -[POMMESSchemaPOMMESClientEvent setHasPommesKnowledgeFallbackOffered:]
+ -[POMMESSchemaPOMMESClientEvent setHasPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown:]
+ -[POMMESSchemaPOMMESClientEvent setHasPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived:]
+ -[POMMESSchemaPOMMESClientEvent setPommesKnowledgeFallbackConfirmationOutcomeReceived:]
+ -[POMMESSchemaPOMMESClientEvent setPommesKnowledgeFallbackOffered:]
+ -[POMMESSchemaPOMMESClientEvent setPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown:]
+ -[POMMESSchemaPOMMESClientEvent setPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived .cxx_destruct]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived confirmationOutcome]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived deleteConfirmationOutcome]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived deletePommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived dictionaryRepresentation]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived hasConfirmationOutcome]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived hasPommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived hash]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived initWithDictionary:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived initWithJSON:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived isEqual:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived jsonData]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived pommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived readFrom:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived setConfirmationOutcome:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived setHasConfirmationOutcome:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived setHasPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived setPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived writeTo:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived(SensitiveConditions) applySensitiveConditionsPolicy:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived(SensitiveConditions) suppressMessageUnderConditions]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered .cxx_destruct]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered deleteIsKnowledgeFallbackConfirmationShown]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered deletePommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered dictionaryRepresentation]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered hasIsKnowledgeFallbackConfirmationShown]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered hasPommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered hash]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered initWithDictionary:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered initWithJSON:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered isEqual:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered isKnowledgeFallbackConfirmationShown]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered jsonData]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered pommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered readFrom:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered setHasIsKnowledgeFallbackConfirmationShown:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered setHasPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered setIsKnowledgeFallbackConfirmationShown:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered setPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered writeTo:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered(SensitiveConditions) applySensitiveConditionsPolicy:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackOffered(SensitiveConditions) suppressMessageUnderConditions]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown .cxx_destruct]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown deletePommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown dictionaryRepresentation]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown hasPommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown hash]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown initWithDictionary:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown initWithJSON:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown isEqual:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown jsonData]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown pommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown readFrom:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown setHasPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown setPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown writeTo:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown(SensitiveConditions) applySensitiveConditionsPolicy:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown(SensitiveConditions) suppressMessageUnderConditions]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived .cxx_destruct]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived confirmationOutcome]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived deleteConfirmationOutcome]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived deletePommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived dictionaryRepresentation]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived hasConfirmationOutcome]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived hasPommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived hash]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived initWithDictionary:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived initWithJSON:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived isEqual:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived jsonData]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived pommesSessionId]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived readFrom:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived setConfirmationOutcome:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived setHasConfirmationOutcome:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived setHasPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived setPommesSessionId:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived writeTo:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived(SensitiveConditions) applySensitiveConditionsPolicy:]
+ -[POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived(SensitiveConditions) suppressMessageUnderConditions]
+ OBJC_IVAR_$_FLOWSchemaFLOWDomainContext._hasSafariContext
+ OBJC_IVAR_$_FLOWSchemaFLOWDomainContext._safariContext
+ OBJC_IVAR_$_FLOWSchemaFLOWSafariContext._has
+ OBJC_IVAR_$_FLOWSchemaFLOWSafariContext._taskType
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetSetStatusDimensions._assetSetStatusEventTimestampInSecondsSince1970
+ OBJC_IVAR_$_ODDSiriSchemaODDAssetSetStatusDimensions._clientProcessAssetAvailabilityStatus
+ OBJC_IVAR_$_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus._gmsAssetAvailabilityStatus
+ OBJC_IVAR_$_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus._hasGmsAssetAvailabilityStatus
+ OBJC_IVAR_$_ODDSiriSchemaODDGmsAssetAvailabilityStatus._has
+ OBJC_IVAR_$_ODDSiriSchemaODDGmsAssetAvailabilityStatus._statusMessage
+ OBJC_IVAR_$_ODDSiriSchemaODDGmsAssetAvailabilityStatus._timestampInSecondsSince1970
+ OBJC_IVAR_$_ORCHSchemaORCHClientEvent._hasUserSessionState
+ OBJC_IVAR_$_ORCHSchemaORCHClientEvent._userSessionState
+ OBJC_IVAR_$_ORCHSchemaORCHMUXUserSessionState._accessLevel
+ OBJC_IVAR_$_ORCHSchemaORCHMUXUserSessionState._has
+ OBJC_IVAR_$_ORCHSchemaORCHMUXUserSessionState._isEndOfRequest
+ OBJC_IVAR_$_ORCHSchemaORCHMUXUserSessionState._state
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._hasPommesKnowledgeFallbackConfirmationOutcomeReceived
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._hasPommesKnowledgeFallbackOffered
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._hasPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._hasPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._pommesKnowledgeFallbackConfirmationOutcomeReceived
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._pommesKnowledgeFallbackOffered
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._pommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ OBJC_IVAR_$_POMMESSchemaPOMMESClientEvent._pommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived._confirmationOutcome
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived._has
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived._hasPommesSessionId
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived._pommesSessionId
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackOffered._has
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackOffered._hasPommesSessionId
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackOffered._isKnowledgeFallbackConfirmationShown
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackOffered._pommesSessionId
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown._hasPommesSessionId
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown._pommesSessionId
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived._confirmationOutcome
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived._has
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived._hasPommesSessionId
+ OBJC_IVAR_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived._pommesSessionId
+ _FLOWSchemaFLOWSafariContextReadFrom
+ _OBJC_CLASS_$_FLOWSchemaFLOWSafariContext
+ _OBJC_CLASS_$_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus
+ _OBJC_CLASS_$_ODDSiriSchemaODDGmsAssetAvailabilityStatus
+ _OBJC_CLASS_$_ORCHSchemaORCHMUXUserSessionState
+ _OBJC_CLASS_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived
+ _OBJC_CLASS_$_POMMESSchemaPOMMESKnowledgeFallbackOffered
+ _OBJC_CLASS_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ _OBJC_CLASS_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ _OBJC_METACLASS_$_FLOWSchemaFLOWSafariContext
+ _OBJC_METACLASS_$_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus
+ _OBJC_METACLASS_$_ODDSiriSchemaODDGmsAssetAvailabilityStatus
+ _OBJC_METACLASS_$_ORCHSchemaORCHMUXUserSessionState
+ _OBJC_METACLASS_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived
+ _OBJC_METACLASS_$_POMMESSchemaPOMMESKnowledgeFallbackOffered
+ _OBJC_METACLASS_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ _OBJC_METACLASS_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ _ODDSiriSchemaODDClientProcessAssetAvailabilityStatusReadFrom
+ _ODDSiriSchemaODDGmsAssetAvailabilityStatusReadFrom
+ _ORCHSchemaORCHMUXUserSessionStateReadFrom
+ _POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceivedReadFrom
+ _POMMESSchemaPOMMESKnowledgeFallbackOfferedReadFrom
+ _POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShownReadFrom
+ _POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceivedReadFrom
+ __OBJC_$_INSTANCE_METHODS_FLOWSchemaFLOWSafariContext(SensitiveConditions)
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus(SensitiveConditions)
+ __OBJC_$_INSTANCE_METHODS_ODDSiriSchemaODDGmsAssetAvailabilityStatus(SensitiveConditions)
+ __OBJC_$_INSTANCE_METHODS_ORCHSchemaORCHMUXUserSessionState(SensitiveConditions)
+ __OBJC_$_INSTANCE_METHODS_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived(SensitiveConditions)
+ __OBJC_$_INSTANCE_METHODS_POMMESSchemaPOMMESKnowledgeFallbackOffered(SensitiveConditions)
+ __OBJC_$_INSTANCE_METHODS_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown(SensitiveConditions)
+ __OBJC_$_INSTANCE_METHODS_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived(SensitiveConditions)
+ __OBJC_$_INSTANCE_VARIABLES_FLOWSchemaFLOWSafariContext
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus
+ __OBJC_$_INSTANCE_VARIABLES_ODDSiriSchemaODDGmsAssetAvailabilityStatus
+ __OBJC_$_INSTANCE_VARIABLES_ORCHSchemaORCHMUXUserSessionState
+ __OBJC_$_INSTANCE_VARIABLES_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived
+ __OBJC_$_INSTANCE_VARIABLES_POMMESSchemaPOMMESKnowledgeFallbackOffered
+ __OBJC_$_INSTANCE_VARIABLES_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ __OBJC_$_INSTANCE_VARIABLES_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ __OBJC_$_PROP_LIST_FLOWSchemaFLOWSafariContext
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus
+ __OBJC_$_PROP_LIST_ODDSiriSchemaODDGmsAssetAvailabilityStatus
+ __OBJC_$_PROP_LIST_ORCHSchemaORCHMUXUserSessionState
+ __OBJC_$_PROP_LIST_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived
+ __OBJC_$_PROP_LIST_POMMESSchemaPOMMESKnowledgeFallbackOffered
+ __OBJC_$_PROP_LIST_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ __OBJC_$_PROP_LIST_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ __OBJC_CLASS_RO_$_FLOWSchemaFLOWSafariContext
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus
+ __OBJC_CLASS_RO_$_ODDSiriSchemaODDGmsAssetAvailabilityStatus
+ __OBJC_CLASS_RO_$_ORCHSchemaORCHMUXUserSessionState
+ __OBJC_CLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived
+ __OBJC_CLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackOffered
+ __OBJC_CLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ __OBJC_CLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ __OBJC_METACLASS_RO_$_FLOWSchemaFLOWSafariContext
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDClientProcessAssetAvailabilityStatus
+ __OBJC_METACLASS_RO_$_ODDSiriSchemaODDGmsAssetAvailabilityStatus
+ __OBJC_METACLASS_RO_$_ORCHSchemaORCHMUXUserSessionState
+ __OBJC_METACLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived
+ __OBJC_METACLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackOffered
+ __OBJC_METACLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ __OBJC_METACLASS_RO_$_POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ _objc_msgSend$accessLevel
+ _objc_msgSend$addClientProcessAssetAvailabilityStatus:
+ _objc_msgSend$assetSetStatusEventTimestampInSecondsSince1970
+ _objc_msgSend$clearClientProcessAssetAvailabilityStatus
+ _objc_msgSend$clientProcessAssetAvailabilityStatus
+ _objc_msgSend$confirmationOutcome
+ _objc_msgSend$deleteGmsAssetAvailabilityStatus
+ _objc_msgSend$deletePommesKnowledgeFallbackConfirmationOutcomeReceived
+ _objc_msgSend$deletePommesKnowledgeFallbackOffered
+ _objc_msgSend$deletePommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ _objc_msgSend$deletePommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ _objc_msgSend$deletePommesSessionId
+ _objc_msgSend$deleteSafariContext
+ _objc_msgSend$deleteUserSessionState
+ _objc_msgSend$gmsAssetAvailabilityStatus
+ _objc_msgSend$isEndOfRequest
+ _objc_msgSend$isKnowledgeFallbackConfirmationShown
+ _objc_msgSend$pommesKnowledgeFallbackConfirmationOutcomeReceived
+ _objc_msgSend$pommesKnowledgeFallbackOffered
+ _objc_msgSend$pommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ _objc_msgSend$pommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ _objc_msgSend$pommesSessionId
+ _objc_msgSend$safariContext
+ _objc_msgSend$setAccessLevel:
+ _objc_msgSend$setAssetSetStatusEventTimestampInSecondsSince1970:
+ _objc_msgSend$setClientProcessAssetAvailabilityStatus:
+ _objc_msgSend$setConfirmationOutcome:
+ _objc_msgSend$setGmsAssetAvailabilityStatus:
+ _objc_msgSend$setIsEndOfRequest:
+ _objc_msgSend$setIsKnowledgeFallbackConfirmationShown:
+ _objc_msgSend$setPommesKnowledgeFallbackConfirmationOutcomeReceived:
+ _objc_msgSend$setPommesKnowledgeFallbackOffered:
+ _objc_msgSend$setPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown:
+ _objc_msgSend$setPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived:
+ _objc_msgSend$setPommesSessionId:
+ _objc_msgSend$setSafariContext:
+ _objc_msgSend$setStatusMessage:
+ _objc_msgSend$setTimestampInSecondsSince1970:
+ _objc_msgSend$setUserSessionState:
+ _objc_msgSend$statusMessage
+ _objc_msgSend$timestampInSecondsSince1970
+ _objc_msgSend$userSessionState
+ _qname_ORCHSchemaORCHClientEvent_WhichEvent_Type_userSessionState
+ _qname_POMMESSchemaPOMMESClientEvent_WhichEvent_Type_pommesKnowledgeFallbackConfirmationOutcomeReceived
+ _qname_POMMESSchemaPOMMESClientEvent_WhichEvent_Type_pommesKnowledgeFallbackOffered
+ _qname_POMMESSchemaPOMMESClientEvent_WhichEvent_Type_pommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown
+ _qname_POMMESSchemaPOMMESClientEvent_WhichEvent_Type_pommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived
+ _symbolic _____ So28FLOWSchemaFLOWSafariTaskTypeV
+ _symbolic _____ So30ORCHSchemaORCHUserSessionStateV
+ _symbolic _____ So36ORCHSchemaORCHUserSessionAccessLevelV
+ _symbolic _____ So54POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeV
+ _symbolic _____ So73POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationOutcomeV
CStrings:
+ "@\"FLOWSchemaFLOWSafariContext\""
+ "@\"ODDSiriSchemaODDGmsAssetAvailabilityStatus\""
+ "@\"ORCHSchemaORCHMUXUserSessionState\""
+ "@\"POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived\""
+ "@\"POMMESSchemaPOMMESKnowledgeFallbackOffered\""
+ "@\"POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown\""
+ "@\"POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived\""
+ "DICTATIONENDPOINTTYPE_EDIT_MENU_SHOW_KEYBOARD"
+ "FLOWSAFARITASKTYPE_ENTER_RECIPE_MODE"
+ "FLOWSAFARITASKTYPE_ENTER_THEATER_MODE"
+ "FLOWSAFARITASKTYPE_EXIT_RECIPE_MODE"
+ "FLOWSAFARITASKTYPE_EXIT_THEATER_MODE"
+ "FLOWSAFARITASKTYPE_LISTEN_TO_PAGE"
+ "FLOWSAFARITASKTYPE_RECIPE_MODE_HIDE_INGREDIENT"
+ "FLOWSAFARITASKTYPE_RECIPE_MODE_NEXT_STEP"
+ "FLOWSAFARITASKTYPE_RECIPE_MODE_PREVIOUS_STEP"
+ "FLOWSAFARITASKTYPE_RECIPE_MODE_SHOW_INGREDIENT"
+ "FLOWSAFARITASKTYPE_RECIPE_MODE_SPECIFIC_STEP"
+ "FLOWSAFARITASKTYPE_UNKOWN"
+ "FLOWSchemaFLOWSafariContext"
+ "INVOCATIONSOURCE_DICTATION_TEXTFIELD_TAP"
+ "INVOCATIONSOURCE_DICTATION_TEXTFIELD_TRAILING_MIC_BUTTON"
+ "ODDSiriSchemaODDClientProcessAssetAvailabilityStatus"
+ "ODDSiriSchemaODDGmsAssetAvailabilityStatus"
+ "ORCHSchemaORCHMUXUserSessionState"
+ "ORCHUSERSESSIONACCESSLEVEL_HIGH"
+ "ORCHUSERSESSIONACCESSLEVEL_LOW"
+ "ORCHUSERSESSIONACCESSLEVEL_UNKNOWN"
+ "ORCHUSERSESSIONSTATE_AMBIENT"
+ "ORCHUSERSESSIONSTATE_ENROLLED"
+ "ORCHUSERSESSIONSTATE_GUEST"
+ "ORCHUSERSESSIONSTATE_UNKNOWN"
+ "PEGASUSDOMAIN_DEVICE_EXPERT"
+ "PEGASUSDOMAIN_GEN_KG"
+ "PEGASUSDOMAIN_V2_WEBINDEX"
+ "POMMESKNOWLEDGEFALLBACKCONFIRMATIONOUTCOME_CANCEL"
+ "POMMESKNOWLEDGEFALLBACKCONFIRMATIONOUTCOME_UNKNOWN"
+ "POMMESKNOWLEDGEFALLBACKCONFIRMATIONOUTCOME_USE_GEN_AI"
+ "POMMESKNOWLEDGEFALLBACKCONFIRMATIONOUTCOME_WEB_SEARCH"
+ "POMMESKNOWLEDGEFALLBACKTURNOFFALWAYSPROMPTCONFIRMATIONOUTCOME_LEAVE_ON"
+ "POMMESKNOWLEDGEFALLBACKTURNOFFALWAYSPROMPTCONFIRMATIONOUTCOME_TURN_OFF"
+ "POMMESKNOWLEDGEFALLBACKTURNOFFALWAYSPROMPTCONFIRMATIONOUTCOME_UNKNOWN"
+ "POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived"
+ "POMMESSchemaPOMMESKnowledgeFallbackOffered"
+ "POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "T@\"FLOWSchemaFLOWSafariContext\",&,N,V_safariContext"
+ "T@\"NSArray\",C,N,V_clientProcessAssetAvailabilityStatus"
+ "T@\"ODDSiriSchemaODDGmsAssetAvailabilityStatus\",&,N,V_gmsAssetAvailabilityStatus"
+ "T@\"ORCHSchemaORCHMUXUserSessionState\",&,N,V_userSessionState"
+ "T@\"POMMESSchemaPOMMESKnowledgeFallbackConfirmationOutcomeReceived\",&,N,V_pommesKnowledgeFallbackConfirmationOutcomeReceived"
+ "T@\"POMMESSchemaPOMMESKnowledgeFallbackOffered\",&,N,V_pommesKnowledgeFallbackOffered"
+ "T@\"POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown\",&,N,V_pommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "T@\"POMMESSchemaPOMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived\",&,N,V_pommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "T@\"SISchemaUUID\",&,N,V_pommesSessionId"
+ "TB,N,V_hasGmsAssetAvailabilityStatus"
+ "TB,N,V_hasPommesKnowledgeFallbackConfirmationOutcomeReceived"
+ "TB,N,V_hasPommesKnowledgeFallbackOffered"
+ "TB,N,V_hasPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "TB,N,V_hasPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "TB,N,V_hasPommesSessionId"
+ "TB,N,V_hasSafariContext"
+ "TB,N,V_hasUserSessionState"
+ "TB,N,V_isEndOfRequest"
+ "TB,N,V_isKnowledgeFallbackConfirmationShown"
+ "TQ,N,V_assetSetStatusEventTimestampInSecondsSince1970"
+ "TQ,N,V_statusMessage"
+ "TQ,N,V_timestampInSecondsSince1970"
+ "Ti,N,V_accessLevel"
+ "Ti,N,V_confirmationOutcome"
+ "_accessLevel"
+ "_assetSetStatusEventTimestampInSecondsSince1970"
+ "_clientProcessAssetAvailabilityStatus"
+ "_confirmationOutcome"
+ "_gmsAssetAvailabilityStatus"
+ "_hasGmsAssetAvailabilityStatus"
+ "_hasPommesKnowledgeFallbackConfirmationOutcomeReceived"
+ "_hasPommesKnowledgeFallbackOffered"
+ "_hasPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "_hasPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "_hasPommesSessionId"
+ "_hasSafariContext"
+ "_hasUserSessionState"
+ "_isEndOfRequest"
+ "_isKnowledgeFallbackConfirmationShown"
+ "_pommesKnowledgeFallbackConfirmationOutcomeReceived"
+ "_pommesKnowledgeFallbackOffered"
+ "_pommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "_pommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "_pommesSessionId"
+ "_safariContext"
+ "_statusMessage"
+ "_timestampInSecondsSince1970"
+ "_userSessionState"
+ "accessLevel"
+ "addClientProcessAssetAvailabilityStatus:"
+ "assetSetStatusEventTimestampInSecondsSince1970"
+ "clearClientProcessAssetAvailabilityStatus"
+ "clientProcessAssetAvailabilityStatus"
+ "clientProcessAssetAvailabilityStatusAtIndex:"
+ "clientProcessAssetAvailabilityStatusCount"
+ "com.apple.aiml.siri.orch.ORCHClientEvent.ORCHMUXUserSessionState"
+ "com.apple.aiml.siri.pommes.POMMESClientEvent.POMMESKnowledgeFallbackConfirmationOutcomeReceived"
+ "com.apple.aiml.siri.pommes.POMMESClientEvent.POMMESKnowledgeFallbackOffered"
+ "com.apple.aiml.siri.pommes.POMMESClientEvent.POMMESKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "com.apple.aiml.siri.pommes.POMMESClientEvent.POMMESKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "confirmationOutcome"
+ "deleteAccessLevel"
+ "deleteAssetSetStatusEventTimestampInSecondsSince1970"
+ "deleteClientProcessAssetAvailabilityStatus"
+ "deleteConfirmationOutcome"
+ "deleteGmsAssetAvailabilityStatus"
+ "deleteIsEndOfRequest"
+ "deleteIsKnowledgeFallbackConfirmationShown"
+ "deletePommesKnowledgeFallbackConfirmationOutcomeReceived"
+ "deletePommesKnowledgeFallbackOffered"
+ "deletePommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "deletePommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "deletePommesSessionId"
+ "deleteSafariContext"
+ "deleteStatusMessage"
+ "deleteTimestampInSecondsSince1970"
+ "deleteUserSessionState"
+ "gmsAssetAvailabilityStatus"
+ "hasAccessLevel"
+ "hasAssetSetStatusEventTimestampInSecondsSince1970"
+ "hasConfirmationOutcome"
+ "hasGmsAssetAvailabilityStatus"
+ "hasIsEndOfRequest"
+ "hasIsKnowledgeFallbackConfirmationShown"
+ "hasPommesKnowledgeFallbackConfirmationOutcomeReceived"
+ "hasPommesKnowledgeFallbackOffered"
+ "hasPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "hasPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "hasPommesSessionId"
+ "hasSafariContext"
+ "hasStatusMessage"
+ "hasTimestampInSecondsSince1970"
+ "hasUserSessionState"
+ "isEndOfRequest"
+ "isKnowledgeFallbackConfirmationShown"
+ "pommesKnowledgeFallbackConfirmationOutcomeReceived"
+ "pommesKnowledgeFallbackOffered"
+ "pommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown"
+ "pommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived"
+ "pommesSessionId"
+ "safariContext"
+ "setAccessLevel:"
+ "setAssetSetStatusEventTimestampInSecondsSince1970:"
+ "setClientProcessAssetAvailabilityStatus:"
+ "setConfirmationOutcome:"
+ "setGmsAssetAvailabilityStatus:"
+ "setHasAccessLevel:"
+ "setHasAssetSetStatusEventTimestampInSecondsSince1970:"
+ "setHasConfirmationOutcome:"
+ "setHasGmsAssetAvailabilityStatus:"
+ "setHasIsEndOfRequest:"
+ "setHasIsKnowledgeFallbackConfirmationShown:"
+ "setHasPommesKnowledgeFallbackConfirmationOutcomeReceived:"
+ "setHasPommesKnowledgeFallbackOffered:"
+ "setHasPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown:"
+ "setHasPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived:"
+ "setHasPommesSessionId:"
+ "setHasSafariContext:"
+ "setHasStatusMessage:"
+ "setHasTimestampInSecondsSince1970:"
+ "setHasUserSessionState:"
+ "setIsEndOfRequest:"
+ "setIsKnowledgeFallbackConfirmationShown:"
+ "setPommesKnowledgeFallbackConfirmationOutcomeReceived:"
+ "setPommesKnowledgeFallbackOffered:"
+ "setPommesKnowledgeFallbackTurnOffAlwaysPromptConfirmationShown:"
+ "setPommesKnowledgeFallbackTurnOffAlwaysPromptOutcomeReceived:"
+ "setPommesSessionId:"
+ "setSafariContext:"
+ "setStatusMessage:"
+ "setTimestampInSecondsSince1970:"
+ "setUserSessionState:"
+ "statusMessage"
+ "timestampInSecondsSince1970"
+ "userSessionState"
+ "{?=\"buildInstallationTimestampInSecondsSince1970\"b1\"assetSetStatusEventTimestampInSecondsSince1970\"b1}"
+ "{?=\"confirmationOutcome\"b1}"
+ "{?=\"isKnowledgeFallbackConfirmationShown\"b1}"
+ "{?=\"state\"b1\"accessLevel\"b1\"isEndOfRequest\"b1}"
+ "{?=\"timestampInSecondsSince1970\"b1\"statusMessage\"b1}"
```
