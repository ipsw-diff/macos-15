## AppAttestInternal

> `/System/Library/PrivateFrameworks/AppAttestInternal.framework/Versions/A/AppAttestInternal`

```diff

-109.3.0.0.0
-  __TEXT.__text: 0x6bd48
+109.6.0.0.0
+  __TEXT.__text: 0x6cad0
   __TEXT.__auth_stubs: 0x1380
   __TEXT.__objc_methlist: 0x68c
   __TEXT.__const: 0x24f0
-  __TEXT.__cstring: 0x5cb8
-  __TEXT.__oslogstring: 0x310a
-  __TEXT.__gcc_except_tab: 0x6e4
+  __TEXT.__cstring: 0x5cd8
+  __TEXT.__oslogstring: 0x33da
+  __TEXT.__gcc_except_tab: 0x730
   __TEXT.__swift5_typeref: 0x940
   __TEXT.__swift5_reflstr: 0xdd3
   __TEXT.__swift5_assocty: 0x180

   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__swift5_capture: 0x23c
   __TEXT.__swift_as_ret: 0x4
-  __TEXT.__unwind_info: 0xf78
+  __TEXT.__unwind_info: 0xf88
   __TEXT.__eh_frame: 0xb50
   __TEXT.__objc_classname: 0xe2
   __TEXT.__objc_methname: 0x11ed

   __DATA_CONST.__objc_arraydata: 0xc8
   __AUTH_CONST.__auth_got: 0x9d0
   __AUTH_CONST.__const: 0x2410
-  __AUTH_CONST.__cfstring: 0x19e0
+  __AUTH_CONST.__cfstring: 0x1a20
   __AUTH_CONST.__objc_const: 0x1768
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x78

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1348
+  Functions: 1351
   Symbols:   1197
-  CStrings:  1049
+  CStrings:  1064
 
Symbols:
+ _AppAttest_AppAttestation_SignWithTeamIdentifier
- GCC_except_table14
CStrings:
+ "%25s:%-5d App_id=%@, %@"
+ "%25s:%-5d Attempting to validate key. { referenceKey=%@ }"
+ "%25s:%-5d Client is not eligible for priv service."
+ "%25s:%-5d Client is not supported. { error=%@ }"
+ "%25s:%-5d Device attestation is not supported."
+ "%25s:%-5d Failed to allocate array for certificates."
+ "%25s:%-5d Failed to attest key, completion handler is nil."
+ "%25s:%-5d Failed to attest key, invalid server response. { response=%@, error=%@ }"
+ "%25s:%-5d Failed to create certificate."
+ "%25s:%-5d Failed to create device attestation request. { error=%@ }"
+ "%25s:%-5d Failed to validate device attestation entitlements. { error=%@ }"
+ "%25s:%-5d Invalid device attestation options. { options=%@ }"
+ "%25s:%-5d Invalid referenceKey. { referenceKey=%@ }"
+ "AppAttest (%@-109.6) - %@"
+ "CDhash"
+ "allowPrivAPI"
+ "com.apple.developer.devicecheck.app-attest-opt-in"
- "AppAttest (%@-109.3) - %@"
- "com.apple.developer.devicecheck.app-attest-optin"
```
