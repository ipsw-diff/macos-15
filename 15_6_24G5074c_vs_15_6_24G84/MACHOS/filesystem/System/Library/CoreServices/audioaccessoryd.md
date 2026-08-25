## audioaccessoryd

> `/System/Library/CoreServices/audioaccessoryd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 25.4.0.0.0
-  __TEXT.__text: 0x1c7a30
+  __TEXT.__text: 0x1c7e1c
   __TEXT.__auth_stubs: 0x2600
-  __TEXT.__objc_stubs: 0xe180
+  __TEXT.__objc_stubs: 0xe1a0
   __TEXT.__objc_methlist: 0x6c10
   __TEXT.__const: 0x3c00
   __TEXT.__gcc_except_tab: 0x3784
-  __TEXT.__cstring: 0x2c613
+  __TEXT.__cstring: 0x2c7b3
   __TEXT.__objc_classname: 0x685
   __TEXT.__objc_methname: 0x15020
   __TEXT.__objc_methtype: 0x23ce

   __TEXT.__swift5_capture: 0x25e8
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0x4118
+  __TEXT.__unwind_info: 0x4128
   __TEXT.__eh_frame: 0x2200
   __DATA_CONST.__auth_got: 0x1310
   __DATA_CONST.__got: 0x918
-  __DATA_CONST.__auth_ptr: 0x6e0
+  __DATA_CONST.__auth_ptr: 0x6f0
   __DATA_CONST.__const: 0xb1f0
-  __DATA_CONST.__cfstring: 0x77a0
+  __DATA_CONST.__cfstring: 0x77e0
   __DATA_CONST.__objc_classlist: 0x1e8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x108

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 6977
+  Functions: 6980
   Symbols:   1047
-  CStrings:  8843
+  CStrings:  8851
 
CStrings:
+ "-[BTServicesDaemon _audioQualityShowBanner:title:deviceAddressString:messageKey:messageArgs:timeoutSeconds:]"
+ "-[BTServicesDaemon _audioQualityShowBanner:title:deviceAddressString:messageKey:messageArgs:timeoutSeconds:]_block_invoke"
+ "AudioQualityMonitor"
+ "Banner-AudioQualityMonitor"
+ "Voice Call"
+ "audioQuality banner click result %d"
+ "audioQuality banner user click"
+ "audioQuality: Type %s, Name %@, Addr %@,  Timeout %.3f"
```
