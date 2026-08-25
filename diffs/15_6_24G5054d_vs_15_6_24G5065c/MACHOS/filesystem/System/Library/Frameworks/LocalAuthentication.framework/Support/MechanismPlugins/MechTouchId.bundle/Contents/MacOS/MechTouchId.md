## MechTouchId

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismPlugins/MechTouchId.bundle/Contents/MacOS/MechTouchId`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1656.140.3.0.0
-  __TEXT.__text: 0x4030
+1656.140.4.0.0
+  __TEXT.__text: 0x4084
   __TEXT.__auth_stubs: 0x1b0
-  __TEXT.__objc_stubs: 0x10a0
+  __TEXT.__objc_stubs: 0x10e0
   __TEXT.__objc_methlist: 0x3b4
   __TEXT.__const: 0x88
   __TEXT.__gcc_except_tab: 0x50
   __TEXT.__cstring: 0x225
-  __TEXT.__objc_methname: 0xf5e
+  __TEXT.__objc_methname: 0xf91
   __TEXT.__oslogstring: 0x2cf
   __TEXT.__objc_classname: 0xb5
   __TEXT.__objc_methtype: 0x2aa
   __TEXT.__unwind_info: 0x160
   __DATA_CONST.__auth_got: 0xe8
-  __DATA_CONST.__got: 0x88
+  __DATA_CONST.__got: 0x90
   __DATA_CONST.__const: 0x210
   __DATA_CONST.__cfstring: 0x340
   __DATA_CONST.__objc_classlist: 0x8

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0x460
-  __DATA.__objc_selrefs: 0x570
+  __DATA.__objc_selrefs: 0x580
   __DATA.__objc_ivar: 0x30
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x2a0

   - /System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismBase.framework/Versions/A/MechanismBase
   - /System/Library/Frameworks/LocalAuthentication.framework/Support/SharedUtils.framework/Versions/A/SharedUtils
   - /System/Library/PrivateFrameworks/CoreBrightness.framework/Versions/A/CoreBrightness
+  - /System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/Versions/A/LocalAuthenticationCore
   - /usr/lib/libDiagnosticMessagesClient.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 64
-  Symbols:   55
-  CStrings:  296
+  Symbols:   56
+  CStrings:  298
 
Symbols:
+ _LACEventTouchID
Functions:
~ sub_1bf0 -> sub_1c78 : 3296 -> 3380
CStrings:
+ "analyticsData"
+ "authenticationAttemptFailedForEvent:"
```
