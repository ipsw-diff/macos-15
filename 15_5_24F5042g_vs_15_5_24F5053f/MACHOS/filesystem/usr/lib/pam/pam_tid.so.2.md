## pam_tid.so.2

> `/usr/lib/pam/pam_tid.so.2`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`

```diff

   __TEXT.__text: 0x24a8
   __TEXT.__auth_stubs: 0x310
   __TEXT.__objc_stubs: 0x320
-  __TEXT.__objc_methlist: 0x194
+  __TEXT.__objc_methlist: 0x19c
   __TEXT.__cstring: 0x36c
   __TEXT.__const: 0x50
   __TEXT.__gcc_except_tab: 0xc0
   __TEXT.__oslogstring: 0xee
-  __TEXT.__objc_classname: 0x16
+  __TEXT.__objc_classname: 0x2f
   __TEXT.__objc_methname: 0x58b
   __TEXT.__objc_methtype: 0x3d8
   __TEXT.__dlopen_cstrs: 0x5d

   __DATA_CONST.__got: 0x58
   __DATA_CONST.__const: 0x218
   __DATA_CONST.__cfstring: 0x140
-  __DATA_CONST.__objc_protolist: 0x10
+  __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA.__objc_const: 0x158
+  __DATA.__objc_const: 0x178
   __DATA.__objc_selrefs: 0x1b0
-  __DATA.__data: 0xc0
+  __DATA.__data: 0x120
   __DATA.__bss: 0x28
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpam.2.dylib
   Functions: 54
-  Symbols:   178
-  CStrings:  135
+  Symbols:   183
+  CStrings:  136
 
Symbols:
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LACAgentProxyRegistering
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LACAgentProxyRegistering
+ __OBJC_$_PROTOCOL_REFS_LACAgentProxyRegistering
+ __OBJC_LABEL_PROTOCOL_$_LACAgentProxyRegistering
+ __OBJC_PROTOCOL_$_LACAgentProxyRegistering
CStrings:
+ "LACAgentProxyRegistering"
```
