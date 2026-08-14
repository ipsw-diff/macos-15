## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/Versions/A/MobileAsset`

```diff

-1487.120.52.0.0
-  __TEXT.__text: 0x90098
+1487.120.62.0.0
+  __TEXT.__text: 0x90160
   __TEXT.__auth_stubs: 0x790
   __TEXT.__objc_methlist: 0x63e4
   __TEXT.__const: 0x288
   __TEXT.__gcc_except_tab: 0xbe4
-  __TEXT.__cstring: 0x105bf
+  __TEXT.__cstring: 0x105e7
   __TEXT.__oslogstring: 0xa0c8
   __TEXT.__unwind_info: 0x1b88
   __TEXT.__objc_classname: 0x889

   __DATA_CONST.__objc_arraydata: 0x2f0
   __AUTH_CONST.__auth_got: 0x3d8
   __AUTH_CONST.__const: 0x1cd0
-  __AUTH_CONST.__cfstring: 0xd980
+  __AUTH_CONST.__cfstring: 0xd9a0
   __AUTH_CONST.__objc_const: 0x98f0
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x28

   - /usr/lib/libobjc.A.dylib
   Functions: 2842
   Symbols:   5560
-  CStrings:  4783
+  CStrings:  4784
 
Symbols:
+ __118-[MAAutoAssetSet _lockAtomic:forAtomicInstance:withNeedPolicy:withTimeout:reportingProgress:isSynchronous:completion:]_block_invoke
+ ___99-[MAAutoAssetSet _mapLockedAtomicEntry:forAtomicInstance:mappingSelector:isSynchronous:completion:]_block_invoke_3
- __99-[MAAutoAssetSet _mapLockedAtomicEntry:forAtomicInstance:mappingSelector:isSynchronous:completion:]_block_invoke
- ___118-[MAAutoAssetSet _lockAtomic:forAtomicInstance:withNeedPolicy:withTimeout:reportingProgress:isSynchronous:completion:]_block_invoke_4
Functions:
~ ___136-[MAAutoAssetSet _checkAtomic:forAtomicInstance:awaitingDownload:withNeedPolicy:withTimeout:reportingProgress:isSynchronous:completion:]_block_invoke_2 : 976 -> 996
~ ___136-[MAAutoAssetSet _checkAtomic:forAtomicInstance:awaitingDownload:withNeedPolicy:withTimeout:reportingProgress:isSynchronous:completion:]_block_invoke_3 : 744 -> 924
CStrings:
+ "checkAtomic(ignoring newerVersionError)"
```
