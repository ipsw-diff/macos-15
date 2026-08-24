## AVKit

> `/System/iOSSupport/System/Library/Frameworks/AVKit.framework/Versions/A/AVKit`

```diff

-1250.7.1.0.0
-  __TEXT.__text: 0xd80d4
+1260.4.1.0.0
+  __TEXT.__text: 0xd8128
   __TEXT.__auth_stubs: 0xe10
   __TEXT.__objc_methlist: 0x11cf4
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__cstring: 0x9b43
+  __TEXT.__cstring: 0x9b41
   __TEXT.__const: 0x690
   __TEXT.__constg_swiftt: 0x50
   __TEXT.__swift5_typeref: 0x6

   __TEXT.__objc_methname: 0x34692
   __TEXT.__objc_methtype: 0x6b8f
   __TEXT.__objc_stubs: 0x1e1c0
-  __DATA_CONST.__got: 0xbf0
+  __DATA_CONST.__got: 0xbf8
   __DATA_CONST.__const: 0x1fd0
   __DATA_CONST.__objc_classlist: 0x640
   __DATA_CONST.__objc_catlist: 0xc8

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 6042
-  Symbols:   14888
+  Symbols:   14889
   CStrings:  9680
 
Symbols:
+ AVNowPlayingInfoSkipCommandInterval_block_invoke.createSharedControllerOnceToken
+ AVNowPlayingInfoSkipCommandInterval_block_invoke.nowPlayingInfoController
+ _kMRMediaRemoteOptionSkipInterval
- AVNowPlayingInfoPreferredIntervalsKey_block_invoke.createSharedControllerOnceToken
- AVNowPlayingInfoPreferredIntervalsKey_block_invoke.nowPlayingInfoController
Functions:
~ ___61-[AVMobileChromelessControlsViewController _observationSetup]_block_invoke_26 : 308 -> 376
~ -[AVNowPlayingInfoController _handleRemoteCommand:options:] : 2996 -> 3012
CStrings:
+ "AVNowPlayingInfoSkipCommandInterval"
- "AVNowPlayingInfoPreferredIntervalsKey"
```
