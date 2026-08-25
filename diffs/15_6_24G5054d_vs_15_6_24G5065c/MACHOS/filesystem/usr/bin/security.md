## security

> `/usr/bin/security`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-61439.140.8.0.0
-  __TEXT.__text: 0x23254
-  __TEXT.__auth_stubs: 0x1ef0
+61439.140.10.0.0
+  __TEXT.__text: 0x236a4
+  __TEXT.__auth_stubs: 0x1f30
   __TEXT.__objc_stubs: 0x9e0
   __TEXT.__objc_methlist: 0x128
   __TEXT.__const: 0x828
   __TEXT.__dlopen_cstrs: 0x10b
   __TEXT.__gcc_except_tab: 0xe00
-  __TEXT.__cstring: 0xc08a
+  __TEXT.__cstring: 0xc24d
   __TEXT.__oslogstring: 0x326
   __TEXT.__objc_classname: 0x12
   __TEXT.__objc_methname: 0x714
   __TEXT.__objc_methtype: 0xed
   __TEXT.__dof_security_: 0x2a0
-  __TEXT.__unwind_info: 0x840
-  __DATA_CONST.__auth_got: 0xf90
-  __DATA_CONST.__got: 0x3f8
+  __TEXT.__unwind_info: 0x850
+  __DATA_CONST.__auth_got: 0xfb0
+  __DATA_CONST.__got: 0x418
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA_CONST.__const: 0x19e8
+  __DATA_CONST.__const: 0x1c08
   __DATA_CONST.__cfstring: 0xbc0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA.__objc_ivar: 0x20
   __DATA.__objc_data: 0x50
   __DATA.__data: 0xa8
-  __DATA.__bss: 0x1700
+  __DATA.__bss: 0x1708
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 424
-  Symbols:   645
-  CStrings:  1215
+  Functions: 428
+  Symbols:   653
+  CStrings:  1231
 
Symbols:
+ _CFRunLoopRun
+ _SecKeyGenerateSymmetric
+ _SecKeychainAddCallback
+ _kSecAttrKeySizeInBits
+ _kSecAttrKeyType
+ _kSecAttrKeyTypeAES
+ _kSecUseKeychain
+ _os_variant_has_internal_content
CStrings:
+ "<loopy key>"
+ "Call SecKeychainAddCallback() and then run the runloop."
+ "Create a symmetric key and destroy it, in a loop."
+ "Got notification %llu\n"
+ "Iteration %llu\n"
+ "Looping..."
+ "Registering for notifications..."
+ "SecKeyGenerateSymmetric: %s\n"
+ "SecKeychainItemDelete: %d\n"
+ "Waiting for notifications..."
+ "[-h]\n"
+ "[-h] -k keychain [description]\n    -k  Use the specified keychain rather than the default\n"
+ "com.apple.security.cltool"
+ "create-key-loop"
+ "k:"
+ "wait-for-notifications"
```
