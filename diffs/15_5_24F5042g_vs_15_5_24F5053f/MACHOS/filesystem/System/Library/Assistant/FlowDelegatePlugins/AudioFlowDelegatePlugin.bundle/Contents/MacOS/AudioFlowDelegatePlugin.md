## AudioFlowDelegatePlugin

> `/System/Library/Assistant/FlowDelegatePlugins/AudioFlowDelegatePlugin.bundle/Contents/MacOS/AudioFlowDelegatePlugin`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-3405.17.1.0.0
-  __TEXT.__text: 0x230c18
-  __TEXT.__auth_stubs: 0x6500
+3405.22.1.0.0
+  __TEXT.__text: 0x230370
+  __TEXT.__auth_stubs: 0x6420
   __TEXT.__objc_methlist: 0x6e8
-  __TEXT.__const: 0x8152
+  __TEXT.__const: 0x83e2
   __TEXT.__cstring: 0x727c
-  __TEXT.__swift5_typeref: 0x3b18
-  __TEXT.__oslogstring: 0x1da27
-  __TEXT.__constg_swiftt: 0x52d0
-  __TEXT.__swift5_builtin: 0x140
-  __TEXT.__swift5_reflstr: 0x3b8b
-  __TEXT.__swift5_assocty: 0xa00
-  __TEXT.__swift5_proto: 0x458
-  __TEXT.__swift5_types: 0x308
+  __TEXT.__swift5_typeref: 0x3b28
+  __TEXT.__oslogstring: 0x1d997
+  __TEXT.__constg_swiftt: 0x5350
+  __TEXT.__swift5_builtin: 0x190
+  __TEXT.__swift5_reflstr: 0x3beb
+  __TEXT.__swift5_assocty: 0xa60
+  __TEXT.__swift5_proto: 0x478
+  __TEXT.__swift5_types: 0x318
   __TEXT.__objc_classname: 0xce
   __TEXT.__objc_methname: 0x260a
   __TEXT.__objc_methtype: 0x3ef
-  __TEXT.__swift5_fieldmd: 0x2e1c
-  __TEXT.__swift5_capture: 0x2d9c
+  __TEXT.__swift5_fieldmd: 0x2e40
+  __TEXT.__swift5_capture: 0x2d20
   __TEXT.__swift_as_entry: 0x180
   __TEXT.__swift_as_ret: 0x1f8
   __TEXT.__swift5_protos: 0x58
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0x2f98
-  __TEXT.__eh_frame: 0x2be8
-  __DATA_CONST.__auth_got: 0x3280
-  __DATA_CONST.__got: 0x1b58
-  __DATA_CONST.__auth_ptr: 0x1e20
-  __DATA_CONST.__const: 0x9298
+  __TEXT.__unwind_info: 0x2f60
+  __TEXT.__eh_frame: 0x2ba0
+  __DATA_CONST.__auth_got: 0x3210
+  __DATA_CONST.__got: 0x1b78
+  __DATA_CONST.__auth_ptr: 0x1e40
+  __DATA_CONST.__const: 0x9200
   __DATA_CONST.__objc_classlist: 0x2b0
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x70
-  __DATA.__objc_const: 0x92e0
+  __DATA.__objc_const: 0x9340
   __DATA.__objc_selrefs: 0xbc8
   __DATA.__objc_data: 0x12a8
-  __DATA.__data: 0xb478
-  __DATA.__bss: 0x7910
+  __DATA.__data: 0xb4c0
+  __DATA.__bss: 0x7d10
   __DATA.__common: 0x468
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4628
+  Functions: 4606
   Symbols:   318
-  CStrings:  2572
+  CStrings:  2569
 
CStrings:
+ "AddMediaDialogProvider#makeUnsupportedDialog, parameterName: %s"
+ "AddMediaDialogProvider#makeUnsupportedMediaItemsDialog, reasonCode: %s"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse App Resolution state found app: %s"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse App resolution resulted in a failure. Error: %s"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse Done, returning disambiguation response: %s"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse applying app to intent after disambiguation"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse error getting app: %@"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse for input: %s"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse success"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse success with app: %@"
+ "AppResolutionOnDeviceStrategy#parseDisambiguationResponse unexpected resopnse: %s"
+ "AppResolutionOnDeviceStrategy#resolveApp App resolution resulted in a failure. Error: %s"
+ "AppResolutionOnDeviceStrategy#resolveApp Unable to get SiriKit intent from parse"
+ "AppResolutionOnDeviceStrategy#resolveApp returning result %s"
+ "AppResolutionOnDeviceStrategy#resolveApp success"
+ "AppResolutionOnDeviceStrategy#resolveApp timed out waiting for resolveApp to return, continuing on with noAppFound"
+ "CommonIntentAppResolver#resolveSelectedApp app IS installed but doesn't support any SiriKit audio intents: %{public}s"
+ "DetermineSnippetProvider#handleIntent called for Intent: %s %{private}s"
+ "SearchForMediaDialogProvider#makeUnsupportedDialog, reason: %s, mediaType: %s"
+ "UpdateMediaAffinityDialogProvider#makeUnsupportedDialog, reason: %s, mediaType: %s"
- "AppResolutionStrategy#parseDisambiguationResponse App Resolution state found app: %s"
- "AppResolutionStrategy#parseDisambiguationResponse App resolution resulted in a failure. Error: %s"
- "AppResolutionStrategy#parseDisambiguationResponse Done, returning disambiguation response: %s"
- "AppResolutionStrategy#parseDisambiguationResponse applying app to intent after disambiguation"
- "AppResolutionStrategy#parseDisambiguationResponse error getting app: %@"
- "AppResolutionStrategy#parseDisambiguationResponse for input: %s"
- "AppResolutionStrategy#parseDisambiguationResponse success"
- "AppResolutionStrategy#parseDisambiguationResponse success with app: %@"
- "AppResolutionStrategy#parseDisambiguationResponse unexpected resopnse: %s"
- "AppResolutionStrategy#resolveApp App resolution resulted in a failure. Error: %s"
- "AppResolutionStrategy#resolveApp Unable to get SiriKit intent from parse"
- "AppResolutionStrategy#resolveApp returning result %s"
- "AppResolutionStrategy#resolveApp success"
- "CommonIntentAppResolver#resolveSelectedApp app IS installed but doesn't support any Sirikit audio intents: %{public}s"
- "DetermineSnippetProvider#handleIntent called for Intent: %s %{public}s"
- "SiriAudioUIAssertionProvider#acquireAndReleaseQuickControlsAssertion No UI sessionID has been provided"
- "SiriAudioUIAssertionProvider#acquireAndReleaseQuickControlsAssertion acquire Media Remote assertion."
- "SiriAudioUIAssertionProvider#acquireAndReleaseQuickControlsAssertion release Media Remote assertion."
- "SiriAudioUIAssertionProvider#acquireUIAssertion returning sessionID: %@"
- "SiriAudioUIAssertionProvider#acquireUIAssertion routeId: %@"
- "SiriAudioUIAssertionProvider#acquireUIAssertion..."
- "SiriAudioUIAssertionProvider#fetchSessionIDIfNeeded shouldSuppressSnippet: %{bool}d"
- "_INPBWholeHouseAudioMetadata#init Resolved devices: %s"
```
