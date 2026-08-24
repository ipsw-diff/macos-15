## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing`

```diff

-2060.60.31.0.0
-  __TEXT.__text: 0x30e2d8
+2060.60.41.1.2
+  __TEXT.__text: 0x30df4c
   __TEXT.__auth_stubs: 0x43d0
-  __TEXT.__objc_methlist: 0x11b7c
-  __TEXT.__cstring: 0x2b355
+  __TEXT.__objc_methlist: 0x11b5c
+  __TEXT.__cstring: 0x2b265
   __TEXT.__const: 0x1880c
   __TEXT.__gcc_except_tab: 0x3150
   __TEXT.__oslogstring: 0x96fe

   __TEXT.__swift_as_entry: 0x2bc
   __TEXT.__swift_as_ret: 0x2c4
   __TEXT.__swift5_mpenum: 0xa8
-  __TEXT.__unwind_info: 0xb6e0
+  __TEXT.__unwind_info: 0xb6d8
   __TEXT.__eh_frame: 0xa398
   __TEXT.__objc_classname: 0x1bae
-  __TEXT.__objc_methname: 0x260d0
+  __TEXT.__objc_methname: 0x26034
   __TEXT.__objc_methtype: 0x5332
-  __TEXT.__objc_stubs: 0x148e0
+  __TEXT.__objc_stubs: 0x14840
   __DATA_CONST.__got: 0xfe8
-  __DATA_CONST.__const: 0x2c80
+  __DATA_CONST.__const: 0x2c60
   __DATA_CONST.__objc_classlist: 0x778
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x2e8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7f30
+  __DATA_CONST.__objc_selrefs: 0x7f08
   __DATA_CONST.__objc_protorefs: 0x198
   __DATA_CONST.__objc_classrefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x510
   __DATA_CONST.__objc_arraydata: 0x2f8
   __AUTH_CONST.__auth_got: 0x2200
-  __AUTH_CONST.__const: 0x12880
-  __AUTH_CONST.__cfstring: 0x113c0
-  __AUTH_CONST.__objc_const: 0x2f5f0
+  __AUTH_CONST.__const: 0x12860
+  __AUTH_CONST.__cfstring: 0x11380
+  __AUTH_CONST.__objc_const: 0x2f5c0
   __AUTH_CONST.__objc_intobj: 0x450
   __AUTH_CONST.__objc_dictobj: 0x410
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH.__objc_data: 0x5db8
   __AUTH.__data: 0x2a58
-  __DATA.__objc_ivar: 0x1f5c
+  __DATA.__objc_ivar: 0x1f58
   __DATA.__data: 0xaa10
   __DATA.__bss: 0x2ef40
   __DATA.__common: 0x110

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 18234
-  Symbols:   19494
-  CStrings:  14021
+  Functions: 18227
+  Symbols:   19482
+  CStrings:  14006
 
Symbols:
+ -[SFRemoteHotspotDevice lastSeen]
+ -[SFRemoteHotspotDevice setLastSeen:]
+ OBJC_IVAR_$_SFRemoteHotspotDevice._lastSeen
- -[SFPasswordSharingInfo emailHash]
- -[SFPasswordSharingInfo phoneHash]
- -[SFPasswordSharingInfo setEmailHash:]
- -[SFPasswordSharingInfo setPhoneHash:]
- -[SFPasswordSharingService _resolveContactForPeerInfo:]
- OBJC_IVAR_$_SFPasswordSharingInfo._emailHash
- OBJC_IVAR_$_SFPasswordSharingInfo._phoneHash
- __55-[SFPasswordSharingService _resolveContactForPeerInfo:]_block_invoke
- ___55-[SFPasswordSharingService _resolveContactForPeerInfo:]_block_invoke
- ___block_descriptor_32_e30_v24?0"NSString"8"NSError"16l
- _objc_msgSend$_resolveContactForPeerInfo:
- _objc_msgSend$emailHash
- _objc_msgSend$phoneHash
- _objc_msgSend$setEmailHash:
- _objc_msgSend$setPhoneHash:
CStrings:
- "### No emailHash?\n"
- "### No phoneHash?\n"
- "-[SFPasswordSharingService _resolveContactForPeerInfo:]_block_invoke"
- "T@\"NSString\",&,N,V_emailHash"
- "T@\"NSString\",&,N,V_phoneHash"
- "WiFiPasswordSharing remote peer is a mutual contact: #@.\n"
- "_emailHash"
- "_phoneHash"
- "_resolveContactForPeerInfo:"
- "com.apple.sharing.WiFiPasswordSharing.MutualContact"
- "emailHash"
- "phoneHash"
- "providerIsContact"
- "setEmailHash:"
- "setPhoneHash:"
```
