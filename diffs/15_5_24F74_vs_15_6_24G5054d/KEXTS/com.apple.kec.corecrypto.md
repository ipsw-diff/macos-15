## com.apple.kec.corecrypto

> `com.apple.kec.corecrypto`

```diff

-1736.120.5.0.0
+1736.140.2.0.0
   __TEXT.__cstring: 0x486a
   __TEXT.__const: 0x144e0
   __TEXT.__fips_hmacs: 0x20
-  __TEXT_EXEC.__text: 0x5ab48
+  __TEXT_EXEC.__text: 0x5aa48
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x2df0
   __DATA.__bss: 0x2980

   __DATA_CONST.__got: 0x10
   __DATA_CONST.__auth_ptr: 0x128
   __DATA_CONST.__const: 0x2c90
-  Functions: 1499
-  Symbols:   1858
+  Functions: 1497
+  Symbols:   1856
   CStrings:  434
 
Symbols:
+ _Constants
+ _InvShiftRows_RotWord
+ _S_Box_Inverse_Zero
+ ccaes_arm_encrypt_key128
+ ccaes_arm_encrypt_key192
+ ccaes_arm_encrypt_key256
- _ccaes_arm_decrypt_key128
- _ccaes_arm_decrypt_key192
- _ccaes_arm_decrypt_key256
- _ccaes_arm_encrypt_key128
- _ccaes_arm_encrypt_key192
- _ccaes_arm_encrypt_key256
- aes_dkey_expansion
- aes_key_expansion
```
