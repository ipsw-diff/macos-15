## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-8.6.7.0.0
-  __TEXT.__text: 0x6fdbec
+8.6.8.0.0
+  __TEXT.__text: 0x6fe238
   __TEXT.__auth_stubs: 0x3dc0
-  __TEXT.__objc_methlist: 0x202e4
+  __TEXT.__objc_methlist: 0x2033c
   __TEXT.__const: 0xaa65c
   __TEXT.__dlopen_cstrs: 0x705
-  __TEXT.__cstring: 0x241bf
+  __TEXT.__cstring: 0x2439f
   __TEXT.__swift5_typeref: 0x3b0f
   __TEXT.__swift5_reflstr: 0x1c78
   __TEXT.__swift5_assocty: 0x900

   __TEXT.__swift5_capture: 0x1cac
   __TEXT.__swift5_mpenum: 0x48
   __TEXT.__swift5_protos: 0x80
-  __TEXT.__oslogstring: 0x2b619
-  __TEXT.__gcc_except_tab: 0x7c64
+  __TEXT.__oslogstring: 0x2b6a5
+  __TEXT.__gcc_except_tab: 0x7c58
   __TEXT.__ustring: 0x210
-  __TEXT.__unwind_info: 0xcc78
+  __TEXT.__unwind_info: 0xcc98
   __TEXT.__eh_frame: 0xac3c
   __TEXT.__objc_classname: 0x3bcd
-  __TEXT.__objc_methname: 0x3f906
+  __TEXT.__objc_methname: 0x3fa00
   __TEXT.__objc_methtype: 0x71fc
-  __TEXT.__objc_stubs: 0x2b960
+  __TEXT.__objc_stubs: 0x2ba40
   __DATA_CONST.__got: 0x1698
   __DATA_CONST.__const: 0x5068
   __DATA_CONST.__objc_classlist: 0x1278
   __DATA_CONST.__objc_catlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x388
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe270
+  __DATA_CONST.__objc_selrefs: 0xe2a8
   __DATA_CONST.__objc_protorefs: 0x1b0
   __DATA_CONST.__objc_superrefs: 0xc38
-  __DATA_CONST.__objc_arraydata: 0x398
+  __DATA_CONST.__objc_arraydata: 0x408
   __AUTH_CONST.__auth_got: 0x1ef8
-  __AUTH_CONST.__const: 0x373a8
-  __AUTH_CONST.__cfstring: 0x20960
+  __AUTH_CONST.__const: 0x373c8
+  __AUTH_CONST.__cfstring: 0x20b40
   __AUTH_CONST.__objc_const: 0x37538
   __AUTH_CONST.__objc_intobj: 0xc30
-  __AUTH_CONST.__objc_arrayobj: 0x108
+  __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH.__objc_data: 0x6d70
   __AUTH.__data: 0x1ca0
   __DATA.__objc_ivar: 0x1df0
   __DATA.__data: 0x57f0
-  __DATA.__bss: 0xb360
+  __DATA.__bss: 0xb370
   __DATA.__common: 0x1574
   __DATA_DIRTY.__objc_data: 0x5d70
   __DATA_DIRTY.__data: 0x70

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 19460
-  Symbols:   27675
-  CStrings:  18560
+  Functions: 19469
+  Symbols:   27690
+  CStrings:  18584
 
Symbols:
+ +[AMSMetrics _defaultAccountClearingTopics]
+ -[AMSMetrics _cachedAccountClearingTopicsFromBag]
+ -[AMSMetrics _clearAccountForEventIfNeeded:]
+ -[AMSMetrics _topicsRequiringAccountClearing]
+ -[AMSMetrics enqueueEventWithoutAccountClearing:]
+ -[AMSMetrics enqueueEventsWithoutAccountClearing:]
+ -[AMSMetrics promiseForEnqueueingEvents:skipAccountClearing:]
+ ___43+[AMSMetrics _defaultAccountClearingTopics]_block_invoke
+ ___49-[AMSMetrics _cachedAccountClearingTopicsFromBag]_block_invoke
+ _objc_msgSend$_clearAccountForEventIfNeeded:
+ _objc_msgSend$_defaultAccountClearingTopics
+ _objc_msgSend$_topicsRequiringAccountClearing
+ _objc_msgSend$cachedValuesForKeys:observationToken:updateHandler:
+ _objc_msgSend$enqueueEventsWithoutAccountClearing:
+ _objc_msgSend$promiseForEnqueueingEvents:skipAccountClearing:
+ _objc_msgSend$removeObserverWithToken:
- GCC_except_table62
CStrings:
+ "%{public}@: Bag values updated for account clearing topics to %@"
+ "%{public}@: [%{public}@] Clearing account for event with topic: %{public}@"
+ "<private>"
+ "_cachedAccountClearingTopicsFromBag"
+ "_clearAccountForEventIfNeeded:"
+ "_defaultAccountClearingTopics"
+ "_topicsRequiringAccountClearing"
+ "accountClearingTopics"
+ "enqueueEventWithoutAccountClearing:"
+ "enqueueEventsWithoutAccountClearing:"
+ "promiseForEnqueueingEvents:skipAccountClearing:"
+ "xp_ase_appstore/arcade_substate"
+ "xp_ase_appstore/billing_refunds"
+ "xp_ase_appstore/preorders"
+ "xp_ase_appstore/subscription_movement"
+ "xp_ase_messaging/appstore_experimentation"
+ "xp_ase_messaging/appstore_notifications"
+ "xp_ase_payments/appstore_payments_ue"
+ "xp_ase_payments/appstore_redeem_ue"
+ "xp_ase_payments/transient"
+ "xp_ase_personalization/appstore"
+ "xp_ase_subscriptions/commerce"
+ "xp_ase_subscriptions/movement"
+ "xp_ase_subscriptions/ue"
+ "xp_ase_transient/appstore_ue"
- "seed"
```
