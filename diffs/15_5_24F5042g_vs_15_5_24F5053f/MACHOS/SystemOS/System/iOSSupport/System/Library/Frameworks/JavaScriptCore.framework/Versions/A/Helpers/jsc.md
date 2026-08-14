## jsc

> `/System/iOSSupport/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/Helpers/jsc`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__const`

```diff

-621.2.1.11.5
-  __TEXT.__text: 0x36be4
-  __TEXT.__auth_stubs: 0x1770
+621.2.3.11.1
+  __TEXT.__text: 0x36df4
+  __TEXT.__auth_stubs: 0x1760
   __TEXT.__const: 0x218
-  __TEXT.__cstring: 0x5c61
-  __DATA_CONST.__auth_got: 0xbb8
+  __TEXT.__cstring: 0x5cb6
+  __DATA_CONST.__auth_got: 0xbb0
   __DATA_CONST.__got: 0xa0
   __DATA_CONST.__const: 0x17e8
   __DATA_CONST.__jsc_ops: 0x0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libedit.3.dylib
   Functions: 324
-  Symbols:   426
-  CStrings:  825
+  Symbols:   425
+  CStrings:  828
 
Symbols:
- __ZN3JSC2VM14clearExceptionEv
Functions:
~ sub_100005ca0 : 10964 -> 10972
~ sub_1000087a4 -> sub_1000087ac : 15084 -> 15176
~ sub_100012f84 -> sub_100012fe8 : 5072 -> 5076
~ sub_10001ccbc -> sub_10001cd24 : 55288 -> 55704
~ sub_100034348 -> sub_100034550 : 4820 -> 4828
CStrings:
+ "dumpFTLCodeSize"
+ "maximumWasmSelfRecursionDepthForInlining"
+ "ratioFTLNodesToBytecodeCost"
```
