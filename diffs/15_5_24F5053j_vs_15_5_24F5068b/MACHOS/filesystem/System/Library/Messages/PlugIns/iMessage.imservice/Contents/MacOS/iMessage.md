## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/Contents/MacOS/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1402.600.31.0.0
-  __TEXT.__text: 0x9edf0
+1402.600.41.1.3
+  __TEXT.__text: 0x9f258
   __TEXT.__auth_stubs: 0x1100
   __TEXT.__objc_stubs: 0xaf80
   __TEXT.__objc_methlist: 0x26c4
   __TEXT.__const: 0x33e
-  __TEXT.__gcc_except_tab: 0xa840
+  __TEXT.__gcc_except_tab: 0xa8c0
   __TEXT.__cstring: 0x2cad
-  __TEXT.__oslogstring: 0x13c88
+  __TEXT.__oslogstring: 0x13d68
   __TEXT.__objc_classname: 0x4e1
   __TEXT.__objc_methname: 0x1015b
   __TEXT.__objc_methtype: 0x2779

   __TEXT.__swift_as_ret: 0x14
   __TEXT.__swift5_capture: 0xa0
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x1e38
+  __TEXT.__unwind_info: 0x1e48
   __TEXT.__eh_frame: 0x2c0
   __DATA_CONST.__auth_got: 0x890
   __DATA_CONST.__got: 0xd68

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1318
+  Functions: 1319
   Symbols:   733
-  CStrings:  4073
+  CStrings:  4076
 
CStrings:
+ "=> Received group photo update from: %@, payload: %@"
+ "About to request group photo for chatGuid %@ from %@ to %@"
+ "Group photo message parsed: isExplicitlyRequestedResponse: %d, isExplicitResponseThatWeDidNotRequest: %d, isExplicitRefresh: %d, isLegacyRequestedResponse: %d, isExplicitlyNewPhoto: %d, isAssumedLegacyNewPhoto: %d"
+ "Removing %@ from inflight photo requests list."
+ "We received a local message from a device that is not our own."
- "Group photo message parsed: isExplicitlyRequestedResponse: %d, isLegacyRequestedResponse: %d, isExplicitlyNewPhoto: %d, isAssumedLegacyNewPhoto: %d"
- "Requesting group photo for chatGuid %@ from %@ to %@"
```
