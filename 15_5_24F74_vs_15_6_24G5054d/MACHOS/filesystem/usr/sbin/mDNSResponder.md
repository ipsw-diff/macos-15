## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2600.120.12.0.0
-  __TEXT.__text: 0xffaa4
+2600.140.2.0.0
+  __TEXT.__text: 0xffab0
   __TEXT.__auth_stubs: 0x2e30
   __TEXT.__objc_stubs: 0xd00
   __TEXT.__objc_methlist: 0x2a4
   __TEXT.__const: 0x1210
-  __TEXT.__cstring: 0x18334
+  __TEXT.__cstring: 0x18379
   __TEXT.__gcc_except_tab: 0x11c
   __TEXT.__oslogstring: 0x1d9e9
   __TEXT.__objc_classname: 0x5eb
Functions:
~ ___mdns_dns_service_manager_register_doh_uri_block_invoke : 984 -> 996
CStrings:
+ "mDNSResponder-2600.140.2"
- "mDNSResponder-2600.120.12"
```
