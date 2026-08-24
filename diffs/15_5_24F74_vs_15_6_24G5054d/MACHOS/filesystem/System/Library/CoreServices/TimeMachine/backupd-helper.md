## backupd-helper

> `/System/Library/CoreServices/TimeMachine/backupd-helper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2433.0.0.0.0
-  __TEXT.__text: 0xdf30
+2435.0.0.0.0
+  __TEXT.__text: 0xdf28
   __TEXT.__auth_stubs: 0x7d0
-  __TEXT.__objc_stubs: 0x21c0
+  __TEXT.__objc_stubs: 0x21e0
   __TEXT.__objc_methlist: 0x73c
   __TEXT.__const: 0x82
   __TEXT.__gcc_except_tab: 0xe8
-  __TEXT.__cstring: 0x2b56
+  __TEXT.__cstring: 0x2b9e
   __TEXT.__objc_classname: 0x110
-  __TEXT.__objc_methname: 0x23d4
-  __TEXT.__objc_methtype: 0x4b5
+  __TEXT.__objc_methname: 0x2405
+  __TEXT.__objc_methtype: 0x4b8
   __TEXT.__unwind_info: 0x2b0
   __DATA_CONST.__auth_got: 0x3f8
-  __DATA_CONST.__got: 0x210
+  __DATA_CONST.__got: 0x208
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x788
-  __DATA_CONST.__cfstring: 0x1a40
+  __DATA_CONST.__cfstring: 0x1a20
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x30

   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0x928
-  __DATA.__objc_selrefs: 0xa70
+  __DATA.__objc_selrefs: 0xa78
   __DATA.__objc_ivar: 0x28
   __DATA.__objc_data: 0x1e0
   __DATA.__data: 0x2c8

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 176
-  Symbols:   232
-  CStrings:  710
+  Symbols:   231
+  CStrings:  709
 
Symbols:
- _NSOSStatusErrorDomain
Functions:
~ sub_10000597c : 800 -> 844
~ sub_100005c9c -> sub_100005cc8 : 320 -> 336
~ sub_100006124 -> sub_100006160 : 204 -> 172
~ sub_10000623c -> sub_100006258 : 3120 -> 3084
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
- "domain"
- "errorByMarkingRetryable"
- "scheme"
- "self.networkURL != nil"
- "smb"
- "underlyingError"
```
