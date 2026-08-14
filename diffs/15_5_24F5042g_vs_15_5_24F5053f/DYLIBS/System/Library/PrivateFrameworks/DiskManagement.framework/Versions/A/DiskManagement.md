## DiskManagement

> `/System/Library/PrivateFrameworks/DiskManagement.framework/Versions/A/DiskManagement`

```diff

-934.120.1.0.0
-  __TEXT.__text: 0x96fa8
-  __TEXT.__auth_stubs: 0x1980
+934.120.4.0.0
+  __TEXT.__text: 0x9725c
+  __TEXT.__auth_stubs: 0x1990
   __TEXT.__objc_methlist: 0x24cc
-  __TEXT.__cstring: 0x34f37
+  __TEXT.__cstring: 0x35037
   __TEXT.__const: 0x1254
-  __TEXT.__gcc_except_tab: 0xf6c
+  __TEXT.__gcc_except_tab: 0xf64
   __TEXT.__oslogstring: 0x33
   __TEXT.__unwind_info: 0x1708
   __TEXT.__eh_frame: 0x40
   __TEXT.__objc_classname: 0x1fb
-  __TEXT.__objc_methname: 0x84bf
+  __TEXT.__objc_methname: 0x84b1
   __TEXT.__objc_methtype: 0x241f
   __TEXT.__objc_stubs: 0x3b60
   __DATA_CONST.__got: 0x408

   __DATA_CONST.__objc_selrefs: 0x1da8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x78
-  __DATA_CONST.__objc_arraydata: 0xe28
-  __AUTH_CONST.__auth_got: 0xcd0
+  __DATA_CONST.__objc_arraydata: 0xea8
+  __AUTH_CONST.__auth_got: 0xcd8
   __AUTH_CONST.__const: 0x4c0
-  __AUTH_CONST.__cfstring: 0x20a00
+  __AUTH_CONST.__cfstring: 0x20ba0
   __AUTH_CONST.__objc_const: 0x1fe0
-  __AUTH_CONST.__objc_arrayobj: 0x1ef0
+  __AUTH_CONST.__objc_arrayobj: 0x1f68
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x6e0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1808
-  Symbols:   3643
-  CStrings:  6928
+  Functions: 1809
+  Symbols:   3645
+  CStrings:  6942
 
Symbols:
+ __DMrealPathForDictionary
+ _fstatfs_ext
+ _objc_msgSend$copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:atomic:
+ _statfs_ext
- _fstatfs
- _objc_msgSend$copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:allowSymlinks:atomic:
Functions:
~ -[DMManager(Info) copyDiskForPath:error:] : 740 -> 744
~ __DMrealPath : 292 -> 300
+ __DMrealPathForDictionary
~ __DMAPFSSubjectDirectoryPathsForTargetMigrator : 1360 -> 1356
~ -[DMManager(Info) copyDiskForVolumeName:error:] : 560 -> 564
~ -[DMManager(Boot) _ensureRecoveryPartitionForVolume:macOSXDiskImageFile:macOSXDiskImageChunkListFile:diagnosticsDiskImageFile:diagnosticsDiskImageChunkListFile:verifyImage:repairDonor:diagnosticsMachineBlacklist:] : 616 -> 744
~ -[DMManager(Boot) replaceDiagnosticsForVolume:diagnosticsDiskImageFile:diagnosticsChunkListFile:verifyImage:allowGrowth:diagnosticsMachineBlacklistInhibit:] : 596 -> 664
~ -[DMAPFS convertFromHFS:dryRun:options:] : 1008 -> 1052
~ -[DMAPFS ensureRecoveryBooter:options:] : 620 -> 676
~ -[DMAPFS addVolumeToContainer:newFilesystem:newName:options:] : 1200 -> 1032
~ -[DMAPFS updatePrebootForVolumeFire:completion:options:] : 576 -> 608
~ -[DMAPFS updatePrebootForVolume:options:] : 568 -> 592
~ __FSGetTypeInfoForPath : 216 -> 220
~ __FSGetTypeInfoForFileDescriptor : 216 -> 220
~ __FSGetLocationForPath : 208 -> 212
~ __FSGetLocationForFileDescriptor : 208 -> 212
~ __FSCopyNameForVolumeFormatAtURL_internal : 364 -> 368
CStrings:
+ "18:38:17"
+ "AppleDiagnosticsChunkList"
+ "AppleDiagnosticsDiskImage"
+ "Apr  6 2025"
+ "BaseSystemChunkList"
+ "BaseSystemDiskImage"
+ "Cannot convert path to UTF8"
+ "Cannot resolve path %@"
+ "Cannot resolve path for key %@"
+ "EtcSourcePath"
+ "InstallBootSourcePath"
+ "LibrarySourcePath"
+ "ODPath"
+ "PrebootPath"
+ "PrebootSourcePath"
+ "UsrSourcePath"
+ "VarSourcePath"
+ "_DMrealPathForDictionary"
+ "copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:atomic:"
- "18:55:34"
- "Cannot convert mount point to UTF8"
- "Cannot resolve mount point"
- "Mar 21 2025"
- "copyFileFromPathDataOnly:toDirAtPath:newName:interimDirs:recursive:preDelete:reportDisk:percentBegin:percentEnd:allowSymlinks:atomic:"
```
