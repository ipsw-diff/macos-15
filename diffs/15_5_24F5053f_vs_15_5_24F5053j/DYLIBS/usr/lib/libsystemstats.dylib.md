## libsystemstats.dylib

> `/usr/lib/libsystemstats.dylib`

```diff

-498.100.2.0.0
-  __TEXT.__text: 0xc55c
-  __TEXT.__auth_stubs: 0x910
+498.120.2.0.0
+  __TEXT.__text: 0xce24
+  __TEXT.__auth_stubs: 0x950
   __TEXT.__objc_methlist: 0x158
-  __TEXT.__const: 0x118
+  __TEXT.__const: 0x120
   __TEXT.__gcc_except_tab: 0x44c
-  __TEXT.__cstring: 0xa4e
-  __TEXT.__oslogstring: 0x94c
+  __TEXT.__cstring: 0xab4
+  __TEXT.__oslogstring: 0xb1a
   __TEXT.__unwind_info: 0x3a0
   __TEXT.__objc_classname: 0x22
   __TEXT.__objc_methname: 0x565
   __TEXT.__objc_methtype: 0x1de
   __TEXT.__objc_stubs: 0x560
-  __DATA_CONST.__got: 0x88
+  __DATA_CONST.__got: 0x90
   __DATA_CONST.__const: 0x1e0
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x1f8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_arraydata: 0x40
-  __AUTH_CONST.__auth_got: 0x498
+  __AUTH_CONST.__auth_got: 0x4b8
   __AUTH_CONST.__const: 0x5d0
-  __AUTH_CONST.__cfstring: 0x4a0
+  __AUTH_CONST.__cfstring: 0x500
   __AUTH_CONST.__objc_const: 0x130
   __AUTH_CONST.__objc_dictobj: 0x28
   __DATA.__data: 0x608

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 265
-  Symbols:   249
-  CStrings:  278
+  Functions: 278
+  Symbols:   257
+  CStrings:  291
 
Symbols:
+ _CFNumberCreate
+ _CFPreferencesCopyValue
+ _CFPreferencesSetValue
+ _CFPreferencesSynchronize
+ _kCFPreferencesAnyHost
+ _systemstats_get_microstackshot_cycle_interval_default
+ _systemstats_get_microstackshot_cycle_interval_override
+ _systemstats_set_microstackshot_cycle_interval_override
CStrings:
+ "Invalid microstackshot cycle override: %llu < min %llu"
+ "Invalid microstackshot cycle override: %llu > max %llu"
+ "Invalid number for microstackshot cycle interval override: %lld"
+ "Invalid number for preferences setting %{public}@: %{public}@"
+ "Invalid value for preferences setting %{public}@: (%{public}@)%{public}@"
+ "Microstackshot PMI cycle interval overridden to %llu"
+ "Must be root to get microstackshot cycle override"
+ "Must be root to set microstackshot cycle override"
+ "PMICycleInterval"
+ "com.apple.microstackshots"
+ "com.apple.microstackshots.preferences_changed"
+ "endtime"
+ "root"
```
