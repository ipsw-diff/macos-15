## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/Versions/A/SoftwareUpdateCore`

```diff

-2171.120.30.0.4
-  __TEXT.__text: 0xab390
-  __TEXT.__auth_stubs: 0x680
-  __TEXT.__objc_methlist: 0x72cc
+2171.120.44.0.1
+  __TEXT.__text: 0xac0e8
+  __TEXT.__auth_stubs: 0x690
+  __TEXT.__objc_methlist: 0x72ec
   __TEXT.__const: 0x118
-  __TEXT.__cstring: 0x14297
-  __TEXT.__oslogstring: 0xae77
-  __TEXT.__gcc_except_tab: 0x6d4
-  __TEXT.__unwind_info: 0x15d0
+  __TEXT.__cstring: 0x1431c
+  __TEXT.__oslogstring: 0xaf1c
+  __TEXT.__gcc_except_tab: 0x744
+  __TEXT.__unwind_info: 0x1608
   __TEXT.__objc_classname: 0x6d5
-  __TEXT.__objc_methname: 0x14105
-  __TEXT.__objc_methtype: 0xec2
-  __TEXT.__objc_stubs: 0xd800
-  __DATA_CONST.__got: 0x810
-  __DATA_CONST.__const: 0x13b8
+  __TEXT.__objc_methname: 0x14127
+  __TEXT.__objc_methtype: 0xedc
+  __TEXT.__objc_stubs: 0xd840
+  __DATA_CONST.__got: 0x820
+  __DATA_CONST.__const: 0x13c0
   __DATA_CONST.__objc_classlist: 0x1c8
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3f30
+  __DATA_CONST.__objc_selrefs: 0x3f40
   __DATA_CONST.__objc_superrefs: 0x1b0
   __DATA_CONST.__objc_arraydata: 0xa8
-  __AUTH_CONST.__auth_got: 0x350
-  __AUTH_CONST.__const: 0x1220
-  __AUTH_CONST.__cfstring: 0x11ee0
+  __AUTH_CONST.__auth_got: 0x358
+  __AUTH_CONST.__const: 0x1280
+  __AUTH_CONST.__cfstring: 0x11f60
   __AUTH_CONST.__objc_const: 0x9d10
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x28

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2854
-  Symbols:   6525
-  CStrings:  6072
+  Functions: 2863
+  Symbols:   6544
+  CStrings:  6083
 
Symbols:
+ +[MAAutoAsset(SUCoreBorderMAAutoAsset) SUCoreBorder_stageDetermineGroupsAvailableForUpdate:timeoutSecs:completion:]
+ -[SUCoreScan _psusDetermineTimeout]
+ -[SUCoreUpdateDownloader _psusStageTimeout]
+ GCC_except_table116
+ GCC_except_table79
+ GCC_except_table88
+ __115+[MAAutoAsset(SUCoreBorderMAAutoAsset) SUCoreBorder_stageDetermineGroupsAvailableForUpdate:timeoutSecs:completion:]_block_invoke
+ __MSUPreferencesCopyValue
+ ___115+[MAAutoAsset(SUCoreBorderMAAutoAsset) SUCoreBorder_stageDetermineGroupsAvailableForUpdate:timeoutSecs:completion:]_block_invoke
+ ___139+[MAAutoAsset(SUCoreBorderMAAutoAsset) SUCoreBorder_stageDownloadGroups:awaitingAllGroups:withStagingTimeout:reportingProgress:completion:]_block_invoke
+ ___139+[MAAutoAsset(SUCoreBorderMAAutoAsset) SUCoreBorder_stageDownloadGroups:awaitingAllGroups:withStagingTimeout:reportingProgress:completion:]_block_invoke_2
+ ___57-[SUCoreUpdateDownloader actionDownloadPSUSAssets:error:]_block_invoke_3
+ ___block_descriptor_48_e8_32bs_e17_v16?0"NSTimer"8l
+ ___block_descriptor_56_e8_32bs40r48r_e51_v32?0"NSDictionary"8"NSDictionary"16"NSError"24l
+ ___copy_helper_block_e8_32b40r48r
+ _kMobileSoftwareUpdatePreSUStagingDetermineTimeoutKey
+ _kMobileSoftwareUpdatePreSUStagingStageTimeoutKey
+ _kSUCoreNotificationPreSUStagingOperationTimedOut
+ _objc_msgSend$SUCoreBorder_stageDetermineGroupsAvailableForUpdate:timeoutSecs:completion:
+ _objc_msgSend$_psusDetermineTimeout
+ _objc_msgSend$_psusStageTimeout
+ _objc_msgSend$errorUserInfo
- +[MAAutoAsset(SUCoreBorderMAAutoAsset) SUCoreBorder_stageDetermineGroupsAvailableForUpdate:completion:]
- _objc_msgSend$SUCoreBorder_stageDetermineGroupsAvailableForUpdate:completion:
- _objc_msgSend$stringByAppendingPathExtension:
CStrings:
+ "%@ timed out after %ld Secs"
+ "%@ timed out after %lf Secs"
+ "1.0.4"
+ "@40@0:8@16d24@?32"
+ "@52@0:8@16B24q28@?36@?44"
+ "SUCoreBorder_stageDetermineGroupsAvailableForUpdate:timeoutSecs:completion:"
+ "[DOCUMENTATION] Failed to determine encoded UI bundle path due to missing file name"
+ "[DOCUMENTATION] Failed to load update bundle at URL: %{public}@"
+ "[DOCUMENTATION] Loading bundle with localBundleURL:%{public}@ encodedUIBundleFileName:%{public}@"
+ "[DOCUMENTATION] No encoded UI bundle path was found within the update bundle."
+ "[PreSUStaging] purge after a timeout: %@"
+ "_psusDetermineTimeout"
+ "_psusStageTimeout"
+ "com.apple.SUCore.PSUS.TimedOut"
+ "d16@0:8"
+ "errorUserInfo"
+ "hang"
- "1.0.3"
- "SUCoreBorder_stageDetermineGroupsAvailableForUpdate:completion:"
- "[DOCUMENTATION] Failed to determine encoded UI bundle path due to no preferences file name"
- "[DOCUMENTATION] No encoded UI bundle path was found at: %{public}@"
- "stringByAppendingPathExtension:"
- "v52@0:8@16B24q28@?36@?44"
```
