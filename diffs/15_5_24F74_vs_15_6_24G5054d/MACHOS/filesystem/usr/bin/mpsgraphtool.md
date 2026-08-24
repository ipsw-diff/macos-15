## mpsgraphtool

> `/usr/bin/mpsgraphtool`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-5.4.11.0.0
-  __TEXT.__text: 0x248d544
+5.6.2.0.0
+  __TEXT.__text: 0x248d584
   __TEXT.__auth_stubs: 0x2cf0
   __TEXT.__objc_stubs: 0x1000
   __TEXT.__init_offsets: 0x310
   __TEXT.__objc_methlist: 0x1d8
   __TEXT.__const: 0x10d50d
-  __TEXT.__cstring: 0x1a4714
+  __TEXT.__cstring: 0x1a4947
   __TEXT.__gcc_except_tab: 0x9fa7c
   __TEXT.__objc_methname: 0xea3
   __TEXT.__objc_classname: 0x31
Functions:
~ __ZN4mlir21createRawElementsAttrENS_16RankedTensorTypeEN4llvm8ArrayRefIcEE : 328 -> 400
~ _GLOBAL__sub_I_CompilerOptions.cpp : 3772 -> 3776
~ __ZN6google8protobuf8internal15ParseAnyTypeUrlERKNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEPS8_ : 24 -> 12
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.6.xctoolchain/usr/bin/ar"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.6.xctoolchain/usr/bin/clang"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.6.xctoolchain/usr/bin/clang++"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.6.xctoolchain/usr/bin/ld"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.5.xctoolchain/usr/bin/ar"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.5.xctoolchain/usr/bin/clang"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.5.xctoolchain/usr/bin/clang++"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/OSX15.5.xctoolchain/usr/bin/ld"
```
