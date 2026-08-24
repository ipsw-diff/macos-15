## GMSSELFIngestor

> `/System/Library/ExtensionKit/Extensions/GMSSELFIngestor.appex/Contents/MacOS/GMSSELFIngestor`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3405.28.1.0.0
-  __TEXT.__text: 0x11dcc
-  __TEXT.__auth_stubs: 0x9c0
-  __TEXT.__const: 0x238
-  __TEXT.__cstring: 0x46a
-  __TEXT.__swift5_typeref: 0x22f
+3406.9.1.0.0
+  __TEXT.__text: 0x13624
+  __TEXT.__auth_stubs: 0x9f0
+  __TEXT.__const: 0x248
+  __TEXT.__cstring: 0x4fa
+  __TEXT.__swift5_typeref: 0x235
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constg_swiftt: 0x178
-  __TEXT.__swift5_reflstr: 0x1e3
-  __TEXT.__swift5_fieldmd: 0x148
+  __TEXT.__swift5_reflstr: 0x203
+  __TEXT.__swift5_fieldmd: 0x154
   __TEXT.__swift5_assocty: 0x30
-  __TEXT.__oslogstring: 0xb1a
-  __TEXT.__objc_methname: 0x2a9
+  __TEXT.__oslogstring: 0xc5a
+  __TEXT.__objc_methname: 0x2ae
   __TEXT.__swift5_capture: 0x14
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_types: 0x10

   __TEXT.__swift_as_ret: 0x4
   __TEXT.__unwind_info: 0x1c0
   __TEXT.__eh_frame: 0xa8
-  __DATA_CONST.__auth_got: 0x4e0
-  __DATA_CONST.__got: 0x150
+  __DATA_CONST.__auth_got: 0x4f8
+  __DATA_CONST.__got: 0x158
   __DATA_CONST.__auth_ptr: 0x130
-  __DATA_CONST.__const: 0x2a0
+  __DATA_CONST.__const: 0x2a8
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA.__objc_const: 0x3a0
+  __DATA.__objc_const: 0x3c0
   __DATA.__objc_selrefs: 0x140
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x450
   __DATA.__bss: 0x280
-  __DATA.__common: 0xa0
+  __DATA.__common: 0xa8
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/ExtensionFoundation.framework/Versions/A/ExtensionFoundation

   - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/Versions/A/SiriInstrumentation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  - /usr/lib/swift/libswiftCompression.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreAudio.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 121
-  Symbols:   107
-  CStrings:  131
+  Functions: 120
+  Symbols:   106
+  CStrings:  139
 
Symbols:
- __swift_FORCE_LOAD_$_swiftCompression
CStrings:
+ "ClientRequestStartEvent"
+ "Failed to compute latency for request due to critical event missing %s"
+ "GMSSELFIngestor.processEvent() event type: com.apple.mm.executeRequest.begin"
+ "RequestLink sourceID:%s sourceComponent: COMPONENTNAME_TRACE, targetID %s targetComponent: COMPONENTNAME_GMS"
+ "com.apple.mm.executeRequest.begin"
+ "isUserSignedIn set to: %s"
+ "promptRequestStartEvent"
+ "requestStartEvent"
+ "setIsWebSearchUsed:"
+ "signedInStatusEvent.metadata: not match"
+ "webSearchStatusEvent.metadata: not match"
- "Failed to compute latency for request %s"
- "isUserSignedIn"
- "isUserSignedIn set to: %{bool}d"
```
