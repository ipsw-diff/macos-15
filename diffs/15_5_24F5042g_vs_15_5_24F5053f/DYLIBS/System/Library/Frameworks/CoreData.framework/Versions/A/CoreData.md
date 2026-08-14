## CoreData

> `/System/Library/Frameworks/CoreData.framework/Versions/A/CoreData`

```diff

-1447.0.0.0.0
-  __TEXT.__text: 0x363e28
+1447.2.0.0.0
+  __TEXT.__text: 0x363ff0
   __TEXT.__auth_stubs: 0x22f0
-  __TEXT.__objc_methlist: 0x11044
+  __TEXT.__objc_methlist: 0x1104c
   __TEXT.__const: 0x1150
-  __TEXT.__cstring: 0x4d318
+  __TEXT.__cstring: 0x4d319
   __TEXT.__constg_swiftt: 0x14c
   __TEXT.__swift5_typeref: 0x346
   __TEXT.__swift5_builtin: 0x28

   __TEXT.__swift5_capture: 0x25c
   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
-  __TEXT.__oslogstring: 0x31b80
+  __TEXT.__oslogstring: 0x31c9d
   __TEXT.__gcc_except_tab: 0x1d370
   __TEXT.__unwind_info: 0x7918
   __TEXT.__eh_frame: 0x630
   __TEXT.__objc_classname: 0x3c0f
-  __TEXT.__objc_methname: 0x1ee5f
+  __TEXT.__objc_methname: 0x1ee7f
   __TEXT.__objc_methtype: 0x4e65
-  __TEXT.__objc_stubs: 0x14780
+  __TEXT.__objc_stubs: 0x147a0
   __DATA_CONST.__got: 0x980
   __DATA_CONST.__const: 0x13b0
   __DATA_CONST.__objc_classlist: 0x1048
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6468
+  __DATA_CONST.__objc_selrefs: 0x6470
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0xd78
   __DATA_CONST.__objc_arraydata: 0x6728
   __AUTH_CONST.__auth_got: 0x1188
   __AUTH_CONST.__const: 0x4ec8
   __AUTH_CONST.__cfstring: 0x26900
-  __AUTH_CONST.__objc_const: 0x2b1a8
+  __AUTH_CONST.__objc_const: 0x2b1c0
   __AUTH_CONST.__objc_dictobj: 0x1f18
   __AUTH_CONST.__objc_arrayobj: 0x6f30
   __AUTH_CONST.__objc_intobj: 0x558

   __AUTH.__data: 0x1b0
   __DATA.__objc_ivar: 0x250c
   __DATA.__data: 0xfc8
-  __DATA.__bss: 0x1160
+  __DATA.__bss: 0x1168
   __DATA.__common: 0x5d0
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_time.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 8779
-  Symbols:   19134
-  CStrings:  15218
+  Functions: 8780
+  Symbols:   19137
+  CStrings:  15225
 
Symbols:
+ -[_PFBackgroundRuntimeVoucher initWithTask:]
+ -[_PFBackgroundRuntimeVoucher setSequenceID:]
+ __OBJC_$_PROP_LIST__PFBackgroundRuntimeVoucher
+ _objc_msgSend$initWithTask:
+ _objc_msgSend$setSequenceID:
- -[_PFBackgroundRuntimeVoucher initWithTask:andSequence:]
- _objc_msgSend$initWithTask:andSequence:
CStrings:
+ "Attempting to recover from failed background task assertion acquisition for task '%@'."
+ "CoreData: error: Attempting to recover from failed background task assertion acquisition for task '%@'.\n"
+ "CoreData: fault: rdar://145887349, bidx > bindings. Statement: %@ bindings: %@\n"
+ "CoreData: fault: rdar://145887349, bindings is not an NSArray. %@\n"
+ "CoreData: rdar://145887349, bidx > bindings. Statement: %@ bindings: %@"
+ "CoreData: rdar://145887349, bindings is not an NSArray. %@"
+ "CoreData: warning: Ended background task assertion %ld.\n"
+ "CoreData: warning: Registration for _beginPowerAssertionNamed completed with class %p on app %p and result %@\n"
+ "CoreData: warning: Successfully acquired background task assertion %ld for task '%@'.\n"
+ "TQ,N,V_sequenceID"
+ "initWithTask:"
+ "sequenceID"
+ "setSequenceID:"
- "Attempting to recover from failed background task assertion acquistion for task '%@'."
- "CoreData: debug: Ended background task assertion %ld.\n"
- "CoreData: debug: Registration for _beginPowerAssertionNamed completed with class %p on app %p and result %@\n"
- "CoreData: debug: Successfully acquired background task assertion %ld for task '%@'.\n"
- "CoreData: error: Attempting to recover from failed background task assertion acquistion for task '%@'.\n"
- "initWithTask:andSequence:"
```
