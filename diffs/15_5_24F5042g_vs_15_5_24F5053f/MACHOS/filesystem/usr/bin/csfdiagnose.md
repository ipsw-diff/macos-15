## csfdiagnose

> `/usr/bin/csfdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-301.22.5.2.0
-  __TEXT.__text: 0x19a84
-  __TEXT.__auth_stubs: 0xb10
+301.22.5.4.0
+  __TEXT.__text: 0x19958
+  __TEXT.__auth_stubs: 0xae0
   __TEXT.__const: 0x132e
-  __TEXT.__cstring: 0xf71
-  __TEXT.__swift5_typeref: 0x4af
   __TEXT.__swift5_entry: 0x8
+  __TEXT.__swift5_typeref: 0x4af
   __TEXT.__swift5_fieldmd: 0x5e0
   __TEXT.__constg_swiftt: 0x378
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_reflstr: 0x251
   __TEXT.__swift5_capture: 0x34
   __TEXT.__objc_methname: 0xfb
+  __TEXT.__cstring: 0xee1
   __TEXT.__swift5_proto: 0x158
   __TEXT.__swift5_types: 0x60
   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x24
   __TEXT.__unwind_info: 0x590
   __TEXT.__eh_frame: 0x8b8
-  __DATA_CONST.__auth_got: 0x588
+  __DATA_CONST.__auth_got: 0x570
   __DATA_CONST.__got: 0x1e8
   __DATA_CONST.__auth_ptr: 0x1a8
   __DATA_CONST.__const: 0xcc0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__objc_selrefs: 0x60
   __DATA.__data: 0x810
-  __DATA.__common: 0x1b8
+  __DATA.__common: 0x1b0
   __DATA.__bss: 0x2b00
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 483
-  Symbols:   308
-  CStrings:  81
+  Symbols:   305
+  CStrings:  77
 
Symbols:
- _geteuid
- _getpwnam
- _setuid
Functions:
~ sub_100001410 : 360 -> 60
~ sub_1000015d0 -> sub_1000014a4 : 76 -> 12
~ sub_100001628 -> sub_1000014bc : 12 -> 20
~ sub_100001684 -> sub_100001520 : 20 -> 364
~ sub_100001698 -> sub_10000168c : 364 -> 76
CStrings:
- "Failed to switch to user 'mobile'."
- "Logged in as 'root'. Switching to 'mobile'."
- "Running csfctl as user 'mobile'"
- "mobile"
```
