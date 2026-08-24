## MobileDevice

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/MobileDevice.framework/Versions/A/MobileDevice`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__dof_MobileDev`
- `__TEXT.__dof_afc`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-1784.120.3.0.0
-  __TEXT.__text: 0x284b58
+1784.140.4.0.0
+  __TEXT.__text: 0x284c1c
   __TEXT.__auth_stubs: 0x4030
   __TEXT.__objc_methlist: 0x3d74
-  __TEXT.__const: 0x1018fc
-  __TEXT.__cstring: 0x7484d
-  __TEXT.__gcc_except_tab: 0x3cd8
+  __TEXT.__const: 0x1017ec
+  __TEXT.__cstring: 0x749d7
+  __TEXT.__gcc_except_tab: 0x3cdc
   __TEXT.__oslogstring: 0x96a
   __TEXT.__ustring: 0x15a
   __TEXT.__dof_MobileDev: 0x1ac1
   __TEXT.__dof_afc: 0x6d7
-  __TEXT.__unwind_info: 0x6858
+  __TEXT.__unwind_info: 0x6868
   __TEXT.__eh_frame: 0x6a4
   __TEXT.__objc_classname: 0xdfc
   __TEXT.__objc_methname: 0x708d

   __DATA_CONST.__objc_selrefs: 0x1b48
   __AUTH_CONST.__auth_got: 0x2030
   __AUTH_CONST.__const: 0x8688
-  __AUTH_CONST.__cfstring: 0x3b380
+  __AUTH_CONST.__cfstring: 0x3b4c0
   __AUTH_CONST.__objc_const: 0x70a0
   __AUTH.__objc_data: 0x19a0
   __AUTH.__data: 0x338

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libssl.35.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9480
-  Symbols:   13801
-  CStrings:  15962
+  Functions: 9483
+  Symbols:   13799
+  CStrings:  15971
 
Symbols:
+ GCC_except_table119
+ GCC_except_table1272
+ GCC_except_table1275
+ GCC_except_table133
+ GCC_except_table1390
+ GCC_except_table148
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table164
+ GCC_except_table172
+ GCC_except_table179
+ GCC_except_table182
+ GCC_except_table193
+ GCC_except_table194
+ GCC_except_table197
+ GCC_except_table198
+ _AttestedRestoreLevel
+ _Constants
+ _InvShiftRows_RotWord
+ _S_Box_Inverse_Zero
+ __AMRestorableDeviceCleanupAttestedRestoreData
+ __AMRestorableDeviceCleanupCheckpointData
+ __ZL17_processASRResultP21__AMRestoreModeDevicePK14__CFDictionaryi
+ __ZN8RPSocket13EventCallback20invoke_and_delete_fnEPS0_
+ _ramrod_socket_set_buffer_limits
+ ccaes_arm_encrypt_key128
+ ccaes_arm_encrypt_key192
+ ccaes_arm_encrypt_key256
- GCC_except_table118
- GCC_except_table124
- GCC_except_table1270
- GCC_except_table1273
- GCC_except_table131
- GCC_except_table1388
- GCC_except_table146
- GCC_except_table154
- GCC_except_table155
- GCC_except_table162
- GCC_except_table165
- GCC_except_table166
- GCC_except_table174
- GCC_except_table187
- GCC_except_table188
- GCC_except_table195
- GCC_except_table196
- GCC_except_table64
- GCC_except_table70
- GCC_except_table89
- _AESSubBytesWordTable
- __AMRestorableDeviceHandleDisconnection_Restoring
- _ccaes_arm_decrypt_key128
- _ccaes_arm_decrypt_key192
- _ccaes_arm_decrypt_key256
- _ccaes_arm_encrypt_key128
- _ccaes_arm_encrypt_key192
- _ccaes_arm_encrypt_key256
- aes_dkey_expansion
- aes_key_expansion
CStrings:
+ "\n=====================================================\n %@ \n=====================================================\n"
+ "%s: failed to load contents of Port DFU file: %@"
+ "1784.140.4"
+ ">>> Attestation %@ <<<"
+ "AMAuthInstallSupportCreateDataFromMappedFileURL failed with = %d"
+ "ASRServerHandleConnection failed: %d (%s)"
+ "ASRServerHandleConnection failure delegated to device"
+ "ASRServerHandleConnection failure is possibly-recoverable network error"
+ "Attestation digest tag matches"
+ "AttestationLevel"
+ "Device disconnected before transition"
+ "Device disconnected during transition"
+ "Device never disconnected during transition"
+ "HostFailsWhenASRFails"
+ "RestoreModeIPv6RecvBuffer"
+ "RestoreModeIPv6SendBuffer"
+ "Successfully restored"
+ "Successfully restored (Level %@ attested)"
+ "Successfully restored (RESTORE ATTESTATION ANOMALY)"
+ "attestedRestoreLevel"
+ "restore library built Jun  3 2025 at 00:14:20"
+ "sock %3d: could not set SO_RCVBUF=%d: %s"
+ "sock %3d: could not set SO_SNDBUF=%d: %s"
+ "ticket digest error"
- "\n=====================================================\n%s\n=====================================================\n"
- " Successfully restored "
- " Successfully restored (RESTORE ATTESTATION ANOMALY) "
- " Successfully restored (Securely attested) "
- "1784.120.3"
- "AMAuthInstallSupportCreateDataFromFileURL failed with = %d"
- "ASRServerHandleConnection failed with possibly recoverable network-related error %s (%d)"
- "ASRServerHandleConnection failed: %d"
- "Attestation ap tag matches"
- "Attestation ap tag mismatch"
- "Attestation manifest hash mismatch"
- "Device removed when in state Restoring, moving device to transition state"
- "failed to parse %@"
- "restore library built Apr 21 2025 at 21:52:33"
- "ticket digest"
```
