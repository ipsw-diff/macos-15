## threadradiod

> `/System/Library/PrivateFrameworks/CoreThreadRadio.framework/threadradiod`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-275.0.503.0.0
-  __TEXT.__text: 0x3db944
+275.0.504.0.0
+  __TEXT.__text: 0x3dd078
   __TEXT.__auth_stubs: 0x11300
   __TEXT.__objc_stubs: 0x9620
   __TEXT.__init_offsets: 0xa4
-  __TEXT.__objc_methlist: 0x64f0
+  __TEXT.__objc_methlist: 0x6500
   __TEXT.__objc_classname: 0x5f4
   __TEXT.__const: 0x8240
-  __TEXT.__gcc_except_tab: 0x2a74c
-  __TEXT.__objc_methname: 0xe952
-  __TEXT.__cstring: 0x2f5c9
-  __TEXT.__oslogstring: 0x22aa9
-  __TEXT.__objc_methtype: 0x4450
-  __TEXT.__unwind_info: 0x7318
+  __TEXT.__gcc_except_tab: 0x2a908
+  __TEXT.__objc_methname: 0xe96a
+  __TEXT.__cstring: 0x2f619
+  __TEXT.__oslogstring: 0x22b31
+  __TEXT.__objc_methtype: 0x46b4
+  __TEXT.__unwind_info: 0x7388
   __TEXT.__eh_frame: 0x60
   __DATA_CONST.__auth_got: 0x8998
   __DATA_CONST.__got: 0x920
   __DATA_CONST.__auth_ptr: 0x60
-  __DATA_CONST.__const: 0xadb0
+  __DATA_CONST.__const: 0xae10
   __DATA_CONST.__cfstring: 0x5ea0
   __DATA_CONST.__objc_classlist: 0x170
   __DATA_CONST.__objc_catlist: 0x28

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x140
   __DATA.__objc_const: 0x84e8
-  __DATA.__objc_selrefs: 0x35b0
+  __DATA.__objc_selrefs: 0x35b8
   __DATA.__objc_ivar: 0x534
   __DATA.__objc_data: 0xe60
   __DATA.__data: 0x588

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libdns_services.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 15834
-  Symbols:   21231
-  CStrings:  12041
+  Functions: 15848
+  Symbols:   21249
+  CStrings:  12049
 
Symbols:
+ -[CtrInternalClient trm_get_ot_data:output:]
+ GCC_except_table139
+ GCC_except_table214
+ GCC_except_table220
+ GCC_except_table223
+ GCC_except_table230
+ GCC_except_table235
+ GCC_except_table294
+ GCC_except_table305
+ GCC_except_table342
+ GCC_except_table435
+ GCC_except_table458
+ GCC_except_table459
+ GCC_except_table469
+ GCC_except_table481
+ GCC_except_table490
+ GCC_except_table496
+ GCC_except_table497
+ GCC_except_table506
+ GCC_except_table507
+ GCC_except_table514
+ GCC_except_table526
+ GCC_except_table527
+ GCC_except_table537
+ GCC_except_table538
+ GCC_except_table546
+ GCC_except_table547
+ GCC_except_table559
+ GCC_except_table560
+ GCC_except_table567
+ GCC_except_table568
+ GCC_except_table580
+ GCC_except_table581
+ GCC_except_table587
+ GCC_except_table588
+ _ZN14InternalIPCAPI23interface_send_ping_reqENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEtbS6_S6_N8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
+ _ZN14InternalIPCAPI25interface_trm_get_ot_dataENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES6_S6_N8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
+ _ZN14InternalIPCAPI30received_ping_stats_trm_updateERKN5boost3anyE
+ __ZN14InternalClient15trm_get_ot_dataE21Ctr_trm_get_ot_data_tPN5boost3anyE
+ __ZN14InternalIPCAPI23interface_send_ping_reqENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEtbS6_S6_N8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
+ __ZN14InternalIPCAPI25interface_trm_get_ot_dataENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES6_S6_N8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
+ __ZN14InternalIPCAPI30received_ping_stats_trm_updateERKN5boost3anyE
+ __ZN14RcpHostContext20add_cmd_TrmGetOTDataE15HostTaskCommandP20_TRM_GET_OT_CMD_DATA
+ __ZN14RcpHostContext33getIsPrimaryResidentThreadCapableEv
+ __ZN21Ctr_trm_get_ot_data_tD1Ev
+ __ZN2ot15AddressResolver15GetMeshLocalEidERNS_3Ip67AddressES3_Rb
+ __ZN2ot15AddressResolver15GetMeshLocalIidERNS_3Ip67AddressERb
+ ___ZN14InternalClient15trm_get_ot_dataE21Ctr_trm_get_ot_data_tPN5boost3anyE_block_invoke
+ ____ZN14InternalClient15trm_get_ot_dataE21Ctr_trm_get_ot_data_tPN5boost3anyE_block_invoke
+ ___copy_helper_block_e8_40c27_ZTS21Ctr_trm_get_ot_data_t96c58_ZTSN8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
+ ___destroy_helper_block_e8_40c27_ZTS21Ctr_trm_get_ot_data_t96c58_ZTSN8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
+ _otThreadGetMeshLocalEIdFromAddressCache
+ _otThreadLookUpRloc16
- GCC_except_table188
- GCC_except_table224
- GCC_except_table233
- GCC_except_table259
- GCC_except_table271
- GCC_except_table312
- GCC_except_table377
- GCC_except_table407
- GCC_except_table436
- GCC_except_table437
- GCC_except_table451
- GCC_except_table461
- GCC_except_table462
- GCC_except_table473
- GCC_except_table498
- GCC_except_table499
- GCC_except_table508
- GCC_except_table509
- GCC_except_table516
- GCC_except_table519
- GCC_except_table528
- GCC_except_table529
- GCC_except_table539
- GCC_except_table540
- GCC_except_table551
- GCC_except_table552
- GCC_except_table561
- GCC_except_table562
- GCC_except_table572
- GCC_except_table573
- GCC_except_table582
- GCC_except_table583
- _ZN14InternalIPCAPI23interface_send_ping_reqENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEtS6_S6_N8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
- __ZN14InternalIPCAPI23interface_send_ping_reqENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEtS6_S6_N8dispatch8callbackIU13block_pointerFvhN5boost3anyEEEE
- __ZN2ot15AddressResolver15GetMeshLocalIidERNS_3Ip67AddressE
CStrings:
+ " Morty_Version: V0.275.0.504"
+ "InternalIPCAPI::interface_address_cache_lookup: Handling \"%s\" method handler for \"%s\""
+ "Sending ping_stats_trm_update to internal-clients"
+ "TrmGetOTData"
+ "com.apple.wpantund.trm"
+ "trm:ping:stats"
+ "trm_get_ot_data:output:"
+ "trm_get_ot_data_block_invoke"
+ "{Result=i{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}}48@0:8{?={basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}SB}16"
+ "{Result=i{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}}80@0:8{?={basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}S{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}}16^{any=^{placeholder}}72"
- " Morty_Version: V0.275.0.503"
- "{Result=i{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}}48@0:8{?={basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}S}16"
```
