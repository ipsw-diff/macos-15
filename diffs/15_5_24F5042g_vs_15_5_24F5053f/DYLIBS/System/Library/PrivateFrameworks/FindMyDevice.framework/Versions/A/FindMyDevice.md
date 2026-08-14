## FindMyDevice

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/Versions/A/FindMyDevice`

```diff

-438.25.2.11.6
-  __TEXT.__text: 0x12e80
+438.25.2.11.7
+  __TEXT.__text: 0x12ea8
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__objc_methlist: 0x1654
-  __TEXT.__cstring: 0x3577
+  __TEXT.__cstring: 0x3576
   __TEXT.__const: 0xb0
   __TEXT.__gcc_except_tab: 0x2c4
   __TEXT.__oslogstring: 0x1126
   __TEXT.__unwind_info: 0x4c0
   __TEXT.__objc_classname: 0x3df
-  __TEXT.__objc_methname: 0x3145
-  __TEXT.__objc_methtype: 0xa1f
+  __TEXT.__objc_methname: 0x314f
+  __TEXT.__objc_methtype: 0xa11
   __TEXT.__objc_stubs: 0x22c0
   __DATA_CONST.__got: 0x100
   __DATA_CONST.__const: 0xc40

   - /usr/lib/libobjc.A.dylib
   Functions: 576
   Symbols:   1754
-  CStrings:  1295
+  CStrings:  1294
 
Symbols:
+ -[FMDAccessoryIdentifier(FMDSupportedAccessory) initWithDeviceVendor:deviceProductId:]
- -[FMDAccessoryIdentifier(FMDSupportedAccessory) initWithVendorID:productID:]
Functions:
~ -[FMDAccessoryIdentifier(FMDSupportedAccessory) initWithVendorID:productID:] -> -[FMDAccessoryIdentifier(FMDSupportedAccessory) initWithDeviceVendor:deviceProductId:] : 148 -> 188
CStrings:
+ "%@_%@"
+ "initWithDeviceVendor:deviceProductId:"
- "%hu_%u"
- "@24@0:8S16I20"
- "initWithVendorID:productID:"
```
