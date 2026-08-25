## fskitd

> `/usr/libexec/fskitd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-531.140.7.0.0
-  __TEXT.__text: 0x43884
+531.140.7.0.2
+  __TEXT.__text: 0x44508
   __TEXT.__auth_stubs: 0x910
-  __TEXT.__objc_stubs: 0x42a0
-  __TEXT.__objc_methlist: 0x1ce4
+  __TEXT.__objc_stubs: 0x42e0
+  __TEXT.__objc_methlist: 0x1d5c
   __TEXT.__const: 0x140
-  __TEXT.__gcc_except_tab: 0x1c30
-  __TEXT.__cstring: 0x249f
-  __TEXT.__oslogstring: 0x2f56
+  __TEXT.__gcc_except_tab: 0x1c58
+  __TEXT.__cstring: 0x265e
+  __TEXT.__oslogstring: 0x2fb0
   __TEXT.__objc_classname: 0x206
-  __TEXT.__objc_methname: 0x5077
+  __TEXT.__objc_methname: 0x51aa
   __TEXT.__objc_methtype: 0x1fae
-  __TEXT.__unwind_info: 0xea8
+  __TEXT.__unwind_info: 0xee0
   __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x300
   __DATA_CONST.__const: 0x2208

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x60
-  __DATA.__objc_const: 0x1f48
-  __DATA.__objc_selrefs: 0x1480
+  __DATA.__objc_const: 0x1f68
+  __DATA.__objc_selrefs: 0x14b0
   __DATA.__objc_ivar: 0x170
   __DATA.__objc_data: 0x500
   __DATA.__data: 0x6c0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 1227
+  Functions: 1239
   Symbols:   254
-  CStrings:  1682
+  CStrings:  1696
 
CStrings:
+ "%s: No module found with short name '%@'"
+ "%s: No moduleIdentity found for fsShortName (%@)"
+ "-[fskitdXPCServer activateVolume:shortName:options:auditToken:replyHandler:]"
+ "-[fskitdXPCServer deactivateVolume:shortName:numericOptions:auditToken:replyHandler:]"
+ "-[fskitdXPCServer getBundleIDFromShortName:user:]_block_invoke"
+ "-[fskitdXPCServer getModuleIdentityFromShortName:user:]_block_invoke"
+ "-[fskitdXPCServer loadResource:shortName:options:auditToken:replyHandler:]"
+ "-[fskitdXPCServer unloadResource:shortName:options:auditToken:replyHandler:]"
+ "activateVolume:shortName:options:auditToken:replyHandler:"
+ "deactivateVolume:shortName:numericOptions:auditToken:replyHandler:"
+ "getBundleIDFromShortName:user:"
+ "getModuleIdentityFromShortName:user:"
+ "loadResource:shortName:options:auditToken:replyHandler:"
+ "unloadResource:shortName:options:auditToken:replyHandler:"
```
