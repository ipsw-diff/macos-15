## JavaScriptCore

> `/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/JavaScriptCore`

```diff

-621.2.3.11.1
-  __TEXT.__text: 0x1789530
+621.2.4.11.2
+  __TEXT.__text: 0x1789ebc
   __TEXT.__jsc_int: 0x7e660
   __TEXT.__auth_stubs: 0x2c80
   __TEXT.__objc_methlist: 0xb9c
   __TEXT.__const: 0x8b7a8
-  __TEXT.__cstring: 0xdb8fd
+  __TEXT.__cstring: 0xdb981
   __TEXT.__gcc_except_tab: 0x2164
   __TEXT.__oslogstring: 0x5bd
   __TEXT.__unwind_info: 0x1bc0

   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__jsc_ops: 0x1990
   __AUTH_CONST.__auth_got: 0x1650
-  __AUTH_CONST.__const: 0x3a730
+  __AUTH_CONST.__const: 0x3a768
   __AUTH_CONST.__cfstring: 0xfa0
   __AUTH_CONST.__objc_const: 0xdf8
   __AUTH.__objc_data: 0x370

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 39923
-  Symbols:   48904
-  CStrings:  19689
+  Functions: 39926
+  Symbols:   48907
+  CStrings:  19692
 
Symbols:
+ __ZN3JSC4Wasm11CalleeGroup11replacementERKN3WTF14AbstractLockerENS0_18FunctionSpaceIndexE
+ __ZN9Inspector26AnimationBackendDispatcher13requestEffectElON3WTF6RefPtrINS1_8JSONImpl6ObjectENS1_12RawPtrTraitsIS4_EENS1_21DefaultRefDerefTraitsIS4_EEEE
+ __ZN9Inspector27AnimationFrontendDispatcher13effectChangedERKN3WTF6StringE
+ __ZNSt3__116__variant_detail12__visitation6__base12__dispatcherIJLm0EEE10__dispatchB8sn190102IOZNS0_6__dtorINS0_8__traitsIJN3WTF6RefPtrIN3JSC4Wasm9JITCalleeENS8_12RawPtrTraitsISC_EENS8_21DefaultRefDerefTraitsISC_EEEENSB_4Plan5ErrorEEEELNS0_6_TraitE1EE9__destroyB8sn190102EvEUlRT_E_JRNS0_6__baseILSL_1EJSH_SJ_EEEEEEDcSN_DpT0_
+ __ZNSt3__116__variant_detail12__visitation6__base12__dispatcherIJLm0EEE10__dispatchB8sn190102IOZNS0_6__dtorINS0_8__traitsIJN3WTF6RefPtrIN9Inspector8Protocol9Animation6EffectENS8_12RawPtrTraitsISD_EENS8_21DefaultRefDerefTraitsISD_EEEENS8_6StringEEEELNS0_6_TraitE1EE9__destroyB8sn190102EvEUlRT_E_JRNS0_6__baseILSL_1EJSI_SJ_EEEEEEDcSN_DpT0_
+ __ZNSt3__116__variant_detail12__visitation6__base12__dispatcherIJLm1EEE10__dispatchB8sn190102IOZNS0_6__dtorINS0_8__traitsIJN3WTF6RefPtrIN3JSC4Wasm9JITCalleeENS8_12RawPtrTraitsISC_EENS8_21DefaultRefDerefTraitsISC_EEEENSB_4Plan5ErrorEEEELNS0_6_TraitE1EE9__destroyB8sn190102EvEUlRT_E_JRNS0_6__baseILSL_1EJSH_SJ_EEEEEEDcSN_DpT0_
+ __ZNSt3__116__variant_detail12__visitation6__base12__dispatcherIJLm1EEE10__dispatchB8sn190102IOZNS0_6__dtorINS0_8__traitsIJN3WTF6RefPtrIN9Inspector8Protocol9Animation6EffectENS8_12RawPtrTraitsISD_EENS8_21DefaultRefDerefTraitsISD_EEEENS8_6StringEEEELNS0_6_TraitE1EE9__destroyB8sn190102EvEUlRT_E_JRNS0_6__baseILSL_1EJSI_SJ_EEEEEEDcSN_DpT0_
- __ZN3JSC13MetadataTable7destroyEPS0_
- __ZN9Inspector27AnimationFrontendDispatcher13effectChangedERKN3WTF6StringEONS1_6RefPtrINS_8Protocol9Animation6EffectENS1_12RawPtrTraitsIS8_EENS1_21DefaultRefDerefTraitsIS8_EEEE
- __ZZN3JSC5IPIntL26jitCompileAndSetHeuristicsEPNS_4Wasm11IPIntCalleeEPNS_21JSWebAssemblyInstanceENS0_6OSRForEENKUlvE_clEv
- __ZZN3JSC5LLIntL26jitCompileAndSetHeuristicsEPNS_4Wasm11LLIntCalleeEPNS_21JSWebAssemblyInstanceENS0_6OSRForEENKUlvE_clEv
CStrings:
+ "Expected<RefPtr<Wasm::JITCallee>, Wasm::Plan::Error> JSC::IPInt::jitCompileSIMDFunction(Wasm::IPIntCallee *, JSWebAssemblyInstance *)"
+ "Expected<RefPtr<Wasm::JITCallee>, Wasm::Plan::Error> JSC::LLInt::jitCompileSIMDFunction(Wasm::LLIntCallee *, JSWebAssemblyInstance *)"
+ "JSC::CodeBlock::~CodeBlock()"
+ "RefPtr<Wasm::Callee> JSC::Wasm::CalleeGroup::wasmCalleeFromFunctionIndexSpace(FunctionSpaceIndex)"
+ "Some arguments of method 'Animation.requestEffect' can't be processed"
+ "requestEffect"
- "Expected<Wasm::JITCallee *, Wasm::Plan::Error> JSC::IPInt::jitCompileSIMDFunction(Wasm::IPIntCallee *, JSWebAssemblyInstance *)"
- "Expected<Wasm::JITCallee *, Wasm::Plan::Error> JSC::LLInt::jitCompileSIMDFunction(Wasm::LLIntCallee *, JSWebAssemblyInstance *)"
- "Wasm::Callee *JSC::Wasm::CalleeGroup::wasmCalleeFromFunctionIndexSpace(FunctionSpaceIndex)"
```
