## OSUpdate

> `/System/Library/PrivateFrameworks/OSUpdate.framework/Versions/A/OSUpdate`

```diff

-2078.120.11.0.0
-  __TEXT.__text: 0x8e4dc
+2078.120.12.0.0
+  __TEXT.__text: 0x8e608
   __TEXT.__auth_stubs: 0xab0
-  __TEXT.__objc_methlist: 0x6e34
+  __TEXT.__objc_methlist: 0x6e44
   __TEXT.__const: 0x191
   __TEXT.__cstring: 0x64c1
-  __TEXT.__oslogstring: 0xbe41
+  __TEXT.__oslogstring: 0xbe6c
   __TEXT.__gcc_except_tab: 0x2028
   __TEXT.__ustring: 0xc
   __TEXT.__unwind_info: 0x1d00
   __TEXT.__objc_classname: 0x81b
-  __TEXT.__objc_methname: 0x150d0
+  __TEXT.__objc_methname: 0x150ee
   __TEXT.__objc_methtype: 0x20a4
-  __TEXT.__objc_stubs: 0xe340
+  __TEXT.__objc_stubs: 0xe360
   __DATA_CONST.__got: 0x9d8
   __DATA_CONST.__const: 0xc48
   __DATA_CONST.__objc_classlist: 0x220
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4518
+  __DATA_CONST.__objc_selrefs: 0x4520
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x3f8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbootpolicy.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2908
-  Symbols:   6481
-  CStrings:  5156
+  Functions: 2909
+  Symbols:   6482
+  CStrings:  5158
 
Symbols:
+ -[SUOSUShimController clearProductKeysToAutoInstall]
+ GCC_except_table120
+ GCC_except_table128
+ GCC_except_table130
+ GCC_except_table145
+ GCC_except_table153
+ GCC_except_table176
+ GCC_except_table74
+ _objc_msgSend$clearProductKeysToAutoInstall
- GCC_except_table118
- GCC_except_table127
- GCC_except_table129
- GCC_except_table134
- GCC_except_table144
- GCC_except_table152
- GCC_except_table175
- GCC_except_table73
Functions:
~ -[SUOSUClient cancelUpdatesQueuedForLater] : 64 -> 100
+ -[SUOSUShimController clearProductKeysToAutoInstall]
~ -[SUOSUShimController _queueUpdatesForLater:withReason:mdmInitiated:window:] : 2268 -> 2276
~ -[SUOSUShimController setIsAutomaticallyInstallMacOSUpdatesPreferenceEnabled:] : 268 -> 276
CStrings:
+ "%@: Clearing product keys to auto install."
+ "clearProductKeysToAutoInstall"
```
