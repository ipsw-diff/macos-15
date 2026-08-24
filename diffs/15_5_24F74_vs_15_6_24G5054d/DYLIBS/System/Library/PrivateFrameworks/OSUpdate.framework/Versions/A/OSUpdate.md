## OSUpdate

> `/System/Library/PrivateFrameworks/OSUpdate.framework/Versions/A/OSUpdate`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-2078.120.19.0.3
-  __TEXT.__text: 0x8ebd4
+2078.140.22.0.0
+  __TEXT.__text: 0x8fa48
   __TEXT.__auth_stubs: 0xab0
-  __TEXT.__objc_methlist: 0x6e9c
+  __TEXT.__objc_methlist: 0x6f0c
   __TEXT.__const: 0x191
-  __TEXT.__cstring: 0x652d
-  __TEXT.__oslogstring: 0xbf2d
+  __TEXT.__cstring: 0x678d
+  __TEXT.__oslogstring: 0xc39e
   __TEXT.__gcc_except_tab: 0x204c
   __TEXT.__ustring: 0xc
-  __TEXT.__unwind_info: 0x1d10
+  __TEXT.__unwind_info: 0x1d18
   __TEXT.__objc_classname: 0x81c
-  __TEXT.__objc_methname: 0x151b8
+  __TEXT.__objc_methname: 0x1546e
   __TEXT.__objc_methtype: 0x20a4
-  __TEXT.__objc_stubs: 0xe3e0
+  __TEXT.__objc_stubs: 0xe4a0
   __DATA_CONST.__got: 0x9d8
-  __DATA_CONST.__const: 0xc48
+  __DATA_CONST.__const: 0xc50
   __DATA_CONST.__objc_classlist: 0x220
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4548
+  __DATA_CONST.__objc_selrefs: 0x4598
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x3f8
   __AUTH_CONST.__auth_got: 0x568
-  __AUTH_CONST.__const: 0x2730
-  __AUTH_CONST.__cfstring: 0x52c0
-  __AUTH_CONST.__objc_const: 0x8988
+  __AUTH_CONST.__const: 0x2780
+  __AUTH_CONST.__cfstring: 0x5320
+  __AUTH_CONST.__objc_const: 0x8a48
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH.__objc_data: 0xaf0
-  __DATA.__objc_ivar: 0x65c
+  __DATA.__objc_ivar: 0x66c
   __DATA.__data: 0x612
   __DATA.__bss: 0x90
   __DATA_DIRTY.__objc_data: 0xa50

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbootpolicy.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2919
-  Symbols:   6497
-  CStrings:  5170
+  Functions: 2926
+  Symbols:   6519
+  CStrings:  5211
 
Symbols:
+ -[SUOSUMobileSoftwareUpdateController _shouldReportDDMError:]
+ -[SUOSUShimController _latestQualifyingMajorOSProduct]
+ -[SUOSUShimController _registerForBackgroundScanInitiatedNotification:outToken:]
+ -[SUOSUShimController backgroundScanCompleteNotifyToken]
+ -[SUOSUShimController backgroundScanInitiatedNotifyToken]
+ -[SUOSUShimController didPostScanCompleteNotification]
+ -[SUOSUShimController isBackgroundScanInProgress]
+ -[SUOSUShimController legacyBackgroundScanInitiatedNotifyToken]
+ -[SUOSUShimController setBackgroundScanCompleteNotifyToken:]
+ -[SUOSUShimController setBackgroundScanInitiatedNotifyToken:]
+ -[SUOSUShimController setDidPostScanCompleteNotification:]
+ -[SUOSUShimController setIsBackgroundScanInProgress:]
+ -[SUOSUShimController setLegacyBackgroundScanInitiatedNotifyToken:]
+ GCC_except_table121
+ GCC_except_table122
+ GCC_except_table132
+ GCC_except_table147
+ GCC_except_table155
+ GCC_except_table178
+ OBJC_IVAR_$_SUOSUShimController._backgroundScanCompleteNotifyToken
+ OBJC_IVAR_$_SUOSUShimController._backgroundScanInitiatedNotifyToken
+ OBJC_IVAR_$_SUOSUShimController._didPostScanCompleteNotification
+ OBJC_IVAR_$_SUOSUShimController._isBackgroundScanInProgress
+ OBJC_IVAR_$_SUOSUShimController._legacyBackgroundScanInitiatedNotifyToken
+ _SUOSUAutomaticBackgroundScanInitiatedNotification
+ ___80-[SUOSUShimController _registerForBackgroundScanInitiatedNotification:outToken:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48bs_e35_v16?0"SUMacControllerDescriptor"8l
+ ___block_descriptor_65_e8_32s40s48s56bs_e17_v16?0"NSError"8l
+ ___block_descriptor_65_e8_32s40s48s56bs_e5_v8?0l
+ _objc_msgSend$_latestQualifyingMajorOSProduct
+ _objc_msgSend$_registerForBackgroundScanInitiatedNotification:outToken:
+ _objc_msgSend$_shouldReportDDMError:
+ _objc_msgSend$didPostScanCompleteNotification
+ _objc_msgSend$isBackgroundScanInProgress
+ _objc_msgSend$setDidPostScanCompleteNotification:
+ _objc_msgSend$setIsBackgroundScanInProgress:
- -[SUOSUShimController _latestAvailableMajorOSProduct]
- -[SUOSUShimController backgroundScanNotifyToken]
- -[SUOSUShimController setBackgroundScanNotifyToken:]
- GCC_except_table119
- GCC_except_table120
- GCC_except_table128
- GCC_except_table145
- GCC_except_table153
- GCC_except_table176
- OBJC_IVAR_$_SUOSUShimController._backgroundScanNotifyToken
- ___147-[SUOSUManagedServiceDaemon postDDMNotificationToAllUsersForScheduledUpdate:updateVersion:ignoreDoNoDisturb:companyName:options:client:completion:]_block_invoke_3
- ___block_descriptor_56_e8_32s40s48bs_e35_v16?0"SUMacControllerDescriptor"8l
- ___block_descriptor_64_e8_32s40s48s56bs_e17_v16?0"NSError"8l
- _objc_msgSend$_latestAvailableMajorOSProduct
CStrings:
+ "%s, Evaluating products to determine if any match the requested parameters: version=%@, bundleIdentifier=%@, variant=%@ availableMajorUpdates=%@"
+ "%s: %@ does not match - a non-recommended update should only be considered if stagedOnly is set."
+ "%s: %@ does not match - a recommended update should only be considered if stagedOnly is not set."
+ "%s: %@ does not match - auxInfo is not a dictionary."
+ "%s: %@ does not match - found qualifying majorOS update but it is deferred."
+ "%s: %@ does not match - requested customer but the update is internal."
+ "%s: %@ does not match - requested internal but the update is customer."
+ "%s: %@ does not match - the bundle identifier(%@) is specified but it does not match(%@)."
+ "%s: %@ does not match - the product is internal but we're not on an internal build."
+ "%s: %@ does not match - the product is not internal but we're on an internal build.."
+ "%s: %@ does not match - the version is specified(%@) but it does not match(%@)"
+ "%s: A MajorOS Update we're iterating through is missing a required attribute. Version:%@ Identifier:%@"
+ "%s: Bypassing MajorOS version check, because full installer is required"
+ "%s: Evaluating products to determine the latest qualifying MajorOS product"
+ "%s: Failed to open Installer App at path:%@ with OSStatus Error:%d"
+ "%s: Found Qualifying MajorOS Updates from URL Scheme:%@"
+ "%s: Found installer on disk: %@"
+ "%s: Found qualifying majorOS Update to present:%@"
+ "%s: Found qualifying majorOS update %@ - %@ (%@)"
+ "%s: Ignoring the latest MajorOSProduct:%@ because it's major/minor version:%@ is not newer than your current major/minor version:%@"
+ "%s: Last notification date is in the future"
+ "%s: Major OS: self.client startInstallingUpdates"
+ "%s: Major OS: switch back to available updates pane"
+ "%s: No active client invoke function"
+ "%s: No active client to do DDM OS update, performing install via softwareupdated w/ options: %@"
+ "%s: No existing installer found on disk"
+ "%s: Not considering majorOS update (%@) as qualifying because it is not MSU-based."
+ "%s: Not considering majorOS update (%@) as qualifying because it is not major."
+ "%s: Not taking any action because a background scan is already in progress."
+ "%s: Notifying the delegate that a background scan has begun."
+ "%s: Notifying the delegate that a background scan is complete."
+ "%s: OnlyConsiderStagedUpdates is set, only fetching MajorOSUpdates that are staged!"
+ "%s: Opening installer: %@"
+ "%s: Posting %@ notification"
+ "%s: Posting %@ notification."
+ "%s: Received a background scan initiated notification: %@"
+ "%s: Refreshing all available updates on behalf of %@ notification."
+ "%s: Refreshing updates due to a successful locally-initiated scan."
+ "%s: Skipping MajorOSInfo fetch as there is already a cached copy of the product key:%@"
+ "%s: Skipping majorOS update (%@) because it is deferred."
+ "%s: Skipping refresh of updates on behalf of %@ notification as the notification was posted locally."
+ "%s: Using %@ as the latest qualifying product."
+ "%s: download only set"
+ "-[SUOSUManagedServiceDaemon postDDMNotificationToAllUsersForScheduledUpdate:updateVersion:ignoreDoNoDisturb:companyName:options:client:completion:]_block_invoke_2"
+ "-[SUOSUShimController _handleSuccessfullyCompletedScan]"
+ "-[SUOSUShimController _latestQualifyingMajorOSProduct]"
+ "-[SUOSUShimController _registerForBackgroundScanInitiatedNotification:outToken:]_block_invoke"
+ "-[SUOSUShimController _registerForScanCompletionNotification:outToken:]_block_invoke"
+ "-[SUOSUShimController startInstallingMajorOSVersion:orWithMajorOSBundleIdentifier:majorOSVariant:shouldOpenIA:inForeground:isMDMInitiated:fromAvailableMajorUpdates:]_block_invoke_2"
+ "Error registering for %@ notification: %d"
+ "TB,V_didPostScanCompleteNotification"
+ "TB,V_isBackgroundScanInProgress"
+ "Ti,V_backgroundScanCompleteNotifyToken"
+ "Ti,V_backgroundScanInitiatedNotifyToken"
+ "Ti,V_legacyBackgroundScanInitiatedNotifyToken"
+ "_backgroundScanCompleteNotifyToken"
+ "_backgroundScanInitiatedNotifyToken"
+ "_didPostScanCompleteNotification"
+ "_isBackgroundScanInProgress"
+ "_latestQualifyingMajorOSProduct"
+ "_legacyBackgroundScanInitiatedNotifyToken"
+ "_registerForBackgroundScanInitiatedNotification:outToken:"
+ "_shouldReportDDMError:"
+ "backgroundScanCompleteNotifyToken"
+ "backgroundScanInitiatedNotifyToken"
+ "com.apple.softwareupdate.AutoBackgroundScanInitiated"
+ "com.apple.softwareupdate.legacyBackgroundScanInitiated"
+ "didPostScanCompleteNotification"
+ "isBackgroundScanInProgress"
+ "legacyBackgroundScanInitiatedNotifyToken"
+ "macOS Sequoia Beta"
+ "setBackgroundScanCompleteNotifyToken:"
+ "setBackgroundScanInitiatedNotifyToken:"
+ "setDidPostScanCompleteNotification:"
+ "setIsBackgroundScanInProgress:"
+ "setLegacyBackgroundScanInitiatedNotifyToken:"
- "%@: Bypassing MajorOS version check, because full installer is required"
- "%@: Failed to open Installer App at path:%@ with OSStatus Error:%d"
- "%@: Found installer on disk: %@"
- "%@: Major OS: self.client startInstallingUpdates"
- "%@: Major OS: switch back to available updates pane"
- "%@: No existing installer found on disk"
- "%@: Opening installer: %@"
- "%@: Posting %@ notification."
- "%@: Refreshing all available updates on behalf of %@ notification."
- "%@: Using %@ as the latest qualifying product."
- "-[SUOSUManagedServiceDaemon postDDMNotificationToAllUsersForScheduledUpdate:updateVersion:ignoreDoNoDisturb:companyName:options:client:completion:]_block_invoke_3"
- "Controller: A MajorOS Update we're iterating through is missing a required attribute. Version:%@ Identifier:%@"
- "Controller: Found Qualifying MajorOS Updates from URL Scheme:%@"
- "Controller: Found Qualifying MajorOSProduct %@ - %@ (%@)"
- "Controller: Found qualifying majorOS Update to present:%@"
- "Controller: Ignoring the latest MajorOSProduct:%@ because it's major/minor version:%@ is not newer than your current major/minor version:%@"
- "Controller: Not considering majorOS update (%@) as qualifying because it is not MSU-based."
- "Controller: Not considering majorOS update (%@) as qualifying because it is not major."
- "Controller: OnlyConsiderStagedUpdates is set, only fetching MajorOSUpdates that are staged!"
- "Controller: Skipping MajorOSInfo fetch as there is already a cached copy of the product key:%@"
- "Controller: Skipping majorOS update (%@) because it is deferred."
- "Found qualifying majorOS update but it is deferred, skipping: %@"
- "If the bundle identifier(%@) is specified but it does not match(%@), skip this update."
- "If the product is internal and we're not internal don't pick."
- "If the product is not internal and we're on an internalOS don't pick."
- "If the version is specified(%@) but it does not match(%@), skip this update."
- "If we want customer and the update is internal, skip it."
- "If we want internal and the update is customer, skip it."
- "Ti,V_backgroundScanNotifyToken"
- "_backgroundScanNotifyToken"
- "_latestAvailableMajorOSProduct"
- "a"
- "availableMajorUpdates: %@"
- "backgroundScanNotifyToken"
- "setBackgroundScanNotifyToken:"
```
