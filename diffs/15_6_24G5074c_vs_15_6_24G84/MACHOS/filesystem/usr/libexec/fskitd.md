## fskitd

> `/usr/libexec/fskitd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-531.140.7.0.2
-  __TEXT.__text: 0x44508
+531.140.9.0.3
+  __TEXT.__text: 0x44450
   __TEXT.__auth_stubs: 0x910
-  __TEXT.__objc_stubs: 0x42e0
-  __TEXT.__objc_methlist: 0x1d5c
+  __TEXT.__objc_stubs: 0x4300
+  __TEXT.__objc_methlist: 0x1d64
   __TEXT.__const: 0x140
-  __TEXT.__gcc_except_tab: 0x1c58
-  __TEXT.__cstring: 0x265e
-  __TEXT.__oslogstring: 0x2fb0
+  __TEXT.__gcc_except_tab: 0x1c48
+  __TEXT.__cstring: 0x26c5
+  __TEXT.__oslogstring: 0x2f9d
   __TEXT.__objc_classname: 0x206
-  __TEXT.__objc_methname: 0x51aa
-  __TEXT.__objc_methtype: 0x1fae
-  __TEXT.__unwind_info: 0xee0
+  __TEXT.__objc_methname: 0x51ea
+  __TEXT.__objc_methtype: 0x1fc9
+  __TEXT.__unwind_info: 0xef0
   __DATA_CONST.__auth_got: 0x498
-  __DATA_CONST.__got: 0x300
-  __DATA_CONST.__const: 0x2208
+  __DATA_CONST.__got: 0x2f0
+  __DATA_CONST.__const: 0x2238
   __DATA_CONST.__cfstring: 0x7a0
   __DATA_CONST.__objc_classlist: 0x80
   __DATA_CONST.__objc_protolist: 0x48

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA.__objc_const: 0x1f68
-  __DATA.__objc_selrefs: 0x14b0
+  __DATA.__objc_selrefs: 0x14b8
   __DATA.__objc_ivar: 0x170
   __DATA.__objc_data: 0x500
   __DATA.__data: 0x6c0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 1239
-  Symbols:   254
-  CStrings:  1696
+  Functions: 1240
+  Symbols:   252
+  CStrings:  1699
 
Symbols:
- _FSModuleIdentityAttributeSupportsKOIO
- _FSModuleIdentityAttributeSupportsKOIO_OLD
CStrings:
+ "%s: pid %d pidversion %d enableBlockResource %d"
+ "-[fskitdXPCServer _checkResource:usingBundle:options:auditToken:connection:replyHandler:]_block_invoke"
+ "cleanupTaskAfterError:resource:bundleIdentifier:token:"
+ "configureUserClient:pid:pidversion:supportBlockResource:"
+ "v72@0:8@16@24@32{?=[8I]}40"
- "%s: pid %d pidversion %d supportsBlockResources %d supportsKOIO %d"
- "configureUserClient:pid:pidversion:supportKOIO:"
```
