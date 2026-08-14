## mds

> `/System/Library/Frameworks/CoreServices.framework/Versions/Current/Frameworks/Metadata.framework/Versions/A/Support/mds`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__dof_mds`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2333.41.1.3.0
-  __TEXT.__text: 0x15fe60
-  __TEXT.__auth_stubs: 0x3c00
-  __TEXT.__objc_stubs: 0xc8c0
+2333.47.1.0.0
+  __TEXT.__text: 0x160a6c
+  __TEXT.__auth_stubs: 0x3c40
+  __TEXT.__objc_stubs: 0xc900
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x7df4
+  __TEXT.__objc_methlist: 0x7e1c
   __TEXT.__const: 0x5ed0
-  __TEXT.__cstring: 0x18252
+  __TEXT.__cstring: 0x1827e
   __TEXT.__objc_classname: 0xcd1
-  __TEXT.__oslogstring: 0x11062
-  __TEXT.__gcc_except_tab: 0x1b94
-  __TEXT.__objc_methname: 0x10a45
-  __TEXT.__objc_methtype: 0x5a0c
+  __TEXT.__oslogstring: 0x11122
+  __TEXT.__gcc_except_tab: 0x1ba4
+  __TEXT.__objc_methname: 0x10a65
+  __TEXT.__objc_methtype: 0x5a18
   __TEXT.__dof_mds: 0x5735
-  __TEXT.__unwind_info: 0x5548
-  __DATA_CONST.__auth_got: 0x1e10
+  __TEXT.__unwind_info: 0x5578
+  __DATA_CONST.__auth_got: 0x1e30
   __DATA_CONST.__got: 0xa20
   __DATA_CONST.__auth_ptr: 0x170
-  __DATA_CONST.__const: 0x17e30
-  __DATA_CONST.__cfstring: 0xdce0
+  __DATA_CONST.__const: 0x17ec0
+  __DATA_CONST.__cfstring: 0xde00
   __DATA_CONST.__objc_classlist: 0x458
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0xd8

   __DATA_CONST.__objc_arraydata: 0xa00
   __DATA_CONST.__objc_arrayobj: 0x168
   __DATA_CONST.__objc_dictobj: 0x500
-  __DATA.__objc_const: 0x18f40
-  __DATA.__objc_selrefs: 0x3820
-  __DATA.__objc_ivar: 0x1854
+  __DATA.__objc_const: 0x18f88
+  __DATA.__objc_selrefs: 0x3830
+  __DATA.__objc_ivar: 0x1858
   __DATA.__objc_data: 0x2b70
   __DATA.__data: 0x3b48
   __DATA.__crash_info: 0x40

   - /usr/lib/libfakelink.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9246
-  Symbols:   1297
-  CStrings:  8836
+  Functions: 9264
+  Symbols:   1301
+  CStrings:  8855
 
Symbols:
+ _audit_token_to_pid
+ _proc_pidfdinfo
+ _proc_pidinfo
+ _puts
CStrings:
+ "???"
+ "DIR"
+ "IndexPid"
+ "Peer checkin mach_port_insert_right failed (cleanup)"
+ "Peer checkin mach_port_insert_right failed (defer) : %s"
+ "REG"
+ "Unmount leak: dev:%d TXT type:%s %s"
+ "Unmount leak: dev:%d fd:%d type:%s flags:%x %s"
+ "_indexPid"
+ "dev:%d TXT type:%s %s"
+ "dev:%d fd:%d type:%s flags:%x %s"
+ "fileLeaks"
+ "fileleaks"
+ "getStatus"
+ "hasFileLeaks"
+ "indexPid"
+ "indexesWithFileLeaksAtUnmountCount"
+ "mountCount"
+ "unmountAttemptCount"
+ "unmountSucceedCount"
+ "v28@?0i8i12i16r*20"
+ "{?=\"_uuid\"^{__CFUUID}\"_hasPersistentUUID\"B\"_suitableForPermissionPreHeat\"B\"_recoverTimeStamp\"d\"_largestOid\"q\"_maxTransactionId\"Q\"_storeProperties\"@\"NSMutableDictionary\"\"_indexVersion\"I\"_indexPid\"i}"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Spotlight/spotlight/server/MDSPeer/MDSPeerManager.m"
- "getPid"
- "{?=\"_uuid\"^{__CFUUID}\"_hasPersistentUUID\"B\"_suitableForPermissionPreHeat\"B\"_recoverTimeStamp\"d\"_largestOid\"q\"_maxTransactionId\"Q\"_storeProperties\"@\"NSMutableDictionary\"\"_indexVersion\"I}"
```
