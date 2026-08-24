## cryptexd

> `/usr/libexec/cryptexd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__subsystem`
- `__DATA_CONST.__object_init`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-493.120.7.0.0
-  __TEXT.__text: 0x5ac88
+493.140.11.0.0
+  __TEXT.__text: 0x5ad9c
   __TEXT.__auth_stubs: 0x1de0
   __TEXT.__objc_stubs: 0x2080
   __TEXT.__objc_methlist: 0xafc

   __TEXT.__objc_methname: 0x1e1d
   __TEXT.__objc_classname: 0x132
   __TEXT.__objc_methtype: 0x501
-  __TEXT.__cstring: 0x3dcf
-  __TEXT.__oslogstring: 0xb0dd
-  __TEXT.__unwind_info: 0xdc8
+  __TEXT.__cstring: 0x3e2b
+  __TEXT.__oslogstring: 0xb0ee
+  __TEXT.__unwind_info: 0xdd0
   __DATA_CONST.__auth_got: 0xf00
   __DATA_CONST.__got: 0x2c0
   __DATA_CONST.__auth_ptr: 0x20

   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 1108
+  Functions: 1109
   Symbols:   590
-  CStrings:  2076
+  CStrings:  2077
 
CStrings:
+ "%{public}s: codex_unbootstrap occurring."
+ "493.140.11"
+ "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Sun Jun  8 20:01:41 PDT 2025; root:libcryptex_executables-493.140.11~510/cryptexd/RELEASE_ARM64E"
+ "Darwin Cryptex Manager Version 2.0.0: Sun Jun  8 20:01:41 PDT 2025; root:libcryptex_executables-493.140.11~510/cryptexd/RELEASE_ARM64E"
+ "Monitor event for %{public}@ (session: %{public}s)"
+ "unbootstrap"
- "%{public}s: codex_unbootstrap occuring."
- "493.120.7"
- "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Sat Apr 19 06:09:39 PDT 2025; root:libcryptex_executables-493.120.7~11/cryptexd/RELEASE_ARM64E"
- "Darwin Cryptex Manager Version 2.0.0: Sat Apr 19 06:09:39 PDT 2025; root:libcryptex_executables-493.120.7~11/cryptexd/RELEASE_ARM64E"
- "Monitor event for %@ (session: %s)"
```
