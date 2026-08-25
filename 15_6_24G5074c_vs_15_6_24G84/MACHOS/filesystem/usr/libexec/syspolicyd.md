## syspolicyd

> `/usr/libexec/syspolicyd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_security_`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-620.140.2.0.0
-  __TEXT.__text: 0xb5690
-  __TEXT.__auth_stubs: 0x29f0
+620.140.3.0.0
+  __TEXT.__text: 0xb5684
+  __TEXT.__auth_stubs: 0x2a00
   __TEXT.__objc_stubs: 0x9b60
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x5014

   __TEXT.__dof_security_: 0x325
   __TEXT.__unwind_info: 0x23c0
   __TEXT.__eh_frame: 0x248
-  __DATA_CONST.__auth_got: 0x1510
+  __DATA_CONST.__auth_got: 0x1518
   __DATA_CONST.__got: 0x830
   __DATA_CONST.__auth_ptr: 0x1d8
   __DATA_CONST.__const: 0x3d28

   - /System/Library/PrivateFrameworks/CloudTelemetry.framework/Versions/A/CloudTelemetry
   - /System/Library/PrivateFrameworks/ConfigurationProfiles.framework/Versions/A/ConfigurationProfiles
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
+  - /System/Library/PrivateFrameworks/OSAnalytics.framework/Versions/A/OSAnalytics
   - /System/Library/PrivateFrameworks/PackageKit.framework/Versions/A/PackageKit
   - /System/Library/PrivateFrameworks/ProtocolBuffer.framework/Versions/A/ProtocolBuffer
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 3427
-  Symbols:   1016
+  Symbols:   1017
   CStrings:  5407
 
Symbols:
+ _OSASanitizePath
Functions:
~ sub_100027cc8 -> sub_100027d38 : 4088 -> 4028
~ sub_100028f38 -> sub_100028f6c : 1960 -> 2008
CStrings:
+ "exec_filename_s"
+ "executable_path_s"
+ "provenance_filename_s"
+ "provenance_path_s"
+ "responsible_filename_s"
+ "responsible_path_s"
+ "responsible_provenance_path_s"
- "exec_filename"
- "executable_path"
- "provenance_filename"
- "provenance_path"
- "responsible_filename"
- "responsible_path"
- "responsible_provenance_path"
```
