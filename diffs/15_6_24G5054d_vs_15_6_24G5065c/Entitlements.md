## 🔑 Entitlements

### filesystem

### Photos

> `/System/Applications/Photos.app/Contents/MacOS/Photos`

```diff

 	<true/>
 	<key>com.apple.modelmanager.inference</key>
 	<true/>
+	<key>com.apple.payment.all-access</key>
+	<true/>
+	<key>com.apple.payment.amp-card-enrollment</key>
+	<true/>
+	<key>com.apple.payment.card-on-file</key>
+	<true/>
 	<key>com.apple.photos.bourgeoisie</key>
 	<true/>
 	<key>com.apple.private.CacheDelete</key>

 	<true/>
 	<key>com.apple.private.imagecapturecore.authorization_bypass</key>
 	<true/>
+	<key>com.apple.private.in-app-payments</key>
+	<true/>
 	<key>com.apple.private.ind.client</key>
 	<true/>
 	<key>com.apple.private.intelligenceplatform.views.read-only</key>

 		<string>com.apple.generativeexperiences.availabilityService</string>
 		<string>com.apple.extensionkitservice</string>
 		<string>com.apple.feedbackd.centralized-feedback</string>
+		<string>com.apple.passd.in-app-payment</string>
+		<string>com.apple.passd.library</string>
+		<string>com.apple.passd.payment</string>
 	</array>
 	<key>com.apple.security.temporary-exception.sbpl</key>
 	<array>

```
### ControlCenter

> `/System/Library/CoreServices/ControlCenter.app/Contents/MacOS/ControlCenter`

```diff

 	<array>
 		<string>Accounts</string>
 	</array>
+	<key>com.apple.private.controlcenter.helper</key>
+	<true/>
 	<key>com.apple.private.corewifi</key>
 	<true/>
 	<key>com.apple.private.disable.screencapturekit.alert</key>

```
### MCXCompositor

> `/System/Library/CoreServices/ManagedClient.app/Contents/Resources/MCXCompositor`

```diff

 </dict>
 </plist>
 
+<!-- Launch Constraints (Parent) -->
+{
+  "appl": 1,
+  "ccat": 0,
+  "comp": 1,
+  "reqs": {
+    "signing-identifier": "com.apple.ManagedClient",
+    "validation-category": 1
+  },
+  "vers": 1
+}
+

```
### PrivateEvolutionPlugin

> `/System/Library/ExtensionKit/Extensions/PrivateEvolutionPlugin.appex/Contents/MacOS/PrivateEvolutionPlugin`

```diff

 	</array>
 	<key>com.apple.security.exception.files.absolute-path.read-only</key>
 	<array>
+		<string>/private/var/db/eligibilityd/eligibility.plist</string>
 		<string>/private/var/MobileAsset/AssetsV2/locks/com.apple.UnifiedAssetFramework/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_GenerativeModels/purpose_auto/</string>
 		<string>/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_UAF_FM_Overrides/purpose_auto/</string>

 	</array>
 	<key>com.apple.security.exception.mach-lookup.global-name</key>
 	<array>
+		<string>com.apple.generativeexperiences.availabilityService</string>
 		<string>com.apple.email.maild</string>
 		<string>com.apple.mlhostd.xpc</string>
 		<string>com.apple.cloudd</string>

```
### AppleCredentialManagerDaemon

> `/System/Library/PrivateFrameworks/AppleCredentialManager.framework/AppleCredentialManagerDaemon`

```diff

 	<true/>
 	<key>com.apple.private.applecredentialmanager.devicerestrictedmode.allow</key>
 	<true/>
+	<key>com.apple.private.applecredentialmanager.transportrestrictedmode.configurewhilelocked.allow</key>
+	<true/>
 	<key>com.apple.security.iokit-user-client-class</key>
 	<array>
 		<string>AppleCredentialManagerUserClient</string>

```
### CSExattrCryptoService

> `/System/Library/PrivateFrameworks/CSExattrCrypto.framework/Versions/A/XPCServices/CSExattrCryptoService.xpc/Contents/MacOS/CSExattrCryptoService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
-	<key>com.apple.private.version-restriction</key>
+	<key>com.apple.private.amfi.version-restriction</key>
 	<integer>1</integer>
 	<key>com.apple.security.files.user-selected.read-only</key>
 	<true/>

```
### CSExattrCryptoService

> `/System/Library/PrivateFrameworks/CSExattrCrypto.framework/Versions/Current/XPCServices/CSExattrCryptoService.xpc/Contents/MacOS/CSExattrCryptoService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
-	<key>com.apple.private.version-restriction</key>
+	<key>com.apple.private.amfi.version-restriction</key>
 	<integer>1</integer>
 	<key>com.apple.security.files.user-selected.read-only</key>
 	<true/>

```


### AppOS

### PasswordManagerBrowserExtensionHelper

> `/System/Library/CoreServices/PasswordManagerBrowserExtensionHelper.app/Contents/MacOS/PasswordManagerBrowserExtensionHelper`

```diff

 	<key>com.apple.private.accounts.allaccounts</key>
 	<true/>
 	<key>com.apple.private.amfi.version-restriction</key>
-	<integer>1</integer>
+	<integer>2</integer>
 	<key>com.apple.private.applemediaservices</key>
 	<true/>
 	<key>com.apple.private.coreservices.canmaplsdatabase</key>

```


