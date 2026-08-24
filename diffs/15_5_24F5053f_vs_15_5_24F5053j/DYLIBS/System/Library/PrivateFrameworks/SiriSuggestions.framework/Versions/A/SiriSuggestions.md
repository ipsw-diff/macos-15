## SiriSuggestions

> `/System/Library/PrivateFrameworks/SiriSuggestions.framework/Versions/A/SiriSuggestions`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-3405.19.1.0.0
-  __TEXT.__text: 0x1dbee4
+3405.21.1.0.0
+  __TEXT.__text: 0x1dbfc0
   __TEXT.__auth_stubs: 0x5300
   __TEXT.__objc_methlist: 0x27c
   __TEXT.__const: 0xb934

   __TEXT.__constg_swiftt: 0x5bd8
   __TEXT.__swift5_reflstr: 0x345f
   __TEXT.__swift5_capture: 0x948
-  __TEXT.__oslogstring: 0x8f1d
+  __TEXT.__oslogstring: 0x8f9d
   __TEXT.__swift5_builtin: 0x50
   __TEXT.__swift5_assocty: 0x1b8
   __TEXT.__swift5_protos: 0x140

   __TEXT.__swift_as_entry: 0xaa0
   __TEXT.__swift_as_ret: 0xb50
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x76b0
-  __TEXT.__eh_frame: 0x157f0
+  __TEXT.__unwind_info: 0x76c8
+  __TEXT.__eh_frame: 0x15838
   __TEXT.__objc_classname: 0x7f
   __TEXT.__objc_methname: 0xf1a
   __TEXT.__objc_methtype: 0x229

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 9419
+  Functions: 9420
   Symbols:   2922
-  CStrings:  1697
+  CStrings:  1698
 
CStrings:
+ "SuggestHelpFilter: created generic suggestHelp but there's a foregrounded app"
+ "SuggestHelpFilter: filtering out suggestHelp because either the resolved mentioned app or the current foregrounded app %s is NOT in our suggestHelp app allow list"
+ "autocompleteINIntentAllowLists"
- "autocompleteINIntentDenyLists"
- "suggestHelp resolved appDetails %s is NOT in our suggestHelp app allow list. Filtering out suggestHelp suggestion"
```
