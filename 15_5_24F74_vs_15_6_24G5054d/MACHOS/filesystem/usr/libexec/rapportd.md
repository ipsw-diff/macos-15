## rapportd

> `/usr/libexec/rapportd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`

```diff

-660.5.1.0.0
-  __TEXT.__text: 0xf0c80
+680.1.1.0.0
+  __TEXT.__text: 0xf108c
   __TEXT.__auth_stubs: 0x2930
-  __TEXT.__objc_stubs: 0xdec0
+  __TEXT.__objc_stubs: 0xdee0
   __TEXT.__objc_methlist: 0x6c54
   __TEXT.__objc_classname: 0x8f8
-  __TEXT.__objc_methtype: 0x356f
-  __TEXT.__objc_methname: 0x1395a
-  __TEXT.__cstring: 0x23871
-  __TEXT.__const: 0x2ff6
+  __TEXT.__objc_methtype: 0x3580
+  __TEXT.__objc_methname: 0x13978
+  __TEXT.__cstring: 0x23991
+  __TEXT.__const: 0x3286
   __TEXT.__gcc_except_tab: 0x1e34
   __TEXT.__oslogstring: 0x105f
   __TEXT.__swift5_typeref: 0x956

   __TEXT.__swift5_assocty: 0x90
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_acfuncs: 0x3c
-  __TEXT.__unwind_info: 0x3538
+  __TEXT.__unwind_info: 0x3540
   __TEXT.__eh_frame: 0x27e0
   __DATA_CONST.__auth_got: 0x14a8
   __DATA_CONST.__got: 0x670
   __DATA_CONST.__auth_ptr: 0x398
-  __DATA_CONST.__const: 0x53b0
+  __DATA_CONST.__const: 0x5450
   __DATA_CONST.__cfstring: 0x5440
   __DATA_CONST.__objc_classlist: 0x268
   __DATA_CONST.__objc_protolist: 0x148

   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_dictobj: 0x50
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA.__objc_const: 0xc178
-  __DATA.__objc_selrefs: 0x4560
-  __DATA.__objc_ivar: 0xc98
+  __DATA.__objc_const: 0xc198
+  __DATA.__objc_selrefs: 0x4568
+  __DATA.__objc_ivar: 0xc9c
   __DATA.__objc_data: 0x1a80
-  __DATA.__data: 0x29a0
-  __DATA.__bss: 0x23d0
+  __DATA.__data: 0x2740
+  __DATA.__bss: 0x2400
   __DATA.__common: 0x68
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 5064
+  Functions: 5077
   Symbols:   1005
-  CStrings:  7719
+  CStrings:  7725
 
CStrings:
+ "680.1.1"
+ "@\"OS_dispatch_queue\"16@0:8"
+ "Sending session stop message for session that has already been invalidated: Service %@, PeerID %@, SID 0x%llX\n"
+ "Session start response received after session was already invalidated."
+ "T@\"OS_dispatch_queue\",&,N"
+ "Waiting to send session stop request for session that has not completed starting: Service %@, PeerID %@"
+ "_pendingSessionStopsMap"
+ "localIdentifier"
+ "v24@0:8@\"OS_dispatch_queue\"16"
- "660.5.1"
- "T@\"NSObject<OS_dispatch_queue>\",&,N"
- "v24@0:8@\"NSObject<OS_dispatch_queue>\"16"
```
