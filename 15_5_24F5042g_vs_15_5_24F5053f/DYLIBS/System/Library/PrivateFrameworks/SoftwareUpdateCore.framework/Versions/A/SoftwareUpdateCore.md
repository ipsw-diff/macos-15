## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/Versions/A/SoftwareUpdateCore`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-2171.120.23.501.1
-  __TEXT.__text: 0xaaf70
+2171.120.30.0.4
+  __TEXT.__text: 0xab390
   __TEXT.__auth_stubs: 0x680
-  __TEXT.__objc_methlist: 0x72ac
+  __TEXT.__objc_methlist: 0x72cc
   __TEXT.__const: 0x118
-  __TEXT.__cstring: 0x14240
-  __TEXT.__oslogstring: 0xad2a
+  __TEXT.__cstring: 0x14297
+  __TEXT.__oslogstring: 0xae77
   __TEXT.__gcc_except_tab: 0x6d4
   __TEXT.__unwind_info: 0x15d0
   __TEXT.__objc_classname: 0x6d5
-  __TEXT.__objc_methname: 0x1405b
+  __TEXT.__objc_methname: 0x14105
   __TEXT.__objc_methtype: 0xec2
-  __TEXT.__objc_stubs: 0xd7c0
+  __TEXT.__objc_stubs: 0xd800
   __DATA_CONST.__got: 0x810
-  __DATA_CONST.__const: 0x13b0
+  __DATA_CONST.__const: 0x13b8
   __DATA_CONST.__objc_classlist: 0x1c8
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3f10
+  __DATA_CONST.__objc_selrefs: 0x3f30
   __DATA_CONST.__objc_superrefs: 0x1b0
   __DATA_CONST.__objc_arraydata: 0xa8
   __AUTH_CONST.__auth_got: 0x350
   __AUTH_CONST.__const: 0x1220
-  __AUTH_CONST.__cfstring: 0x11e80
-  __AUTH_CONST.__objc_const: 0x9ce0
+  __AUTH_CONST.__cfstring: 0x11ee0
+  __AUTH_CONST.__objc_const: 0x9d10
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH.__objc_data: 0x11d0
-  __DATA.__objc_ivar: 0x8f8
+  __DATA.__objc_ivar: 0x8fc
   __DATA.__data: 0x360
   __DATA.__bss: 0xc0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2849
-  Symbols:   6518
-  CStrings:  6059
+  Functions: 2854
+  Symbols:   6525
+  CStrings:  6072
 
Symbols:
+ -[SUCoreDocumentation encodedUIBundleFileName]
+ -[SUCoreDocumentation encodedUIBundlePath]
+ -[SUCoreDocumentation setEncodedUIBundleFileName:]
+ OBJC_IVAR_$_SUCoreDocumentation._encodedUIBundleFileName
+ _kSUAssetEncodedUIBundleFileNameKey
+ _objc_msgSend$encodedUIBundleFileName
+ _objc_msgSend$stringByAppendingPathExtension:
CStrings:
+ "\n[>>>\n                        releaseNotesSummary: %@\n                               releaseNotes: %@\n                           licenseAgreement: %@\n                    humanReadableUpdateName: %@\n                   humanReadableUpdateTitle: %@\n                 humanReadableUpdateVersion: %@\n                  humanReadableMoreInfoLink: %@\n                        notificationEnabled: %@\n                    notificationTitleString: %@\n                     notificationBodyString: %@\n                   recommendedUpdateEnabled: %@\n                recommendedUpdateApplicable: %@\n recommendedUpdateNotificationFrequencyDays: %@\n              recommendedUpdateMinOSVersion: %@\n              recommendedUpdateMaxOSVersion: %@\n               recommendedUpdateTitleString: %@\n           recommendedUpdateAlertBodyString: %@\n                  mandatoryUpdateBodyString: %@\n    securityAdvisoryNotificationTitleString: %@\n     securityAdvisoryNotificationBodyString: %@\n deviceCompatibilityNotificationTitleString: %@\n  deviceCompatibilityNotificationBodyString: %@\n                             productVersion: %@\n                                 slaVersion: %@\n                             localBundleURL: %@\n                             serverAssetURL: %@\n                     serverAssetMeasurement: %@\n                       serverAssetAlgorithm: %@\n                                   language: %@\n                releaseNotesSummaryFileName: %@\n                       releaseNotesFileName: %@\n                   licenseAgreementFileName: %@\n                    preferencesIconFileName: %@\n                    encodedUIBundleFileName: %@\n<<<]"
+ "EncodedUI"
+ "EncodedUIBundleFileName"
+ "T@\"NSString\",&,V_encodedUIBundleFileName"
+ "[DOCUMENTATION] Failed to determine encoded UI bundle path due to local bundle URL not present (asset not downloaded)"
+ "[DOCUMENTATION] Failed to determine encoded UI bundle path due to no preferences file name"
+ "[DOCUMENTATION] No encoded UI bundle path was found at: %{public}@"
+ "[DOCUMENTATION] Using encoded UI bundle path: %{public}@"
+ "_encodedUIBundleFileName"
+ "encodedUIBundleFileName"
+ "encodedUIBundlePath"
+ "setEncodedUIBundleFileName:"
+ "stringByAppendingPathExtension:"
+ "suda"
- "\n[>>>\n                        releaseNotesSummary: %@\n                               releaseNotes: %@\n                           licenseAgreement: %@\n                    humanReadableUpdateName: %@\n                   humanReadableUpdateTitle: %@\n                 humanReadableUpdateVersion: %@\n                  humanReadableMoreInfoLink: %@\n                        notificationEnabled: %@\n                    notificationTitleString: %@\n                     notificationBodyString: %@\n                   recommendedUpdateEnabled: %@\n                recommendedUpdateApplicable: %@\n recommendedUpdateNotificationFrequencyDays: %@\n              recommendedUpdateMinOSVersion: %@\n              recommendedUpdateMaxOSVersion: %@\n               recommendedUpdateTitleString: %@\n           recommendedUpdateAlertBodyString: %@\n                  mandatoryUpdateBodyString: %@\n    securityAdvisoryNotificationTitleString: %@\n     securityAdvisoryNotificationBodyString: %@\n deviceCompatibilityNotificationTitleString: %@\n  deviceCompatibilityNotificationBodyString: %@\n                             productVersion: %@\n                                 slaVersion: %@\n                             localBundleURL: %@\n                             serverAssetURL: %@\n                     serverAssetMeasurement: %@\n                       serverAssetAlgorithm: %@\n                                   language: %@\n                releaseNotesSummaryFileName: %@\n                       releaseNotesFileName: %@\n                   licenseAgreementFileName: %@\n                    preferencesIconFileName: %@\n<<<]"
```
