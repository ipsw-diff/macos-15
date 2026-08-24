## CoreAudio

> `/System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio`

```diff

-328.605.1.0.0
-  __TEXT.__text: 0x5d2760
+328.606.0.0.0
+  __TEXT.__text: 0x5d2848
   __TEXT.__auth_stubs: 0x2f70
   __TEXT.__objc_methlist: 0x1384
   __TEXT.__const: 0x503c0
   __TEXT.__dlopen_cstrs: 0xfb
-  __TEXT.__gcc_except_tab: 0x63850
+  __TEXT.__gcc_except_tab: 0x638bc
   __TEXT.__cstring: 0x301b4
   __TEXT.__oslogstring: 0x535e8
   __TEXT.__unwind_info: 0x1a860
Symbols:
+ __ZN26HALS_MetaDeviceDescription22AllocateClockSubDeviceEN10applesauce2CF9StringRefE
- __ZN26HALS_MetaDeviceDescription22AllocateClockSubDeviceEN2OS2CF6StringE
Functions:
~ ___ZN15HALS_MetaDevice15SetPropertyDataEjRK26AudioObjectPropertyAddressjPKvjS4_P11HALS_Client_block_invoke.163 : 1280 -> 1456
~ ___ZNK15HALS_MetaDevice15GetPropertyDataEjRK26AudioObjectPropertyAddressjRjPvjPKvP11HALS_Client_block_invoke.125 : 156 -> 308
~ __ZN26HALS_MetaDeviceDescription19UpdateSubDeviceListEP11HALS_Device : 1436 -> 1412
~ __ZN26HALS_MetaDeviceDescription22AllocateClockSubDeviceEN2OS2CF6StringE -> __ZN26HALS_MetaDeviceDescription22AllocateClockSubDeviceEN10applesauce2CF9StringRefE : 864 -> 792
```
