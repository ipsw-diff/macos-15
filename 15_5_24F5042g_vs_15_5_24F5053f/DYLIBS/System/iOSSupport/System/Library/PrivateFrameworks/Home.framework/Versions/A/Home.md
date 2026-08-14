## Home

> `/System/iOSSupport/System/Library/PrivateFrameworks/Home.framework/Versions/A/Home`

```diff

-1026.6.20.0.0
-  __TEXT.__text: 0x341f98
-  __TEXT.__auth_stubs: 0x3030
-  __TEXT.__objc_methlist: 0x2a4bc
+1026.6.26.0.0
+  __TEXT.__text: 0x341cf8
+  __TEXT.__auth_stubs: 0x3020
+  __TEXT.__objc_methlist: 0x2a4ec
   __TEXT.__const: 0x2948
-  __TEXT.__cstring: 0x32726
-  __TEXT.__swift5_typeref: 0x1ac0
-  __TEXT.__swift5_reflstr: 0x674
+  __TEXT.__cstring: 0x327b2
+  __TEXT.__swift5_typeref: 0x1aca
+  __TEXT.__swift5_reflstr: 0x654
   __TEXT.__swift5_assocty: 0x270
-  __TEXT.__constg_swiftt: 0x12fc
+  __TEXT.__constg_swiftt: 0x12e4
   __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_fieldmd: 0x798
+  __TEXT.__swift5_fieldmd: 0x78c
   __TEXT.__swift5_proto: 0x174
   __TEXT.__swift5_types: 0xc0
   __TEXT.__swift5_capture: 0x7d0
-  __TEXT.__oslogstring: 0x1992f
+  __TEXT.__oslogstring: 0x19946
   __TEXT.__swift_as_entry: 0x158
   __TEXT.__swift_as_ret: 0x168
   __TEXT.__swift5_protos: 0x34
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__gcc_except_tab: 0x54e4
   __TEXT.__ustring: 0x88
-  __TEXT.__unwind_info: 0xccf8
+  __TEXT.__unwind_info: 0xcd00
   __TEXT.__eh_frame: 0x5328
   __TEXT.__objc_classname: 0x682a
-  __TEXT.__objc_methname: 0x55785
+  __TEXT.__objc_methname: 0x5578b
   __TEXT.__objc_methtype: 0x70eb
   __TEXT.__objc_stubs: 0x37940
   __DATA_CONST.__got: 0x2c20
-  __DATA_CONST.__const: 0x10918
-  __DATA_CONST.__objc_classlist: 0x1730
+  __DATA_CONST.__const: 0x10920
+  __DATA_CONST.__objc_classlist: 0x1738
   __DATA_CONST.__objc_catlist: 0x400
   __DATA_CONST.__objc_protolist: 0x7d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x11a90
+  __DATA_CONST.__objc_selrefs: 0x11a98
   __DATA_CONST.__objc_protorefs: 0x2f0
   __DATA_CONST.__objc_superrefs: 0x12d0
   __DATA_CONST.__objc_arraydata: 0x370
-  __AUTH_CONST.__auth_got: 0x1828
+  __AUTH_CONST.__auth_got: 0x1820
   __AUTH_CONST.__const: 0xd3c8
-  __AUTH_CONST.__cfstring: 0x25980
-  __AUTH_CONST.__objc_const: 0x489c8
+  __AUTH_CONST.__cfstring: 0x259a0
+  __AUTH_CONST.__objc_const: 0x489d0
   __AUTH_CONST.__objc_intobj: 0x2100
   __AUTH_CONST.__objc_doubleobj: 0x170
   __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_floatobj: 0x50
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH.__objc_data: 0xf750
-  __AUTH.__data: 0xa60
-  __DATA.__objc_ivar: 0x2108
-  __DATA.__data: 0x6d28
+  __AUTH.__objc_data: 0xf7a0
+  __AUTH.__data: 0xa90
+  __DATA.__objc_ivar: 0x2104
+  __DATA.__data: 0x6d08
   __DATA.__objc_stublist: 0x10
   __DATA.__bss: 0x3d78
   __DATA.__common: 0x110

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 18991
-  Symbols:   35983
-  CStrings:  21877
+  Functions: 19000
+  Symbols:   35991
+  CStrings:  21878
 
Symbols:
+ -[HFUserNotificationServiceTopic initWithServiceTypes:accessoryCategoryTypes:topicNameLocalizationKey:accessoryType:]
+ -[HFUserNotificationServiceTopic initWithTopicNameLocalizationKey:accessoryType:]
+ -[HMHome(Additions) hf_shouldPostHH2UgradeRequired]
+ OBJC_IVAR_$_HFUserNotificationServiceTopic._accessoryType
+ _HFForceHomeHubMigrationBannerVisible
+ _HFForceHomeHubMigrationBannerVisibleKey
+ _OBJC_CLASS_$_HFMatterAccessoryLikeItemProvider
+ _OBJC_METACLASS_$_HFMatterAccessoryLikeItemProvider
+ __CLASS_METHODS_HFMatterAccessoryLikeItemProvider
+ __DATA_HFMatterAccessoryLikeItemProvider
+ __INSTANCE_METHODS_HFMatterAccessoryLikeItemProvider
+ __METACLASS_DATA_HFMatterAccessoryLikeItemProvider
+ _objc_msgSend$initWithServiceTypes:accessoryCategoryTypes:topicNameLocalizationKey:accessoryType:
+ _objc_msgSend$initWithTopicNameLocalizationKey:accessoryType:
+ _symbolic _____SgXw 4Home31MatterAccessoryLikeItemProviderC
- -[HFUserNotificationServiceTopic initWithServiceTypes:accessoryCategoryTypes:topicNameLocalizationKey:iconForAccessoryType:]
- -[HFUserNotificationServiceTopic setIsMatter:]
- -[HMHome(Additions) hf_shouldPostHomeUgradeRequired]
- OBJC_IVAR_$_HFUserNotificationServiceTopic._iconForAccessoryType
- OBJC_IVAR_$_HFUserNotificationServiceTopic._isMatter
- _objc_msgSend$initWithServiceTypes:accessoryCategoryTypes:topicNameLocalizationKey:iconForAccessoryType:
- _objc_msgSend$setIsMatter:
CStrings:
+ "(%s) shouldPostHH2UpgradeRequired = %{BOOL}d"
+ "-[HMHome(Additions) hf_shouldPostHH2UgradeRequired]"
+ "Accessory %@ is non visible, so skipping this service entirely"
+ "Adding appliance HFUserNotificationServiceTopic. Found %lu accessories: %@"
+ "HFForceHomeHubMigrationBannerVisibleKey"
+ "HFMatterAccessoryLikeItemProvider"
+ "hf_shouldPostHH2UgradeRequired"
+ "initWithServiceTypes:accessoryCategoryTypes:topicNameLocalizationKey:accessoryType:"
+ "initWithTopicNameLocalizationKey:accessoryType:"
+ "itemProviderInHome:inRoom:"
- "%{public}@: Failed to get device type, falling back to HMAccessory value %{public}u"
- "%{public}@: Failed to get matter device on accessory %@"
- "TB,N,V_isMatter"
- "_iconForAccessoryType"
- "_isMatter"
- "_primaryDeviceType"
- "hf_shouldPostHomeUgradeRequired"
- "initWithServiceTypes:accessoryCategoryTypes:topicNameLocalizationKey:iconForAccessoryType:"
- "setIsMatter:"
```
