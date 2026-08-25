## FindMyDevice

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/Versions/A/FindMyDevice`

```diff

-438.26.4.2.5
-  __TEXT.__text: 0x15780
+438.26.4.2.10
+  __TEXT.__text: 0x16bc0
   __TEXT.__auth_stubs: 0x300
-  __TEXT.__objc_methlist: 0x18a4
-  __TEXT.__cstring: 0x378f
+  __TEXT.__objc_methlist: 0x19b4
+  __TEXT.__cstring: 0x3868
   __TEXT.__const: 0xc0
   __TEXT.__gcc_except_tab: 0x2c4
-  __TEXT.__oslogstring: 0x14a6
-  __TEXT.__unwind_info: 0x540
-  __TEXT.__objc_classname: 0x448
-  __TEXT.__objc_methname: 0x371a
-  __TEXT.__objc_methtype: 0xa7f
-  __TEXT.__objc_stubs: 0x26c0
-  __DATA_CONST.__got: 0x128
-  __DATA_CONST.__const: 0xc80
-  __DATA_CONST.__objc_classlist: 0xc0
+  __TEXT.__oslogstring: 0x16aa
+  __TEXT.__unwind_info: 0x550
+  __TEXT.__objc_classname: 0x46e
+  __TEXT.__objc_methname: 0x3928
+  __TEXT.__objc_methtype: 0xa8b
+  __TEXT.__objc_stubs: 0x2880
+  __DATA_CONST.__got: 0x130
+  __DATA_CONST.__const: 0xc88
+  __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd70
+  __DATA_CONST.__objc_selrefs: 0xdd8
   __DATA_CONST.__objc_protorefs: 0x50
-  __DATA_CONST.__objc_superrefs: 0xa0
+  __DATA_CONST.__objc_superrefs: 0xa8
   __AUTH_CONST.__auth_got: 0x190
   __AUTH_CONST.__const: 0x980
-  __AUTH_CONST.__cfstring: 0x3c20
-  __AUTH_CONST.__objc_const: 0x4240
-  __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH.__objc_data: 0x780
-  __DATA.__objc_ivar: 0x168
+  __AUTH_CONST.__cfstring: 0x3d60
+  __AUTH_CONST.__objc_const: 0x4500
+  __AUTH_CONST.__objc_intobj: 0x48
+  __AUTH.__objc_data: 0x7d0
+  __DATA.__objc_ivar: 0x184
   __DATA.__data: 0x8b8
   __DATA.__common: 0x10
   __DATA.__bss: 0x140

   - /System/Library/PrivateFrameworks/InternationalSupport.framework/Versions/A/InternationalSupport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 643
-  Symbols:   1887
-  CStrings:  1404
+  Functions: 664
+  Symbols:   1940
+  CStrings:  1445
 
Symbols:
+ +[FMDSharedConfigurationFollowUpEntry supportsSecureCoding]
+ -[FMDSharedConfiguration _createAwarenessStringsDictionaryWithData:key:deviceClasses:]
+ -[FMDSharedConfiguration _createFollowUpStringsDictionaryWithData:key:deviceClasses:]
+ -[FMDSharedConfiguration sharedConfigurationDictionaryFromData:key:deviceClasses:]
+ -[FMDSharedConfigurationFollowUpEntry .cxx_destruct]
+ -[FMDSharedConfigurationFollowUpEntry category]
+ -[FMDSharedConfigurationFollowUpEntry encodeWithCoder:]
+ -[FMDSharedConfigurationFollowUpEntry idNumber]
+ -[FMDSharedConfigurationFollowUpEntry informativeText]
+ -[FMDSharedConfigurationFollowUpEntry initWithCoder:]
+ -[FMDSharedConfigurationFollowUpEntry init]
+ -[FMDSharedConfigurationFollowUpEntry message]
+ -[FMDSharedConfigurationFollowUpEntry reminderInMins]
+ -[FMDSharedConfigurationFollowUpEntry setCategory:]
+ -[FMDSharedConfigurationFollowUpEntry setIdNumber:]
+ -[FMDSharedConfigurationFollowUpEntry setInformativeText:]
+ -[FMDSharedConfigurationFollowUpEntry setMessage:]
+ -[FMDSharedConfigurationFollowUpEntry setReminderInMins:]
+ -[FMDSharedConfigurationFollowUpEntry setSubtitleText:]
+ -[FMDSharedConfigurationFollowUpEntry setTitle:]
+ -[FMDSharedConfigurationFollowUpEntry subtitleText]
+ -[FMDSharedConfigurationFollowUpEntry title]
+ OBJC_IVAR_$_FMDSharedConfigurationFollowUpEntry._category
+ OBJC_IVAR_$_FMDSharedConfigurationFollowUpEntry._idNumber
+ OBJC_IVAR_$_FMDSharedConfigurationFollowUpEntry._informativeText
+ OBJC_IVAR_$_FMDSharedConfigurationFollowUpEntry._message
+ OBJC_IVAR_$_FMDSharedConfigurationFollowUpEntry._reminderInMins
+ OBJC_IVAR_$_FMDSharedConfigurationFollowUpEntry._subtitleText
+ OBJC_IVAR_$_FMDSharedConfigurationFollowUpEntry._title
+ _OBJC_CLASS_$_FMDSharedConfigurationFollowUpEntry
+ _OBJC_METACLASS_$_FMDSharedConfigurationFollowUpEntry
+ _OUTLINED_FUNCTION_5
+ __OBJC_$_CLASS_METHODS_FMDSharedConfigurationFollowUpEntry
+ __OBJC_$_CLASS_PROP_LIST_FMDSharedConfigurationFollowUpEntry
+ __OBJC_$_INSTANCE_METHODS_FMDSharedConfigurationFollowUpEntry
+ __OBJC_$_INSTANCE_VARIABLES_FMDSharedConfigurationFollowUpEntry
+ __OBJC_$_PROP_LIST_FMDSharedConfigurationFollowUpEntry
+ __OBJC_CLASS_PROTOCOLS_$_FMDSharedConfigurationFollowUpEntry
+ __OBJC_CLASS_RO_$_FMDSharedConfigurationFollowUpEntry
+ __OBJC_METACLASS_RO_$_FMDSharedConfigurationFollowUpEntry
+ _kFMDCoreFollowUpTheftAndLossReminderSignOutTimestampKey
+ _objc_msgSend$_createAwarenessStringsDictionaryWithData:key:deviceClasses:
+ _objc_msgSend$_createFollowUpStringsDictionaryWithData:key:deviceClasses:
+ _objc_msgSend$category
+ _objc_msgSend$idNumber
+ _objc_msgSend$informativeText
+ _objc_msgSend$initWithInt:
+ _objc_msgSend$message
+ _objc_msgSend$reminderInMins
+ _objc_msgSend$setCategory:
+ _objc_msgSend$setIdNumber:
+ _objc_msgSend$setInformativeText:
+ _objc_msgSend$setReminderInMins:
+ _objc_msgSend$setSubtitleText:
+ _objc_msgSend$sharedConfigurationDictionaryFromData:key:deviceClasses:
+ _objc_msgSend$subtitleText
- -[FMDSharedConfiguration entryWithData:key:deviceClasses:]
- ___49-[FMDSharedConfiguration forceDownloadWithReply:]_block_invoke
- _objc_msgSend$entryWithData:key:deviceClasses:
CStrings:
+ "@\"NSNumber\""
+ "Entry found at %lu, but doesn't contain a remainder in mins"
+ "Entry found at %lu, but doesn't contain an id"
+ "Entry found at %lu, but id isn't a number: %@"
+ "Entry found at %lu, but it doesn't contain category"
+ "Entry found at %lu, but it doesn't contain informative text"
+ "Entry found at %lu, but it doesn't contain message"
+ "Entry found at %lu, but it doesn't contain subtitle text"
+ "Entry found at %lu, but it doesn't contain title"
+ "Entry found at %lu, but remainder in mins isn't a number: %@"
+ "FMDSharedConfigurationFollowUpEntry"
+ "Failed to parse awareness strings"
+ "SignOutTimestamp"
+ "T@\"NSNumber\",C,N,V_idNumber"
+ "T@\"NSNumber\",C,N,V_reminderInMins"
+ "T@\"NSString\",C,N,V_category"
+ "T@\"NSString\",C,N,V_informativeText"
+ "T@\"NSString\",C,N,V_subtitleText"
+ "TNL_REMINDER_INFORMATIVE_TEXT_DEFAULT"
+ "TNL_REMINDER_MESSAGE_DEFAULT"
+ "TNL_REMINDER_SUBTITLE_TEXT_DEFAULT"
+ "TNL_REMINDER_TITLE_DEFAULT"
+ "_category"
+ "_createAwarenessStringsDictionaryWithData:key:deviceClasses:"
+ "_createFollowUpStringsDictionaryWithData:key:deviceClasses:"
+ "_idNumber"
+ "_informativeText"
+ "_reminderInMins"
+ "_subtitleText"
+ "followUpStrings"
+ "i"
+ "idNumber"
+ "informativeText"
+ "initWithInt:"
+ "reminderInMins"
+ "setCategory:"
+ "setIdNumber:"
+ "setInformativeText:"
+ "setReminderInMins:"
+ "setSubtitleText:"
+ "sharedConfigurationDictionaryFromData:key:deviceClasses:"
+ "subtitleText"
- "entryWithData:key:deviceClasses:"
```
