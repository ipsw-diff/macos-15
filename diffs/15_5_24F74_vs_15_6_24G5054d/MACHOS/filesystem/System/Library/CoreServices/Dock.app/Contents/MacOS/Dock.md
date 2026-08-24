## Dock

> `/System/Library/CoreServices/Dock.app/Contents/MacOS/Dock`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_floatobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`

```diff

-2341.4.7.0.0
-  __TEXT.__text: 0x3063a8
-  __TEXT.__auth_stubs: 0x7360
-  __TEXT.__objc_stubs: 0x16020
+2341.4.8.0.0
+  __TEXT.__text: 0x305c68
+  __TEXT.__auth_stubs: 0x7270
+  __TEXT.__objc_stubs: 0x15fc0
   __TEXT.__init_offsets: 0x8
-  __TEXT.__objc_methlist: 0x11390
-  __TEXT.__const: 0xcc10
+  __TEXT.__objc_methlist: 0x11358
+  __TEXT.__const: 0xcd00
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__cstring: 0x17396
-  __TEXT.__objc_methname: 0x1c126
+  __TEXT.__cstring: 0x17006
+  __TEXT.__objc_methname: 0x1c07e
   __TEXT.__swift5_typeref: 0x5e5d
   __TEXT.__swift5_capture: 0x29a8
-  __TEXT.__objc_classname: 0x1ecb
-  __TEXT.__objc_methtype: 0x813b
   __TEXT.__gcc_except_tab: 0x1824
+  __TEXT.__objc_classname: 0x1ebc
+  __TEXT.__objc_methtype: 0x811f
   __TEXT.__oslogstring: 0x649b
   __TEXT.__ustring: 0x14c
   __TEXT.__constg_swiftt: 0x7b70

   __TEXT.__swift_as_entry: 0x40
   __TEXT.__swift_as_ret: 0x44
   __TEXT.__swift5_mpenum: 0x34
-  __TEXT.__unwind_info: 0xcdd8
+  __TEXT.__unwind_info: 0xcdd0
   __TEXT.__eh_frame: 0x4b7c
-  __DATA_CONST.__auth_got: 0x39c8
-  __DATA_CONST.__got: 0x1308
-  __DATA_CONST.__auth_ptr: 0x1558
+  __DATA_CONST.__auth_got: 0x3950
+  __DATA_CONST.__got: 0x12e8
+  __DATA_CONST.__auth_ptr: 0x14f0
   __DATA_CONST.__const: 0x20808
-  __DATA_CONST.__cfstring: 0x7900
-  __DATA_CONST.__objc_classlist: 0xbd0
+  __DATA_CONST.__cfstring: 0x76a0
+  __DATA_CONST.__objc_classlist: 0xbc8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x648
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x2c0
-  __DATA_CONST.__objc_superrefs: 0x668
+  __DATA_CONST.__objc_superrefs: 0x660
   __DATA_CONST.__objc_intobj: 0x120
   __DATA_CONST.__objc_doubleobj: 0x80
   __DATA_CONST.__objc_floatobj: 0xd0
   __DATA_CONST.__objc_arraydata: 0x1a8
   __DATA_CONST.__objc_arrayobj: 0x1c8
   __DATA_CONST.__objc_dictobj: 0x50
-  __DATA.__objc_const: 0x29418
-  __DATA.__objc_selrefs: 0x7040
-  __DATA.__objc_ivar: 0x1784
-  __DATA.__objc_data: 0x7e48
-  __DATA.__data: 0xdd10
+  __DATA.__objc_const: 0x292d0
+  __DATA.__objc_selrefs: 0x7028
+  __DATA.__objc_ivar: 0x1770
+  __DATA.__objc_data: 0x7df8
+  __DATA.__data: 0xdc30
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0xcc20
   __DATA.__common: 0x6f8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 20713
-  Symbols:   2650
-  CStrings:  9523
+  Functions: 20709
+  Symbols:   2631
+  CStrings:  9493
 
Symbols:
- _APP_SANDBOX_READ_WRITE
- _CONTAINER_PERSONA_PRIMARY
- _SANDBOX_EXTENSION_CANONICAL
- _SecStaticCodeCheckValidityWithErrors
- _container_copy_sandbox_token
- _container_get_info_value_for_key
- _container_get_path
- _container_query_create
- _container_query_free
- _container_query_get_single_result
- _container_query_operation_set_flags
- _container_query_set_class
- _container_query_set_identifiers
- _container_query_set_persona_unique_string
- _kASBContainerIdentityKey
- _sandbox_extension_consume
- _sandbox_extension_issue_file
- _sandbox_extension_release
- _strlcpy
CStrings:
- "*16@0:8"
- "@\"AppDataContainer\""
- "AppDataContainer"
- "Container ACL contains non-data entry for app bundle %@"
- "Error consuming sandbox extension: %d: %s"
- "Error copying sandbox token: %d: %s"
- "Error getting code for path %@: %d"
- "Error getting code signing info for path %@: %d"
- "Error issuing sandbox extension for %s: %d: %s"
- "Error releasing sandbox extension handle %lld: %d: %s"
- "Failed to create CF object from XPC for app bundle %@"
- "Failed to create requirements for app bundle %@: %d"
- "Failed to meet even one requirement for app bundle %@"
- "Failed to satisfy requirement for app bundle %@: %d (%@)"
- "No container identity requirement for container for app bundle %@"
- "No data container for app bundle %@"
- "No data container path for app bundle %@"
- "No signing identifier found for path: %@"
- "Non-array ACL for container for app bundle %@"
- "Signing identifier not a string for path: %@"
- "T@\"AppDataContainer\",R,N,V_appDataContainer"
- "Unable to create a container query"
- "Zero length data container path for app bundle %@"
- "_appDataContainer"
- "_hasSandboxExtension"
- "_sandboxExtensionHandle"
- "appDataContainer"
- "app_data_container_sandbox_extension"
- "cStringUsingEncoding:"
- "issueSandboxExtension"
```
