## libswiftCore.dylib

> `/usr/lib/swift/libswiftCore.dylib`

```diff

-6.1.0.110.5
-  __TEXT.__text: 0x46ef38
+6.1.2.1.2
+  __TEXT.__text: 0x46f0f0
   __TEXT.__auth_stubs: 0xda0
   __TEXT.__delay_stubs: 0x108
   __TEXT.__delay_helper: 0x27c

   __TEXT.__objc_methlist: 0x1d48
   __TEXT.__const: 0xb72b4
   __TEXT.__lldbsummaries: 0x46
-  __TEXT.__cstring: 0x12a83
+  __TEXT.__cstring: 0x12b46
   __TEXT.__swift5_typeref: 0x5745
   __TEXT.__swift5_capture: 0x3ac
   __TEXT.__swift5_reflstr: 0x12c1

   __TEXT.__objc_methtype: 0x268
   __TEXT.__objc_stubs: 0x140
   __DATA_CONST.__got: 0x70
-  __DATA_CONST.__const: 0x2b18
+  __DATA_CONST.__const: 0x2b40
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_nlclslist: 0x30
   __DATA_CONST.__objc_protolist: 0x68

   __AUTH.__objc_data: 0x340
   __AUTH.__data: 0x10608
   __DATA.__objc_ivar: 0x38
-  __DATA.__data: 0xda0
+  __DATA.__data: 0xdc0
   __DATA.__crash_info: 0x40
-  __DATA.swift5_backtrace: 0x8000
-  __DATA.__bss: 0x12040
+  __DATA.swift5_backtrace: 0xc000
+  __DATA.__bss: 0x12048
   __DATA.__common: 0xa8
   __DATA_DIRTY.__objc_data: 0xc90
   __DATA_DIRTY.__data: 0xe20

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
   Functions: 21511
-  Symbols:   38685
-  CStrings:  2940
+  Symbols:   38686
+  CStrings:  2946
 
Symbols:
+ __ZN12_GLOBAL__N_124swiftBacktraceOutputPathE
+ __ZN5swift7runtime9backtrace12_GLOBAL__N_111timeout_bufE
+ __ZN5swift7runtime9backtrace12_GLOBAL__N_115backtracer_argvE
+ __ZN5swift7runtime9backtrace12_GLOBAL__N_17top_bufE
+ __ZN5swift7runtime9backtrace12_GLOBAL__N_18addr_bufE
+ __ZN5swift7runtime9backtrace12_GLOBAL__N_19limit_bufE
- __ZN12_GLOBAL__N_111timeout_bufE
- __ZN12_GLOBAL__N_115backtracer_argvE
- __ZN12_GLOBAL__N_17top_bufE
- __ZN12_GLOBAL__N_18addr_bufE
- __ZN12_GLOBAL__N_19limit_bufE
Functions:
~ __swift_spawnBacktracer : 392 -> 944
~ __ZN12_GLOBAL__N_132_swift_processBacktracingSettingEN7__swift9__runtime4llvm9StringRefES3_ : 2324 -> 2548
~ _GLOBAL__sub_I_Backtrace.cpp : 1092 -> 1268
~ __ZN12_GLOBAL__N_119handle_fatal_signalEiP9__siginfoPv : 1160 -> 648
CStrings:
+ "--format"
+ "format"
+ "json"
+ "swift runtime: backtracer output path too long; output path setting will be ignored.\n"
+ "swift runtime: unable to protect backtracer output path; path setting will be ignored.\n"
+ "swift runtime: unable to protect environment for swift-backtrace at %p; disabling backtracing.\n"
+ "swift runtime: unknown backtrace format '%.*s'\n"
+ "text"
- "swift runtime: unable to protect environment for swift-backtrace at %p: %d; disabling backtracing.\n"
- "swift runtime: unknown output-to setting '%.*s'\n"
```
