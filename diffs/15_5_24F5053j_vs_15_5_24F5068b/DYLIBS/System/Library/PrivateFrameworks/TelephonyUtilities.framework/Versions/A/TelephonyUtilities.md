## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/Versions/A/TelephonyUtilities`

```diff

-1525.600.31.0.0
-  __TEXT.__text: 0x13f040
+1525.600.42.0.0
+  __TEXT.__text: 0x13f14c
   __TEXT.__auth_stubs: 0x1180
-  __TEXT.__objc_methlist: 0x17620
+  __TEXT.__objc_methlist: 0x17648
   __TEXT.__cstring: 0xeed3
   __TEXT.__const: 0x21a
   __TEXT.__oslogstring: 0xea66
-  __TEXT.__gcc_except_tab: 0x12a4
+  __TEXT.__gcc_except_tab: 0x12c8
   __TEXT.__ustring: 0xde
   __TEXT.__dlopen_cstrs: 0x504
   __TEXT.__swift5_typeref: 0x59

   __TEXT.__swift5_reflstr: 0x1c
   __TEXT.__swift5_fieldmd: 0x34
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x4990
-  __TEXT.__objc_classname: 0x23a4
-  __TEXT.__objc_methname: 0x35fac
+  __TEXT.__unwind_info: 0x49a0
+  __TEXT.__objc_classname: 0x23a5
+  __TEXT.__objc_methname: 0x36029
   __TEXT.__objc_methtype: 0x78a9
   __TEXT.__objc_stubs: 0x1d840
-  __DATA_CONST.__got: 0xa78
+  __DATA_CONST.__got: 0xa80
   __DATA_CONST.__const: 0x15c8
   __DATA_CONST.__objc_classlist: 0x6e8
   __DATA_CONST.__objc_catlist: 0xb8
   __DATA_CONST.__objc_protolist: 0x3d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9d70
+  __DATA_CONST.__objc_selrefs: 0x9d88
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x5e8
   __DATA_CONST.__objc_arraydata: 0x3f8
   __AUTH_CONST.__auth_got: 0x8d0
   __AUTH_CONST.__const: 0x3a00
   __AUTH_CONST.__cfstring: 0xfa20
-  __AUTH_CONST.__objc_const: 0x23400
+  __AUTH_CONST.__objc_const: 0x23430
   __AUTH_CONST.__objc_intobj: 0x2e8
   __AUTH_CONST.__objc_arrayobj: 0x150
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH.__objc_data: 0x2210
   __AUTH.__data: 0x90
-  __DATA.__objc_ivar: 0x1570
+  __DATA.__objc_ivar: 0x1574
   __DATA.__data: 0x2e00
   __DATA.__bss: 0x670
   __DATA.__common: 0x1

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 8315
-  Symbols:   17140
-  CStrings:  12101
+  Functions: 8318
+  Symbols:   17145
+  CStrings:  12106
 
Symbols:
+ -[TUConversation cachedDisplayName]
+ -[TUConversation handleContactStoreDidChange:]
+ -[TUConversation setCachedDisplayName:]
+ GCC_except_table190
+ OBJC_IVAR_$_TUConversation._cachedDisplayName
+ _CNContactStoreDidChangeNotification
- GCC_except_table187
Functions:
~ -[TUConversation displayName] : 152 -> 308
+ -[TUConversation handleContactStoreDidChange:]
+ -[TUConversation setCachedDisplayName:]
+ -[TUConversation localMember]
~ -[TUConversation .cxx_destruct] : 464 -> 476
CStrings:
+ "T@\"NSString\",&,N,V_cachedDisplayName"
+ "_cachedDisplayName"
+ "cachedDisplayName"
+ "handleContactStoreDidChange:"
+ "setCachedDisplayName:"
```
