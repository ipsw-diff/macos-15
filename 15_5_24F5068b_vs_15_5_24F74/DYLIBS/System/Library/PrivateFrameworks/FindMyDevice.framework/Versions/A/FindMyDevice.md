## FindMyDevice

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/Versions/A/FindMyDevice`

```diff

 438.25.2.11.18
-  __TEXT.__text: 0x133a0
-  __TEXT.__auth_stubs: 0x2f0
-  __TEXT.__objc_methlist: 0x1704
-  __TEXT.__cstring: 0x35b5
-  __TEXT.__const: 0xb0
+  __TEXT.__text: 0x15428
+  __TEXT.__auth_stubs: 0x300
+  __TEXT.__objc_methlist: 0x188c
+  __TEXT.__cstring: 0x378f
+  __TEXT.__const: 0xc0
   __TEXT.__gcc_except_tab: 0x2c4
-  __TEXT.__oslogstring: 0x1126
-  __TEXT.__unwind_info: 0x4d8
-  __TEXT.__objc_classname: 0x3f2
-  __TEXT.__objc_methname: 0x326a
-  __TEXT.__objc_methtype: 0xa2e
-  __TEXT.__objc_stubs: 0x2340
-  __DATA_CONST.__got: 0x108
-  __DATA_CONST.__const: 0xc40
-  __DATA_CONST.__objc_classlist: 0xb0
+  __TEXT.__oslogstring: 0x14a6
+  __TEXT.__unwind_info: 0x530
+  __TEXT.__objc_classname: 0x448
+  __TEXT.__objc_methname: 0x36e0
+  __TEXT.__objc_methtype: 0xa7f
+  __TEXT.__objc_stubs: 0x26a0
+  __DATA_CONST.__got: 0x128
+  __DATA_CONST.__const: 0xc80
+  __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_catlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x98
+  __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc48
-  __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0x98
-  __AUTH_CONST.__auth_got: 0x188
-  __AUTH_CONST.__const: 0x960
-  __AUTH_CONST.__cfstring: 0x3920
-  __AUTH_CONST.__objc_const: 0x3fd0
+  __DATA_CONST.__objc_selrefs: 0xd60
+  __DATA_CONST.__objc_protorefs: 0x50
+  __DATA_CONST.__objc_superrefs: 0xa0
+  __AUTH_CONST.__auth_got: 0x190
+  __AUTH_CONST.__const: 0x980
+  __AUTH_CONST.__cfstring: 0x3c20
+  __AUTH_CONST.__objc_const: 0x4240
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH.__objc_data: 0x6e0
-  __DATA.__objc_ivar: 0x158
-  __DATA.__data: 0x858
+  __AUTH.__objc_data: 0x780
+  __DATA.__objc_ivar: 0x168
+  __DATA.__data: 0x8b8
   __DATA.__common: 0x10
-  __DATA.__bss: 0x130
+  __DATA.__bss: 0x140
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/LocalAuthentication.framework/Versions/A/LocalAuthentication

   - /System/Library/PrivateFrameworks/InternationalSupport.framework/Versions/A/InternationalSupport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 589
-  Symbols:   1787
-  CStrings:  1308
+  Functions: 638
+  Symbols:   1881
+  CStrings:  1402
 
Symbols:
+ +[FMDSharedConfiguration localizedStringWithKey:]
+ +[FMDSharedConfiguration sharedInstance]
+ +[FMNSXPCConnectionConfiguration sharedConfigurationConfiguration]
+ -[FMDSharedConfiguration contentsWithLocale:]
+ -[FMDSharedConfiguration defaultEntryForConfiguration:deviceClasses:]
+ -[FMDSharedConfiguration downloadWithLocale:reply:]
+ -[FMDSharedConfiguration downloadWithReply:]
+ -[FMDSharedConfiguration entryForConfiguration:deviceClasses:]
+ -[FMDSharedConfiguration entryForConfiguration:deviceClasses:locale:]
+ -[FMDSharedConfiguration entryWithData:key:deviceClasses:]
+ -[FMDSharedConfiguration expiryDateWithContents:]
+ -[FMDSharedConfiguration fileURLWithLocale:]
+ -[FMDSharedConfiguration getTheftAndLossCoverageWithSerialNumber:reply:]
+ -[FMDSharedConfiguration localeString]
+ -[FMDSharedConfigurationEntry .cxx_destruct]
+ -[FMDSharedConfigurationEntry disclaimer]
+ -[FMDSharedConfigurationEntry init]
+ -[FMDSharedConfigurationEntry isEnabled]
+ -[FMDSharedConfigurationEntry message]
+ -[FMDSharedConfigurationEntry setDisclaimer:]
+ -[FMDSharedConfigurationEntry setEnabled:]
+ -[FMDSharedConfigurationEntry setMessage:]
+ -[FMDSharedConfigurationEntry setTitle:]
+ -[FMDSharedConfigurationEntry title]
+ OBJC_IVAR_$_FMDSharedConfigurationEntry._disclaimer
+ OBJC_IVAR_$_FMDSharedConfigurationEntry._enabled
+ OBJC_IVAR_$_FMDSharedConfigurationEntry._message
+ OBJC_IVAR_$_FMDSharedConfigurationEntry._title
+ _FMDSharedConfigurationKeyTheftAndLoss
+ _OBJC_CLASS_$_FMDSharedConfiguration
+ _OBJC_CLASS_$_FMDSharedConfigurationEntry
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_METACLASS_$_FMDSharedConfiguration
+ _OBJC_METACLASS_$_FMDSharedConfigurationEntry
+ __51-[FMDSharedConfiguration downloadWithLocale:reply:]_block_invoke
+ __OBJC_$_CLASS_METHODS_FMDSharedConfiguration
+ __OBJC_$_CLASS_PROP_LIST_FMDSharedConfiguration
+ __OBJC_$_INSTANCE_METHODS_FMDSharedConfiguration
+ __OBJC_$_INSTANCE_METHODS_FMDSharedConfigurationEntry
+ __OBJC_$_INSTANCE_VARIABLES_FMDSharedConfigurationEntry
+ __OBJC_$_PROP_LIST_FMDSharedConfiguration
+ __OBJC_$_PROP_LIST_FMDSharedConfigurationEntry
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_FMDSharedConfigurationXPCInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_FMDSharedConfigurationXPCInterface
+ __OBJC_$_PROTOCOL_REFS_FMDSharedConfigurationXPCInterface
+ __OBJC_CLASS_RO_$_FMDSharedConfiguration
+ __OBJC_CLASS_RO_$_FMDSharedConfigurationEntry
+ __OBJC_LABEL_PROTOCOL_$_FMDSharedConfigurationXPCInterface
+ __OBJC_METACLASS_RO_$_FMDSharedConfiguration
+ __OBJC_METACLASS_RO_$_FMDSharedConfigurationEntry
+ __OBJC_PROTOCOL_$_FMDSharedConfigurationXPCInterface
+ __OBJC_PROTOCOL_REFERENCE_$_FMDSharedConfigurationXPCInterface
+ ___40+[FMDSharedConfiguration sharedInstance]_block_invoke
+ ___44-[FMDSharedConfiguration downloadWithReply:]_block_invoke
+ ___51-[FMDSharedConfiguration downloadWithLocale:reply:]_block_invoke
+ ___72-[FMDSharedConfiguration getTheftAndLossCoverageWithSerialNumber:reply:]_block_invoke
+ ___72-[FMDSharedConfiguration getTheftAndLossCoverageWithSerialNumber:reply:]_block_invoke_2
+ _kFMDBrassStatusKey
+ _kFMDSharedConfigurationAccessEntitlement
+ _kFMDSharedConfigurationConfigVersionKey
+ _kFMDSharedConfigurationDataKey
+ _kFMDSharedConfigurationExpiryKey
+ _kFMDSharedConfigurationLastRequestedKey
+ _kFMDSharedConfigurationXPCServiceAccessEntitlement
+ _objc_msgSend$JSONObjectWithData:options:error:
+ _objc_msgSend$URLByAppendingPathComponent:isDirectory:
+ _objc_msgSend$componentsJoinedByString:
+ _objc_msgSend$containerURLForSecurityApplicationGroupIdentifier:
+ _objc_msgSend$contentsWithLocale:
+ _objc_msgSend$count
+ _objc_msgSend$createDirectoryAtURL:withIntermediateDirectories:attributes:error:
+ _objc_msgSend$dateByAddingTimeInterval:
+ _objc_msgSend$defaultEntryForConfiguration:deviceClasses:
+ _objc_msgSend$dictionaryWithContentsOfURL:error:
+ _objc_msgSend$doubleValue
+ _objc_msgSend$downloadSharedConfigurationWithLocale:reply:
+ _objc_msgSend$downloadWithLocale:reply:
+ _objc_msgSend$entryForConfiguration:deviceClasses:locale:
+ _objc_msgSend$entryWithData:key:deviceClasses:
+ _objc_msgSend$fileURLWithLocale:
+ _objc_msgSend$getTheftAndLossCoverageWithSerialNumber:reply:
+ _objc_msgSend$localeString
+ _objc_msgSend$localizedStringWithKey:
+ _objc_msgSend$minimizedLanguagesFromLanguages:
+ _objc_msgSend$objectAtIndexedSubscript:
+ _objc_msgSend$path
+ _objc_msgSend$preferredLanguages
+ _objc_msgSend$setDisclaimer:
+ _objc_msgSend$setEnabled:
+ _objc_msgSend$setMessage:
+ _objc_msgSend$stringByReplacingOccurrencesOfString:withString:
+ _objc_opt_respondsToSelector
+ sharedInstance.dispatch_predicate
CStrings:
+ "%@.plist"
+ ","
+ "Application Support"
+ "Calling process has no preferredLanguages."
+ "Calling process is missing InternationalSupport."
+ "Calling process is missing container entitlements"
+ "DA"
+ "Entry at index %lu doesn't have a category"
+ "Entry at index %lu is not a dictionary"
+ "Entry found at %lu, but disclaimer label exists and is not a string: %@"
+ "Entry found at %lu, but doesn't contain an enabled flag"
+ "Entry found at %lu, but enabled flag isn't a number: %@"
+ "Entry found at %lu, but it doesn't contain a message"
+ "Entry found at %lu, but it doesn't contain a title"
+ "Entry found at %lu, but message is not a string: %@"
+ "Entry found at %lu, but title is not a string: %@"
+ "FMDSharedConfiguration"
+ "FMDSharedConfigurationEntry"
+ "FMDSharedConfigurationXPCInterface"
+ "Failed to create container directories"
+ "Failed to read contents for %@, error: %@"
+ "JSONObjectWithData:options:error:"
+ "LR"
+ "Library"
+ "Localizable-WARRANTY_DIAGNOSTICS"
+ "No contents for %@"
+ "No data for %@, returning default"
+ "No defaults for configuration %@ (%@)"
+ "No entries"
+ "No entry for %@"
+ "No match found among %lu entries"
+ "Not valid JSON: %@"
+ "T@\"FMDSharedConfiguration\",R,N"
+ "T@\"NSString\",C,N,V_disclaimer"
+ "T@\"NSString\",C,N,V_message"
+ "T@\"NSString\",C,N,V_title"
+ "TB,N,GisEnabled,V_enabled"
+ "TNL_DISCLAIMER_LABEL_DEFAULT"
+ "TNL_DISCLAIMER_MESSAGE_DEFAULT"
+ "TNL_DISCLAIMER_TITLE_DEFAULT"
+ "TTL"
+ "URLByAppendingPathComponent:isDirectory:"
+ "Unsupported top-level type: %@"
+ "V"
+ "_disclaimer"
+ "_enabled"
+ "_message"
+ "awarenessEnabled"
+ "awarenessStrings"
+ "brassStatus"
+ "category"
+ "com.apple.icloud.FindMyDevice.FindMyDeviceSharedConfiguration.access"
+ "com.apple.icloud.FindMyDevice.FindMyDeviceSharedConfigurationXPCService.access"
+ "componentsJoinedByString:"
+ "containerURLForSecurityApplicationGroupIdentifier:"
+ "contentsWithLocale:"
+ "count"
+ "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
+ "dateByAddingTimeInterval:"
+ "defaultEntryForConfiguration:deviceClasses:"
+ "dictionaryWithContentsOfURL:error:"
+ "disclaimer"
+ "disclaimerLabel"
+ "doubleValue"
+ "downloadSharedConfigurationWithLocale:reply:"
+ "downloadWithLocale:reply:"
+ "downloadWithReply:"
+ "en-US"
+ "enabled"
+ "entryForConfiguration:deviceClasses:"
+ "entryForConfiguration:deviceClasses:locale:"
+ "entryWithData:key:deviceClasses:"
+ "expiryDateWithContents:"
+ "fileURLWithLocale:"
+ "getTheftAndLossCoverageWithSerialNumber:reply:"
+ "getTheftAndLossCoverageWithUDID:reply:"
+ "group.com.apple.icloud.findmydevice.shared-configuration"
+ "iPhone"
+ "isEnabled"
+ "localeString"
+ "localizedStringWithKey:"
+ "minimizedLanguagesFromLanguages:"
+ "objectAtIndexedSubscript:"
+ "path"
+ "preferredLanguages"
+ "setDisclaimer:"
+ "setEnabled:"
+ "setMessage:"
+ "sharedConfigurationConfiguration"
+ "stringByReplacingOccurrencesOfString:withString:"
+ "theftLoss"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSError\">24"
+ "v32@0:8@\"NSString\"16@?<v@?Q@\"NSError\">24"
+ "~"
```
