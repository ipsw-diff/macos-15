## 🔑 Entitlements

### filesystem

### NetAuthAgent

> `/System/Library/CoreServices/NetAuthAgent.app/Contents/MacOS/NetAuthAgent`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>keychain-access-groups</key>
 	<array>
 		<string>NetAuth</string>

```
### NetAuthSysAgent

> `/System/Library/CoreServices/NetAuthAgent.app/Contents/MacOS/NetAuthSysAgent`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
 	<key>com.apple.private.netauth.useragent.allow</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

```
### com.apple.CMValidateMovieDataReferenceService

> `/System/Library/Frameworks/CoreMedia.framework/Versions/A/XPCServices/com.apple.CMValidateMovieDataReferenceService.xpc/Contents/MacOS/com.apple.CMValidateMovieDataReferenceService`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
+	<key>com.apple.private.tcc.allow-prompting</key>
+	<array>
+		<string>kTCCServiceSystemPolicyDesktopFolder</string>
+		<string>kTCCServiceSystemPolicyDocumentsFolder</string>
+		<string>kTCCServiceSystemPolicyDownloadsFolder</string>
+		<string>kTCCServicePhotos</string>
+		<string>kTCCServiceSystemPolicyRemovableVolumes</string>
+	</array>
+</dict>
+</plist>
 

```
### com.apple.CMValidateMovieDataReferenceService

> `/System/Library/Frameworks/CoreMedia.framework/Versions/Current/XPCServices/com.apple.CMValidateMovieDataReferenceService.xpc/Contents/MacOS/com.apple.CMValidateMovieDataReferenceService`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.amfi.version-restriction</key>
+	<integer>1</integer>
+	<key>com.apple.private.tcc.allow-prompting</key>
+	<array>
+		<string>kTCCServiceSystemPolicyDesktopFolder</string>
+		<string>kTCCServiceSystemPolicyDocumentsFolder</string>
+		<string>kTCCServiceSystemPolicyDownloadsFolder</string>
+		<string>kTCCServicePhotos</string>
+		<string>kTCCServiceSystemPolicyRemovableVolumes</string>
+	</array>
+</dict>
+</plist>
 

```
### com.apple.MediaLibraryService

> `/System/Library/Frameworks/MediaLibrary.framework/Versions/A/XPCServices/com.apple.MediaLibraryService.xpc/Contents/MacOS/com.apple.MediaLibraryService`

```diff

 <plist version="1.0">
 <dict>
 	<key>com.apple.private.amfi.version-restriction</key>
-	<integer>1</integer>
+	<integer>2</integer>
 	<key>com.apple.private.photolibraryd.read-access</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

```
### com.apple.MediaLibraryService

> `/System/Library/Frameworks/MediaLibrary.framework/Versions/Current/XPCServices/com.apple.MediaLibraryService.xpc/Contents/MacOS/com.apple.MediaLibraryService`

```diff

 <plist version="1.0">
 <dict>
 	<key>com.apple.private.amfi.version-restriction</key>
-	<integer>1</integer>
+	<integer>2</integer>
 	<key>com.apple.private.photolibraryd.read-access</key>
 	<true/>
 	<key>com.apple.private.tcc.allow</key>

```


### AppOS

### PasswordManagerBrowserExtensionHelper

> `/System/Library/CoreServices/PasswordManagerBrowserExtensionHelper.app/Contents/MacOS/PasswordManagerBrowserExtensionHelper`

```diff

           "team-identifier": "KL8N8XSYF4"
         }
       },
+      {
+        "$and": {
+          "signing-identifier": "com.brave.Browser.beta",
+          "team-identifier": "KL8N8XSYF4"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "com.brave.Browser.nightly",
+          "team-identifier": "KL8N8XSYF4"
+        }
+      },
       {
         "$and": {
           "signing-identifier": "com.vivaldi.Vivaldi",

           "signing-identifier": "com.bookry.wavebox",
           "team-identifier": "4259LE8SU5"
         }
+      },
+      {
+        "$and": {
+          "signing-identifier": "com.quark.desktop",
+          "team-identifier": "6TFXDT6MK5"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "com.naver.Whale",
+          "team-identifier": "K9UP278937"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "com.tencent.qqbrowserappmac",
+          "team-identifier": "88L2Q4487U"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "io.island.Island",
+          "team-identifier": "38ZC4T8AWY"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "io.island.Island.beta",
+          "team-identifier": "38ZC4T8AWY"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "io.island.Island.canary",
+          "team-identifier": "38ZC4T8AWY"
+        }
+      },
+      {
+        "$and": {
+          "signing-identifier": "io.island.Island.dev",
+          "team-identifier": "38ZC4T8AWY"
+        }
       }
     ]
   },

```


