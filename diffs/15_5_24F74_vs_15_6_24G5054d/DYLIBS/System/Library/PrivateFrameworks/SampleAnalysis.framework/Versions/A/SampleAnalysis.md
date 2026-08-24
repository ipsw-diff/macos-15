## SampleAnalysis

> `/System/Library/PrivateFrameworks/SampleAnalysis.framework/Versions/A/SampleAnalysis`

```diff

-385.14.0.0.0
-  __TEXT.__text: 0x103ecc
-  __TEXT.__auth_stubs: 0x1840
+385.15.0.0.0
+  __TEXT.__text: 0x1048cc
+  __TEXT.__auth_stubs: 0x1850
   __TEXT.__objc_methlist: 0x5adc
   __TEXT.__const: 0x378
   __TEXT.__dlopen_cstrs: 0x16a
-  __TEXT.__cstring: 0x17b60
-  __TEXT.__oslogstring: 0xc95f
+  __TEXT.__cstring: 0x17c13
+  __TEXT.__oslogstring: 0xca70
   __TEXT.__gcc_except_tab: 0xa618
   __TEXT.__unwind_info: 0x2190
   __TEXT.__objc_classname: 0xabb
   __TEXT.__objc_methname: 0xd390
   __TEXT.__objc_methtype: 0x1811
   __TEXT.__objc_stubs: 0x7e40
-  __DATA_CONST.__got: 0x430
+  __DATA_CONST.__got: 0x438
   __DATA_CONST.__const: 0xd58
   __DATA_CONST.__objc_classlist: 0x3f0
   __DATA_CONST.__objc_catlist: 0x10

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x2a8
   __DATA_CONST.__objc_arraydata: 0x1b8
-  __AUTH_CONST.__auth_got: 0xc38
+  __AUTH_CONST.__auth_got: 0xc40
   __AUTH_CONST.__const: 0x3e10
-  __AUTH_CONST.__cfstring: 0xbbc0
+  __AUTH_CONST.__cfstring: 0xbd00
   __AUTH_CONST.__objc_const: 0xf978
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0x1f8

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   Functions: 2884
-  Symbols:   6623
-  CStrings:  5951
+  Symbols:   6625
+  CStrings:  5967
 
Symbols:
+ _OSKextCopyLoadedKextInfo
+ _kCFBundleIdentifierKey
Functions:
~ _CopyLoadInfosForLiveProcess : 3192 -> 5752
CStrings:
+ "Ignoring kext %@"
+ "No UUID for kext %@, not including in load info"
+ "No cpu type(%d)/subtype(%d) 0x%x/0x%x for main kernel binary"
+ "No load address for kext %@, not including in load info"
+ "OSBundleCPUSubtype"
+ "OSBundleCPUType"
+ "OSBundleExecLoadAddress"
+ "OSBundleExecLoadSize"
+ "OSBundleExecutablePath"
+ "OSBundleLoadAddress"
+ "OSBundleLoadSize"
+ "OSBundleUUID"
+ "OSKext provided no load infos"
+ "UUID too short for kext %@ (%lu), not including in load info"
+ "__kernel__"
+ "com.apple.kpi."
```
