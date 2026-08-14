## 🔑 Entitlements

### filesystem

### Notes

> `/System/Applications/Notes.app/Contents/MacOS/Notes`

```diff

 	</array>
 	<key>com.apple.proactive.PersonalizationPortrait.Contact</key>
 	<true/>
+	<key>com.apple.sage.summarization</key>
+	<true/>
+	<key>com.apple.sage.textcomposition</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.application-groups</key>

 		<string>com.apple.calculator</string>
 		<string>com.apple.applicationaccess</string>
 	</array>
-	<key>com.apple.security.exception.shared-preference.read-write</key>
-	<array>
-		<string>com.apple.siri.generativeassistantsettings</string>
-	</array>
 	<key>com.apple.security.files.user-selected.read-write</key>
 	<true/>
 	<key>com.apple.security.network.client</key>

 		<string>com.apple.generativeexperiences.summarization</string>
 		<string>com.apple.generativeexperiences.textcomposition</string>
 		<string>com.apple.generativeexperiences.availabilityService</string>
+		<string>com.apple.sage.textcomposition</string>
 		<string>com.apple.icbaccountsd</string>
 		<string>com.apple.ind.xpc</string>
 		<string>com.apple.mobile.keybagd.UserManager.xpc</string>

 		<string>com.apple.synapse.add-link-context-service</string>
 		<string>com.apple.security.octagon</string>
 		<string>com.apple.securityd.ckks</string>
+		<string>com.apple.sage.summarization</string>
 		<string>com.apple.synapse.DocumentWorkflowsService</string>
 		<string>com.apple.spotlight.CSExattrCryptoService</string>
 		<string>com.apple.commcenter.coretelephony.xpc</string>

 		<string>com.apple.SocialLayer</string>
 		<string>com.apple.gms.availability</string>
 	</array>
+	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.siri.generativeassistantsettings</string>
+	</array>
 	<key>com.apple.spotlight.documentunderstanding.entitledattributes</key>
 	<true/>
 	<key>com.apple.spotlight.photos.entitledattributes</key>

```
### Reminders

> `/System/Applications/Reminders.app/Contents/MacOS/Reminders`

```diff

 	<string></string>
 	<key>com.apple.developer.associated-domains</key>
 	<array/>
+	<key>com.apple.developer.hardened-process</key>
+	<true/>
 	<key>com.apple.developer.icloud-container-environment</key>
 	<string>Production</string>
 	<key>com.apple.developer.icloud-container-identifiers</key>

```
### RemindersQuickLookExtension

> `/System/Applications/Reminders.app/Contents/PlugIns/RemindersQuickLookExtension.appex/Contents/MacOS/RemindersQuickLookExtension`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.developer.hardened-process</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.files.user-selected.read-only</key>

```
### AssetMetricsExtension

> `/System/Library/ExtensionKit/Extensions/AssetMetricsExtension.appex/Contents/MacOS/AssetMetricsExtension`

```diff

 	<key>com.apple.private.biome.read-write</key>
 	<array>
 		<string>Lighthouse.Ledger.LighthousePluginEvent</string>
+		<string>IntelligenceFlow.Telemetry</string>
+		<string>GenerativeModels.GenerativeFunctions.Instrumentation</string>
+		<string>Sage.Transcript</string>
+		<string>IntelligenceFlow.Transcript.Datastream</string>
 	</array>
 	<key>com.apple.private.biome.writer</key>
 	<array>

 	<true/>
 	<key>com.apple.private.intelligenceplatform.use-cases</key>
 	<dict>
-		<key>MLHostTelemetry</key>
+		<key>AssetMetricsWorker</key>
 		<dict>
 			<key>Streams</key>
 			<array>
 				<string>Lighthouse.Ledger.TaskCustomEvent</string>
+				<string>IntelligenceFlow.Telemetry</string>
+				<string>GenerativeModels.GenerativeFunctions.Instrumentation</string>
+				<string>IntelligenceFlow.Transcript.Datastream</string>
+				<string>Lighthouse.Ledger.LighthousePluginEvent</string>
+				<string>Sage.Transcript</string>
+				<string>Siri.SELFProcessedEvent</string>
+				<string>IntelligenceFlow.Transcript.Datastream</string>
 			</array>
 		</dict>
 	</dict>

 	<array>
 		<string>com.apple.AssetMetricsWorker</string>
 	</array>
+	<key>com.apple.siri.analytics.assistant</key>
+	<array>
+		<string>stream.unifiedMessageStream.readonly</string>
+		<string>stream.rawUnifiedMessageStream.readonly</string>
+	</array>
 </dict>
 </plist>
 

```
### FedStatsMLHostPlugin

> `/System/Library/ExtensionKit/Extensions/FedStatsMLHostPlugin.appex/Contents/MacOS/FedStatsMLHostPlugin`

```diff

 		<string>Safari.Browsing.Assistant</string>
 		<string>GenerativeExperiences.GeneratedImageFeatures.UserInteraction</string>
 		<string>GenerativeExperiences.PromptTags</string>
+		<string>GenerativeExperiences.WritingToolsFeatures.ComposeAndAdjust</string>
 		<string>AdAttributionKit.AggregatedReporting.Purchase</string>
 		<string>AdAttributionKit.AggregatedReporting.Conversion</string>
 		<string>Siri.ASR.RequestMetricsRecord</string>

```
### FindMyIntentsExtension

> `/System/Library/ExtensionKit/Extensions/FindMyIntentsExtension.appex/Contents/MacOS/FindMyIntentsExtension`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.findmy.findmylocate.fenceservice</key>
+	<true/>
 	<key>com.apple.findmy.findmylocate.friendshipservice</key>
 	<true/>
 	<key>com.apple.findmy.findmylocate.locationservice</key>

 		<string>com.apple.findmy.findmylocate.friendshipservice</string>
 		<string>com.apple.findmy.findmylocate.settings</string>
 		<string>com.apple.findmy.findmylocate.locationservice</string>
+		<string>com.apple.findmy.findmylocate.fenceservice</string>
+		<string>com.apple.icloud.searchpartyd.intentsession</string>
 		<string>com.apple.icloud.searchparty.locationfetch.items</string>
 		<string>com.apple.icloud.searchpartyd.ownersession</string>
 		<string>com.apple.icloud.searchpartyd.beaconmanager</string>

 		<string>com.apple.findmy.findmylocate.friendshipservice</string>
 		<string>com.apple.findmy.findmylocate.settings</string>
 		<string>com.apple.findmy.findmylocate.locationservice</string>
+		<string>com.apple.findmy.findmylocate.fenceservice</string>
+		<string>com.apple.icloud.searchpartyd.intentsession</string>
 		<string>com.apple.icloud.searchparty.locationfetch.items</string>
 		<string>com.apple.icloud.searchpartyd.ownersession</string>
 		<string>com.apple.icloud.searchpartyd.beaconmanager</string>

```
### ODDIMetricsExtension

> `/System/Library/ExtensionKit/Extensions/ODDIMetricsExtension.appex/Contents/MacOS/ODDIMetricsExtension`

```diff

 <plist version="1.0">
 <dict>
 	<key>application-identifier</key>
-	<string>com.apple.siri.ODDI.MetricsExtension</string>
+	<string>com.apple.siri.ODDIMetricsExtension</string>
 	<key>com.apple.assistant.settings</key>
 	<true/>
 	<key>com.apple.private.assistant.settings</key>
 	<true/>
 	<key>com.apple.private.biome.client-identifier</key>
-	<string>com.apple.siri.ODDI.MetricsExtension</string>
+	<string>com.apple.siri.ODDIMetricsExtension</string>
 	<key>com.apple.private.biome.read-only</key>
 	<array>
 		<string>Siri.SELFProcessedEvent</string>

```
### ScreenTimePreferencesExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimePreferencesExtension.appex/Contents/MacOS/ScreenTimePreferencesExtension`

```diff

 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.DeviceActivity</string>
+		<string>group.com.apple.ScreenTime</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-write</key>
 	<array>

```
### SecurityPrivacyExtension

> `/System/Library/ExtensionKit/Extensions/SecurityPrivacyExtension.appex/Contents/MacOS/SecurityPrivacyExtension`

```diff

 		<dict>
 			<key>Streams</key>
 			<dict>
+				<key>AppleIntelligenceReport.FedStatsTransparencyLog</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
 				<key>GenerativeExperiences.TransparencyLog</key>
 				<dict>
 					<key>mode</key>

```
### SettingsSystemExtensionController

> `/System/Library/ExtensionKit/Extensions/SettingsSystemExtensionController.appex/Contents/MacOS/SettingsSystemExtensionController`

```diff

 	<true/>
 	<key>com.apple.private.system-settings.extensions-controller</key>
 	<true/>
+	<key>com.apple.private.tcc.external.report</key>
+	<true/>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
 	<key>com.apple.security.files.user-selected.read-only</key>

```
### spotlightknowledged

> `/System/Library/Frameworks/CoreSpotlight.framework/spotlightknowledged`

```diff

 	<true/>
 	<key>com.apple.spotlight.search</key>
 	<true/>
+	<key>com.apple.tailspin.dump-output</key>
+	<true/>
 </dict>
 </plist>
 

```
### MTLCompilerService

> `/System/Library/Frameworks/Metal.framework/Versions/A/XPCServices/MTLCompilerService.xpc/Contents/MacOS/MTLCompilerService`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.developer.hardened-process</key>
+	<true/>
+</dict>
+</plist>
 

```
### MTLCompilerService

> `/System/Library/Frameworks/Metal.framework/Versions/Current/XPCServices/MTLCompilerService.xpc/Contents/MacOS/MTLCompilerService`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.developer.hardened-process</key>
+	<true/>
+</dict>
+</plist>
 

```
### amsaccountsd

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/Resources/amsaccountsd`

```diff

 	</array>
 	<key>com.apple.developer.networking.wifi-info</key>
 	<true/>
+	<key>com.apple.frontboard.launchapplications</key>
+	<true/>
 	<key>com.apple.keystore.absinthe</key>
 	<true/>
 	<key>com.apple.keystore.sik.access</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.frontboard.systemappservices</string>
 		<string>com.apple.amsondevicestoraged.xpc</string>
 		<string>com.apple.companiond.xpc</string>
 		<string>com.apple.locationd.registration</string>

```
### amsaccountsd

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/Current/Resources/amsaccountsd`

```diff

 	</array>
 	<key>com.apple.developer.networking.wifi-info</key>
 	<true/>
+	<key>com.apple.frontboard.launchapplications</key>
+	<true/>
 	<key>com.apple.keystore.absinthe</key>
 	<true/>
 	<key>com.apple.keystore.sik.access</key>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.frontboard.systemappservices</string>
 		<string>com.apple.amsondevicestoraged.xpc</string>
 		<string>com.apple.companiond.xpc</string>
 		<string>com.apple.locationd.registration</string>

```
### homed

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed`

```diff

 	<true/>
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
### identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/Contents/MacOS/identityservicesd`

```diff

 	</array>
 	<key>com.apple.security.lockdownmode.read</key>
 	<true/>
+	<key>com.apple.security.personal-information.addressbook</key>
+	<true/>
 	<key>com.apple.symptom_diagnostics.report</key>
 	<true/>
 	<key>com.apple.transparency.kt</key>

```
### modelcatalogd

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/Versions/A/modelcatalogd`

```diff

 				</dict>
 			</dict>
 		</dict>
+		<key>RegionalSafetyAnalysisMetrics</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>GenerativeExperiences.GuardrailResult</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
 	</dict>
 	<key>com.apple.private.security.storage.AppleIntelligencePlatform</key>
 	<true/>

```

### 🆕 PhotosStoryDiagnostics

> `/System/Library/PrivateFrameworks/PhotosIntelligence.framework/PlugIns/PhotosStoryDiagnostics.appex/Contents/MacOS/PhotosStoryDiagnostics`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.PhotosIntelligence.PhotosStoryDiagnostics</string>
	<key>com.apple.DiagnosticExtensions.extension</key>
	<true/>
	<key>com.apple.private.photos.internaldirectory.data.read-write</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServicePhotos</string>
	</array>
	<key>com.apple.security.app-sandbox</key>
	<true/>
</dict>
</plist>

```
### ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/Versions/A/ScreenTimeAgent`

```diff

 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.DeviceActivity</string>
+		<string>group.com.apple.ScreenTime</string>
 	</array>
 	<key>com.apple.security.attestation.access</key>
 	<true/>

```
### STSDiagnostic

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/PlugIns/STSDiagnostic.appex/Contents/MacOS/STSDiagnostic`

```diff

 	<key>com.apple.security.temporary-exception.files.home-relative-path.read-write</key>
 	<array>
 		<string>/Library/Logs/SiriTTSService/</string>
+		<string>/Library/Caches/SiriTTS/BNNSModels/</string>
 	</array>
 </dict>
 </plist>

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

 	<true/>
 	<key>com.apple.imagent.av</key>
 	<true/>
+	<key>com.apple.imsharedutilities.forceContactsOOP</key>
+	<true/>
 	<key>com.apple.messages.nicknames</key>
 	<true/>
 	<key>com.apple.multitasking.termination</key>

```
### csfdiagnose

> `/usr/bin/csfdiagnose`

```diff

 <dict>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.application-identifier</key>
+	<string>com.apple.csfctl</string>
 	<key>com.apple.generativeexperiences.availabilityService</key>
 	<true/>
+	<key>com.apple.generativeexperiences.availabilityService.secureWriteCloudSubscriptionFeaturesAvailability</key>
+	<true/>
 	<key>com.apple.generativeexperiences.availabilityService.waitlistStatus</key>
 	<true/>
 	<key>com.apple.modelcatalog.full-access</key>

```
### adprivacyd

> `/usr/libexec/adprivacyd`

```diff

 	<true/>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.ak.auth.xpc</string>
 		<string>com.apple.ap.promotedcontent.supportinterface</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>

 		<string>com.apple.AdPlatforms</string>
 		<string>com.apple.AppStore</string>
 	</array>
+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.ak.auth.xpc</string>
+	</array>
 	<key>com.apple.trial.client</key>
 	<array>
 		<string>511</string>

```
### audiomxd

> `/usr/libexec/audiomxd`

```diff

 	<true/>
 	<key>com.apple.private.xpc.launchd.per-user-lookup</key>
 	<true/>
-	<key>com.apple.security.exception.mach-lookup.global-name</key>
-	<array>
-		<string>com.apple.audio.isolated.historicalaudiod</string>
-	</array>
 </dict>
 </plist>
 

```
### corebrightnessd

> `/usr/libexec/corebrightnessd`

```diff

 	<array>
 		<string>AppleKeyStoreUserClient</string>
 	</array>
+	<key>com.apple.systemstatus.domains</key>
+	<array>
+		<string>media</string>
+	</array>
 </dict>
 </plist>
 

```
### dprivacyd

> `/usr/libexec/dprivacyd`

```diff

 	</array>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
+	<key>com.apple.private.biome.client-identifier</key>
+	<string>com.apple.dprivacyd</string>
 	<key>com.apple.private.biome.read-write</key>
 	<array>
 		<string>Lighthouse.Ledger.DediscoPrivacyEvent</string>

 	</dict>
 	<key>com.apple.private.dprivacyd.allow</key>
 	<true/>
+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>dprivacyd</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>AppleIntelligenceReport.FedStatsTransparencyLog</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+	</dict>
 	<key>com.apple.private.kernel.override-cpumon</key>
 	<true/>
 	<key>com.apple.private.screentime-communication</key>

 	<true/>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.biome.access.user</string>
 		<string>com.apple.cloudd</string>
 		<string>com.apple.ScreenTimeAgent.communication</string>
 		<string>com.apple.familycircle.agent</string>
 	</array>
 	<key>com.apple.security.exception.shared-preference.read-only</key>
 	<array>
+		<string>com.apple.AppleIntelligenceReport</string>
 		<string>com.apple.DPSubmissionService</string>
 	</array>
 	<key>com.apple.security.system-groups</key>

```
### fskit_agent

> `/usr/libexec/fskit_agent`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>application-identifier</key>
+	<string>com.apple.fskit.fskit_agent</string>
+	<key>com.apple.application-identifier</key>
+	<string>com.apple.fskit.fskit_agent</string>
+	<key>com.apple.private.LiveFS.connection</key>
+	<true/>
+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>
+	<key>com.apple.private.extensionkit.extension-management</key>
+	<true/>
+	<key>com.apple.private.fskit.module-runner</key>
+	<true/>
+	<key>com.apple.private.security.restricted-application-group</key>
+	<array>
+		<string>group.com.apple.fskit.settings</string>
+	</array>
+	<key>com.apple.runningboard.terminateprocess</key>
+	<true/>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.fskit.settings</string>
+	</array>
+</dict>
+</plist>
 

```
### historicalaudiod

> `/usr/libexec/historicalaudiod`

```diff

 	<true/>
 	<key>com.apple.coreaudio.register-internal-aus</key>
 	<true/>
+	<key>com.apple.private.audio.dark-wake-audio</key>
+	<true/>
 	<key>com.apple.private.audio.hal.aop-audio.user-access</key>
 	<true/>
 	<key>com.apple.private.audio.hal.speaker-tap.user-access</key>
 	<true/>
+	<key>com.apple.private.audio.notification-wake-audio</key>
+	<true/>
 	<key>com.apple.private.audio.orchestration.registration</key>
 	<true/>
 	<key>com.apple.private.audio.suppress-mic-indicator</key>

 	<array>
 		<string>kTCCServiceMicrophone</string>
 	</array>
+	<key>com.apple.security.exception.files.absolute-path.read-write</key>
+	<array>
+		<string>/dev/exfiltration-adc-historicala</string>
+	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>kern.task_conclave</string>

```
### micactivityd

> `/usr/libexec/micactivityd`

```diff

 	<true/>
 	<key>com.apple.private.audio.suppress-mic-indicator</key>
 	<true/>
+	<key>com.apple.security.exception.files.absolute-path.read-write</key>
+	<array>
+		<string>/dev/exfiltration-adc-micactivity</string>
+	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
 		<string>com.apple.audio.isolated.client.service</string>

```
### promotedcontentd

> `/usr/libexec/promotedcontentd`

```diff

 		<string>com.apple.adid</string>
 		<string>com.apple.symptom_diagnostics</string>
 		<string>com.apple.appstored.xpc</string>
+		<string>com.apple.ak.auth.xpc</string>
 	</array>
 	<key>com.apple.security.exception.process-info</key>
 	<true/>

 	</array>
 	<key>com.apple.security.network.client</key>
 	<true/>
+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.ak.auth.xpc</string>
+	</array>
 	<key>com.apple.security.ts.tmpdir</key>
 	<string>com.apple.ap.promotedcontentd</string>
 	<key>com.apple.trial.client</key>

```


