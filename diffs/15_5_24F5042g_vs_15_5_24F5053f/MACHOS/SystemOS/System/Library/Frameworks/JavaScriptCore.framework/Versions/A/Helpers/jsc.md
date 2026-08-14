## jsc

> `/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/Helpers/jsc`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__const`

```diff

-621.2.1.11.5
-  __TEXT.__text: 0x36ff4
-  __TEXT.__auth_stubs: 0x1760
+621.2.3.11.1
+  __TEXT.__text: 0x37204
+  __TEXT.__auth_stubs: 0x1750
   __TEXT.__const: 0x218
-  __TEXT.__cstring: 0x5c3c
-  __DATA_CONST.__auth_got: 0xbb0
+  __TEXT.__cstring: 0x5c91
+  __DATA_CONST.__auth_got: 0xba8
   __DATA_CONST.__got: 0xa0
   __DATA_CONST.__const: 0x17e8
   __DATA_CONST.__jsc_ops: 0x0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libedit.3.dylib
   Functions: 326
-  Symbols:   425
-  CStrings:  825
+  Symbols:   424
+  CStrings:  828
 
Symbols:
- __ZN3JSC2VM14clearExceptionEv
Functions:
~ sub_100005c90 : 10940 -> 10948
~ sub_10000877c -> sub_100008784 : 15084 -> 15176
~ sub_10001336c -> sub_1000133d0 : 5072 -> 5076
~ sub_10001d0bc -> sub_10001d124 : 55288 -> 55704
~ sub_100034748 -> sub_100034950 : 4820 -> 4828
CStrings:
+ "dumpFTLCodeSize"
+ "maximumWasmSelfRecursionDepthForInlining"
+ "ratioFTLNodesToBytecodeCost"
```
