## newsd

> `/System/Library/PrivateFrameworks/NewsDaemon.framework/newsd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-5681.0.0.0.0
-  __TEXT.__text: 0x4a728
-  __TEXT.__auth_stubs: 0x1980
-  __TEXT.__objc_stubs: 0x3180
-  __TEXT.__objc_methlist: 0x1794
-  __TEXT.__const: 0x1438
+5691.0.0.0.0
+  __TEXT.__text: 0x4a8c0
+  __TEXT.__auth_stubs: 0x1990
+  __TEXT.__objc_stubs: 0x31e0
+  __TEXT.__objc_methlist: 0x179c
+  __TEXT.__const: 0x1650
   __TEXT.__gcc_except_tab: 0x2f0
-  __TEXT.__cstring: 0x2d7c
-  __TEXT.__objc_methname: 0x4f49
-  __TEXT.__oslogstring: 0x1f4d
+  __TEXT.__cstring: 0x2dac
+  __TEXT.__objc_methname: 0x4f9c
+  __TEXT.__oslogstring: 0x201d
   __TEXT.__objc_classname: 0x508
   __TEXT.__objc_methtype: 0x14b3
   __TEXT.__swift5_typeref: 0xc91

   __TEXT.__swift5_capture: 0x3dc
   __TEXT.__swift_as_ret: 0xbc
   __TEXT.__swift5_assocty: 0xd0
-  __TEXT.__unwind_info: 0x1288
+  __TEXT.__unwind_info: 0x1290
   __TEXT.__eh_frame: 0x2048
-  __DATA_CONST.__auth_got: 0xcd0
+  __DATA_CONST.__auth_got: 0xcd8
   __DATA_CONST.__got: 0x6a0
   __DATA_CONST.__auth_ptr: 0x4c0
-  __DATA_CONST.__const: 0x22d0
+  __DATA_CONST.__const: 0x2310
   __DATA_CONST.__cfstring: 0x480
   __DATA_CONST.__objc_classlist: 0x118
   __DATA_CONST.__objc_protolist: 0x1a8

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x35e8
-  __DATA.__objc_selrefs: 0x13d8
+  __DATA.__objc_selrefs: 0x13f0
   __DATA.__objc_ivar: 0x100
   __DATA.__objc_data: 0xb30
-  __DATA.__data: 0x1e30
+  __DATA.__data: 0x1c38
   __DATA.__bss: 0x1fe0
   __DATA.__common: 0x20
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1378
-  Symbols:   778
-  CStrings:  1364
+  Functions: 1379
+  Symbols:   779
+  CStrings:  1370
 
Symbols:
+ _FCURLForAVAssetDownloads
CStrings:
+ "_cleanUpAVAssetDownloads"
+ "did clear AV asset downloads directory, count=%lu"
+ "failed to clear AV asset downloads directory, error=%{public}@"
+ "fc_containsObjectPassingTest:"
+ "fc_removeContentsOfDirectoryAtURL:removedItemCount:error:"
+ "will clear AV asset downloads directory since there are no more audio download requests"
+ "writeUserDidReadHeadlineWithAnalyticsElement:atDate:"
+ "writeUserDidSeeHeadlinesWithAnalyticsElements:atDate:"
- "writeUserDidReadHeadlineWithAnalyticsElement:atDate:withCompletion:"
- "writeUserDidSeeHeadlinesWithAnalyticsElements:atDate:withCompletion:"
```
