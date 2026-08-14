## cryptexd

> `/usr/libexec/cryptexd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__object_init`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-493.120.3.0.0
-  __TEXT.__text: 0x5a77c
+493.120.5.0.0
+  __TEXT.__text: 0x5ac88
   __TEXT.__auth_stubs: 0x1de0
   __TEXT.__objc_stubs: 0x2080
   __TEXT.__objc_methlist: 0xafc

   __TEXT.__objc_methname: 0x1e1d
   __TEXT.__objc_classname: 0x132
   __TEXT.__objc_methtype: 0x501
-  __TEXT.__cstring: 0x3dc9
-  __TEXT.__oslogstring: 0xb04b
-  __TEXT.__unwind_info: 0xdb8
+  __TEXT.__cstring: 0x3dd1
+  __TEXT.__oslogstring: 0xb0dd
+  __TEXT.__unwind_info: 0xdc8
   __DATA_CONST.__auth_got: 0xf00
   __DATA_CONST.__got: 0x2c0
   __DATA_CONST.__auth_ptr: 0x20

   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 1106
+  Functions: 1108
   Symbols:   590
-  CStrings:  2072
+  CStrings:  2076
 
CStrings:
+ "%{public}s: failed to open destination path for %s %{darwin.errno}d"
+ "%{public}s: failed to open root path for %s %{darwin.errno}d"
+ "493.120.5"
+ "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Sun Apr 13 23:04:57 PDT 2025; root:libcryptex_executables-493.120.5~125/cryptexd/RELEASE_ARM64E"
+ "Darwin Cryptex Manager Version 2.0.0: Sun Apr 13 23:04:57 PDT 2025; root:libcryptex_executables-493.120.5~125/cryptexd/RELEASE_ARM64E"
+ "_quire_bootstrap_binary_to"
+ "_quire_unbootstrap_binary_from"
+ "handle resource [no error]"
+ "handle resource: %@"
+ "iterate '%{public}s' resources for '%{public}s' view [no error]"
+ "iterate '%{public}s' resources for '%{public}s' view: %@"
- "%{public}s: failed to create trampoline for %s under root %{darwin.errno}d"
- "493.120.3"
- "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Sun Apr  6 19:19:23 PDT 2025; root:libcryptex_executables-493.120.3~316/cryptexd/RELEASE_ARM64E"
- "Darwin Cryptex Manager Version 2.0.0: Sun Apr  6 19:19:23 PDT 2025; root:libcryptex_executables-493.120.3~316/cryptexd/RELEASE_ARM64E"
- "_quire_bootstrap_binary"
- "_quire_unbootstrap_binary"
- "unexpected failure: quire deallocated with open boot session state dir = %d"
```
