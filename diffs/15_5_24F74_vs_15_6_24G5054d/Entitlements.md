## 🔑 Entitlements

### filesystem

### Archive Utility

> `/System/Library/CoreServices/Applications/Archive Utility.app/Contents/MacOS/Archive Utility`

```diff

 	<true/>
 	<key>com.apple.private.app-sandbox.unquarantine</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.ArchiveUtility.PKSignedContainer</string>
+	</array>
 	<key>com.apple.private.security.storage.ArchiveUtility</key>
 	<true/>
 	<key>com.apple.private.security.syspolicy.package-installation</key>
 	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.ArchiveUtility.PKSignedContainer</string>
+	</array>
 	<key>com.apple.security.files.user-selected.read-write</key>
 	<true/>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>

```
### ManagedClient

> `/System/Library/CoreServices/ManagedClient.app/Contents/MacOS/ManagedClient`

```diff

 </dict>
 </plist>
 
+<!-- Launch Constraints (Self) -->
+{
+  "appl": 1,
+  "ccat": 1,
+  "comp": 1,
+  "reqs": {},
+  "vers": 1
+}
+
+<!-- Launch Constraints (Parent) -->
+{
+  "appl": 1,
+  "ccat": 0,
+  "comp": 1,
+  "reqs": {
+    "signing-identifier": {
+      "$in": [
+        "com.apple.loginwindow",
+        "com.apple.mdmclient",
+        "com.apple.ManagedClient",
+        "com.apple.ManagedClientAgent",
+        "com.apple.createmobileaccount",
+        "com.apple.devicemanagementclient.cloudconfigd",
+        "com.apple.familycontrolsd",
+        "com.apple.profiles",
+        "com.apple.profiles_internal",
+        "com.apple.configprofileutil",
+        "com.apple.mcx.ProfileHelper",
+        "com.apple.taskgated-helper",
+        "com.apple.parentalcontrolsd",
+        "com.apple.mcxquery",
+        "com.apple.mcxrefresh",
+        "com.apple.mbsystemadministration",
+        "com.apple.sysadminctl",
+        "com.apple.xpc.launchd"
+      ]
+    },
+    "validation-category": 1
+  },
+  "vers": 1
+}
+

```
### ImageThumbnailExtension

> `/System/Library/ExtensionKit/Extensions/ImageThumbnailExtension.appex/Contents/MacOS/ImageThumbnailExtension`

```diff

 	<true/>
 	<key>com.apple.private.extension-sandbox-profile</key>
 	<string>quicklook-thumbnail-secure</string>
-	<key>com.apple.private.quicklook-thumbnail.video</key>
+	<key>com.apple.private.quicklook-thumbnail.raw-image</key>
 	<true/>
 	<key>com.apple.private.security.message-filter</key>
 	<true/>

```
### acdiagnose

> `/System/Library/Frameworks/Accounts.framework/Versions/A/Support/acdiagnose`

```diff

 	<string>AAACCOUNTS.com.apple.acdiagnose</string>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>keychain-access-groups</key>
 	<array>
 		<string>apple</string>

```
### AirPlaySenderService

> `/System/Library/PrivateFrameworks/AirPlaySenderKit.framework/Versions/A/XPCServices/AirPlaySenderService.xpc/Contents/MacOS/AirPlaySenderService`

```diff

 	<array>
 		<string>com.apple.airplay</string>
 		<string>com.apple.airplay.pairing</string>
+		<string>com.apple.pairing</string>
 	</array>
 </dict>
 </plist>

```
### AirPlaySenderService

> `/System/Library/PrivateFrameworks/AirPlaySenderKit.framework/Versions/Current/XPCServices/AirPlaySenderService.xpc/Contents/MacOS/AirPlaySenderService`

```diff

 	<array>
 		<string>com.apple.airplay</string>
 		<string>com.apple.airplay.pairing</string>
+		<string>com.apple.pairing</string>
 	</array>
 </dict>
 </plist>

```
### assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/Support/assistantd`

```diff

 		<string>SIRI_AUDIO_APP_SELECTION_HOMEPOD</string>
 		<string>SIRI_AUDIO_DISABLE_MEDIA_ENTITY_SYNC</string>
 		<string>SIRI_AUDIO_LAPSED_MUSIC_USER</string>
+		<string>SIRI_AUDIO_STC</string>
 		<string>SIRI_AUDIO_TAPTORADAR_CONFIGURATION</string>
 		<string>SIRI_AUDIO_TTS_BEHAVIOR</string>
 		<string>SIRI_DATA_INTEGRATION_TEST1</string>

```
### CSExattrCryptoService

> `/System/Library/PrivateFrameworks/CSExattrCrypto.framework/Versions/A/XPCServices/CSExattrCryptoService.xpc/Contents/MacOS/CSExattrCryptoService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.security.files.user-selected.read-only</key>
 	<true/>
 	<key>com.apple.security.files.user-selected.read-write</key>

```
### CSExattrCryptoService

> `/System/Library/PrivateFrameworks/CSExattrCrypto.framework/Versions/Current/XPCServices/CSExattrCryptoService.xpc/Contents/MacOS/CSExattrCryptoService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.security.files.user-selected.read-only</key>
 	<true/>
 	<key>com.apple.security.files.user-selected.read-write</key>

```
### cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Versions/A/Support/cloudphotod`

```diff

 <dict>
 	<key>aps-connection-initiate</key>
 	<true/>
+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
 	<key>com.apple.application-identifier</key>
 	<string>AAPLPHOTOS.com.apple.cloudphotod</string>
 	<key>com.apple.authkit.client.private</key>

 	<string>serverPreferred</string>
 	<key>com.apple.developer.icloud-container-environment</key>
 	<string>Production</string>
+	<key>com.apple.developer.icloud-extended-share-access</key>
+	<array>
+		<string>InProcessShareOwnerParticipantInfo</string>
+	</array>
 	<key>com.apple.developer.icloud-services</key>
 	<array>
 		<string>CloudKit</string>

```
### corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

```diff

 <dict>
 	<key>application-identifier</key>
 	<string>com.apple.corespeechd</string>
+	<key>com.apple.account.AppleAccount</key>
+	<true/>
+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
 	<key>com.apple.airplay.carplayavvc</key>
 	<true/>
 	<key>com.apple.aned.private.ANEAccess.allow</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.account.AppleAccount</string>
+		<string>com.apple.accounts.appleaccount.fullaccess</string>
 		<string>com.apple.corefollowup.agent</string>
 		<string>com.apple.audio.isolated.historicalaudio.client.service</string>
 		<string>com.apple.mobile.usermanagerd.xpc</string>

```
### corespeechd_system

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd_system`

```diff

 <dict>
 	<key>application-identifier</key>
 	<string></string>
+	<key>com.apple.account.AppleAccount</key>
+	<true/>
+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
 	<key>com.apple.airplay.carplayavvc</key>
 	<true/>
 	<key>com.apple.aned.private.ANEAccess.allow</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.account.AppleAccount</string>
+		<string>com.apple.accounts.appleaccount.fullaccess</string>
 		<string>com.apple.corefollowup.agent</string>
 		<string>com.apple.audio.isolated.historicalaudio.client.service</string>
 		<string>com.apple.mobile.usermanagerd.xpc</string>

```
### FindMyDeviceEraseXPCService

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/XPCServices/FindMyDeviceEraseXPCService.xpc/Contents/MacOS/FindMyDeviceEraseXPCService`

```diff

 	<true/>
 	<key>com.apple.private.remote.mobile_obliteration</key>
 	<true/>
+	<key>com.apple.private.security.nvram.fmm</key>
+	<true/>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.nfcd.hwmanager</string>

```
### FindMyMacd

> `/System/Library/PrivateFrameworks/FindMyMac.framework/Versions/A/Resources/FindMyMacd`

```diff

 	<true/>
 	<key>com.apple.private.iokit.system-nvram-allow</key>
 	<true/>
+	<key>com.apple.private.security.nvram.fmm</key>
+	<true/>
 	<key>com.apple.private.security.nvram.recovery-boot-mode</key>
 	<true/>
 </dict>

```
### FindMyMacd

> `/System/Library/PrivateFrameworks/FindMyMac.framework/Versions/Current/Resources/FindMyMacd`

```diff

 	<true/>
 	<key>com.apple.private.iokit.system-nvram-allow</key>
 	<true/>
+	<key>com.apple.private.security.nvram.fmm</key>
+	<true/>
 	<key>com.apple.private.security.nvram.recovery-boot-mode</key>
 	<true/>
 </dict>

```
### revisiond

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/Versions/A/Support/revisiond`

```diff

 		<string>kTCCServiceSystemPolicyRemovableVolumes</string>
 		<string>kTCCServiceSystemPolicyNetworkVolumes</string>
 	</array>
+	<key>com.apple.private.vfs.authorized-access</key>
+	<true/>
 	<key>com.apple.private.vfs.fsevents-watcher</key>
 	<true/>
 	<key>com.apple.private.vfs.open-by-id</key>

```
### generativeexperiencesd

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/Versions/A/generativeexperiencesd`

```diff

 	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
-		<key>RegionalSafetyAnalysisMetrics</key>
-		<dict>
-			<key>Streams</key>
-			<dict>
-				<key>RegionalSafetyAnalysis.Disablement</key>
-				<dict>
-					<key>mode</key>
-					<string>read-write</string>
-				</dict>
-				<key>RegionalSafetyAnalysis.Eligibility</key>
-				<dict>
-					<key>mode</key>
-					<string>read-write</string>
-				</dict>
-			</dict>
-		</dict>
 		<key>com.apple.GenerativeFunctions.PeriodicTasks.InstrumentationUpload</key>
 		<dict>
 			<key>Streams</key>

 	</array>
 	<key>com.apple.private.launchservices.canmodifypreferences</key>
 	<true/>
+	<key>com.apple.private.nsurlsession.impersonate</key>
+	<true/>
 	<key>com.apple.private.security.storage.AppleIntelligencePlatform</key>
 	<true/>
 	<key>com.apple.private.security.storage.MobileAssetGenerativeModels</key>

 	<true/>
 	<key>com.apple.proactive.eventtracker</key>
 	<true/>
+	<key>com.apple.timed</key>
+	<true/>
 </dict>
 </plist>
 

```
### cryptegraft

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Support/cryptegraft`

```diff

 <dict>
 	<key>allow-softwareupdated</key>
 	<true/>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.private.softwareupdated-helpers</key>
 	<true/>
 </dict>

```
### com.apple.MobileSoftwareUpdate.CryptegraftService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/A/XPCServices/com.apple.MobileSoftwareUpdate.CryptegraftService.xpc/Contents/MacOS/com.apple.MobileSoftwareUpdate.CryptegraftService`

```diff

 	<string>com.apple.MobileSoftwareUpdate.CryptegraftService</string>
 	<key>com.apple.application-identifier</key>
 	<string>com.apple.MobileSoftwareUpdate.CryptegraftService</string>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.private.biome.read-write</key>
 	<array>
 		<string>Device.Metadata</string>

```
### com.apple.MobileSoftwareUpdate.CryptegraftService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/Current/XPCServices/com.apple.MobileSoftwareUpdate.CryptegraftService.xpc/Contents/MacOS/com.apple.MobileSoftwareUpdate.CryptegraftService`

```diff

 	<string>com.apple.MobileSoftwareUpdate.CryptegraftService</string>
 	<key>com.apple.application-identifier</key>
 	<string>com.apple.MobileSoftwareUpdate.CryptegraftService</string>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.private.biome.read-write</key>
 	<array>
 		<string>Device.Metadata</string>

```
### modelcatalogd

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/Versions/A/modelcatalogd`

```diff

 	<string>com.apple.modelcatalogd</string>
 	<key>com.apple.duet.activityscheduler.allow</key>
 	<true/>
+	<key>com.apple.generativeexperiences.FailureTracking</key>
+	<true/>
 	<key>com.apple.private.assets.accessible-asset-types</key>
 	<array>
 		<string>com.apple.MobileAsset.UAF.FM.GenerativeModels</string>

 		<string>com.apple.duetactivityscheduler</string>
 		<string>com.apple.siri.uaf.service</string>
 		<string>com.apple.mobileasset.autoasset</string>
+		<string>com.apple.generativeexperiences.FailureTracking</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>

```
### com.apple.SpeechRecognitionCore.speechrecognitiond

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/Versions/A/XPCServices/com.apple.SpeechRecognitionCore.brokerd.xpc/Contents/XPCServices/com.apple.SpeechRecognitionCore.speechrecognitiond.xpc/Contents/MacOS/com.apple.SpeechRecognitionCore.speechrecognitiond`

```diff

 	<key>com.apple.assistant.dictation.prerecorded</key>
 	<true/>
 	<key>com.apple.private.amfi.version-restriction</key>
-	<true/>
+	<integer>1</integer>
 	<key>com.apple.private.assets.accessible-asset-types</key>
 	<array>
 		<string>com.apple.MobileAsset.EmbeddedSpeech</string>

```
### StocksKitService

> `/System/Library/PrivateFrameworks/StocksKit.framework/XPCServices/StocksKitService.xpc/Contents/MacOS/StocksKitService`

```diff

 <dict>
 	<key>application-identifier</key>
 	<string>ZL6BUSYGB3.com.apple.StocksKitService</string>
+	<key>com.apple.itunesstored.private</key>
+	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.applemediaservices</key>
+	<true/>
 	<key>com.apple.private.network.socket-delegate</key>
 	<true/>
+	<key>com.apple.private.sandbox.profile:embedded</key>
+	<string>temporary-sandbox</string>
 	<key>com.apple.private.security.daemon-container</key>
 	<true/>
-	<key>com.apple.private.security.restricted-application-groups</key>
+	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.stocks</string>
 	</array>
-	<key>com.apple.security.application-groups</key>
+	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
 	<array>
-		<string>group.com.apple.stocks</string>
+		<string>/Library/Caches/com.apple.AppleMediaServices/</string>
+	</array>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.fairplayd.versioned</string>
+		<string>com.apple.adid</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.newscore</string>
+		<string>com.apple.itunesstored</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.stocks2</string>
+		<string>com.apple.stocks.stockskit</string>
+		<string>com.apple.StocksKitService</string>
+		<string>com.apple.AppleMediaServices</string>
+	</array>
+	<key>com.apple.security.iokit-user-client-class</key>
+	<array>
+		<string>IOSurfaceRootUserClient</string>
+		<string>AppleParavirtDeviceUserClient</string>
 	</array>
+	<key>com.apple.security.network.client</key>
+	<true/>
+	<key>com.apple.security.ts.daemon-container</key>
+	<true/>
 	<key>fairplay-client</key>
 	<string>1417937365</string>
+	<key>platform-application</key>
+	<true/>
 </dict>
 </plist>
 

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

 	<key>com.apple.private.ids.messaging</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
-		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.lp</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>

 	<key>com.apple.private.ids.messaging.high-priority</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
-		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.lp</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>

 	</array>
 	<key>com.apple.private.ids.registration</key>
 	<array>
-		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.facetime.multi</string>
 		<string>com.apple.private.alloy.facetime.sync</string>
 	</array>

 	<key>com.apple.private.ids.self-session</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
-		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.audio</string>

 	<key>com.apple.private.ids.session</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
-		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.audio</string>

 	<key>com.apple.private.ids.session-private</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
-		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.audio</string>

```
### GameCenterMessageExtension

> `/System/iOSSupport/System/Library/PrivateFrameworks/GameCenterUI.framework/PlugIns/GameCenterMessageExtension.appex/Contents/MacOS/GameCenterMessageExtension`

```diff

 		<string>Multiplayer</string>
 		<string>TurnBasedMultiplayer</string>
 	</array>
+	<key>com.apple.developer.hardened-process</key>
+	<true/>
 	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
 	<string>com.apple.gamecenter</string>
 	<key>com.apple.itunesstored.private</key>

```
### xip

> `/usr/bin/xip`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.xip.PKSignedContainer</string>
+	</array>
 	<key>com.apple.private.security.syspolicy.package-installation</key>
 	<true/>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.xip.PKSignedContainer</string>
+	</array>
 </dict>
 </plist>
 

```
### AirPlayXPCHelper

> `/usr/libexec/AirPlayXPCHelper`

```diff

 	<true/>
 	<key>com.apple.wlan.authentication</key>
 	<true/>
+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.pairing</string>
+	</array>
 </dict>
 </plist>
 

```

### 🆕 dpdkswitchd

> `/usr/libexec/dpdkswitchd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.networking.ethernet.user-access</key>
	<true/>
	<key>com.apple.private.AppleDPDKPCIUserClient.access</key>
	<true/>
	<key>com.apple.private.AppleDPDKResourcesUserClient.access</key>
	<true/>
	<key>com.apple.private.AppleUIOMemUserClient.access</key>
	<true/>
	<key>com.apple.private.AppleUIOPCIUserClient.access</key>
	<true/>
	<key>com.apple.security.iokit-user-client-class</key>
	<array>
		<string>IOUserEthernetResourceUserClient</string>
	</array>
</dict>
</plist>

```
### findmydeviced

> `/usr/libexec/findmydeviced`

```diff

 	<true/>
 	<key>com.apple.private.octagon</key>
 	<true/>
+	<key>com.apple.private.security.nvram.fmm</key>
+	<true/>
 	<key>com.apple.private.storagekitd.info</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

```
### findmylocateagent

> `/usr/libexec/findmylocateagent`

```diff

 	<true/>
 	<key>com.apple.private.cloudkit.systemService</key>
 	<true/>
+	<key>com.apple.private.communicationsfilter</key>
+	<true/>
 	<key>com.apple.private.ids.messaging</key>
 	<array>
 		<string>com.apple.private.alloy.fmf.local</string>

```
### gamed

> `/usr/libexec/gamed`

```diff

 	<true/>
 	<key>com.apple.datadetectors.source-write.user</key>
 	<true/>
+	<key>com.apple.developer.hardened-process</key>
+	<true/>
 	<key>com.apple.developer.icloud-container-environment</key>
 	<string>Production</string>
 	<key>com.apple.developer.icloud-database-environment</key>

```
### makewhatis

> `/usr/libexec/makewhatis`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
+</dict>
+</plist>
 

```

### 🆕 memoryanalyticsd

> `/usr/libexec/memoryanalyticsd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.accounts.appleaccount.fullaccess</key>
	<true/>
	<key>com.apple.application-identifier</key>
	<string>com.apple.memoryanalyticsd</string>
	<key>com.apple.diagnosticpipeline.request</key>
	<true/>
	<key>com.apple.private.AuthorizationServices</key>
	<array>
		<string>system.preferences.nvram</string>
	</array>
	<key>com.apple.private.osanalytics.defaults.allow </key>
	<true/>
	<key>com.apple.runningboard.process-state</key>
	<true/>
	<key>com.apple.security.system-groups</key>
	<array>
		<string>systemgroup.com.apple.ReportMemoryException</string>
		<string>systemgroup.com.apple.osanalytics</string>
	</array>
	<key>com.apple.system-task-ports.read</key>
	<true/>
	<key>keychain-access-groups</key>
	<array>
		<string>appleaccount</string>
	</array>
</dict>
</plist>

```
### micactivityd

> `/usr/libexec/micactivityd`

```diff

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
-		<string>com.apple.audio.isolated.client.service</string>
+		<string>com.apple.audio.orchestrator.registrar.service</string>
 	</array>
 </dict>
 </plist>

```
### opendirectoryd

> `/usr/libexec/opendirectoryd`

```diff

 	</array>
 	<key>com.apple.private.CoreAuthentication.SPI</key>
 	<true/>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.private.applecredentialmanager.allow</key>
 	<true/>
 	<key>com.apple.private.endpoint-security.submit.authentication.od</key>

```
### secd

> `/usr/libexec/secd`

```diff

 	</array>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.private.appleaccount.app-hidden-from-icloud-settings</key>
 	<true/>
 	<key>com.apple.private.applecredentialmanager.allow</key>

```
### siriknowledged

> `/usr/libexec/siriknowledged`

```diff

 	<string>com.apple.siriknowledged</string>
 	<key>com.apple.assistant.settings</key>
 	<true/>
+	<key>com.apple.authkit.client.internal</key>
+	<true/>
+	<key>com.apple.authkit.client.private</key>
+	<true/>
 	<key>com.apple.developer.aps-environment</key>
 	<string>production</string>
 	<key>com.apple.developer.device-information.user-assigned-device-name</key>

 	<array>
 		<string>CloudKit</string>
 	</array>
+	<key>com.apple.findmy.findmylocate.friendshipservice</key>
+	<true/>
+	<key>com.apple.findmy.findmylocate.locationservice</key>
+	<true/>
+	<key>com.apple.findmy.findmylocate.settings</key>
+	<true/>
 	<key>com.apple.frontboard.launchapplications</key>
 	<true/>
 	<key>com.apple.generativeexperiences.availabilityService</key>
 	<true/>
+	<key>com.apple.icloud.searchpartyd.beaconmanager</key>
+	<true/>
+	<key>com.apple.icloud.searchpartyd.beaconsharing.access</key>
+	<true/>
 	<key>com.apple.icloud.searchpartyd.ownersession</key>
 	<true/>
 	<key>com.apple.locationd.effective_bundle</key>
 	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
 	<key>com.apple.private.aps-connection-initiate</key>
 	<true/>
 	<key>com.apple.private.assets.accessible-asset-types</key>

 			</dict>
 		</dict>
 	</dict>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.siri.findmy</string>
+	</array>
 	<key>com.apple.private.security.storage.CoreKnowledge</key>
 	<true/>
 	<key>com.apple.private.security.storage.FindMy</key>

 	</array>
 	<key>com.apple.rootless.storage.coreknowledge</key>
 	<true/>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.siri.findmy</string>
+	</array>
 	<key>com.apple.security.exception.files.absolute-path.read-only</key>
 	<array>
 		<string>/private/var/MobileAsset/</string>

 		<string>com.apple.calaccessd</string>
 		<string>com.apple.feedbacklogger</string>
 		<string>com.apple.biome.access.user</string>
+		<string>com.apple.findmy.findmylocate.friendshipservice</string>
+		<string>com.apple.findmy.findmylocate.settings</string>
+		<string>com.apple.findmy.findmylocate.locationservice</string>
+		<string>com.apple.icloud.searchpartyd.beaconmanager</string>
+		<string>com.apple.icloud.searchpartyd.beaconsharingservice</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>

 		<string>com.apple.IntelligenceTasks</string>
 		<string>com.apple.SiriEntityMatcher</string>
 	</array>
+	<key>com.apple.security.files.user-selected.read-only</key>
+	<true/>
 	<key>com.apple.security.network.client</key>
 	<true/>
 	<key>com.apple.security.personal-information.addressbook</key>

```
### trustd

> `/usr/libexec/trustd`

```diff

 	<string>com.apple.trustd</string>
 	<key>com.apple.application-identifier</key>
 	<string>com.apple.trustd</string>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.private.assets.accessible-asset-types</key>
 	<array>
 		<string>com.apple.MobileAsset.PKITrustStore</string>

```
### ipconfig

> `/usr/sbin/ipconfig`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.IPConfiguration.get-information</key>
+	<true/>
+</dict>
+</plist>
 

```


### AppOS

### PasswordManagerBrowserExtensionHelper

> `/System/Library/CoreServices/PasswordManagerBrowserExtensionHelper.app/Contents/MacOS/PasswordManagerBrowserExtensionHelper`

```diff

           "team-identifier": "S6N382Y83G"
         }
       },
+      {
+        "$and": {
+          "signing-identifier": "company.thebrowser.dia",
+          "team-identifier": "S6N382Y83G"
+        }
+      },
       {
         "$and": {
           "signing-identifier": "com.brave.Browser",

           "team-identifier": "4XF3XNRN6Y"
         }
       },
+      {
+        "$and": {
+          "signing-identifier": "com.vivaldi.Vivaldi.snapshot",
+          "team-identifier": "4XF3XNRN6Y"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "net.imput.helium",
+          "team-identifier": "S4Q33XPHB4"
+        }
+      },
       {
         "$and": {
           "signing-identifier": "com.operasoftware.Opera",

           "team-identifier": "TFVG979488"
         }
       },
+      {
+        "$and": {
+          "signing-identifier": "com.kagi.kagimacOS.RC",
+          "team-identifier": "TFVG979488"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "io.ungoogled-software.ungoogled-chromium",
+          "team-identifier": "B9A88FL5XJ"
+        }
+      },
       {
         "$and": {
           "signing-identifier": "app.zen-browser.zen",
-          "team-identifier": "H36NPCN86W"
+          "team-identifier": "9V5K9TP787"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "com.bookry.wavebox",
+          "team-identifier": "4259LE8SU5"
         }
       }
     ]

```


