## ARDAgent

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/MacOS/ARDAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__data`

```diff

-709.5.2.0.0
-  __TEXT.__text: 0x9df98
-  __TEXT.__auth_stubs: 0x27e0
-  __TEXT.__objc_stubs: 0x25e0
-  __TEXT.__objc_methlist: 0xd50
+709.6.2.0.0
+  __TEXT.__text: 0xa2a04
+  __TEXT.__auth_stubs: 0x2820
+  __TEXT.__objc_stubs: 0x2ac0
+  __TEXT.__objc_methlist: 0xee8
   __TEXT.__const: 0x1028
-  __TEXT.__oslogstring: 0x5f0e
-  __TEXT.__cstring: 0x21fd6
-  __TEXT.__objc_methname: 0x2494
-  __TEXT.__objc_classname: 0x141
-  __TEXT.__objc_methtype: 0x8cc
-  __TEXT.__unwind_info: 0xef8
-  __DATA_CONST.__auth_got: 0x13f8
-  __DATA_CONST.__got: 0x4c8
+  __TEXT.__oslogstring: 0x650c
+  __TEXT.__cstring: 0x22a16
+  __TEXT.__objc_methname: 0x2896
+  __TEXT.__objc_classname: 0x182
+  __TEXT.__objc_methtype: 0x972
+  __TEXT.__unwind_info: 0xf50
+  __DATA_CONST.__auth_got: 0x1418
+  __DATA_CONST.__got: 0x4f0
   __DATA_CONST.__auth_ptr: 0x38
   __DATA_CONST.__const: 0x948
-  __DATA_CONST.__cfstring: 0x3420
-  __DATA_CONST.__objc_classlist: 0x60
+  __DATA_CONST.__cfstring: 0x3a60
+  __DATA_CONST.__objc_classlist: 0x70
+  __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x60
-  __DATA_CONST.__objc_arraydata: 0x28
-  __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA.__objc_const: 0x1250
-  __DATA.__objc_selrefs: 0xc00
-  __DATA.__objc_ivar: 0xac
-  __DATA.__objc_data: 0x3c0
+  __DATA_CONST.__objc_superrefs: 0x68
+  __DATA_CONST.__objc_arraydata: 0x38
+  __DATA_CONST.__objc_arrayobj: 0x48
+  __DATA.__objc_const: 0x1430
+  __DATA.__objc_selrefs: 0xd40
+  __DATA.__objc_ivar: 0xb0
+  __DATA.__objc_data: 0x460
   __DATA.__data: 0x3d0
   __DATA.__bss: 0x15cc
   __DATA.__common: 0xd7e9

   - /usr/lib/libpcre2-8.0.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1434
-  Symbols:   803
-  CStrings:  4358
+  Functions: 1484
+  Symbols:   812
+  CStrings:  4514
 
Symbols:
+ _OBJC_CLASS_$_NSUUID
+ _kODAttributeTypeAllTypes
+ _kODAttributeTypeHomeDirectory
+ _kODAttributeTypePrimaryGroupID
+ _kODAttributeTypeUserShell
+ _objc_autoreleaseReturnValue
+ _objc_retainAutorelease
+ _objc_retainAutoreleasedReturnValue
+ _objc_storeStrong
CStrings:
+ "%s requires an option"
+ "-%d"
+ "-ChangeSettings"
+ "-ControlObserve"
+ "-DeleteFiles"
+ "-GenerateReports"
+ "-ObserveOnly"
+ "-OpenQuitApps"
+ "-RestartShutDown"
+ "-SendFiles"
+ "-ShowObserve"
+ "-TextMessages"
+ "-[ChangeClientSettings loadCommandsFromInstallerPackageAtPath:]"
+ "-[ChangeClientSettings makeUsers:]"
+ "-[ChangeClientSettings naPrivsWithArgs:index:]"
+ "-[ChangeClientSettings parseComputerInfoWithArgs:startingAtIndex:topic:subCommand:fieldName:]"
+ "-[ChangeClientSettings parseKickstartArgs:]"
+ "-[ChangeClientSettings parseMakeUserArgs:]"
+ "-[ChangeClientSettings runKickstartCommands:]"
+ "-[ChangeClientSettings setPrivileges:forUser:]"
+ "-[ODHelper localUserRecordByShortName:]"
+ "-[ODHelper localUserUIDs]"
+ "-[ODHelper newLocalUserWithName:attributes:password:]"
+ "-[ODHelper setARDPrivileges:forUserRecord:]"
+ "-access"
+ "-all"
+ "-allUsers"
+ "-allowAccessFor"
+ "-computerinfo"
+ "-computerinfo requires options"
+ "-configure"
+ "-dirlogins"
+ "-mask"
+ "-menuextra"
+ "-none"
+ "-on"
+ "-p"
+ "-privs"
+ "-reqperm"
+ "-set%d"
+ "-setdirlogins"
+ "-setmenuextra"
+ "-setreqperm"
+ "-setvnclegacy"
+ "-specifiedUsers"
+ "-users"
+ "-vnclegacy"
+ ".cxx_destruct"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/RemoteDesktop/agent/ChangeClientSettings.m"
+ "/Users/%@"
+ "20"
+ "@\"NSMutableDictionary\""
+ "@24@0:8Q16"
+ "ChangeClientSettings"
+ "Contents/Resources/postflight_kickstart_entries"
+ "Contents/Resources/postflight_makeuser_entries"
+ "I32@0:8@16Q24"
+ "MockChangeClientSettings"
+ "Q56@0:8@16Q24@32@40@48"
+ "Read 'Error' %s"
+ "Subarray"
+ "T@\"NSMutableDictionary\",&,V_allSettings"
+ "Text%d"
+ "URLByAppendingPathComponent:"
+ "UUID"
+ "UUIDString"
+ "_allSettings"
+ "allSettings"
+ "bad option for %s"
+ "begin make users"
+ "begin update kickstart settings"
+ "changePassword error %s"
+ "componentsJoinedByString:"
+ "could not find user: %s"
+ "could not open search node: %s"
+ "create user %@ with attributes %@"
+ "createNewLocalUserWithODHelper:name:attributes:password:"
+ "createRecordWithRecordType error %s"
+ "createRecordWithRecordType:name:attributes:error:"
+ "created user %s"
+ "end make users"
+ "end update kickstart settings"
+ "filePathURL"
+ "found postflight_kickstart_entries, sending to ChangeClientSettings"
+ "group record exists"
+ "hasSuffix:"
+ "indexOfObject:"
+ "integerValue"
+ "invalid option: %s"
+ "kickstart file error %s"
+ "kickstart: %s"
+ "loadCommandsFromInstallerPackageAtPath:"
+ "localUserRecordByShortName:"
+ "localUserUIDs"
+ "lowerEUID"
+ "makeUser: %s"
+ "makeUsers:"
+ "makeuser file error %s"
+ "naPrivsWithArgs:index:"
+ "naprivs"
+ "newLocalUserWithName:attributes:password:"
+ "no kickstart commands"
+ "no makeuser commands"
+ "no parameters to kickstart tool"
+ "no parameters to makeUser tool"
+ "no password"
+ "no record name"
+ "no short name"
+ "numberWithInteger:"
+ "numberWithUnsignedInteger:"
+ "objectAtIndexedSubscript:"
+ "parameterValueWithArgs:topic:subcommand:"
+ "parseComputerInfoWithArgs:startingAtIndex:topic:subCommand:fieldName:"
+ "parseKickstartArgs:"
+ "parseMakeUserArgs:"
+ "raiseEUID"
+ "recordWithRecordType error %s"
+ "runKickstartCommands:"
+ "set ARD_AllLocalUsers to no"
+ "set ARD_AllLocalUsers to yes"
+ "set DirectoryGroupLoginsEnabled to no"
+ "set DirectoryGroupLoginsEnabled to yes"
+ "set LoadRemoteManagementMenuExtra to no"
+ "set LoadRemoteManagementMenuExtra to yes"
+ "set ScreenSharingReqPermEnabled to no"
+ "set ScreenSharingReqPermEnabled to yes"
+ "set VNCLegacyConnectionsEnabled to no"
+ "set VNCLegacyConnectionsEnabled to yes"
+ "set preference %@ to %@ in suite %@"
+ "set privileges %x for user %@"
+ "setARDPrivileges:forUserRecord:"
+ "setAllSettings:"
+ "setPreference:forKey:suiteID:"
+ "setPrivileges:forUser:"
+ "setValue:forAttribute: error %s"
+ "setValue:forAttribute:error:"
+ "setValue:forKey:"
+ "stringByJoiningArrayFromIndex:"
+ "stripSingleQuotesFromString"
+ "subArrayFromIndex:"
+ "subarrayWithRange:"
+ "substringFromQuotedValue"
+ "suiteID"
+ "synchronizeAndReturnError %s"
+ "synchronizeAndReturnError:"
+ "too many args to kickstart: %lu"
+ "too many args to makeuser: %lu"
+ "unable to create new user"
+ "unable to set new user password"
+ "unquote"
+ "user directory path already exists"
+ "user record exists"
+ "v28@0:8I16@20"
+ "v40@0:8@16@24@32"
+ "v40@0:8^v16^{__CFString=}24^{__CFString=}32"
+ "v48@0:8@16@24@32@40"
+ "value"
- "Read 'Error'"
```
