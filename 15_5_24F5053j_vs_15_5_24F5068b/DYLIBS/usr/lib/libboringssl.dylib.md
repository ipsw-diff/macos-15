## libboringssl.dylib

> `/usr/lib/libboringssl.dylib`

```diff

-486.120.2.0.0
-  __TEXT.__text: 0x9facc
-  __TEXT.__auth_stubs: 0x17a0
+486.121.1.0.0
+  __TEXT.__text: 0x9fdc0
+  __TEXT.__auth_stubs: 0x17b0
   __TEXT.__objc_methlist: 0x1dc
-  __TEXT.__cstring: 0x11dbb
+  __TEXT.__cstring: 0x11e0d
   __TEXT.__const: 0xfed8
   __TEXT.__oslogstring: 0x56da
-  __TEXT.__gcc_except_tab: 0x2900
-  __TEXT.__unwind_info: 0x23c0
+  __TEXT.__gcc_except_tab: 0x28e8
+  __TEXT.__unwind_info: 0x23b8
   __TEXT.__eh_frame: 0x130
   __TEXT.__objc_classname: 0x241
   __TEXT.__objc_methname: 0xe76

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0x28
-  __AUTH_CONST.__auth_got: 0xbe8
+  __AUTH_CONST.__auth_got: 0xbf0
   __AUTH_CONST.__const: 0x2238
   __AUTH_CONST.__cfstring: 0xc0
   __AUTH_CONST.__objc_const: 0x2168

   - /usr/lib/libnetwork.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3136
-  Symbols:   3982
-  CStrings:  3589
+  Functions: 3140
+  Symbols:   3983
+  CStrings:  3592
 
Symbols:
+ _CFSetApplyFunction
+ _nw_protocol_boringssl_returned_raw_string_pointer_deallocate
- GCC_except_table146
Functions:
~ _boringssl_context_info_handler : 1760 -> 2248
~ _nw_protocol_boringssl_deallocate_metadata : 296 -> 336
~ __ZN4bssl22tls13_client_handshakeEPNS_13SSL_HANDSHAKEE : 6776 -> 7024
~ __ZN4bssl35ssl_ext_key_share_parse_serverhelloEPNS_13SSL_HANDSHAKEEPNS_5ArrayIhEEPhP6cbs_st : 428 -> 464
~ __ZN4bssl22tls13_server_handshakeEPNS_13SSL_HANDSHAKEE : 8756 -> 8824
~ __ZN4bsslL23add_new_session_ticketsEPNS_13SSL_HANDSHAKEEPb : 844 -> 852
~ __ZN4bssl20ssl_setup_key_sharesEPNS_13SSL_HANDSHAKEEt : 764 -> 772
~ __ZN4bssl21ssl_setup_pake_sharesEPNS_13SSL_HANDSHAKEE : 888 -> 872
~ __ZN4bssl30ssl_ext_pake_parse_serverhelloEPNS_13SSL_HANDSHAKEEPtPNS_5ArrayIhEEPhP6cbs_st : 504 -> 532
~ __ZN4bsslL36ext_supported_groups_add_clienthelloEPKNS_13SSL_HANDSHAKEEP6cbb_stS4_NS_23ssl_client_hello_type_tE : 280 -> 300
~ __ZN4bsslL27ext_sigalgs_add_clienthelloEPKNS_13SSL_HANDSHAKEEP6cbb_stS4_NS_23ssl_client_hello_type_tE : 164 -> 180
~ __ZN4bsslL29ext_key_share_add_clienthelloEPKNS_13SSL_HANDSHAKEEP6cbb_stS4_NS_23ssl_client_hello_type_tE : 176 -> 184
~ __ZN4bsslL42ext_psk_key_exchange_modes_add_clienthelloEPKNS_13SSL_HANDSHAKEEP6cbb_stS4_NS_23ssl_client_hello_type_tE : 160 -> 168
~ __ZN4bsslL26ext_pake_parse_clienthelloEPNS_13SSL_HANDSHAKEEPhP6cbs_st : 848 -> 524
+ _OUTLINED_FUNCTION_11
~ _nw_protocol_boringssl_copy_metadata_contents : 688 -> 692
+ _nw_protocol_boringssl_returned_raw_string_pointer_deallocate
+ _ZN4bsslL23add_new_session_ticketsEPNS_13SSL_HANDSHAKEEPb.cold.1
+ parse_integer.cold.1
~ boringssl_context_info_handler.cold.1 : 64 -> 40
CStrings:
+ "!hs->pake_participant"
+ "do_send_hello_retry_request"
+ "hs->pake_participant == nullptr"
```
