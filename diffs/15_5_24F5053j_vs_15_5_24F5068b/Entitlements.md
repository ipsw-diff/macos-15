## 🔑 Entitlements

### filesystem

### FindMy

> `/System/Applications/FindMy.app/Contents/MacOS/FindMy`

```diff

 	<true/>
 	<key>com.apple.icloud.FindMyDevice.FindMyDeviceHelperXPCService.access</key>
 	<true/>
+	<key>com.apple.icloud.FindMyDevice.FindMyDeviceSharedConfiguration.access</key>
+	<true/>
 	<key>com.apple.icloud.findmydeviced.access</key>
 	<true/>
 	<key>com.apple.icloud.searchparty.ownersession.fmipitemaccess</key>

 	</array>
 	<key>com.apple.private.octagon</key>
 	<true/>
+	<key>com.apple.private.security.restricted-application-groups</key>
+	<array>
+		<string>group.com.apple.icloud.findmydevice.shared-configuration</string>
+	</array>
 	<key>com.apple.private.security.storage.FindMy</key>
 	<true/>
 	<key>com.apple.private.security.system-application</key>

 	<key>com.apple.security.application-groups</key>
 	<array>
 		<string>group.com.apple.icloud.fm</string>
+		<string>group.com.apple.icloud.findmydevice.shared-configuration</string>
 	</array>
 	<key>com.apple.security.device.bluetooth</key>
 	<true/>

 		<string>com.apple.server.bluetooth</string>
 		<string>com.apple.SharingServices</string>
 		<string>com.apple.server.bluetooth.general.xpc</string>
+		<string>com.apple.icloud.findmydeviced.findmydevice-user-agent</string>
 	</array>
 	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
 	<array>

```
### IndexSettings

> `/System/Library/CoreServices/UAUPlugins/SettingsUAUPlugin.bundle/Contents/Resources/IndexSettings`

```diff

 		<string>com.apple.linkd.mediator</string>
 		<string>com.apple.linkd.transcript</string>
 	</array>
-	<key>com.apple.security.temporary-exception.shared-preference.read-write</key>
-	<array>
-		<string>com.apple.systemsettings.extensions</string>
-	</array>
 </dict>
 </plist>
 

```
### UserAccountUpdater

> `/System/Library/CoreServices/UserAccountUpdater`

```diff

 	<true/>
 	<key>com.apple.private.systemmigration.daemonclient</key>
 	<true/>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.private.migrationhelper.allow</string>
+	</array>
 </dict>
 </plist>
 

```
### AMPDeviceDiscoveryAgent

> `/System/Library/PrivateFrameworks/AMPDevices.framework/Versions/A/Support/AMPDeviceDiscoveryAgent`

```diff

 		<string>com.apple.amp.devicesd</string>
 		<string>com.apple.remotepairing.version</string>
 		<string>com.apple.remotepairing.service</string>
+		<string>com.apple.deviceinterfaced.tadfu-transport-server</string>
 	</array>
 	<key>com.apple.security.temporary-exception.sbpl</key>
 	<string>(allow network-outbound (literal "/private/var/run/usbmuxd"))</string>

```
### AMPDeviceDiscoveryAgent

> `/System/Library/PrivateFrameworks/AMPDevices.framework/Versions/Current/Support/AMPDeviceDiscoveryAgent`

```diff

 		<string>com.apple.amp.devicesd</string>
 		<string>com.apple.remotepairing.version</string>
 		<string>com.apple.remotepairing.service</string>
+		<string>com.apple.deviceinterfaced.tadfu-transport-server</string>
 	</array>
 	<key>com.apple.security.temporary-exception.sbpl</key>
 	<string>(allow network-outbound (literal "/private/var/run/usbmuxd"))</string>

```
### contactsdonationagent

> `/System/Library/PrivateFrameworks/ContactsDonation.framework/Versions/A/Support/contactsdonationagent`

```diff

 	</array>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.contactsd.support</string>
+	</array>
 	<key>com.apple.security.personal-information.addressbook</key>
 	<true/>
 	<key>com.apple.security.temporary-exception.sbpl</key>

```


### AppOS

### PasswordManagerBrowserExtensionHelper

> `/System/Library/CoreServices/PasswordManagerBrowserExtensionHelper.app/Contents/MacOS/PasswordManagerBrowserExtensionHelper`

```diff

           "team-identifier": "EQHXZ8M8AV"
         }
       },
+      {
+        "$and": {
+          "signing-identifier": "com.google.Chrome.dev",
+          "team-identifier": "EQHXZ8M8AV"
+        }
+      },
       {
         "$and": {
           "signing-identifier": "com.google.Chrome.canary",

           "signing-identifier": "com.operasoftware.OperaGX",
           "team-identifier": "A2P9LX4JPN"
         }
+      },
+      {
+        "$and": {
+          "signing-identifier": "com.kagi.kagimacOS",
+          "team-identifier": "TFVG979488"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "app.zen-browser.zen",
+          "team-identifier": "H36NPCN86W"
+        }
       }
     ]
   },

```


