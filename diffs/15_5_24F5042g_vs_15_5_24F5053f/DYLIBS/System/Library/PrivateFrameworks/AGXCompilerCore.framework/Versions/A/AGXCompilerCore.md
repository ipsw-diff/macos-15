## AGXCompilerCore

> `/System/Library/PrivateFrameworks/AGXCompilerCore.framework/Versions/A/AGXCompilerCore`

```diff

-325.36.0.0.0
-  __TEXT.__text: 0x1ce50c
+327.1.0.0.0
+  __TEXT.__text: 0x1ce5d0
   __TEXT.__auth_stubs: 0x2230
   __TEXT.__const: 0x48d30
-  __TEXT.__cstring: 0x158c3
+  __TEXT.__cstring: 0x158c2
   __TEXT.__oslogstring: 0x40f
   __TEXT.__objc_methname: 0xb
   __TEXT.__objc_stubs: 0x20

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 5753
-  Symbols:   8307
+  Symbols:   8308
   CStrings:  3840
 
Symbols:
+ ___chkstk_darwin
Functions:
~ __ZN17AGCLLVMUserObject26replaceRaytracingFunctionsEv : 17456 -> 17524
~ __ZN10AGCLLVMCtxC1ERK19AGCLLVMTargetConfigN4llvm3AGX11AGXCompilerE3ApiRKNSt3__112basic_stringIcNS7_11char_traitsIcEENS7_9allocatorIcEEEESF_ : 680 -> 684
~ __ZN24AGCLLVMGen6TargetLowererI23RaytracingConstantsGen1E30buildConvertHFP8_ParseArgTypesEPN4llvm8CallInstE : 548 -> 616
~ __ZN24AGCLLVMGen6TargetLowererI23RaytracingConstantsGen1E19buildSimdMatrixInitEPN4llvm8CallInstEb : 876 -> 884
~ __ZN24AGCLLVMGen6TargetLowererI23RaytracingConstantsGen1E28buildSimdMatrixLoadStoreImplEbPN4llvm4TypeEPNS2_5ValueES6_S6_S6_S6_ : 1060 -> 1072
~ __ZN24AGCLLVMGen6TargetLowererI23RaytracingConstantsGen1E42buildSimdMatrix16x16MultiplyAccumulateImplEPN4llvm4TypeEPNS2_5ValueES6_S6_S6_S6_bbbbNSt3__16vectorINS2_9StringRefENS7_9allocatorIS9_EEEE : 3672 -> 3708
CStrings:
+ "v8f8"
- ".v256"
```
