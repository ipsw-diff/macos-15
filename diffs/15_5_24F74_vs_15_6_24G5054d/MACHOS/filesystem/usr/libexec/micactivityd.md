## micactivityd

> `/usr/libexec/micactivityd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_imageinfo`

```diff

-20.0.0.0.0
-  __TEXT.__text: 0x9fc
-  __TEXT.__auth_stubs: 0x180
-  __TEXT.__objc_stubs: 0x20
-  __TEXT.__objc_methlist: 0x20
-  __TEXT.__const: 0x20
-  __TEXT.__gcc_except_tab: 0x48
-  __TEXT.__oslogstring: 0x22a
-  __TEXT.__cstring: 0xe6
-  __TEXT.__objc_methname: 0x1e
-  __TEXT.__objc_classname: 0x13
-  __TEXT.__objc_methtype: 0x10
-  __TEXT.__dlopen_cstrs: 0x6c
-  __TEXT.__unwind_info: 0xa0
-  __DATA_CONST.__auth_got: 0xd0
-  __DATA_CONST.__got: 0x18
-  __DATA_CONST.__const: 0x68
-  __DATA_CONST.__objc_classlist: 0x8
+21.0.0.0.0
+  __TEXT.__text: 0x2cc
+  __TEXT.__auth_stubs: 0xc0
+  __TEXT.__cstring: 0x3d
+  __TEXT.__const: 0x2
+  __TEXT.__oslogstring: 0xf
+  __TEXT.__swift5_entry: 0x8
+  __TEXT.__unwind_info: 0x70
+  __DATA_CONST.__auth_got: 0x60
+  __DATA_CONST.__auth_ptr: 0x8
+  __DATA_CONST.__const: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_superrefs: 0x8
-  __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0x10
-  __DATA.__objc_data: 0x50
-  __DATA.__bss: 0x28
+  __DATA.__bss: 0x8
+  __DATA.__common: 0x20
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
-  - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
+  - /System/Library/PrivateFrameworks/CoreAudioOrchestration.framework/Versions/A/CoreAudioOrchestration
   - /System/Library/PrivateFrameworks/caulk.framework/Versions/A/caulk
   - /usr/lib/libSystem.B.dylib
-  - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 12
-  Symbols:   34
-  CStrings:  26
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreAudio.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDarwin.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftIOKit.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_errno.dylib
+  - /usr/lib/swift/libswift_math.dylib
+  - /usr/lib/swift/libswift_signal.dylib
+  - /usr/lib/swift/libswift_stdio.dylib
+  - /usr/lib/swift/libswift_time.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  - /usr/lib/swift/libswiftsys_time.dylib
+  - /usr/lib/swift/libswiftunistd.dylib
+  Functions: 5
+  Symbols:   33
+  CStrings:  3
 
Symbols:
+ _$s22CoreAudioOrchestration36CreateOrchestratorClientPortalForMADSo21NSXPCListenerEndpointCSgyF
+ _$s2os6LoggerV9logObjectSo03OS_a1_C0Cvg
+ _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
+ _$s2os6LoggerVMa
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
+ ___chkstk_darwin
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftDarwin
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftIOKit
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_errno
+ __swift_FORCE_LOAD_$_swift_math
+ __swift_FORCE_LOAD_$_swift_signal
+ __swift_FORCE_LOAD_$_swift_stdio
+ __swift_FORCE_LOAD_$_swift_time
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftsys_time
+ __swift_FORCE_LOAD_$_swiftunistd
+ _swift_once
+ _swift_slowAlloc
+ _swift_slowDealloc
- _OBJC_CLASS_$_NSObject
- _OBJC_METACLASS_$_NSObject
- __Block_object_assign
- __Block_object_dispose
- __NSConcreteStackBlock
- __Unwind_Resume
- ___cxa_guard_acquire
- ___cxa_guard_release
- ___gxx_personality_v0
- ___stack_chk_fail
- ___stack_chk_guard
- ___stdoutp
- __objc_empty_cache
- __sl_dlopen
- _abort_report_np
- _dlerror
- _dlsym
- _free
- _fwrite
- _objc_alloc_init
- _objc_autoreleasePoolPop
- _objc_autoreleasePoolPush
- _objc_msgSend
- _objc_msgSendSuper2
- _objc_retainAutoreleaseReturnValue
- _objc_retainAutoreleasedReturnValue
- _os_log_create
- _setlinebuf
CStrings:
+ "IsolatedCoreAudioMicActivity"
+ "Launching MAD!"
- "%25s:%-5d Beginning CreateMicActivityService!\n"
- "%25s:%-5d Beginning init!"
- "%25s:%-5d CreateMicrophoneActivityPortal is true!"
- "%25s:%-5d CreateMicrophoneActivityPortal not found in IsolatedCoreAudioClient - a newer version of IsolatedCoreAudioClient may be needed!"
- "%25s:%-5d Creating the service!"
- "%25s:%-5d IsolatedCoreAudioClient is not available"
- "%25s:%-5d IsolatedCoreAudioClient microphone activity portal launched"
- "%25s:%-5d Launching micactivityd!"
- "%25s:%-5d Log 1\n"
- "%25s:%-5d Log 2\n"
- "%25s:%-5d Log 3\n"
- "%25s:%-5d isIsolatedCoreAudioClientAvailable is true!\n"
- "%s"
- "/System/Library/PrivateFrameworks/IsolatedCoreAudioClient.framework/Contents/MacOS/IsolatedCoreAudioClient"
- "@16@0:8"
- "CreateMicActivityService"
- "CreateMicrophoneActivityPortal"
- "IsolatedCoreAudioMicActivityD"
- "Launching micactivityd!\n"
- "MicActivityServer"
- "init"
- "main.mm"
- "softlink:o:path:/System/Library/PrivateFrameworks/IsolatedCoreAudioClient.framework/IsolatedCoreAudioClient"
- "v16@0:8"
- "v8@?0"
```
