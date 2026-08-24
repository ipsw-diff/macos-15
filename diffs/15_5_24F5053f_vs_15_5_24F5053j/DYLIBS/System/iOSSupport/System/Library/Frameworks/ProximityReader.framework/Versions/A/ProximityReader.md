## ProximityReader

> `/System/iOSSupport/System/Library/Frameworks/ProximityReader.framework/Versions/A/ProximityReader`

```diff

-134.20.0.0.0
-  __TEXT.__text: 0x7e348
-  __TEXT.__auth_stubs: 0x1a60
+135.1.0.0.0
+  __TEXT.__text: 0x7d458
+  __TEXT.__auth_stubs: 0x1a80
   __TEXT.__objc_methlist: 0x260
-  __TEXT.__const: 0x3910
-  __TEXT.__cstring: 0x418c
+  __TEXT.__const: 0x3930
+  __TEXT.__cstring: 0x410c
   __TEXT.__swift5_typeref: 0xe34
-  __TEXT.__swift5_reflstr: 0x1e02
+  __TEXT.__swift5_reflstr: 0x1e12
   __TEXT.__swift5_assocty: 0x210
   __TEXT.__constg_swiftt: 0x14bc
   __TEXT.__swift5_fieldmd: 0x1b0c
   __TEXT.__swift5_proto: 0x28c
   __TEXT.__swift5_types: 0x194
-  __TEXT.__swift5_protos: 0x10
-  __TEXT.__swift5_capture: 0x5d0
-  __TEXT.__swift5_builtin: 0x64
-  __TEXT.__oslogstring: 0x1622
   __TEXT.__swift_as_entry: 0x1b8
   __TEXT.__swift_as_ret: 0x1b8
+  __TEXT.__swift5_capture: 0x5d0
+  __TEXT.__oslogstring: 0x1562
+  __TEXT.__swift5_builtin: 0x64
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x21a8
-  __TEXT.__eh_frame: 0x3f78
+  __TEXT.__swift5_protos: 0x10
+  __TEXT.__unwind_info: 0x2168
+  __TEXT.__eh_frame: 0x3e60
   __TEXT.__objc_classname: 0x22
   __TEXT.__objc_methname: 0x8be
   __TEXT.__objc_methtype: 0x38
   __TEXT.__objc_stubs: 0x1e0
-  __DATA_CONST.__got: 0x540
+  __DATA_CONST.__got: 0x538
   __DATA_CONST.__const: 0x140
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x2d8
   __DATA_CONST.__objc_protorefs: 0x28
-  __AUTH_CONST.__auth_got: 0xd38
+  __AUTH_CONST.__auth_got: 0xd48
   __AUTH_CONST.__const: 0x3218
   __AUTH_CONST.__cfstring: 0x5c0
   __AUTH_CONST.__objc_const: 0x11a0
   __AUTH.__objc_data: 0x2d0
   __AUTH.__data: 0x1f80
-  __DATA.__data: 0xc30
-  __DATA.__bss: 0x5a30
-  __DATA.__common: 0x98
+  __DATA.__data: 0xc28
+  __DATA.__bss: 0x5a20
+  __DATA.__common: 0x50
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2590
-  Symbols:   706
-  CStrings:  588
+  Functions: 2585
+  Symbols:   705
+  CStrings:  579
 
Symbols:
- _objc_release_x28
CStrings:
+ "Closed by remote?=%{bool,public}d"
+ "Error (%s: %{public}@"
+ "Error (%s: a previous request is running, returning busy"
+ "Error (%s: proxy error handler [ %s ]"
+ "Error (%s: unexpected error [ %s ]"
+ "Error (%s: unexpected proxy type"
+ "Error (capturePIN): %{public}s"
+ "Error (closeSession): proxy error handler [ %s ]"
+ "Error (closeSession): unexpected proxy type"
+ "Error (isAccountLinked): %{public}s"
+ "Error (linkAccount): %{public}s"
+ "Error (prepare): %{public}s"
+ "Error (prepare): unexpected session type"
+ "Error (prepare): unknown"
+ "Error (read): %{public}s"
+ "Error (readerIdentifier): %{public}s"
+ "Error (refreshContext): isRead = %{bool,public}d, failed"
+ "Error (refreshContext): proxy error handler [ %s ]"
+ "Error (refreshContext): unexpected proxy type"
+ "Error (status): %{public}s"
+ "Error (storeAndForwardDecline): %{public}s"
+ "Error (storeAndForwardDecline): unexpected error [ %s ]"
+ "Error (storeAndForwardStatus): %{public}s"
+ "Error (storeAndForwardStatus): unexpected error [ %s ]"
+ "Going to background, disconnecting"
+ "No VAS merchant provided"
+ "OS deprecation date: %{public}s"
+ "PIN capture is not supported during a SAF session"
+ "PIN token is empty"
+ "Result (cancelRead): %{bool,public}d"
+ "Result (fetchStoredPaymentCardReadResultBatch): success"
+ "Result (fetchStoredPaymentCardReadResultCount): success"
+ "Result (isAccountLinked): %{bool,public}d"
+ "Result (read): success"
+ "Result (readerIdentifier): %{public}s"
+ "Result (refreshContext): success"
+ "Result (resetBatchState): success"
+ "Result (resolveBatch): success"
+ "Result (storeAndForwardDecline): success"
+ "Result (storeAndForwardStatus): success"
+ "Session is wrong, nil or invalidated [ %s ]"
+ "Transaction ID is invalid"
+ "Transactions received [%ld] do not match the requested [%ld]"
+ "Unknown store error: %@"
+ "Unknown transaction data type [ %ld ]"
+ "Warning (%s: backgroundRequestNotAllowed"
+ "Warning (%s: readFromBackgroundError"
+ "XPC service disconnected"
+ "added eventHandlers=%{public}ld"
+ "added updateHandlers=%{public}ld"
+ "closing session with delete=%{bool,public}d"
+ "events stream cancelled"
+ "last reader removed, releasing connection"
+ "prepareStoreAndForward()"
+ "readerFeedback: %{public}s, eventHandlers count=%{public}ld"
+ "readerIdentifier retrieved from cache"
+ "removed eventHandlers=%{public}ld"
+ "removed updateHandlers=%{public}ld"
- "AID validated - %{private}s"
- "Application not in foreground, returning from %s"
- "Application not in foreground, returning from [%s]"
- "Attempting to access %s - Not Supported"
- "Calling capturePIN in a SAF session, not supported"
- "Error (%s): [%@]"
- "Error (%s): a previous request is running, returning busy"
- "Error (%s): a previous store request is running, returning busy"
- "Error (%s): proxy error handler: %@"
- "Error (%s): unexpected error received: [%@]"
- "Error (%s): unexpected error type"
- "Error (capturePIN): %s"
- "Error (context): Unexpected error type"
- "Error (context): isRead = %{bool}d, %@"
- "Error (context): isRead = %{bool}d, ReadError.readNotAllowed"
- "Error (decline): %@"
- "Error (decline): unexpected error [%@]"
- "Error (isAccountLinked): %s"
- "Error (linkAccount): %s"
- "Error (prepare): %s"
- "Error (prepare): ErrorDetails.unknownSessionError"
- "Error (read): %s"
- "Error (readerIdentifier): %s"
- "Error (status): %s"
- "Error (storeAndForwardStatus): %@"
- "Error (storeAndForwardStatus): unexpected error [%@]"
- "Error while closing reader session"
- "Going to background, disconnect"
- "OS deprecation date: %s"
- "PIN token invalid! PIN Token empty."
- "PIN transaction ID is invalid"
- "PaymentCardReadResult - %@"
- "PaymentCardReader destroyed"
- "PaymentCardReaderSession destroyed"
- "PaymentTerminalServiceDelegate.closed(), remote?=%{bool}d"
- "Result (cancelRead): result = %{bool}d"
- "Result (context): context created"
- "Result (isAccountLinked): returned %{bool}d"
- "Result (prepare): Unexpected session type"
- "Result (read): success with result"
- "Result (readerIdentifier): success %s"
- "Result (storeAndForwardStatus): %@"
- "Returning batch result with [%ld] transactions"
- "Service XPC disconnected"
- "Session is wrong, nil or invalidated [%s]"
- "Success (decline): Transaction declined"
- "Transactions received[%ld] do not match the requested[%ld]"
- "Unknown StoreErrorInternal: %@"
- "Unknown transaction data type [%ld]"
- "User cancelled"
- "added eventHandlers=%ld"
- "added updateHandlers=%ld"
- "cancel transaction"
- "closeSession | remote proxy error handler: %@"
- "closeSession | remote proxy was not of expected type"
- "closing session with delete=%{bool}d"
- "getTerminalId() - retrieve from cache"
- "no VAS merchant provided"
- "prepare(using:options:)"
- "prepare(using:options:updateHandler:)"
- "prepareStoreAndForward(options:)"
- "read(_:_:eventHandler:)"
- "reader Last reader removed, release connection"
- "readerFeedback: %s, eventHandlers count=%ld"
- "refreshContext | remote proxy error handler: %@"
- "removed eventHandlers=%ld"
- "removed updateHandlers=%ld"
```
