## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/Contents/MacOS/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-1402.600.41.1.5
-  __TEXT.__text: 0x9f258
+1402.700.41.0.0
+  __TEXT.__text: 0x9f398
   __TEXT.__auth_stubs: 0x1100
   __TEXT.__objc_stubs: 0xaf80
   __TEXT.__objc_methlist: 0x26c4
-  __TEXT.__const: 0x33e
+  __TEXT.__const: 0x38a
   __TEXT.__gcc_except_tab: 0xa8c0
-  __TEXT.__cstring: 0x2cad
-  __TEXT.__oslogstring: 0x13d68
+  __TEXT.__cstring: 0x2d0d
+  __TEXT.__oslogstring: 0x13d88
   __TEXT.__objc_classname: 0x4e1
-  __TEXT.__objc_methname: 0x1015b
-  __TEXT.__objc_methtype: 0x2779
+  __TEXT.__objc_methname: 0x10169
+  __TEXT.__objc_methtype: 0x277d
   __TEXT.__ustring: 0x4
   __TEXT.__constg_swiftt: 0x178
   __TEXT.__swift5_typeref: 0x261

   __DATA_CONST.__got: 0xd68
   __DATA_CONST.__auth_ptr: 0x18
   __DATA_CONST.__const: 0x2f90
-  __DATA_CONST.__cfstring: 0x3180
+  __DATA_CONST.__cfstring: 0x31c0
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x78

   __DATA.__objc_selrefs: 0x3318
   __DATA.__objc_ivar: 0x1b0
   __DATA.__objc_data: 0x888
-  __DATA.__data: 0x798
+  __DATA.__data: 0x750
   __DATA.__bss: 0xa8
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 1319
   Symbols:   733
-  CStrings:  4076
+  CStrings:  4078
 
Functions:
~ sub_3a5b0 : 3584 -> 3596
~ sub_41400 -> sub_4140c : 5032 -> 5096
~ sub_427a8 -> sub_427f4 : 728 -> 732
~ sub_42cd4 -> sub_42d24 : 3132 -> 3324
~ sub_43910 -> sub_43a20 : 1368 -> 1380
~ sub_44e94 -> sub_44fb0 : 620 -> 628
~ sub_45100 -> sub_45224 : 520 -> 524
~ sub_470b8 -> sub_471e0 : 1252 -> 1256
~ sub_4759c -> sub_476c8 : 1604 -> 1616
~ sub_47ee8 -> sub_48020 : 924 -> 928
~ sub_4c384 -> sub_4c4c0 : 316 -> 320
CStrings:
+ "Couldn't send new features to these destinations: %@, [%lu] times we're in fallback"
+ "MessageDeliveryControllerTooManyFallbacks"
+ "Repeatedly trying to send fallback message"
+ "_sendMessage:context:deliveryContext:fromID:fromAccount:toID:chatIdentifier:toSessionToken:toGroup:toParticipants:originallyToParticipants:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:canInlineAttachments:type:msgPayloadUploadDictionary:originalPayload:replyToMessageGUID:fallbackCount:willSendBlock:completionBlock:"
+ "v188@0:8@16@24@32@40@48@56@64@72@80@88@96@104@112@120B128q132@140@148@156Q164@?172@?180"
- "Couldn't send new features to these destinations: %@"
- "_sendMessage:context:deliveryContext:fromID:fromAccount:toID:chatIdentifier:toSessionToken:toGroup:toParticipants:originallyToParticipants:requiredRegProperties:interestingRegProperties:requiresLackOfRegProperties:canInlineAttachments:type:msgPayloadUploadDictionary:originalPayload:replyToMessageGUID:willSendBlock:completionBlock:"
- "v180@0:8@16@24@32@40@48@56@64@72@80@88@96@104@112@120B128q132@140@148@156@?164@?172"
```
