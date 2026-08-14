## SoftwareUpdate

> `/System/Library/PrivateFrameworks/SoftwareUpdate.framework/Versions/A/SoftwareUpdate`

```diff

-2078.120.12.0.0
-  __TEXT.__text: 0x83714
+2078.120.19.0.3
+  __TEXT.__text: 0x83e4c
   __TEXT.__auth_stubs: 0x1070
-  __TEXT.__objc_methlist: 0x653c
+  __TEXT.__objc_methlist: 0x65c8
   __TEXT.__const: 0x670
-  __TEXT.__gcc_except_tab: 0x135c
-  __TEXT.__cstring: 0x8628
-  __TEXT.__oslogstring: 0xb730
+  __TEXT.__gcc_except_tab: 0x1378
+  __TEXT.__cstring: 0x8679
+  __TEXT.__oslogstring: 0xb7f7
   __TEXT.__dof_SoftwareU: 0xc9e
-  __TEXT.__unwind_info: 0x2200
+  __TEXT.__unwind_info: 0x2228
   __TEXT.__eh_frame: 0x48
-  __TEXT.__objc_classname: 0x875
-  __TEXT.__objc_methname: 0x119c2
+  __TEXT.__objc_classname: 0x886
+  __TEXT.__objc_methname: 0x11ac1
   __TEXT.__objc_methtype: 0x1cd4
-  __TEXT.__objc_stubs: 0xc2c0
-  __DATA_CONST.__got: 0x7a8
-  __DATA_CONST.__const: 0xa80
+  __TEXT.__objc_stubs: 0xc260
+  __DATA_CONST.__got: 0x790
+  __DATA_CONST.__const: 0xa90
   __DATA_CONST.__objc_classlist: 0x240
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3f70
+  __DATA_CONST.__objc_selrefs: 0x3f98
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x1e8
   __DATA_CONST.__objc_arraydata: 0x70
   __AUTH_CONST.__auth_got: 0x848
   __AUTH_CONST.__const: 0x2a60
-  __AUTH_CONST.__cfstring: 0x75c0
-  __AUTH_CONST.__objc_const: 0x8bc8
+  __AUTH_CONST.__cfstring: 0x7620
+  __AUTH_CONST.__objc_const: 0x8bd0
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH.__objc_data: 0x1680

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpartition2_dynamic.dylib
-  Functions: 3207
-  Symbols:   6419
-  CStrings:  4998
+  Functions: 3222
+  Symbols:   6429
+  CStrings:  5011
 
Symbols:
+ -[SUPreferenceManager _clearAnyPreferenceWithKey:withError:]
+ -[SUPreferenceManager setEncodedBundleOverridePath:]
+ -[SUPreferenceManager setSettingsClientOverride:]
+ -[SUSharedPrefs(SystemSettingsUI) encodedUIBundleOverridePath]
+ -[SUSharedPrefs(SystemSettingsUI) setEncodedUIBundleOverridePath:]
+ -[SUSharedPrefs(SystemSettingsUI) setSettingsClientOverride:]
+ -[SUSharedPrefs(SystemSettingsUI) setSettingsIsClientOverridePersisted:]
+ -[SUSharedPrefs(SystemSettingsUI) settingsClientOverride]
+ -[SUSharedPrefs(SystemSettingsUI) settingsIsClientOverridePersisted]
+ -[SUUpdateServiceClient clearAnyPreferenceWithKey:reply:]
+ -[SUUpdateServiceDaemon clearAnyPreferenceWithKey:reply:]
+ GCC_except_table71
+ GCC_except_table74
+ GCC_except_table77
+ GCC_except_table80
+ _SUEncodedUIBundleOverridePath
+ _SUSettingsClientOverride
+ __60-[SUPreferenceManager _clearAnyPreferenceWithKey:withError:]_block_invoke
+ __OBJC_$_CLASS_METHODS_SUSharedPrefs(AnyUserPrefs|ScanStatus|SessionStatus|SystemSettingsUI|ForSUHelper|DevPrefs|Utilities)
+ __OBJC_$_INSTANCE_METHODS_SUSharedPrefs(AnyUserPrefs|ScanStatus|SessionStatus|SystemSettingsUI|ForSUHelper|DevPrefs|Utilities)
+ ___60-[SUPreferenceManager _clearAnyPreferenceWithKey:withError:]_block_invoke
+ _objc_msgSend$_clearAnyPreferenceWithKey:withError:
+ _objc_msgSend$_pk_containsBlockOrFunctionPredicatesOrExpressions
+ _objc_msgSend$clearAnyPreferenceWithKey:reply:
- -[NSPredicate(SU_Sanitization) _su_allExpressions]
- GCC_except_table72
- GCC_except_table78
- _OBJC_CLASS_$_NSBlockPredicate
- _OBJC_CLASS_$_NSComparisonPredicate
- _OBJC_CLASS_$_NSCompoundPredicate
- __OBJC_$_CLASS_METHODS_SUSharedPrefs(AnyUserPrefs|ScanStatus|SessionStatus|ForSUHelper|DevPrefs|Utilities)
- __OBJC_$_INSTANCE_METHODS_SUSharedPrefs(AnyUserPrefs|ScanStatus|SessionStatus|ForSUHelper|DevPrefs|Utilities)
- _objc_msgSend$_su_allExpressions
- _objc_msgSend$_su_containsBlockOrFunctionPredicatesOrExpressions
- _objc_msgSend$expressionType
- _objc_msgSend$leftExpression
- _objc_msgSend$rightExpression
- _objc_msgSend$subpredicates
CStrings:
+ "%@: Failed to set SUEncodedUIBundleOverridePath: %@"
+ "%@: Failed to set SUSettingsClientOverride: %@"
+ "Client Pid:%d tried to clear an SU Preference but is not entitled!"
+ "EncodedUIBundleOverridePath"
+ "SUPreferenceManager: Clearing %@"
+ "SettingsClientOverride"
+ "SettingsPersistClientOverride"
+ "SystemSettingsUI"
+ "_clearAnyPreferenceWithKey:withError:"
+ "_pk_containsBlockOrFunctionPredicatesOrExpressions"
+ "clearAnyPreferenceWithKey:reply:"
+ "encodedUIBundleOverridePath"
+ "setEncodedBundleOverridePath:"
+ "setEncodedUIBundleOverridePath:"
+ "setSettingsClientOverride:"
+ "setSettingsIsClientOverridePersisted:"
+ "settingsClientOverride"
+ "settingsIsClientOverridePersisted"
- "_su_allExpressions"
- "expressionType"
- "leftExpression"
- "rightExpression"
- "subpredicates"
```
