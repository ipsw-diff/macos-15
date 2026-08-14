## AppleServiceToolkit

> `/System/Library/PrivateFrameworks/AppleServiceToolkit.framework/Versions/A/AppleServiceToolkit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-198.0.0.0.0
-  __TEXT.__text: 0x3148c
-  __TEXT.__auth_stubs: 0x540
-  __TEXT.__objc_methlist: 0x3754
+203.0.0.0.0
+  __TEXT.__text: 0x316d0
+  __TEXT.__auth_stubs: 0x550
+  __TEXT.__objc_methlist: 0x377c
   __TEXT.__const: 0x170
-  __TEXT.__cstring: 0x28a1
-  __TEXT.__oslogstring: 0x20ea
-  __TEXT.__gcc_except_tab: 0x12ac
-  __TEXT.__unwind_info: 0xc68
+  __TEXT.__cstring: 0x293f
+  __TEXT.__oslogstring: 0x2104
+  __TEXT.__gcc_except_tab: 0x13f4
+  __TEXT.__unwind_info: 0xc70
   __TEXT.__objc_classname: 0x739
-  __TEXT.__objc_methname: 0x75f3
+  __TEXT.__objc_methname: 0x7616
   __TEXT.__objc_methtype: 0x1aa4
   __TEXT.__objc_stubs: 0x58e0
   __DATA_CONST.__got: 0x330
-  __DATA_CONST.__const: 0x3a8
+  __DATA_CONST.__const: 0x3c8
   __DATA_CONST.__objc_classlist: 0x1f8
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1be0
+  __DATA_CONST.__objc_selrefs: 0x1be8
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x1a8
   __DATA_CONST.__objc_arraydata: 0x110
-  __AUTH_CONST.__auth_got: 0x2b0
-  __AUTH_CONST.__const: 0xaf0
-  __AUTH_CONST.__cfstring: 0x29e0
-  __AUTH_CONST.__objc_const: 0x61c0
+  __AUTH_CONST.__auth_got: 0x2b8
+  __AUTH_CONST.__const: 0xb10
+  __AUTH_CONST.__cfstring: 0x2980
+  __AUTH_CONST.__objc_const: 0x61f0
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH.__objc_data: 0x13b0
-  __DATA.__objc_ivar: 0x390
+  __DATA.__objc_ivar: 0x394
   __DATA.__data: 0x800
   __DATA.__bss: 0x170
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1244
-  Symbols:   3021
-  CStrings:  2149
+  Functions: 1248
+  Symbols:   3030
+  CStrings:  2156
 
Symbols:
+ -[ASTAction completion]
+ -[ASTAction setCompletion:]
+ -[ASTControlCommand completionArray]
+ GCC_except_table106
+ GCC_except_table117
+ GCC_except_table12
+ GCC_except_table121
+ GCC_except_table77
+ GCC_except_table83
+ GCC_except_table88
+ GCC_except_table98
+ GCC_except_table99
+ OBJC_IVAR_$_ASTAction._completion
+ ___51-[ASTRemoteServerSession _continueWithLastRequest:]_block_invoke
+ ___51-[ASTRemoteServerSession _continueWithLastRequest:]_block_invoke_2
+ ___block_descriptor_32_e21_v32?0?<v?>8Q16^B24l
+ _objc_msgSend$completionArray
+ _objc_setProperty_atomic_copy
- GCC_except_table104
- GCC_except_table107
- GCC_except_table119
- GCC_except_table73
- GCC_except_table81
- GCC_except_table84
- GCC_except_table91
- GCC_except_table96
- _objc_msgSend$diagnosticMode
CStrings:
+ "-[ASTRemoteServerSession _authInfoIfNecessary]"
+ "-[ASTRemoteServerSession _endAndUnenrollIfNecessary:]"
+ "-[ASTRemoteServerSession _profile]"
+ "-[ASTRemoteServerSession _teardown]"
+ "-[ASTRemoteServerSession sendAuthInfoResult:error:]"
+ "T@?,C,V_completion"
+ "[ASTRemoteServerSession] %s"
+ "[ASTRemoteServerSession] %s phase: %ld"
+ "[ASTRemoteServerSession] %s session has been requested to end, exiting.."
+ "completionArray"
+ "v32@?0@?<v@?>8Q16^B24"
- "1.6"
- "AST/%@ (Macintosh; Intel Mac OS X %@; %@) Version/%@ Build/%@ %@/%@"
- "CPUArchitecture"
- "[ASTConnectionManager] Protocol version mismatch, device prepare endpoint is operating under protocol version 1.7"
```
