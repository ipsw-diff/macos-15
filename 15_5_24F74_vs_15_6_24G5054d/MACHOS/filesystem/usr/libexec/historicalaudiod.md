## historicalaudiod

> `/usr/libexec/historicalaudiod`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-20.0.0.0.0
-  __TEXT.__text: 0xea8
-  __TEXT.__auth_stubs: 0x290
+21.0.0.0.0
+  __TEXT.__text: 0xf24
+  __TEXT.__auth_stubs: 0x2a0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__objc_methlist: 0x20
   __TEXT.__const: 0x32

   __TEXT.__objc_classname: 0x1c
   __TEXT.__objc_methtype: 0x10
   __TEXT.__dlopen_cstrs: 0x6c
+  __TEXT.__swift5_typeref: 0x8
   __TEXT.__swift5_entry: 0x8
   __TEXT.__unwind_info: 0xb8
-  __DATA_CONST.__auth_got: 0x158
+  __DATA_CONST.__auth_got: 0x160
   __DATA_CONST.__got: 0x18
-  __DATA_CONST.__auth_ptr: 0x8
+  __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0xf8
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA.__objc_const: 0x90
   __DATA.__objc_selrefs: 0x10
   __DATA.__objc_data: 0x50
+  __DATA.__data: 0x8
   __DATA.__bss: 0x28
-  __DATA.__common: 0x30
+  __DATA.__common: 0x48
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/CoreAudioOrchestration.framework/Versions/A/CoreAudioOrchestration
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 27
-  Symbols:   69
+  Functions: 28
+  Symbols:   71
   CStrings:  29
 
Symbols:
+ _$s22CoreAudioOrchestration36CreateOrchestratorClientPortalForHAD3XPC11XPCEndpointVSgyF
+ _$s3XPC11XPCEndpointVMn
+ _swift_getTypeByMangledNameInContext2
- _$s22CoreAudioOrchestration36CreateOrchestratorClientPortalForHADyyF
```
