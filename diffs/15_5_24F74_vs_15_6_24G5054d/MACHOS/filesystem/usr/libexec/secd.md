## secd

> `/usr/libexec/secd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_data`
- `__DATA.__data`
- `__DATA.__thread_vars`

```diff

-61439.120.27.0.0
-  __TEXT.__text: 0x2618d4
-  __TEXT.__auth_stubs: 0x3760
-  __TEXT.__objc_stubs: 0x1aca0
-  __TEXT.__objc_methlist: 0x1467c
-  __TEXT.__const: 0x3ec
-  __TEXT.__cstring: 0x1f0ab
-  __TEXT.__oslogstring: 0x28ef8
+61439.140.8.0.0
+  __TEXT.__text: 0x2622b8
+  __TEXT.__auth_stubs: 0x3790
+  __TEXT.__objc_stubs: 0x1ad00
+  __TEXT.__objc_methlist: 0x146c4
+  __TEXT.__const: 0x3e4
+  __TEXT.__cstring: 0x1f0e7
+  __TEXT.__oslogstring: 0x29163
   __TEXT.__dlopen_cstrs: 0x172
-  __TEXT.__gcc_except_tab: 0xad38
+  __TEXT.__gcc_except_tab: 0xad3c
   __TEXT.__objc_classname: 0x2271
-  __TEXT.__objc_methname: 0x29f74
-  __TEXT.__objc_methtype: 0x9d38
-  __TEXT.__unwind_info: 0x60d8
-  __DATA_CONST.__auth_got: 0x1bc0
+  __TEXT.__objc_methname: 0x2a027
+  __TEXT.__objc_methtype: 0x9d4d
+  __TEXT.__unwind_info: 0x60f0
+  __DATA_CONST.__auth_got: 0x1bd8
   __DATA_CONST.__got: 0xfb8
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA_CONST.__const: 0x14530
+  __DATA_CONST.__const: 0x145a0
   __DATA_CONST.__cfstring: 0x1a060
   __DATA_CONST.__objc_classlist: 0x870
   __DATA_CONST.__objc_catlist: 0x68

   __DATA_CONST.__objc_arraydata: 0x3f8
   __DATA_CONST.__objc_dictobj: 0x78
   __DATA_CONST.__objc_arrayobj: 0x360
-  __DATA.__objc_const: 0x218f8
-  __DATA.__objc_selrefs: 0x8b80
+  __DATA.__objc_const: 0x21900
+  __DATA.__objc_selrefs: 0x8b98
   __DATA.__objc_ivar: 0x1954
   __DATA.__objc_data: 0x5460
   __DATA.__data: 0x1d00
   __DATA.__thread_vars: 0xc0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0xd70
+  __DATA.__bss: 0xd88
   - /AppleInternal/Library/Frameworks/TapToRadarKit.framework/Versions/A/TapToRadarKit
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9232
-  Symbols:   1414
-  CStrings:  14867
+  Functions: 9241
+  Symbols:   1417
+  CStrings:  14886
 
Symbols:
+ _os_signpost_id_generate
+ _pthread_mutex_trylock
+ _qos_class_self
CStrings:
+ "Going for groups verifying, with resync if required"
+ "Going for groups verifying, without resync"
+ "Passed NULL StatCtx"
+ "Resync: Using already provided list of remote groups"
+ "Unable to allocate StatCtx: %{darwin.errno}d"
+ "Verify Groups, Resync is not requested, so returning"
+ "Verify Groups, Resync is requested, and we are NOT on par with CK; therefore going for resyncing"
+ "Verify Groups, Resync is requested, but we are on par with CK, therefore returning"
+ "com.apple.security.keychain_db.signposts"
+ "priority=%{public,signpost.telemetry:number1,name=priority}d  enableTelemetry=YES "
+ "read_connection_nowait"
+ "read_connection_wait"
+ "resyncFromRPC:privateRemoteZonesByZoneID:sharedRemoteZonesByZoneID:completion:"
+ "signpost"
+ "v44@0:8B16@20@28@?36"
+ "verifyGroupsInSyncAndResync:WithCompletion:"
+ "verifyGroupsInSyncAndResyncMissingGroupsWithCompletion:"
+ "write_connection_nowait"
+ "write_connection_wait"
```
