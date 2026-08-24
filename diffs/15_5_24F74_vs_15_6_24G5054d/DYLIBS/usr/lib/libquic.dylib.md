## libquic.dylib

> `/usr/lib/libquic.dylib`

```diff

-4277.121.5.0.0
-  __TEXT.__text: 0xcf6e4
-  __TEXT.__auth_stubs: 0x18b0
+4277.140.27.0.0
+  __TEXT.__text: 0xcef10
+  __TEXT.__auth_stubs: 0x18a0
   __TEXT.__objc_methlist: 0x238
   __TEXT.__const: 0x355
-  __TEXT.__cstring: 0x8da1
-  __TEXT.__oslogstring: 0x115c5
-  __TEXT.__unwind_info: 0xd60
+  __TEXT.__cstring: 0x8c69
+  __TEXT.__oslogstring: 0x11578
+  __TEXT.__unwind_info: 0xd58
   __TEXT.__objc_classname: 0xa
   __TEXT.__objc_methname: 0x7c5
   __TEXT.__objc_methtype: 0xbd0
   __TEXT.__objc_stubs: 0x640
   __DATA_CONST.__got: 0x80
-  __DATA_CONST.__const: 0x1be0
+  __DATA_CONST.__const: 0x1ba0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x1e0
   __DATA_CONST.__objc_superrefs: 0x8
-  __AUTH_CONST.__auth_got: 0xc60
-  __AUTH_CONST.__const: 0x2fb0
+  __AUTH_CONST.__auth_got: 0xc58
+  __AUTH_CONST.__const: 0x2fe0
   __AUTH_CONST.__cfstring: 0x1480
   __AUTH_CONST.__objc_const: 0xf8
   __AUTH.__objc_data: 0x50

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1175
-  Symbols:   1700
-  CStrings:  2748
+  Functions: 1173
+  Symbols:   1697
+  CStrings:  2723
 
Symbols:
- _os_variant_has_internal_diagnostics
- _quic_reassq_recalculate_size
- _sec_framer_debug
CStrings:
+ "%{public}s tried to set path->mss to 0 from quic_conn_get_mss_from_interface()"
- "%s hmac="
- "%s hp="
- "%s iv="
- "%s key="
- "%s: AES-128 (qpod),"
- "%s: AES-128,"
- "%s: AES-256,"
- "%s: ChaCha20Poly1305,"
- "%{public}s   [%llu, %llu)"
- "%{public}s %{private}s"
- "%{public}s frame %s len %u"
- "%{public}s path->mss == path->initial_mss is null or 0"
- "%{public}s reassq state:"
- "com.apple.network.quic.testing.keys"
- "quic_reassq_recalculate_size"
- "read-0-rtt"
- "read-1rrt-0"
- "read-1rrt-1"
- "read-handshake"
- "read-initial"
- "sec_framer_debug"
- "write-0-rtt"
- "write-1rrt-0"
- "write-1rrt-1"
- "write-handshake"
- "write-initial"
```
