## CoreServicesInternal

> `/System/Library/PrivateFrameworks/CoreServicesInternal.framework/Versions/A/CoreServicesInternal`

```diff

-554.6.0.0.0
-  __TEXT.__text: 0x364b0
+554.6.1.0.0
+  __TEXT.__text: 0x364c4
   __TEXT.__auth_stubs: 0x1bf0
   __TEXT.__delay_stubs: 0x1b8
   __TEXT.__delay_helper: 0x49c
Symbols:
+ _fstatfs_ext
+ _statfs_ext
- _fstatfs
- _statfs
Functions:
~ __FSGetTypeInfoForPath : 216 -> 220
~ __FSGetTypeInfoForFileDescriptor : 216 -> 220
~ __FSGetLocationForPath : 208 -> 212
~ __FSGetLocationForFileDescriptor : 208 -> 212
~ __FSCopyNameForVolumeFormatAtURL_internal : 364 -> 368
```
