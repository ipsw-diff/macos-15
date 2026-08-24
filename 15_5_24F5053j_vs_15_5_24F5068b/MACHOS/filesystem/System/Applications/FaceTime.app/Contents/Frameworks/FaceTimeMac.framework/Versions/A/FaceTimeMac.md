## FaceTimeMac

> `/System/Applications/FaceTime.app/Contents/Frameworks/FaceTimeMac.framework/Versions/A/FaceTimeMac`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2975.600.31.0.0
-  __TEXT.__text: 0xeea08
+2975.600.42.0.0
+  __TEXT.__text: 0xeecc0
   __TEXT.__auth_stubs: 0x29a0
   __TEXT.__objc_methlist: 0xe64
   __TEXT.__const: 0x34c4

   __TEXT.__swift5_assocty: 0x258
   __TEXT.__swift5_proto: 0x248
   __TEXT.__swift5_types: 0x1cc
-  __TEXT.__oslogstring: 0x5080
+  __TEXT.__oslogstring: 0x5100
   __TEXT.__swift_as_entry: 0x320
   __TEXT.__swift_as_ret: 0x35c
   __TEXT.__swift5_protos: 0x68
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__unwind_info: 0x3288
+  __TEXT.__unwind_info: 0x3280
   __TEXT.__eh_frame: 0x7fe8
   __DATA_CONST.__auth_got: 0x14d0
   __DATA_CONST.__got: 0x838

   - @rpath/FaceTimeSettingsUI.framework/Versions/A/FaceTimeSettingsUI
   Functions: 3546
   Symbols:   1299
-  CStrings:  1463
+  CStrings:  1465
 
Functions:
~ sub_199e8 : 232 -> 832
~ sub_19ad0 -> sub_19d28 : 2880 -> 2816
~ sub_1b3fc -> sub_1b614 : 56 -> 36
~ sub_1b434 -> sub_1b638 : 8 -> 56
~ _block_copy_helper -> sub_1b670 : 16 -> 8
~ _block_destroy_helper -> _block_copy_helper : 8 -> 16
~ sub_1b454 -> _block_destroy_helper : 72 -> 8
~ sub_1b49c -> sub_1b690 : 68 -> 72
~ sub_1b4e0 -> sub_1b6d8 : 36 -> 68
~ sub_7a278 -> sub_7a490 : 680 -> 840
CStrings:
+ "Camera is already selected, ignoring request."
+ "Failed to select camera device %s isConnected: %s isSuspended: %s"
```
