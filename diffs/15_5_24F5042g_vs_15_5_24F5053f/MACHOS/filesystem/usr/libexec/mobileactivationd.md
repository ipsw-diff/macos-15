## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1017.120.3.0.0
-  __TEXT.__text: 0x5f6f0
+  __TEXT.__text: 0x5f754
   __TEXT.__auth_stubs: 0xfb0
   __TEXT.__objc_stubs: 0x2180
   __TEXT.__objc_methlist: 0x84c
-  __TEXT.__const: 0x9411
+  __TEXT.__const: 0x99a1
   __TEXT.__gcc_except_tab: 0x1224
   __TEXT.__objc_methname: 0x25d2
   __TEXT.__oslogstring: 0x12cd

   __DATA_CONST.__auth_got: 0x7e8
   __DATA_CONST.__got: 0x400
   __DATA_CONST.__auth_ptr: 0x58
-  __DATA_CONST.__const: 0x3500
+  __DATA_CONST.__const: 0x3a20
   __DATA_CONST.__cfstring: 0x95a0
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_catlist: 0x8

   - /usr/lib/libbootpolicy.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1238
-  Symbols:   2984
+  Symbols:   3000
   CStrings:  2267
 
Symbols:
+ _ApplePlatformBackportECCRootG1
+ _ApplePlatformBackportECCRootG1PublicKey
+ _ApplePlatformBackportECCRootG1SKID
+ _ApplePlatformBackportECCRootG1SPKI
+ _ApplePlatformBackportRSARootG1
+ _ApplePlatformBackportRSARootG1PublicKey
+ _ApplePlatformBackportRSARootG1SKID
+ _ApplePlatformBackportRSARootG1SPKI
+ _TestApplePlatformBackportECCRootG1
+ _TestApplePlatformBackportECCRootG1PublicKey
+ _TestApplePlatformBackportECCRootG1SKID
+ _TestApplePlatformBackportECCRootG1SPKI
+ _TestApplePlatformBackportRSARootG1
+ _TestApplePlatformBackportRSARootG1PublicKey
+ _TestApplePlatformBackportRSARootG1SKID
+ _TestApplePlatformBackportRSARootG1SPKI
Functions:
~ _X509PolicySetFlagsForRoots : 416 -> 496
~ _X509ChainCheckPathWithOptions : 1300 -> 1320
CStrings:
+ "Absinthe/2.0 macOS Device Activator (MobileActivation-1017.120.3 built on Apr  6 2025 at 18:37:56)"
- "Absinthe/2.0 macOS Device Activator (MobileActivation-1017.120.3 built on Mar 21 2025 at 19:08:28)"
```
