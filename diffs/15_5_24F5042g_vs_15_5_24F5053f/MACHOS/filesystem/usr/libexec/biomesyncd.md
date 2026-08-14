## biomesyncd

> `/usr/libexec/biomesyncd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__linkguard`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-166.20.0.0.0
-  __TEXT.__text: 0x4ce0c
+166.22.1.0.0
+  __TEXT.__text: 0x4c8f0
   __TEXT.__auth_stubs: 0xb60
-  __TEXT.__objc_stubs: 0x78a0
+  __TEXT.__objc_stubs: 0x7860
   __TEXT.__objc_methlist: 0x3aec
   __TEXT.__const: 0x1110
   __TEXT.__gcc_except_tab: 0x9b0
-  __TEXT.__objc_methname: 0x9698
-  __TEXT.__cstring: 0x4b91
+  __TEXT.__objc_methname: 0x9664
+  __TEXT.__cstring: 0x4b5d
   __TEXT.__objc_classname: 0x830
   __TEXT.__objc_methtype: 0x18ff
-  __TEXT.__oslogstring: 0x5518
-  __TEXT.__unwind_info: 0xf80
+  __TEXT.__oslogstring: 0x549e
+  __TEXT.__unwind_info: 0xf78
   __DATA_CONST.__auth_got: 0x5c0
-  __DATA_CONST.__got: 0x3b8
-  __DATA_CONST.__const: 0x11b0
+  __DATA_CONST.__got: 0x3b0
+  __DATA_CONST.__const: 0x1160
   __DATA_CONST.__cfstring: 0x41a0
   __DATA_CONST.__objc_classlist: 0x1b8
   __DATA_CONST.__objc_catlist: 0x20

   __DATA_CONST.__linkguard: 0xf
   __DATA_CONST.__objc_dictobj: 0x78
   __DATA.__objc_const: 0x76a8
-  __DATA.__objc_selrefs: 0x25a8
+  __DATA.__objc_selrefs: 0x2598
   __DATA.__objc_ivar: 0x3d4
   __DATA.__objc_data: 0x1130
   __DATA.__data: 0x8a0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1566
-  Symbols:   319
-  CStrings:  2857
+  Functions: 1563
+  Symbols:   318
+  CStrings:  2851
 
Symbols:
- _OBJC_CLASS_$_BMPersonaUtilities
CStrings:
- "-[BMSyncServiceServer cascadeRapportSyncWithReply:]"
- "Server started, replying to com.apple.rapport.matching: %s"
- "cascade activity fired \"%s\""
- "currentPersonaIdentifierLoggingDescription"
- "rapportSyncWithError persona is %@"
- "teardown"
```
