## libBNNS.dylib

> `/System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBNNS.dylib`

```diff

-1497.120.3.0.0
-  __TEXT.__text: 0xa0d0fc
-  __TEXT.__auth_stubs: 0x1220
-  __TEXT.__gcc_except_tab: 0x2b3c4
+1497.120.5.0.0
+  __TEXT.__text: 0xa0ce5c
+  __TEXT.__auth_stubs: 0x1230
+  __TEXT.__gcc_except_tab: 0x2b3d8
   __TEXT.__const: 0x1532f
-  __TEXT.__cstring: 0x2c545
+  __TEXT.__cstring: 0x2c893
   __TEXT.__oslogstring: 0x303
   __TEXT.__unwind_info: 0xb8c8
   __TEXT.__eh_frame: 0xbe00
   __DATA_CONST.__got: 0xf8
   __DATA_CONST.__const: 0x37e8
-  __AUTH_CONST.__auth_got: 0x918
+  __AUTH_CONST.__auth_got: 0x920
   __AUTH_CONST.__const: 0xfb28
   __AUTH_CONST.__cfstring: 0x200
   __AUTH.__data: 0x4e8

   - /System/Library/PrivateFrameworks/MIL.framework/Versions/A/MIL
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 11556
-  Symbols:   608
-  CStrings:  4300
+  Functions: 11558
+  Symbols:   610
+  CStrings:  4314
 
Symbols:
+ _BNNSGraphContextMakeWithLogging
+ __ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEElsEj
CStrings:
+ "BNNS Graph: conv op values changed, execution failed (1)"
+ "BNNS Graph: conv op values changed, execution failed (2)"
+ "BNNS Graph: ffn op values changed, execution failed (1)"
+ "BNNS Graph: ffn op values changed, execution failed (2)"
+ "BNNS Graph: ffn op values changed, execution failed (3)"
+ "BNNS Graph: layer norm encountered NaN, execution failed. (1)"
+ "BNNS Graph: layer norm encountered NaN, execution failed. (2)"
+ "BNNS Graph: layer norm op values changed, execution failed. (1)"
+ "BNNS Graph: layer norm op values changed, execution failed. (2)"
+ "BNNS Graph: layer norm op values changed, execution failed. (3)"
+ "BNNS Graph: layer norm op values changed, execution failed. (4)"
+ "BNNS Graph: mha op values changed, execution failed (1)"
+ "BNNS Graph: mha op values changed, execution failed (2)"
+ "BNNS Graph: mha op values changed, execution failed (3)"
+ "BNNS Graph: null pointer not expected"
+ "BNNS Graph: null pointer not expected (1)"
+ "BNNS Graph: null pointer not expected (2)"
+ "BNNS Graph: null pointer not expected (3)"
+ "BNNS: BNNSGraphContextMakeWithLogging failed to allocate memory"
+ "BNNS: BNNSGraphContextMakeWithLogging failed to initialize context"
+ "BNNS: BNNSGraphContextMakeWithLogging passed graph with unsupported ir_version "
+ "BNNS: BNNSGraphContextMakeWithLogging passed invalid graph"
+ "BNNSGraphContextMakeWithLogging"
+ "BasicNeuralNetworkSubroutines-1497.120.5~112"
- "BNNS Graph: conv op values changed, execution failed"
- "BNNS Graph: ffn encountered NaN, execution failed"
- "BNNS Graph: ffn op values changed, execution failed"
- "BNNS Graph: ffn_norm encountered NaN, execution failed"
- "BNNS Graph: layer norm encountered NaN, execution failed."
- "BNNS Graph: layer norm op values changed, execution failed."
- "BNNS Graph: mha encountered NaN, execution failed"
- "BNNS Graph: mha op values changed, execution failed"
- "BNNSGraphContextMake"
- "BasicNeuralNetworkSubroutines-1497.120.3~15"
```
