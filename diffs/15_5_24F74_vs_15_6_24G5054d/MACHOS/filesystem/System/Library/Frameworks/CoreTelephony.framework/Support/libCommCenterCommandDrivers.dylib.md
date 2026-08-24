## libCommCenterCommandDrivers.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterCommandDrivers.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__cfstring`

```diff

-12409.0.0.0.0
-  __TEXT.__text: 0x333d0
-  __TEXT.__auth_stubs: 0xf30
+12412.0.0.0.0
+  __TEXT.__text: 0x339ac
+  __TEXT.__auth_stubs: 0xf50
   __TEXT.__init_offsets: 0x8
-  __TEXT.__const: 0x4554
-  __TEXT.__gcc_except_tab: 0x49c0
-  __TEXT.__oslogstring: 0x1753
-  __TEXT.__cstring: 0x124f
-  __TEXT.__unwind_info: 0x1708
+  __TEXT.__const: 0x4574
+  __TEXT.__gcc_except_tab: 0x49cc
+  __TEXT.__oslogstring: 0x1a6d
+  __TEXT.__cstring: 0x133b
+  __TEXT.__unwind_info: 0x1710
   __DATA_CONST.__got: 0x200
   __DATA_CONST.__const: 0x690
-  __AUTH_CONST.__auth_got: 0x7a0
-  __AUTH_CONST.__const: 0x50e0
+  __AUTH_CONST.__auth_got: 0x7b0
+  __AUTH_CONST.__const: 0x50f0
   __AUTH_CONST.__cfstring: 0x80
   __DATA.__bss: 0x110
   __DATA.__common: 0x248

   - /usr/lib/libTelephonyUtilDynamic.dylib
   - /usr/lib/libc++.1.dylib
   Functions: 1305
-  Symbols:   2507
-  CStrings:  399
+  Symbols:   2509
+  CStrings:  414
 
Symbols:
+ __Z8asString16DataCodingScheme
+ __os_log_debug_impl
+ _syslog$DARWIN_EXTSN
- ___TUAssertTrigger
Functions:
~ __ZN3awd8asStringENS_5AppIDE : 60 -> 88
~ __ZN3awd8asStringENS_11ClientStateE : 60 -> 88
~ __ZN3awd8asStringENS_11PayloadTypeE : 60 -> 88
~ __ZN3awdlsERN3ctu16LogMessageBufferENSt3__110shared_ptrINS_10AppContextEEE : 1488 -> 1456
~ __ZN20DesenseCommandDriver23addSingleFrequencyToMapEyjjPNSt3__13mapIy11DesenseFreqNS0_4lessIyEENS0_9allocatorINS0_4pairIKyS2_EEEEEE : 360 -> 588
~ __ZNK22BasebandSettingsDriver22getFileTransferTimeoutEv : 44 -> 208
~ __ZN17CallCommandDriver20shouldMTCallContinueEbRK8CallInfo : 1436 -> 1748
~ __ZNK10subscriber16SimCommandDriver35handleSimConfigurationMismatch_syncERKNSt3__16vectorIhNS1_9allocatorIhEEEES7_ : 1040 -> 1120
~ __ZNK10subscriber16SimCommandDriver27getVinylCapabilitiesFromATRERKNSt3__16vectorIhNS1_9allocatorIhEEEE : 596 -> 776
~ __ZN10subscriber16SimCommandDriver11parseEapSimEPKN3ctu11OsLogLoggerENS_7SimTypeERKNSt3__16vectorIhNS6_9allocatorIhEEEERNS6_3mapINS_8AuthInfoESA_NS6_4lessISE_EENS8_INS6_4pairIKSE_SA_EEEEEE : 1020 -> 1180
~ __Z18decodeOperatorNamePKN3ctu11OsLogLoggerERKNSt3__16vectorIhNS3_9allocatorIhEEEE16DataCodingScheme : 272 -> 440
~ __ZNK22PhonebookCommandDriver9swapPairsERNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 216 -> 368
~ __ZN22PhonebookCommandDriver18getVectorForStringERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEb : 852 -> 856
CStrings:
+ "#D Adding Frequency: %llu, Bandwidth: %u, Priority: %d"
+ "#D Carrier has CarrierAllowsRingingMultipleDevices set to false or doesn't have that key defined"
+ "#D Carrier has CarrierAllowsRingingMultipleDevices set to true!"
+ "#D Decoding PLMN name of %lu bytes using coding scheme %s"
+ "#D Duplicated frequency (%llu), keeping higher bandwidth (%u)"
+ "#D No historical bytes, not capable"
+ "#D No report required"
+ "#D Queried hardware model config (%d) and suffix (%s)"
+ "#D SIM authenticate success; reporting result on card %s"
+ "#D Swapped the characters: %s"
+ "#D Vinyl capabilities byte: 0x%02x"
+ "#D We are on an Data-Only device AND we are on an external build"
+ "#D isInternalBuild: %d, voiceCallsAllowedRightNow (Buddy): %d, dataDeviceWithAllowsRingingMultipleDevices: %d, dataOnlyDevice: %d, Thumper Secondar device: %d"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreTelephony/CommCenter/CommCenterCommandDrivers/Awd/AwdCommandDriver.cpp"
+ "Assertion failure: ( %s ), in file %s, line: %d"
```
