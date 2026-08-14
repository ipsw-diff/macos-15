## SiriSetup

> `/System/Library/PrivateFrameworks/SiriSetup.framework/Versions/A/SiriSetup`

```diff

-3405.12.1.0.0
-  __TEXT.__text: 0x2e938
-  __TEXT.__auth_stubs: 0xd10
-  __TEXT.__objc_methlist: 0xd5c
-  __TEXT.__const: 0xf74
+3405.17.1.0.0
+  __TEXT.__text: 0x2eaf8
+  __TEXT.__auth_stubs: 0xd40
+  __TEXT.__objc_methlist: 0xd6c
+  __TEXT.__const: 0xf84
   __TEXT.__cstring: 0x3368
-  __TEXT.__constg_swiftt: 0x21e8
+  __TEXT.__oslogstring: 0x36
+  __TEXT.__constg_swiftt: 0x21f0
   __TEXT.__swift5_typeref: 0x9b0
   __TEXT.__swift5_reflstr: 0x1025
   __TEXT.__swift5_fieldmd: 0xe50

   __TEXT.__swift5_capture: 0x37c
   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
-  __TEXT.__oslogstring: 0x3
-  __TEXT.__unwind_info: 0x990
+  __TEXT.__unwind_info: 0x9a0
   __TEXT.__eh_frame: 0x288
   __TEXT.__objc_classname: 0x1b2
-  __TEXT.__objc_methname: 0x18e7
+  __TEXT.__objc_methname: 0x18f8
   __TEXT.__objc_methtype: 0x370
-  __TEXT.__objc_stubs: 0x820
+  __TEXT.__objc_stubs: 0x840
   __DATA_CONST.__got: 0x2b8
-  __DATA_CONST.__const: 0x210
+  __DATA_CONST.__const: 0x230
   __DATA_CONST.__objc_classlist: 0x108
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x820
+  __DATA_CONST.__objc_selrefs: 0x828
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x48
-  __AUTH_CONST.__auth_got: 0x690
-  __AUTH_CONST.__const: 0x1ae8
+  __AUTH_CONST.__auth_got: 0x6a8
+  __AUTH_CONST.__const: 0x1b10
   __AUTH_CONST.__cfstring: 0x2e0
   __AUTH_CONST.__objc_const: 0x2dd0
   __AUTH_CONST.__objc_intobj: 0x18

   __AUTH.__data: 0xb18
   __DATA.__objc_ivar: 0x68
   __DATA.__data: 0xae8
-  __DATA.__bss: 0xe80
+  __DATA.__bss: 0xe90
   __DATA.__common: 0x11
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 984
-  Symbols:   930
-  CStrings:  742
+  Functions: 988
+  Symbols:   943
+  CStrings:  745
 
Symbols:
+ -[SRSVoiceTrainingManager setSuspendAudio:]
+ SRSLog
+ SRSLog.log
+ SRSLog.onceToken
+ _SRSLog
+ __NSConcreteGlobalBlock
+ ___SRSLog_block_invoke
+ ___block_descriptor_32_e5_v8?0l
+ ___block_literal_global
+ _dispatch_once
+ _objc_msgSend$setSuspendAudio:
+ _objc_retainAutoreleaseReturnValue
+ _os_log_create
CStrings:
+ "Fetched audio session [%i]"
+ "Fetching audio session."
+ "setSuspendAudio:"
```
