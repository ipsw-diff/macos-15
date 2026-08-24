## backupd

> `/System/Library/CoreServices/TimeMachine/backupd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-2433.0.0.0.0
-  __TEXT.__text: 0x1741c4
-  __TEXT.__auth_stubs: 0x3cc0
-  __TEXT.__objc_stubs: 0x77a0
+2435.0.0.0.0
+  __TEXT.__text: 0x1740dc
+  __TEXT.__auth_stubs: 0x3ca0
+  __TEXT.__objc_stubs: 0x7820
   __TEXT.__objc_methlist: 0x38f0
-  __TEXT.__const: 0x7e30
+  __TEXT.__const: 0x89f0
   __TEXT.__gcc_except_tab: 0xd10
-  __TEXT.__objc_methname: 0xa917
-  __TEXT.__cstring: 0x1361c
+  __TEXT.__objc_methname: 0xa977
+  __TEXT.__cstring: 0x1379c
   __TEXT.__objc_classname: 0x83a
-  __TEXT.__objc_methtype: 0x3518
+  __TEXT.__objc_methtype: 0x351b
   __TEXT.__constg_swiftt: 0x3060
   __TEXT.__swift5_typeref: 0x3c0a
   __TEXT.__swift5_reflstr: 0x2e01

   __TEXT.__swift5_entry: 0x8
   __TEXT.__unwind_info: 0x5478
   __TEXT.__eh_frame: 0xb4fc
-  __DATA_CONST.__auth_got: 0x1e78
+  __DATA_CONST.__auth_got: 0x1e68
   __DATA_CONST.__got: 0xf78
-  __DATA_CONST.__auth_ptr: 0xb08
+  __DATA_CONST.__auth_ptr: 0xa60
   __DATA_CONST.__const: 0x90d8
-  __DATA_CONST.__cfstring: 0x5b40
+  __DATA_CONST.__cfstring: 0x5b20
   __DATA_CONST.__objc_classlist: 0x2d0
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x2f0

   __DATA_CONST.__objc_arraydata: 0x68
   __DATA_CONST.__objc_arrayobj: 0x90
   __DATA.__objc_const: 0x8e70
-  __DATA.__objc_selrefs: 0x2a00
+  __DATA.__objc_selrefs: 0x2a20
   __DATA.__objc_ivar: 0x354
   __DATA.__objc_data: 0x2d58
-  __DATA.__data: 0x5f20
+  __DATA.__data: 0x5320
   __DATA.__bss: 0xc5b0
   __DATA.__common: 0xf0
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 6096
-  Symbols:   1693
-  CStrings:  3952
+  Symbols:   1691
+  CStrings:  3954
 
Symbols:
- _$s10Foundation3URLV6schemeSSSgvg
- _$sSy10FoundationE8containsySbqd__SyRd__lF
CStrings:
+ "@40@0:8@16@?24^@32"
+ "AFP is deprecated, trying to mount the AFP volume using SMB instead"
+ "_mountpointForNetworkURL:cancelBlock:error:"
+ "setSmbConversionState:"
+ "smbConversionState"
+ "tm_URLByReplacingSchemeWithSMB"
+ "tm_isAFP"
+ "tm_isSMB"
- "@32@0:8@?16^@24"
- "_mountNetworkCancelBlock:error:"
- "afp"
- "scheme"
- "self.networkURL != nil"
- "smb"
```
