## WebKitLegacy

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebKitLegacy.framework/Versions/A/WebKitLegacy`

```diff

-621.2.5.11.5
-  __TEXT.__text: 0x183870
+621.2.5.11.8
+  __TEXT.__text: 0x1837b8
   __TEXT.__auth_stubs: 0x8d60
   __TEXT.__objc_methlist: 0x10248
   __TEXT.__const: 0x672
-  __TEXT.__gcc_except_tab: 0x104b0
-  __TEXT.__cstring: 0x264f3
+  __TEXT.__gcc_except_tab: 0x104a8
+  __TEXT.__cstring: 0x2646a
   __TEXT.__oslogstring: 0x141
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0x8aa8

   __DATA_CONST.__objc_arraydata: 0x38
   __AUTH_CONST.__auth_got: 0x46c8
   __AUTH_CONST.__const: 0x5680
-  __AUTH_CONST.__cfstring: 0xe540
+  __AUTH_CONST.__cfstring: 0xe4c0
   __AUTH_CONST.__objc_const: 0x11378
   __AUTH_CONST.__objc_intobj: 0x3c0
   __AUTH_CONST.__objc_arrayobj: 0x30

   - /usr/lib/libsqlite3.dylib
   Functions: 7503
   Symbols:   15732
-  CStrings:  8560
+  CStrings:  8556
 
Functions:
~ +[WebPreferences initialize] : 15144 -> 15128
~ +[WebPreferences(WebPrivateExperimentalFeatures) _experimentalFeatures] : 23460 -> 23332
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 21796 -> 21756
CStrings:
- "Enable opt-in partitioned cookies"
- "Opt-in partitioned cookies (CHIPS)"
- "OptInPartitionedCookiesEnabled"
- "WebKitOptInPartitionedCookiesEnabled"
```
