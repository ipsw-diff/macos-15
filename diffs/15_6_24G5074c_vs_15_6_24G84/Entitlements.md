## 🔑 Entitlements

### filesystem

### com.apple.Notes.HTMLConverter

> `/System/Library/PrivateFrameworks/NotesUI.framework/Versions/A/XPCServices/com.apple.Notes.HTMLConverter.xpc/Contents/MacOS/com.apple.Notes.HTMLConverter`

```diff

 <dict>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
-	<key>com.apple.security.network.client</key>
-	<true/>
 </dict>
 </plist>
 

```
### com.apple.Notes.HTMLConverter

> `/System/Library/PrivateFrameworks/NotesUI.framework/Versions/Current/XPCServices/com.apple.Notes.HTMLConverter.xpc/Contents/MacOS/com.apple.Notes.HTMLConverter`

```diff

 <dict>
 	<key>com.apple.security.app-sandbox</key>
 	<true/>
-	<key>com.apple.security.network.client</key>
-	<true/>
 </dict>
 </plist>
 

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

 	<key>com.apple.private.ids.messaging</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
+		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.lp</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>

 	<key>com.apple.private.ids.messaging.high-priority</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
+		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.lp</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>

 	</array>
 	<key>com.apple.private.ids.registration</key>
 	<array>
+		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.facetime.multi</string>
 		<string>com.apple.private.alloy.facetime.sync</string>
 	</array>

 	<key>com.apple.private.ids.self-session</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
+		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.audio</string>

 	<key>com.apple.private.ids.session</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
+		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.audio</string>

 	<key>com.apple.private.ids.session-private</key>
 	<array>
 		<string>com.apple.private.alloy.facetime.multi</string>
+		<string>com.apple.private.alloy.gftaastest.communication</string>
 		<string>com.apple.private.alloy.phonecontinuity</string>
 		<string>com.apple.private.alloy.facetime.video</string>
 		<string>com.apple.private.alloy.facetime.audio</string>

```


