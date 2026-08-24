## libboringssl.dylib

> `/usr/lib/libboringssl.dylib`

```diff

-486.121.1.0.0
-  __TEXT.__text: 0x9fdc0
-  __TEXT.__auth_stubs: 0x17b0
+486.140.5.0.1
+  __TEXT.__text: 0x9ff7c
+  __TEXT.__auth_stubs: 0x17c0
   __TEXT.__objc_methlist: 0x1dc
-  __TEXT.__cstring: 0x11e0d
+  __TEXT.__cstring: 0x11fc5
   __TEXT.__const: 0xfed8
-  __TEXT.__oslogstring: 0x56da
+  __TEXT.__oslogstring: 0x56f7
   __TEXT.__gcc_except_tab: 0x28e8
-  __TEXT.__unwind_info: 0x23b8
+  __TEXT.__unwind_info: 0x23c8
   __TEXT.__eh_frame: 0x130
   __TEXT.__objc_classname: 0x241
   __TEXT.__objc_methname: 0xe76

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0x28
-  __AUTH_CONST.__auth_got: 0xbf0
+  __AUTH_CONST.__auth_got: 0xbf8
   __AUTH_CONST.__const: 0x2238
   __AUTH_CONST.__cfstring: 0xc0
   __AUTH_CONST.__objc_const: 0x2168

   - /usr/lib/libnetwork.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3140
-  Symbols:   3983
+  Functions: 3143
+  Symbols:   3987
   CStrings:  3592
 
Symbols:
+ GCC_except_table132
+ GCC_except_table167
+ GCC_except_table96
+ _SSL_renegotiate_pending
+ __boringssl_context_certificate_request_callback_block_invoke
+ _boringssl_session_get_negotiated_pake
+ _nw_protocol_get_parameters
- GCC_except_table131
- GCC_except_table166
- GCC_except_table95
Functions:
~ _nw_protocol_boringssl_signal_connected : 820 -> 840
+ _boringssl_session_get_negotiated_pake
~ ___boringssl_session_apply_protocol_options_for_transport_block_invoke : 6816 -> 6856
+ _SSL_renegotiate_pending
~ _boringssl_context_certificate_request_callback : 1196 -> 1392
~ ___boringssl_context_certificate_request_callback_block_invoke : 196 -> 84
+ __boringssl_context_certificate_request_callback_block_invoke.225
CStrings:
+ "%{public}s(%d) %{public}s[%p] TLS configured [min_version(0x%04x) max_version(0x%04x) name(%{public}s) tickets(%{bool}d) false_start(%{bool}d) enforce_ev(%{bool}d) enforce_ats(%{bool}d) ats_non_pfs_ciphersuite_allowed(%{bool}d) ech(%{bool}d) pqtls(%{bool}d), pake(%{bool}d)]"
+ "%{public}s(%d) %{public}s[%p] TLS connected [version(0x%04x) ciphersuite(%s) group(0x%04x) signature_alg(0x%04x) alpn(%{public}s) resumed(%d) offered_ticket(%d) false_started(%d) ocsp_received(%d) sct_received(%d) connect_time(%llums) flight_time(%llums) rtt(%llums) write_stalls(%zu) read_stalls(%zu) pake(0x%04x)]"
- "%{public}s(%d) %{public}s[%p] TLS configured [min_version(0x%04x) max_version(0x%04x) name(%{public}s) tickets(%{bool}d) false_start(%{bool}d) enforce_ev(%{bool}d) enforce_ats(%{bool}d) ats_non_pfs_ciphersuite_allowed(%{bool}d) ech(%{bool}d) pqtls(%{bool}d)]"
- "%{public}s(%d) %{public}s[%p] TLS connected [version(0x%04x) ciphersuite(%s) group(0x%04x) signature_alg(0x%04x) alpn(%{public}s) resumed(%d) offered_ticket(%d) false_started(%d) ocsp_received(%d) sct_received(%d) connect_time(%llums) flight_time(%llums) rtt(%llums) write_stalls(%zu) read_stalls(%zu)]"
```
