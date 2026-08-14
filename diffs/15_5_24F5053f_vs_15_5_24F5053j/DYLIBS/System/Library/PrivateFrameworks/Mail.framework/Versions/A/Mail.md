## Mail

> `/System/Library/PrivateFrameworks/Mail.framework/Versions/A/Mail`

```diff

-3826.600.32.0.0
-  __TEXT.__text: 0xac662c
+3826.600.41.1.1
+  __TEXT.__text: 0xac68a4
   __TEXT.__auth_stubs: 0x5eb0
   __TEXT.__objc_methlist: 0x1917c
   __TEXT.__const: 0x435b0
-  __TEXT.__gcc_except_tab: 0x4ef6c
-  __TEXT.__cstring: 0x33481
-  __TEXT.__oslogstring: 0x1e39b
+  __TEXT.__gcc_except_tab: 0x4efb0
+  __TEXT.__cstring: 0x33471
+  __TEXT.__oslogstring: 0x1e4fb
   __TEXT.__ustring: 0x44
   __TEXT.__swift5_typeref: 0xfa22
   __TEXT.__constg_swiftt: 0xbc60

   __TEXT.__unwind_info: 0x23078
   __TEXT.__eh_frame: 0x1bb1c
   __TEXT.__objc_classname: 0x396c
-  __TEXT.__objc_methname: 0x3d956
+  __TEXT.__objc_methname: 0x3d94e
   __TEXT.__objc_methtype: 0x636c
   __TEXT.__objc_stubs: 0x2d240
   __DATA_CONST.__got: 0x34d8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 49909
+  Functions: 49910
   Symbols:   27347
-  CStrings:  18177
+  CStrings:  18182
 
Symbols:
+ __54-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke
+ __54-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke_2
- __54-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke_3
- ___54-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke_3
Functions:
~ ___54-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke_2 : 548 -> 784
~ -[MFLibraryStore getTopLevelMimePart:headers:body:forMessage:fetchIfNotAvailable:updateFlags:allowPartial:skipSignatureVerification:decodeContext:] : 1616 -> 1752
~ -[MFLibraryStore _getTopLevelMimePart:headers:body:forMessage:fetchIfNotAvailable:updateFlags:allowPartial:skipSignatureVerification:decodeContext:] : 2544 -> 2736
+ __54-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke_2.cold.1
CStrings:
+ "%{public}@: Message is not using default decoder to getTopLevelMimePart"
+ "-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke"
+ "Fetch operation cannot be added as dependency as parent operation is null"
+ "MFLibraryStore: don't need mime part, already have body and headers cached for message: %{public}@"
+ "Message is not available locally: %{public}@"
+ "Only want headers, not fetching/parsing the body for message: %{public}@"
+ "T@\"EMFollowUp\",&"
+ "T@\"EMFollowUp\",&,V_followUp"
+ "T@\"EMGeneratedSummary\",C"
+ "T@\"EMGeneratedSummary\",C,V_generatedSummary"
- "-[MFMessageContext async_cacheBodyForMessage:monitor:]_block_invoke_3"
- "T@\"EMFollowUp\",&,N"
- "T@\"EMFollowUp\",&,N,V_followUp"
- "T@\"EMGeneratedSummary\",C,N"
- "T@\"EMGeneratedSummary\",C,N,V_generatedSummary"
```
