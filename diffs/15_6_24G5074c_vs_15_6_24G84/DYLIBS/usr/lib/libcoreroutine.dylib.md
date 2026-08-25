## libcoreroutine.dylib

> `/usr/lib/libcoreroutine.dylib`

```diff

-990.0.10.0.0
-  __TEXT.__text: 0x4cfa1c
+990.0.10.3.1
+  __TEXT.__text: 0x4cf050
   __TEXT.__auth_stubs: 0x1660
-  __TEXT.__objc_methlist: 0x2628c
-  __TEXT.__const: 0x17e0
+  __TEXT.__objc_methlist: 0x26264
+  __TEXT.__const: 0x17d0
   __TEXT.__dlopen_cstrs: 0xb2
-  __TEXT.__cstring: 0x3577b
-  __TEXT.__oslogstring: 0x54076
+  __TEXT.__cstring: 0x356bf
+  __TEXT.__oslogstring: 0x54021
   __TEXT.__swift5_typeref: 0xd
   __TEXT.__gcc_except_tab: 0x1a42c
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0xa8d8
+  __TEXT.__unwind_info: 0xa8c8
   __TEXT.__eh_frame: 0x60
-  __TEXT.__objc_classname: 0x47a3
-  __TEXT.__objc_methname: 0x6d7c6
-  __TEXT.__objc_methtype: 0xa6f1
-  __TEXT.__objc_stubs: 0x3f780
+  __TEXT.__objc_classname: 0x47a2
+  __TEXT.__objc_methname: 0x6d72f
+  __TEXT.__objc_methtype: 0xa6dd
+  __TEXT.__objc_stubs: 0x3f720
   __DATA_CONST.__got: 0x2510
-  __DATA_CONST.__const: 0x28a8
+  __DATA_CONST.__const: 0x28a0
   __DATA_CONST.__objc_classlist: 0x1120
   __DATA_CONST.__objc_catlist: 0x2c8
   __DATA_CONST.__objc_protolist: 0x2d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x132b0
+  __DATA_CONST.__objc_selrefs: 0x13298
   __DATA_CONST.__objc_protorefs: 0x120
   __DATA_CONST.__objc_superrefs: 0xe48
   __DATA_CONST.__objc_arraydata: 0x2620
   __AUTH_CONST.__auth_got: 0xb40
   __AUTH_CONST.__const: 0xbf50
-  __AUTH_CONST.__cfstring: 0x1e1a0
-  __AUTH_CONST.__objc_const: 0x3fcd8
-  __AUTH_CONST.__objc_intobj: 0x31b0
+  __AUTH_CONST.__cfstring: 0x1e180
+  __AUTH_CONST.__objc_const: 0x3fca8
+  __AUTH_CONST.__objc_intobj: 0x31c8
   __AUTH_CONST.__objc_arrayobj: 0xbb8
   __AUTH_CONST.__objc_doubleobj: 0x950
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH.__objc_data: 0x6d10
-  __DATA.__objc_ivar: 0x2ad4
+  __DATA.__objc_ivar: 0x2ad0
   __DATA.__data: 0x27d0
   __DATA.__bss: 0x138
   __DATA_DIRTY.__objc_data: 0x3e30

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 15627
-  Symbols:   32897
-  CStrings:  26027
+  Functions: 15624
+  Symbols:   32888
+  CStrings:  26016
 
Symbols:
- -[RTPersistenceMigrator __executeVacuumStepWithStore:coordinator:delegate:vacuumDate:]
- -[RTPersistenceMigrator didVacuumStore]
- -[RTPersistenceStore performVacuumWithCoordinator:error:]
- OBJC_IVAR_$_RTPersistenceMigrator._didVacuumStore
- _RTPersistentStoreMetadataLastVacuumDateKey
- _kRTPersistentStoreVacuumTimeInterval
- _objc_msgSend$__executeVacuumStepWithStore:coordinator:delegate:vacuumDate:
- _objc_msgSend$didVacuumStore
- _objc_msgSend$performVacuumWithCoordinator:error:
Functions:
~ -[RTPersistenceMigrator initWithStore:modelProvider:delegate:] : 456 -> 452
~ -[RTPersistenceMigrator _executeVacuumStep] : 2044 -> 1468
- -[RTPersistenceMigrator __executeVacuumStepWithStore:coordinator:delegate:vacuumDate:]
~ -[RTPersistenceMigrator _executeRecreateStep] : 1160 -> 1104
- -[RTPersistenceMigrator didVacuumStore]
~ -[RTPersistenceDriver(Metrics) persistenceDriver:persistenceMigrator:didFinishMigratingStore:withModelProvider:] : 1060 -> 1000
- -[RTPersistenceStore performVacuumWithCoordinator:error:]
CStrings:
+ "21:03:12"
+ "3"
+ "Jul 15 2025"
- "-[RTPersistenceMigrator __executeVacuumStepWithStore:coordinator:delegate:vacuumDate:]"
- "-[RTPersistenceStore performVacuumWithCoordinator:error:]"
- "09:00:31"
- "Invalid parameter not satisfying: vacuumDate"
- "Jun  3 2025"
- "Q48@0:8@16@24@32@40"
- "RTPersistentStoreMetadataLastVacuumDateKey"
- "TB,R,V_didVacuumStore"
- "__executeVacuumStepWithStore:coordinator:delegate:vacuumDate:"
- "_didVacuumStore"
- "didVacuumStore"
- "performVacuumWithCoordinator:error:"
- "vacuum duration, %lf"
- "vacuuming store %@"
```
