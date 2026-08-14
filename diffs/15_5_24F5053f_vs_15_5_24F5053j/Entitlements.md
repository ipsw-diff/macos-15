## 🔑 Entitlements

### filesystem

### Mail

> `/System/Applications/Mail.app/Contents/MacOS/Mail`

```diff

 		<string>com.apple.intelligenceplatform.EntityResolution</string>
 		<string>com.apple.intelligenceplatform.Feedback</string>
 		<string>com.apple.intelligenceplatform.View</string>
+		<string>com.apple.aa.daemon.xpc</string>
 		<string>com.apple.ak.privateemail.xpc</string>
 		<string>com.apple.email.maild</string>
 		<string>com.apple.financed.service.financestore</string>

 	<array>
 		<string>~/Library/Mail</string>
 	</array>
+	<key>com.apple.trial.client</key>
+	<array>
+		<string>337</string>
+	</array>
 	<key>com.apple.usermanagerd.persona.background</key>
 	<true/>
 	<key>com.apple.usermanagerd.persona.create</key>

```
### MailShareExtension

> `/System/Applications/Mail.app/Contents/PlugIns/MailShareExtension.appex/Contents/MacOS/MailShareExtension`

```diff

 	<array>
 		<string>CloudKit</string>
 	</array>
+	<key>com.apple.private.CloudSharing.SPI</key>
+	<true/>
 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
 	<key>com.apple.private.clouddocs.folder-sharing-proxy</key>

```

### 🆕 TVAppServicesAccountNotificationPlugin

> `/System/Library/Accounts/Notification/TVAppServicesAccountNotificationPlugin.bundle/Contents/MacOS/TVAppServicesAccountNotificationPlugin`

- No entitlements *(yet)*
### sessionlogoutd

> `/System/Library/CoreServices/sessionlogoutd`

```diff

 	<true/>
 	<key>com.apple.private.security.nvram.recovery-boot-mode</key>
 	<true/>
+	<key>com.apple.private.security.storage-exempt.heritable</key>
+	<true/>
+	<key>com.apple.private.tcc.manager.access.modify</key>
+	<array>
+		<string>kTCCServiceSystemPolicyAllFiles</string>
+	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceSystemPolicyAllFiles</string>
+	</array>
 	<key>com.apple.usermanagerd.persona.logout</key>
 	<true/>
 </dict>

```
### FedStatsMLHostPluginClassA

> `/System/Library/ExtensionKit/Extensions/FedStatsMLHostPluginClassA.appex/Contents/MacOS/FedStatsMLHostPluginClassA`

```diff

 		<string>RegionalSafetyAnalysis.Disablement</string>
 		<string>RegionalSafetyAnalysis.GuardrailResult</string>
 		<string>GenerativeExperiences.GuardrailResult</string>
+		<string>GenerativeExperiences.GeneratedImageFeatures.FailureReason</string>
 	</array>
 	<key>com.apple.private.cloudkit.masquerade</key>
 	<true/>

```
### KerberosExtension

> `/System/Library/PrivateFrameworks/AppSSOKerberos.framework/PlugIns/KerberosExtension.appex/Contents/MacOS/KerberosExtension`

```diff

 	<array>
 		<string>group.com.apple.KerberosExtension</string>
 	</array>
+	<key>com.apple.security.exception.process-info</key>
+	<true/>
 	<key>com.apple.security.network.client</key>
 	<true/>
 	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>

```
### analyticsagent

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsagent`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
 	<key>com.apple.generativeexperiences.availabilityService</key>
 	<true/>
 	<key>com.apple.private.CoreAnalytics.ManagementCommands.allow</key>
 	<true/>
+	<key>com.apple.private.applemediaservices</key>
+	<true/>
 	<key>com.apple.private.osanalytics.defaults.allow</key>
 	<true/>
 </dict>

```
### com.apple.SpeechRecognitionCore.speechrecognitiond

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/Versions/A/XPCServices/com.apple.SpeechRecognitionCore.brokerd.xpc/Contents/XPCServices/com.apple.SpeechRecognitionCore.speechrecognitiond.xpc/Contents/MacOS/com.apple.SpeechRecognitionCore.speechrecognitiond`

```diff

 	<true/>
 	<key>com.apple.assistant.dictation.prerecorded</key>
 	<true/>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<true/>
 	<key>com.apple.private.assets.accessible-asset-types</key>
 	<array>
 		<string>com.apple.MobileAsset.EmbeddedSpeech</string>

```
### StocksKitService

> `/System/Library/PrivateFrameworks/StocksKit.framework/XPCServices/StocksKitService.xpc/Contents/MacOS/StocksKitService`

```diff

 	<true/>
 	<key>com.apple.private.security.daemon-container</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.stocks</string>
+	</array>
 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.stocks</string>

```
### AXVisualSupportAgent

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/A/Resources/AXVisualSupportAgent.app/Contents/MacOS/AXVisualSupportAgent`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.accessibility.AccessibilityPersonalVoiceUsageOverride</key>
+	<true/>
 	<key>com.apple.corespeech.corespeechd.xpc</key>
 	<true/>
 	<key>com.apple.corespeech.xpc</key>

 	<array>
 		<string>kTCCServiceAccessibility</string>
 		<string>kTCCServiceMicrophone</string>
+		<string>kTCCServiceVoiceBanking</string>
 	</array>
 	<key>com.apple.security.device.audio-input</key>
 	<true/>

```
### AXVisualSupportAgent

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/Current/Resources/AXVisualSupportAgent.app/Contents/MacOS/AXVisualSupportAgent`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.accessibility.AccessibilityPersonalVoiceUsageOverride</key>
+	<true/>
 	<key>com.apple.corespeech.corespeechd.xpc</key>
 	<true/>
 	<key>com.apple.corespeech.xpc</key>

 	<array>
 		<string>kTCCServiceAccessibility</string>
 		<string>kTCCServiceMicrophone</string>
+		<string>kTCCServiceVoiceBanking</string>
 	</array>
 	<key>com.apple.security.device.audio-input</key>
 	<true/>

```

### 🆕 stz

> `/usr/bin/stz`

- No entitlements *(yet)*
### findmydevice-user-agent

> `/usr/libexec/findmydevice-user-agent`

```diff

 <dict>
 	<key>com.apple.accounts.appleaccount.fullaccess</key>
 	<true/>
+	<key>com.apple.icloud.FindMyDevice.FindMyDeviceSharedConfigurationXPCService.access</key>
+	<true/>
 	<key>com.apple.icloud.findmydeviced.access</key>
 	<true/>
 	<key>com.apple.icloud.findmydeviced.ua-services.access</key>

 	<true/>
 	<key>com.apple.private.octagon</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.icloud.findmydevice.shared-configuration</string>
+	</array>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.icloud.findmydevice.shared-configuration</string>
+	</array>
 </dict>
 </plist>
 

```
### findmydeviced

> `/usr/libexec/findmydeviced`

```diff

 	<true/>
 	<key>com.apple.icloud.FindMyDevice.FindMyDeviceIdentityXPCService.access</key>
 	<true/>
+	<key>com.apple.icloud.FindMyDevice.FindMyDeviceSharedConfigurationXPCService.access</key>
+	<true/>
 	<key>com.apple.icloud.searchpartyd.beaconmanager</key>
 	<true/>
 	<key>com.apple.icloud.searchpartyd.ownersession</key>

```


