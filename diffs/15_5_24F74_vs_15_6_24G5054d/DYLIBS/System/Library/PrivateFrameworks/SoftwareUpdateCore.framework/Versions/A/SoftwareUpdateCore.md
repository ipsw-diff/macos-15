## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/Versions/A/SoftwareUpdateCore`

```diff

-2171.120.44.0.1
-  __TEXT.__text: 0xac0e8
+2171.140.7.0.0
+  __TEXT.__text: 0xac7e8
   __TEXT.__auth_stubs: 0x690
-  __TEXT.__objc_methlist: 0x72ec
+  __TEXT.__objc_methlist: 0x730c
   __TEXT.__const: 0x118
-  __TEXT.__cstring: 0x1431c
-  __TEXT.__oslogstring: 0xaf1c
+  __TEXT.__cstring: 0x1438d
+  __TEXT.__oslogstring: 0xb01b
   __TEXT.__gcc_except_tab: 0x744
   __TEXT.__unwind_info: 0x1608
-  __TEXT.__objc_classname: 0x6d5
-  __TEXT.__objc_methname: 0x14127
-  __TEXT.__objc_methtype: 0xedc
-  __TEXT.__objc_stubs: 0xd840
-  __DATA_CONST.__got: 0x820
-  __DATA_CONST.__const: 0x13c0
+  __TEXT.__objc_classname: 0x6d6
+  __TEXT.__objc_methname: 0x141a9
+  __TEXT.__objc_methtype: 0xeef
+  __TEXT.__objc_stubs: 0xd880
+  __DATA_CONST.__got: 0x828
+  __DATA_CONST.__const: 0x13c8
   __DATA_CONST.__objc_classlist: 0x1c8
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3f40
+  __DATA_CONST.__objc_selrefs: 0x3f58
   __DATA_CONST.__objc_superrefs: 0x1b0
-  __DATA_CONST.__objc_arraydata: 0xa8
+  __DATA_CONST.__objc_arraydata: 0xe8
   __AUTH_CONST.__auth_got: 0x358
   __AUTH_CONST.__const: 0x1280
-  __AUTH_CONST.__cfstring: 0x11f60
-  __AUTH_CONST.__objc_const: 0x9d10
-  __AUTH_CONST.__objc_intobj: 0xc0
-  __AUTH_CONST.__objc_dictobj: 0x28
+  __AUTH_CONST.__cfstring: 0x12040
+  __AUTH_CONST.__objc_const: 0x9d40
+  __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0xa8
+  __AUTH_CONST.__objc_intobj: 0x90
   __AUTH.__objc_data: 0x11d0
-  __DATA.__objc_ivar: 0x8fc
+  __DATA.__objc_ivar: 0x900
   __DATA.__data: 0x360
   __DATA.__bss: 0xc0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2863
-  Symbols:   6544
-  CStrings:  6083
+  Functions: 2866
+  Symbols:   6552
+  CStrings:  6100
 
Symbols:
+ +[MAAutoAsset(SUCoreBorderMAAutoAsset) _generateSimulatedResults:bytes:huge:]
+ -[SUCoreDescriptor preSUStagingMaxSize]
+ -[SUCoreDescriptor setPreSUStagingMaxSize:]
+ GCC_except_table80
+ GCC_except_table89
+ OBJC_IVAR_$_SUCoreDescriptor._preSUStagingMaxSize
+ _KSUAssetPreSUStagingMaxSizeKey
+ _kMobileSoftwareUpdatePreSUStagingMaxSizeKey
+ _objc_msgSend$_generateSimulatedResults:bytes:huge:
+ _objc_msgSend$preSUStagingMaxSize
- GCC_except_table79
- GCC_except_table88
CStrings:
+ "%{public}@ Ignore PSUS assets because required=%llu, optional=%llu, max=%llu"
+ "%{public}@ Using PSUS max size from preferences: %llu"
+ "%{public}@ [PreSUStaging] optional asset to stage: %{public}@"
+ "%{public}@ [PreSUStaging] required asset to stage: %{public}@"
+ "EncodedUIv2"
+ "PSUSMaxSize"
+ "PreSUStagingMaxSize"
+ "TQ,N,V_preSUStagingMaxSize"
+ "_generateSimulatedResults:bytes:huge:"
+ "_preSUStagingMaxSize"
+ "huge"
+ "optional-asset1-v2"
+ "optional-asset2-v2"
+ "preSUStagingMaxSize"
+ "required-asset1-v2"
+ "required-asset2-v2"
+ "setPreSUStagingMaxSize:"
+ "v36@0:8^@16^@24B32"
- "EncodedUI"
```
