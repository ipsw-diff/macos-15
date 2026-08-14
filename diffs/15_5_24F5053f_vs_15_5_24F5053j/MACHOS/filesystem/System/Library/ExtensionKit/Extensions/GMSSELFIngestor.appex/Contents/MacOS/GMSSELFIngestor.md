## GMSSELFIngestor

> `/System/Library/ExtensionKit/Extensions/GMSSELFIngestor.appex/Contents/MacOS/GMSSELFIngestor`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3405.25.2.0.0
+3405.28.1.0.0
   __TEXT.__text: 0x11dcc
   __TEXT.__auth_stubs: 0x9c0
   __TEXT.__const: 0x238

   __DATA_CONST.__auth_got: 0x4e0
   __DATA_CONST.__got: 0x150
   __DATA_CONST.__auth_ptr: 0x130
-  __DATA_CONST.__const: 0x298
+  __DATA_CONST.__const: 0x2a0
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__objc_const: 0x3a0

   - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/Versions/A/SiriInstrumentation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
+  - /usr/lib/swift/libswiftCompression.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreAudio.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 121
-  Symbols:   106
+  Symbols:   107
   CStrings:  131
 
Symbols:
+ __swift_FORCE_LOAD_$_swiftCompression
```
