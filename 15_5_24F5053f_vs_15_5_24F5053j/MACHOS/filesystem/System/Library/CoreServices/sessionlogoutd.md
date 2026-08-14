## sessionlogoutd

> `/System/Library/CoreServices/sessionlogoutd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-113.0.0.2.0
-  __TEXT.__text: 0x5f5c
-  __TEXT.__auth_stubs: 0x7f0
-  __TEXT.__objc_stubs: 0xc60
-  __TEXT.__objc_methlist: 0x4e4
-  __TEXT.__cstring: 0x1b7a
+113.6.1.0.0
+  __TEXT.__text: 0x73e4
+  __TEXT.__auth_stubs: 0x860
+  __TEXT.__objc_stubs: 0xf00
+  __TEXT.__objc_methlist: 0x544
+  __TEXT.__cstring: 0x1f12
   __TEXT.__gcc_except_tab: 0x84
   __TEXT.__objc_classname: 0xb0
-  __TEXT.__objc_methtype: 0x23b
-  __TEXT.__const: 0x38
-  __TEXT.__objc_methname: 0xe80
-  __TEXT.__unwind_info: 0x190
-  __DATA_CONST.__auth_got: 0x408
-  __DATA_CONST.__got: 0x150
-  __DATA_CONST.__const: 0x118
-  __DATA_CONST.__cfstring: 0x1200
+  __TEXT.__objc_methtype: 0x263
+  __TEXT.__const: 0x48
+  __TEXT.__objc_methname: 0x1097
+  __TEXT.__unwind_info: 0x1d8
+  __DATA_CONST.__auth_got: 0x440
+  __DATA_CONST.__got: 0x170
+  __DATA_CONST.__const: 0x1a8
+  __DATA_CONST.__cfstring: 0x1440
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA.__objc_const: 0x978
-  __DATA.__objc_selrefs: 0x410
+  __DATA.__objc_selrefs: 0x4b8
   __DATA.__objc_ivar: 0x70
   __DATA.__objc_data: 0x190
   __DATA.__data: 0x160

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 102
-  Symbols:   178
-  CStrings:  430
+  Functions: 125
+  Symbols:   189
+  CStrings:  486
 
Symbols:
+ _NSFileOwnerAccountName
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSFileManager
+ ___assert_rtn
+ __dispatch_queue_attr_concurrent
+ _dispatch_barrier_async
+ _dispatch_queue_create
+ _dispatch_sync
+ _kill
+ _objc_enumerationMutation
+ _strncmp
CStrings:
+ "    all files and directories were removed from %@"
+ "    all files were removed from %@"
+ "    attempt %ld to remove directory %@"
+ "    directory removal attempt completed %@"
+ "    directory removal attempt failed %@"
+ "    directory removal timed out after %ld attempts for %@"
+ "    directory was removed %@"
+ "    path is a file %@"
+ "(err == 0) == (*procList != NULL)"
+ "*procList == NULL"
+ "-[SessionLogoutd _filesExistInDirectory:]"
+ "-[SessionLogoutd _killAllProcessesForUser:]"
+ "-[SessionLogoutd _removeDirectory:endDate:directoriesAllowed:]"
+ "-[SessionLogoutd _userFilesCleanupWithCompletionHandler:]"
+ "-[SessionLogoutd continueLogoutAfterUnmountHomeDirectory]"
+ "-[SessionLogoutd networkHomeUnmountComplete]"
+ "-[SessionLogoutd unmountHomeDirectory:]"
+ "-[SessionLogoutd unmountHomeDirectory:]_block_invoke"
+ "/Library/Application Support/Apple/ParentalControls/Users/"
+ "/Library/Caches"
+ "/Library/Caches/Desktop Pictures/"
+ "/Library/Logs/Console/"
+ "/Users"
+ "/var/at/tabs"
+ "/var/db/launchd.db/com.apple.launchd.peruser.%u"
+ "GetBSDProcessList"
+ "NO"
+ "NULL"
+ "Resetting BackToMyMac"
+ "Starting directory removal %@"
+ "Starting unmount of home directory"
+ "Stopping processes for %u"
+ "Utilities.m"
+ "_filesExistInDirectory:"
+ "_killAllProcessesForUser:"
+ "_removeDirectory:endDate:directoriesAllowed:"
+ "_removeHomeDirectory:endDate:"
+ "_removeVarFolders:endDate:"
+ "_userFilesCleanupWithCompletionHandler:"
+ "_userVarPath"
+ "addObject:"
+ "array"
+ "attributesOfItemAtPath:error:"
+ "chflags parent: %s  error: %s"
+ "chflags path: %s  error: %s"
+ "com.apple.sessionlogoutd.guestAccountCleanup"
+ "complete = %@"
+ "contentsOfDirectoryAtPath:error:"
+ "continueLogoutAfterUnmountHomeDirectory"
+ "countByEnumeratingWithState:objects:count:"
+ "date"
+ "dateWithTimeIntervalSinceNow:"
+ "defaultManager"
+ "directory path is nil"
+ "fileExistsAtPath:"
+ "fileExistsAtPath:isDirectory:"
+ "laterDate:"
+ "network home unmount complete"
+ "network home unmount did not finish"
+ "networkHomeUnmountComplete"
+ "procCount != NULL"
+ "procList != NULL"
+ "removefile error: %s"
+ "result == NULL"
+ "stringByAppendingPathComponent:"
+ "stringWithFormat:"
+ "unmountHomeDirectory:"
+ "user files cleanup complete"
+ "v20@0:8I16"
+ "v24@0:8@?16"
+ "v36@0:8@16@24B32"
- "-[SessionLogoutd guestAccountCleanup]"
- "First round /var/folders delete had issues, attempting again"
- "First round home delete had issues, attempting again"
- "RemoveDirectoryAndChangeFlagsIfNeededAtPath"
- "Resetting BackToMyMac and removing Guest account home"
- "Unable to remove old guest account /var/folders directory path = %@"
- "Unable to remove old guest account home directory path = %@"
- "chflags parent: %s  error: %d"
- "chflags path: %s  error: %d"
- "error_callback"
- "guest var folders removed at:%@"
- "guestAccountCleanup"
- "nil"
- "removefile error:%s"
- "unmountHomeDirectory"
```
