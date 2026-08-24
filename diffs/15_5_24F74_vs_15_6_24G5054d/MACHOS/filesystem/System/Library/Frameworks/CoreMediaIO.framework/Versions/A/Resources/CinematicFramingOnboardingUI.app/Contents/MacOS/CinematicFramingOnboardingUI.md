## CinematicFramingOnboardingUI

> `/System/Library/Frameworks/CoreMediaIO.framework/Versions/A/Resources/CinematicFramingOnboardingUI.app/Contents/MacOS/CinematicFramingOnboardingUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-587.122.6.0.2
-  __TEXT.__text: 0x13bc
-  __TEXT.__auth_stubs: 0x2a0
+587.140.7.0.0
+  __TEXT.__text: 0x1554
+  __TEXT.__auth_stubs: 0x2e0
   __TEXT.__objc_stubs: 0xae0
   __TEXT.__objc_methlist: 0x5cc
-  __TEXT.__const: 0x18
+  __TEXT.__const: 0x20
   __TEXT.__gcc_except_tab: 0x18
   __TEXT.__objc_methname: 0x15b3
   __TEXT.__objc_classname: 0xdb
   __TEXT.__objc_methtype: 0x9c4
-  __TEXT.__cstring: 0x1f3
+  __TEXT.__cstring: 0x297
+  __TEXT.__oslogstring: 0x4b
   __TEXT.__dlopen_cstrs: 0x5a
   __TEXT.__unwind_info: 0xe0
-  __DATA_CONST.__auth_got: 0x160
+  __DATA_CONST.__auth_got: 0x180
   __DATA_CONST.__got: 0x88
   __DATA_CONST.__const: 0xf0
-  __DATA_CONST.__cfstring: 0x320
+  __DATA_CONST.__cfstring: 0x360
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA.__objc_ivar: 0x24
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x120
+  __DATA.__common: 0x10
   __DATA.__bss: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 47
-  Symbols:   74
-  CStrings:  313
+  Symbols:   78
+  CStrings:  318
 
Symbols:
+ __os_log_send_and_compose_impl
+ _fig_log_call_emit_and_clean_up_after_send_and_compose
+ _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
+ _fig_note_initialize_category_with_default_work_cf
+ _os_log_type_enabled
- _objc_release
Functions:
~ sub_10000113c -> sub_1000011dc : 12 -> 132
~ sub_100001e90 -> sub_100001fa8 : 108 -> 396
CStrings:
+ "-[CinematicFramingRemoteAlertViewController handleControlCenterButton:]"
+ "<<<< CinematicFramingRemoteAlertViewController >>>> %s: called for %@ (%@)"
+ "cinematicframingremotealertviewcontroller_trace"
+ "com.apple.cameracapture"
+ "com.apple.coremedia"
```
