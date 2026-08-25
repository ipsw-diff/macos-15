## AskPermission

> `/System/Library/PrivateFrameworks/AskPermission.framework/Versions/A/AskPermission`

```diff

-128.6.2.0.0
-  __TEXT.__text: 0x6f50
-  __TEXT.__auth_stubs: 0x280
+128.6.4.0.0
+  __TEXT.__text: 0x7b70
+  __TEXT.__auth_stubs: 0x2a0
   __TEXT.__objc_methlist: 0xa1c
   __TEXT.__const: 0x70
   __TEXT.__gcc_except_tab: 0x348
-  __TEXT.__cstring: 0x5f6
-  __TEXT.__oslogstring: 0x878
-  __TEXT.__unwind_info: 0x2a0
+  __TEXT.__cstring: 0x60b
+  __TEXT.__oslogstring: 0x981
+  __TEXT.__unwind_info: 0x290
   __TEXT.__objc_classname: 0x192
   __TEXT.__objc_methname: 0x1905
   __TEXT.__objc_methtype: 0x5fc

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA_CONST.__objc_arraydata: 0x10
-  __AUTH_CONST.__auth_got: 0x150
+  __AUTH_CONST.__auth_got: 0x160
   __AUTH_CONST.__const: 0x2e0
-  __AUTH_CONST.__cfstring: 0xae0
+  __AUTH_CONST.__cfstring: 0xb20
   __AUTH_CONST.__objc_const: 0x1168
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_arrayobj: 0x18

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 190
-  Symbols:   648
-  CStrings:  504
+  Symbols:   650
+  CStrings:  511
 
Symbols:
+ _AMSLogKey
+ _NSStringFromSelector
+ ___block_descriptor_56_e8_32s_e42_"AMSPromise"24?0"NSString"8"NSError"16l
+ ___block_descriptor_56_e8_32s_e59_"AMSPromise"24?0"AMSMetricsIdentifierStore"8"NSError"16l
+ ___block_descriptor_64_e8_32s40s_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
- ___block_descriptor_48_e8_32s40s_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
- ___block_descriptor_48_e8_32s_e42_"AMSPromise"24?0"NSString"8"NSError"16l
- ___block_descriptor_48_e8_32s_e59_"AMSPromise"24?0"AMSMetricsIdentifierStore"8"NSError"16l
Functions:
~ +[APMetricsEvent metricsEventWithAccount:request:] : 576 -> 1600
~ ___50+[APMetricsEvent metricsEventWithAccount:request:]_block_invoke : 500 -> 1356
~ +[APMetricsEvent nonIdentifiableMetricsFieldsForAccount:] : 384 -> 844
~ ___57+[APMetricsEvent nonIdentifiableMetricsFieldsForAccount:]_block_invoke : 704 -> 1108
~ __57+[APMetricsEvent nonIdentifiableMetricsFieldsForAccount:]_block_invoke.54 -> __57+[APMetricsEvent nonIdentifiableMetricsFieldsForAccount:]_block_invoke.61 : 844 -> 1204
CStrings:
+ "%@: %@ "
+ "%@: [%@] %@ "
+ "%{public}@Creating metrics event. Account: %{public}@ | Request: %{public}@"
+ "%{public}@Error loading Metrics Store for userID: %@"
+ "%{public}@Error loading Metrics clientID: %@"
+ "%{public}@Error obtaining metrics fields: %{public}@"
+ "%{public}@Generating metrics fields for account: %{public}@"
+ "%{public}@LOB is not App Store. Enqueueing standard metrics."
+ "%{public}@Loaded Metrics clientID: %@"
+ "%{public}@Loaded Metrics event fields: %@"
+ "%{public}@Obtained metrics fields: %{public}@"
+ "%{public}@Request is for App Store LOB."
- "%{public}@: Error loading Metrics Store for userID: %@"
- "%{public}@: Error loading Metrics clientID: %@"
- "%{public}@: LOB is not App Store. Enqueueing standard metrics."
- "%{public}@: Loaded Metrics clientID: %@"
- "%{public}@: Loaded Metrics event fields: %@"
```
