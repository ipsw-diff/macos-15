## pcsstatus

> `/usr/libexec/pcsstatus`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1037.120.2.0.0
-  __TEXT.__text: 0x112c0
+1037.140.4.0.0
+  __TEXT.__text: 0x11680
   __TEXT.__auth_stubs: 0x820
-  __TEXT.__objc_stubs: 0x1d20
-  __TEXT.__objc_methlist: 0x7d4
+  __TEXT.__objc_stubs: 0x1d80
+  __TEXT.__objc_methlist: 0x7e4
   __TEXT.__const: 0xa0
-  __TEXT.__objc_methname: 0x1ed8
-  __TEXT.__cstring: 0xf62
+  __TEXT.__objc_methname: 0x1f1f
+  __TEXT.__cstring: 0xf4f
   __TEXT.__objc_classname: 0x76
   __TEXT.__objc_methtype: 0x5df
-  __TEXT.__gcc_except_tab: 0xda8
+  __TEXT.__gcc_except_tab: 0xdb4
   __TEXT.__ustring: 0x8
-  __TEXT.__oslogstring: 0xdb0
-  __TEXT.__unwind_info: 0x3f0
+  __TEXT.__oslogstring: 0xe65
+  __TEXT.__unwind_info: 0x3f8
   __DATA_CONST.__auth_got: 0x420
   __DATA_CONST.__got: 0x318
   __DATA_CONST.__const: 0x828

   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__objc_dictobj: 0x50
+  __DATA_CONST.__objc_intobj: 0x18
   __DATA.__objc_const: 0x9d8
-  __DATA.__objc_selrefs: 0x9a8
+  __DATA.__objc_selrefs: 0x9c0
   __DATA.__objc_ivar: 0x78
   __DATA.__objc_data: 0x140
   __DATA.__data: 0x228

   - /System/Library/PrivateFrameworks/UserManagement.framework/Versions/A/UserManagement
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 264
-  Symbols:   240
-  CStrings:  733
+  Functions: 265
+  Symbols:   241
+  CStrings:  739
 
Symbols:
+ _OBJC_CLASS_$_NSConstantIntegerNumber
CStrings:
+ "Received unexpected server throttle response, clamping to 10 seconds"
+ "accountEligibleForMBRestoreForDSID:error:"
+ "accountInfoWithCompletionHandler: %d/%d error: %@"
+ "checkRegistry: Account ineligible for MB restore: %@"
+ "deviceToDeviceEncryptionAvailability"
+ "errorIsSAThrottle:"
+ "i"
+ "intValue"
+ "setupSubscriptions: Account ineligible for MB restore: %@"
- "accountStatusWithCompletionHandler:"
- "accountStatusWithCompletionHandler: %d error: %@"
- "v24@?0q8@\"NSError\"16"
```
