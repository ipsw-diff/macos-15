## TimeMachine

> `/System/Library/PrivateFrameworks/TimeMachine.framework/Versions/A/TimeMachine`

```diff

-2433.0.0.0.0
-  __TEXT.__text: 0xd8ca4
+2435.0.0.0.0
+  __TEXT.__text: 0xd8f20
   __TEXT.__auth_stubs: 0x26a0
-  __TEXT.__objc_methlist: 0x5810
-  __TEXT.__const: 0x27c4
-  __TEXT.__cstring: 0xb66c
+  __TEXT.__objc_methlist: 0x5830
+  __TEXT.__const: 0x2b74
+  __TEXT.__cstring: 0xb7dc
   __TEXT.__gcc_except_tab: 0x1e8c
   __TEXT.__dlopen_cstrs: 0xb0
   __TEXT.__ustring: 0x4

   __TEXT.__swift5_builtin: 0x17c
   __TEXT.__swift5_protos: 0x10
   __TEXT.__swift5_mpenum: 0xd8
-  __TEXT.__unwind_info: 0x31f0
+  __TEXT.__unwind_info: 0x31f8
   __TEXT.__eh_frame: 0x3538
   __TEXT.__objc_classname: 0x8ce
-  __TEXT.__objc_methname: 0xcbee
+  __TEXT.__objc_methname: 0xcccf
   __TEXT.__objc_methtype: 0x25f9
-  __TEXT.__objc_stubs: 0x9620
+  __TEXT.__objc_stubs: 0x9700
   __DATA_CONST.__got: 0xaf0
   __DATA_CONST.__const: 0xa70
   __DATA_CONST.__objc_classlist: 0x290
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3250
+  __DATA_CONST.__objc_selrefs: 0x3298
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x220
   __DATA_CONST.__objc_arraydata: 0x108
   __AUTH_CONST.__auth_got: 0x1368
   __AUTH_CONST.__const: 0x5470
-  __AUTH_CONST.__cfstring: 0x7fa0
-  __AUTH_CONST.__objc_const: 0x8958
+  __AUTH_CONST.__cfstring: 0x8060
+  __AUTH_CONST.__objc_const: 0x8978
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x15f8
   __AUTH.__data: 0x388
   __DATA.__objc_ivar: 0x478
-  __DATA.__data: 0x95e0
+  __DATA.__data: 0x9240
   __DATA.__bss: 0x3e30
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x4b0

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3884
-  Symbols:   5752
-  CStrings:  3871
+  Functions: 3887
+  Symbols:   5762
+  CStrings:  3886
 
Symbols:
+ -[NSURL(TMAdditions) tm_URLByReplacingSchemeWithSMB]
+ -[NSURL(TMAdditions) tm_isAFP]
+ -[NSURL(TMAdditions) tm_isSMB]
+ _objc_msgSend$URLHostAllowedCharacterSet
+ _objc_msgSend$lowercaseString
+ _objc_msgSend$scheme
+ _objc_msgSend$setScheme:
+ _objc_msgSend$stringByAddingPercentEncodingWithAllowedCharacters:
+ _objc_msgSend$stringByReplacingOccurrencesOfString:withString:options:range:
+ _objc_msgSend$tm_isSMB
CStrings:
+ "BACKUP_WARNING_OBSOLETE_AFP_DESTINATION"
+ "BACKUP_WARNING_OBSOLETE_TIME_CAPSULE_DESTINATION"
+ "MountPoint %@ does not contain volumeName %@"
+ "URLHostAllowedCharacterSet"
+ "_afpovertcp._tcp."
+ "_smb._tcp."
+ "afp"
+ "lowercaseString"
+ "scheme"
+ "setScheme:"
+ "smb"
+ "stringByAddingPercentEncodingWithAllowedCharacters:"
+ "stringByReplacingOccurrencesOfString:withString:options:range:"
+ "tm_URLByReplacingSchemeWithSMB"
+ "tm_isAFP"
+ "tm_isSMB"
- "Mounted wrong device, mountPoint %@ does not contain volumeName %@"
```
