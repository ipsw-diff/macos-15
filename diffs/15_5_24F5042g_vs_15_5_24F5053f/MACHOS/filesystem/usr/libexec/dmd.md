## dmd

> `/usr/libexec/dmd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-221.4.7.0.0
-  __TEXT.__text: 0x65840
+221.5.1.0.0
+  __TEXT.__text: 0x657ec
   __TEXT.__auth_stubs: 0x980
-  __TEXT.__objc_stubs: 0x9880
-  __TEXT.__objc_methlist: 0x6174
+  __TEXT.__objc_stubs: 0x9860
+  __TEXT.__objc_methlist: 0x616c
   __TEXT.__const: 0x140
   __TEXT.__objc_classname: 0x1b21
-  __TEXT.__objc_methname: 0xc39e
-  __TEXT.__objc_methtype: 0x16f9
+  __TEXT.__objc_methname: 0xc281
+  __TEXT.__objc_methtype: 0x16a5
   __TEXT.__cstring: 0x427d
   __TEXT.__oslogstring: 0x69e8
   __TEXT.__gcc_except_tab: 0xc94
   __TEXT.__ustring: 0x498
   __TEXT.__unwind_info: 0x1870
   __DATA_CONST.__auth_got: 0x4d0
-  __DATA_CONST.__got: 0xef0
+  __DATA_CONST.__got: 0xef8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x1888
   __DATA_CONST.__cfstring: 0x4780

   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__objc_dictobj: 0x140
   __DATA.__objc_const: 0x1a610
-  __DATA.__objc_selrefs: 0x2be8
+  __DATA.__objc_selrefs: 0x2bd8
   __DATA.__objc_ivar: 0x374
   __DATA.__objc_data: 0x3de0
   __DATA.__data: 0xba8

   - /System/Library/PrivateFrameworks/login.framework/Versions/A/login
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2294
-  Symbols:   694
-  CStrings:  3217
+  Functions: 2293
+  Symbols:   695
+  CStrings:  3213
 
Symbols:
+ _DMFAppSourceDeclarativeManagement
CStrings:
+ "allExpiredScreenTimeBudgetsShouldBeSynchronous:replyHandler:"
+ "v28@0:8B16@?<v@?@\"NSArray\"@\"NSError\">20"
- "filterForExpiredBudgetIdentifiers:shouldBeSynchronous:replyHandler:"
- "ignoreNilConfiguration"
- "setVPNUUIDString:cellularSliceUUIDString:contentFilterUUIDString:DNSProxyUUIDString:relayUUIDString:associatedDomains:enableDirectDownloads:allowUserToHide:allowUserToLock:configuration:ignoreNilConfiguration:options:sourceIdentifier:forBundleIdentifier:"
- "v124@0:8@16@24@32@40@48@56@64@72@80@88B96Q100@108@116"
- "v36@0:8@\"NSArray\"16B24@?<v@?@\"NSArray\"@\"NSError\">28"
- "v36@0:8@16B24@?28"
```
