## Home

> `/System/iOSSupport/System/Library/PrivateFrameworks/Home.framework/Versions/A/Home`

```diff

-1026.6.29.4.2
-  __TEXT.__text: 0x341d40
+1026.7.14.0.0
+  __TEXT.__text: 0x342948
   __TEXT.__auth_stubs: 0x3020
-  __TEXT.__objc_methlist: 0x2a4ec
-  __TEXT.__const: 0x2948
-  __TEXT.__cstring: 0x327b2
+  __TEXT.__objc_methlist: 0x2a51c
+  __TEXT.__const: 0x2e98
+  __TEXT.__cstring: 0x32817
   __TEXT.__swift5_typeref: 0x1aca
   __TEXT.__swift5_reflstr: 0x654
   __TEXT.__swift5_assocty: 0x270

   __TEXT.__swift5_proto: 0x174
   __TEXT.__swift5_types: 0xc0
   __TEXT.__swift5_capture: 0x7d0
-  __TEXT.__oslogstring: 0x19956
+  __TEXT.__oslogstring: 0x19bd3
   __TEXT.__swift_as_entry: 0x158
   __TEXT.__swift_as_ret: 0x168
   __TEXT.__swift5_protos: 0x34

   __TEXT.__unwind_info: 0xcd00
   __TEXT.__eh_frame: 0x5328
   __TEXT.__objc_classname: 0x682a
-  __TEXT.__objc_methname: 0x5578b
+  __TEXT.__objc_methname: 0x557f7
   __TEXT.__objc_methtype: 0x70eb
-  __TEXT.__objc_stubs: 0x37940
-  __DATA_CONST.__got: 0x2c20
+  __TEXT.__objc_stubs: 0x37960
+  __DATA_CONST.__got: 0x2c30
   __DATA_CONST.__const: 0x10920
   __DATA_CONST.__objc_classlist: 0x1738
   __DATA_CONST.__objc_catlist: 0x400
   __DATA_CONST.__objc_protolist: 0x7d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x11a98
+  __DATA_CONST.__objc_selrefs: 0x11ab8
   __DATA_CONST.__objc_protorefs: 0x2f0
   __DATA_CONST.__objc_superrefs: 0x12d0
   __DATA_CONST.__objc_arraydata: 0x370
   __AUTH_CONST.__auth_got: 0x1820
   __AUTH_CONST.__const: 0xd3c8
   __AUTH_CONST.__cfstring: 0x259a0
-  __AUTH_CONST.__objc_const: 0x489d0
+  __AUTH_CONST.__objc_const: 0x489f0
   __AUTH_CONST.__objc_intobj: 0x2100
   __AUTH_CONST.__objc_doubleobj: 0x170
   __AUTH_CONST.__objc_arrayobj: 0x258
   __AUTH_CONST.__objc_floatobj: 0x50
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0xf7a0
-  __AUTH.__data: 0xa90
+  __AUTH.__data: 0xa88
   __DATA.__objc_ivar: 0x2104
-  __DATA.__data: 0x6d08
+  __DATA.__data: 0x67c0
   __DATA.__objc_stublist: 0x10
   __DATA.__bss: 0x3d78
   __DATA.__common: 0x110

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 19000
-  Symbols:   35991
-  CStrings:  21878
+  Functions: 19002
+  Symbols:   35993
+  CStrings:  21887
 
Symbols:
+ -[HFItemManager(HomeKitDelegates) accessory:didUpdateHH1EOLEnabled:]
+ -[HMAccessory(HFMediaAdditions) hf_isHH1EOLEnabled]
+ GCC_except_table104
+ GCC_except_table180
+ _objc_msgSend$isHH1EOLEnabled
- GCC_except_table103
- GCC_except_table178
- GCC_except_table87
CStrings:
+ "%@ (%{public}@): Failed to update face recognition enabled(%d) for person manager %@ with error %@"
+ "%s Matter snapshot changed, but does not match current home. Snapshot: %{public}s, current home controller ID: %{public}s, current home ID: %{public}s"
+ "%s Triggering item update because Matter snapshot changed. snapshot: (%{public}s) items: %{public}s devices: (%{public}s)"
+ "(%s) Among %@, wallet key device states of compatible paired watches are %@ | uniqueIdentifier = %{public}@"
+ "(%s) Returning %{BOOL}d because current device and paired watches are not wallet key compatible | uniqueIdentifier = %{public}@"
+ "(%s) Returning NO for wallet key compatibility for current device because of %@ | uniqueIdentifier = %{public}@"
+ "(%s) accessory %@ (uniqueIdentifier: %{public}@) | hh1EOLEnabled = %{BOOL}d"
+ "-[HFItemManager(HomeKitDelegates) accessory:didUpdateHH1EOLEnabled:]"
+ "Home %@ (%{public}@) does not have any resident device, which is required for Face Recognition feature"
+ "No cameras in home %@ (%{public}@) support recording"
+ "Successfully turned on has onboarded for access code flag for home %@ (%{public}@)"
+ "When turning on has onboarded for access code flag for home %@ (%{public}@), error occurred: %@"
+ "[hf_hasReachableResidents] Total residents: %lu - Reachable: %@ | home = %@ (%{public}@)"
+ "[hf_shouldBlockCurrentUserFromHomeForRoarUpgrade] User is blocked from home. HMHomeAccessNotAllowedReasonCode %lu | home = %@ (%{public}@)"
+ "accessory:didUpdateHH1EOLEnabled:"
+ "hf_isHH1EOLEnabled"
+ "isHH1EOLEnabled"
+ "registerMatterDelegates()"
+ "residentDevice:didUpdateHH1EOLEnabled:"
- "%@: Failed to update face recognition enabled(%d) for person manager %@ with error %@"
- "%@:%@ Total residents: %lu - Reachable: %@"
- "(%@:%s) Among %@, wallet key device states of compatible paired watches are %@"
- "(%@:%s) Returning %{BOOL}d because current device and paired watches are not wallet key compatible"
- "(%@:%s) Returning NO for wallet key compatibility for current device because of %@"
- "Home %@ does not have any resident device, which is required for Face Recognition feature"
- "No cameras in home %@ support recording"
- "Successfully turned on has onboarded for access code flag for home %@"
- "User is blocked from home. HMHomeAccessNotAllowedReasonCode %lu"
- "When turning on has onboarded for access code flag for home %@, error occurred: %@"
```
