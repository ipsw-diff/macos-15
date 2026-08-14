## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2600.120.6.0.0
-  __TEXT.__text: 0xff980
+2600.120.11.0.1
+  __TEXT.__text: 0xffaa4
   __TEXT.__auth_stubs: 0x2e30
   __TEXT.__objc_stubs: 0xd00
   __TEXT.__objc_methlist: 0x2a4
-  __TEXT.__const: 0x1210
-  __TEXT.__cstring: 0x18333
+  __TEXT.__const: 0x1218
+  __TEXT.__cstring: 0x18338
   __TEXT.__gcc_except_tab: 0x11c
-  __TEXT.__oslogstring: 0x1d990
+  __TEXT.__oslogstring: 0x1d9e9
   __TEXT.__objc_classname: 0x5eb
   __TEXT.__objc_methname: 0xcda
   __TEXT.__objc_methtype: 0x4ea

   __DATA.__objc_superrefs: 0x10
   __DATA.__objc_data: 0x1130
   __DATA.__data: 0x4250
-  __DATA.__bss: 0x16d38
+  __DATA.__bss: 0x16d40
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
   Functions: 1751
-  Symbols:   3749
+  Symbols:   3750
   CStrings:  4467
 
Symbols:
+ init_log_utility_service.log_utility_listener
Functions:
~ _main : 9808 -> 9824
~ _KQueueLoop : 10604 -> 10860
~ ___SendQueries_block_invoke : 1544 -> 1512
~ __unicast_assist_addr_update_ex : 1348 -> 1400
CStrings:
+ "SKIPPED unicast assist query - %{sensitive, mask.hash, mdnsresponder:ip_addr}.20P %d %{sensitive, mask.hash, mdnsresponder:domain_name}.*P %{mdns:rrtype}d qhash %x"
+ "mDNSResponder-2600.120.11.0.1"
+ "unicast assist qhash (%s) keeping presence - %{sensitive, mask.hash, mdnsresponder:ip_addr}.20P qhash %x"
+ "unicast assist qhash flushed (%s) - %{sensitive, mask.hash, mdnsresponder:ip_addr}.20P qhash %x"
+ "unicast assist qhash flushed (overflow) - %{sensitive, mask.hash, mdnsresponder:ip_addr}.20P qhash %x"
+ "unicast assist record %s %s%s - %{sensitive, mask.hash, mdnsresponder:ip_addr}.20P %2.2u %{sensitive, mask.hash, mdnsresponder:domain_name}.*P %{public}s qhash %x rectype 0x%X%s"
+ "unicast assist record flushed (0 qhashes) - %{sensitive, mask.hash, mdnsresponder:ip_addr}.20P %2.2u ifhash %x"
- "SKIPPED unicast assist query - %{sensitive, mask.hash, mdnsresponder:ip_addr}.20P %d %{sensitive, mask.hash, mdnsresponder:domain_name}.*P %{public}s qhash %x"
- "mDNSResponder-2600.120.6"
- "unicast assist qhash (%s) keeping presence - %{public, mdnsresponder:ip_addr}.20P qhash %x"
- "unicast assist qhash flushed (%s) - %{public, mdnsresponder:ip_addr}.20P qhash %x"
- "unicast assist qhash flushed (overflow) - %{public, mdnsresponder:ip_addr}.20P qhash %x"
- "unicast assist record %s %s%s - %{public, mdnsresponder:ip_addr}.20P %2.2u %{public, mdnsresponder:domain_name}.*P %{public}s qhash %x rectype 0x%X%s"
- "unicast assist record flushed (0 qhashes) - %{public, mdnsresponder:ip_addr}.20P %2.2u ifhash %x"
```
