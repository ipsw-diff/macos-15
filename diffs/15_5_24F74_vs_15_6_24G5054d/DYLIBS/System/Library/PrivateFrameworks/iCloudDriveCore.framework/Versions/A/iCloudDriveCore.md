## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/iCloudDriveCore`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-3437.120.20.0.0
-  __TEXT.__text: 0x346ccc
+3437.140.4.0.0
+  __TEXT.__text: 0x347328
   __TEXT.__auth_stubs: 0x1a20
-  __TEXT.__objc_methlist: 0x191dc
+  __TEXT.__objc_methlist: 0x19204
   __TEXT.__const: 0x4d0
-  __TEXT.__cstring: 0x7ab3f
-  __TEXT.__oslogstring: 0x3bf49
-  __TEXT.__gcc_except_tab: 0x1a0fc
+  __TEXT.__cstring: 0x7ac07
+  __TEXT.__oslogstring: 0x3bf5f
+  __TEXT.__gcc_except_tab: 0x1a110
   __TEXT.__ustring: 0x88
-  __TEXT.__unwind_info: 0x9b98
+  __TEXT.__unwind_info: 0x9bb8
   __TEXT.__objc_classname: 0x2679
-  __TEXT.__objc_methname: 0x4171e
+  __TEXT.__objc_methname: 0x4179d
   __TEXT.__objc_methtype: 0x8964
-  __TEXT.__objc_stubs: 0x2cfa0
+  __TEXT.__objc_stubs: 0x2d000
   __DATA_CONST.__got: 0x1758
   __DATA_CONST.__const: 0x1ca8
   __DATA_CONST.__objc_classlist: 0x998
   __DATA_CONST.__objc_catlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xddf0
+  __DATA_CONST.__objc_selrefs: 0xde08
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x878
   __DATA_CONST.__objc_arraydata: 0xf60
   __AUTH_CONST.__auth_got: 0xd20
   __AUTH_CONST.__const: 0xaa18
-  __AUTH_CONST.__cfstring: 0x22560
-  __AUTH_CONST.__objc_const: 0x3b120
+  __AUTH_CONST.__cfstring: 0x225c0
+  __AUTH_CONST.__objc_const: 0x3b170
   __AUTH_CONST.__objc_intobj: 0xb40
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x50
   __AUTH.__objc_data: 0x5ff0
-  __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x1ee0
+  __AUTH.__data: 0x30
+  __DATA.__objc_ivar: 0x1ee4
   __DATA.__data: 0x25f0
-  __DATA.__bss: 0x620
+  __DATA.__bss: 0x630
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 13384
-  Symbols:   23342
-  CStrings:  22304
+  Functions: 13392
+  Symbols:   23350
+  CStrings:  22312
 
Symbols:
+ -[BRCStageRegistry markUploadActiveForStageID:]
+ -[BRCStageRegistry(FPFSAdditions) cloneFileURL:toUploadStageID:liveStageFilename:error:]
+ -[BRCUserDefaults supportedKeynoteBundleIdentifiers]
+ -[BRCUserDefaults supportedNumbersBundleIdentifiers]
+ -[BRCUserDefaults supportedPagesBundleIdentifiers]
+ GCC_except_table189
+ GCC_except_table212
+ GCC_except_table219
+ GCC_except_table578
+ OBJC_IVAR_$_BRCSharingAcceptFlowOperation._appBundleID
+ ___45-[NSURL(BRCShareURL) brc_applicationBundleID]_block_invoke
+ ___88-[BRCStageRegistry(FPFSAdditions) cloneFileURL:toUploadStageID:liveStageFilename:error:]_block_invoke
+ ___block_descriptor_40_e8_32s_e34_B32?0"NSString"8"NSString"16Q24l
+ ___block_descriptor_41_e8_32s_e34_B32?0"NSString"8"NSString"16Q24l
+ ___block_descriptor_64_e8_32s40s48s56s_e8_i12?0i8l
+ ___block_descriptor_80_e8_32s40s48bs56r64r72r_e47_v24?0"NSFileProviderItemVersion"8"NSError"16l
+ _objc_msgSend$cloneFileURL:toUploadStageID:liveStageFilename:error:
+ _objc_msgSend$markUploadActiveForStageID:
+ _objc_msgSend$supportedKeynoteBundleIdentifiers
+ _objc_msgSend$supportedNumbersBundleIdentifiers
+ _objc_msgSend$supportedPagesBundleIdentifiers
- -[BRCStageRegistry _garbageCollectUploads]
- -[BRCStageRegistry(FPFSAdditions) cloneURLToLiveStage:liveStageFilename:error:]
- GCC_except_table210
- GCC_except_table575
- __65-[BRCStageRegistry _garbageCollectUploadsIncludingActiveUploads:]_block_invoke
- ___79-[BRCStageRegistry(FPFSAdditions) cloneURLToLiveStage:liveStageFilename:error:]_block_invoke
- ___block_descriptor_40_e8_32s_e27_B24?0"BRFileObjectID"8Q16l
- ___block_descriptor_57_e8_32s40s48r_e88_i24?0r*8^{stat=iSSQIIi{timespec=qq}{timespec=qq}{timespec=qq}{timespec=qq}qqiIIi[2q]}16l
- ___block_descriptor_65_e8_32s40s48r56r_e88_i24?0r*8^{stat=iSSQIIi{timespec=qq}{timespec=qq}{timespec=qq}{timespec=qq}qqiIIi[2q]}16l
- ___block_descriptor_80_e8_32s40bs48r56r64r72r_e47_v24?0"NSFileProviderItemVersion"8"NSError"16l
- ___copy_helper_block_e8_32s40b48r56r64r72r
- _objc_msgSend$_garbageCollectUploads
- _objc_msgSend$cloneURLToLiveStage:liveStageFilename:error:
CStrings:
+ "-[BRCStageRegistry(FPFSAdditions) cloneFileURL:toUploadStageID:liveStageFilename:error:]"
+ "-[BRCStageRegistry(FPFSAdditions) cloneFileURL:toUploadStageID:liveStageFilename:error:]_block_invoke"
+ "B32@?0@\"NSString\"8@\"NSString\"16Q24"
+ "NSURL+BRCShareURL.m"
+ "[CRIT] Assertion failed: _appBundleID%@"
+ "[DEBUG] Purged %lld bytes%@"
+ "_appBundleID"
+ "cloneFileURL:toUploadStageID:liveStageFilename:error:"
+ "com.apple.Keynote,com.apple.iWork.Keynote"
+ "com.apple.Numbers,com.apple.iWork.Numbers"
+ "com.apple.Pages,com.apple.iWork.Pages"
+ "cu-%@"
+ "iwork.universal-purchase.keynote"
+ "iwork.universal-purchase.numbers"
+ "iwork.universal-purchase.pages"
+ "markUploadActiveForStageID:"
+ "supportedKeynoteBundleIdentifiers"
+ "supportedNumbersBundleIdentifiers"
+ "supportedPagesBundleIdentifiers"
- "-[BRCStageRegistry _garbageCollectUploadsIncludingActiveUploads:]_block_invoke"
- "-[BRCStageRegistry(FPFSAdditions) cloneURLToLiveStage:liveStageFilename:error:]"
- "-[BRCStageRegistry(FPFSAdditions) cloneURLToLiveStage:liveStageFilename:error:]_block_invoke"
- "B24@?0@\"BRFileObjectID\"8Q16"
- "[DEBUG] removing staged file for upload: %@%@"
- "_garbageCollectUploads"
- "cloneURLToLiveStage:liveStageFilename:error:"
- "com.apple.iWork.Keynote"
- "com.apple.iWork.Numbers"
- "com.apple.iWork.Pages"
- "cu_%@"
```
