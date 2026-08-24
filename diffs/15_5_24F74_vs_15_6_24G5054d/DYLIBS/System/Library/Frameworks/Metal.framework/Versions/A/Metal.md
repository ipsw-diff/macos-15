## Metal

> `/System/Library/Frameworks/Metal.framework/Versions/A/Metal`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-368.12.0.0.0
-  __TEXT.__text: 0x1a56bc
+368.51.0.0.0
+  __TEXT.__text: 0x1a56ec
   __TEXT.__auth_stubs: 0x1c50
   __TEXT.__objc_methlist: 0x18304
   __TEXT.__gcc_except_tab: 0x92d4

   __TEXT.__unwind_info: 0x6f60
   __TEXT.__eh_frame: 0x78
   __TEXT.__objc_classname: 0x31cc
-  __TEXT.__objc_methname: 0x2ef2b
-  __TEXT.__objc_methtype: 0x18cda
+  __TEXT.__objc_methname: 0x2ef4d
+  __TEXT.__objc_methtype: 0x18ce1
   __TEXT.__objc_stubs: 0x14240
   __DATA_CONST.__got: 0x870
   __DATA_CONST.__const: 0x1898
Symbols:
+ -[MTLFunctionReflectionInternal initWithArguments:argumentCount:builtInArgumentCount:globalBindings:globalBindingCount:pluginReturnData:primitiveKind:tags:tagCount:]
+ _objc_msgSend$initWithArguments:argumentCount:builtInArgumentCount:globalBindings:globalBindingCount:pluginReturnData:primitiveKind:tags:tagCount:
- -[MTLFunctionReflectionInternal initWithArguments:argumentCount:builtInArgumentCount:pluginReturnData:primitiveKind:tags:tagCount:]
- _objc_msgSend$initWithArguments:argumentCount:builtInArgumentCount:pluginReturnData:primitiveKind:tags:tagCount:
Functions:
~ -[MTLFunctionReflectionInternal initWithArguments:argumentCount:builtInArgumentCount:pluginReturnData:primitiveKind:tags:tagCount:] -> -[MTLFunctionReflectionInternal initWithArguments:argumentCount:builtInArgumentCount:globalBindings:globalBindingCount:pluginReturnData:primitiveKind:tags:tagCount:] : 340 -> 416
~ -[MTLFunctionReflectionInternal initWithDevice:reflectionData:functionType:options:] : 784 -> 788
~ __ZN25MTLLibraryDataWithArchive20specializationHashesEv : 552 -> 544
~ __ZN25MTLLibraryDataWithArchive15stitchingHashesEv : 552 -> 544
~ __ZN25MTLLibraryDataWithArchive14functionHashesEv : 492 -> 484
~ ___80-[MTLCompiler compileStatelessFunctionRequest:reflectionOnly:completionHandler:]_block_invoke : 740 -> 732
CStrings:
+ "01:09:06"
+ "@72@0:8^@16I24I28^@32I40@44Q52^@60I68"
+ "Jun  6 2025"
+ "Jun  6 2025 01:09:06"
+ "initWithArguments:argumentCount:builtInArgumentCount:globalBindings:globalBindingCount:pluginReturnData:primitiveKind:tags:tagCount:"
- "00:46:53"
- "@60@0:8^@16I24I28@32Q40^@48I56"
- "Apr 19 2025"
- "Apr 19 2025 00:46:53"
- "initWithArguments:argumentCount:builtInArgumentCount:pluginReturnData:primitiveKind:tags:tagCount:"
```
