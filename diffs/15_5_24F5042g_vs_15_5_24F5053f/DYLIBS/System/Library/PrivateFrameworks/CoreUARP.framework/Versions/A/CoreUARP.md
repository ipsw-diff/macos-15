## CoreUARP

> `/System/Library/PrivateFrameworks/CoreUARP.framework/Versions/A/CoreUARP`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-1207.120.16.0.0
-  __TEXT.__text: 0x8e7c8
+1207.120.19.0.0
+  __TEXT.__text: 0x8f1b4
   __TEXT.__auth_stubs: 0x7e0
-  __TEXT.__objc_methlist: 0x8914
+  __TEXT.__objc_methlist: 0x899c
   __TEXT.__const: 0x230
-  __TEXT.__cstring: 0x71df
-  __TEXT.__oslogstring: 0x61f5
+  __TEXT.__cstring: 0x725e
+  __TEXT.__oslogstring: 0x6267
   __TEXT.__gcc_except_tab: 0x834
   __TEXT.__dlopen_cstrs: 0x10e
   __TEXT.__unwind_info: 0x2560
   __TEXT.__objc_classname: 0x18c4
-  __TEXT.__objc_methname: 0xdaf0
-  __TEXT.__objc_methtype: 0x3a45
-  __TEXT.__objc_stubs: 0x95a0
-  __DATA_CONST.__got: 0x740
-  __DATA_CONST.__const: 0x1730
+  __TEXT.__objc_methname: 0xdc9d
+  __TEXT.__objc_methtype: 0x3a57
+  __TEXT.__objc_stubs: 0x9660
+  __DATA_CONST.__got: 0x748
+  __DATA_CONST.__const: 0x1738
   __DATA_CONST.__objc_classlist: 0x688
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3010
+  __DATA_CONST.__objc_selrefs: 0x3060
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x678
   __AUTH_CONST.__auth_got: 0x400
   __AUTH_CONST.__const: 0x9c0
-  __AUTH_CONST.__cfstring: 0x6ee0
-  __AUTH_CONST.__objc_const: 0x11888
-  __AUTH_CONST.__objc_intobj: 0xc90
+  __AUTH_CONST.__cfstring: 0x6f00
+  __AUTH_CONST.__objc_const: 0x11958
+  __AUTH_CONST.__objc_intobj: 0xca8
   __AUTH.__objc_data: 0x4150
-  __DATA.__objc_ivar: 0xb94
+  __DATA.__objc_ivar: 0xba4
   __DATA.__data: 0x40d
   __DATA.__bss: 0x1b2b
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 3838
-  Symbols:   7733
-  CStrings:  4645
+  Functions: 3852
+  Symbols:   7763
+  CStrings:  4664
 
Symbols:
+ -[UARPAccessoryHardwareIPv4 .cxx_destruct]
+ -[UARPAccessoryHardwareIPv4 appleModelNumber]
+ -[UARPAccessoryHardwareIPv4 initWithAppleModelNumber:]
+ -[UARPAccessoryHardwareIPv6 .cxx_destruct]
+ -[UARPAccessoryHardwareIPv6 appleModelNumber]
+ -[UARPAccessoryHardwareIPv6 initWithAppleModelNumber:]
+ -[UARPDynamicAssetCmapMapping appendCmapEventsArray:]
+ -[UARPDynamicAssetCmapMapping initWithEventsArray:appleModelNumber:]
+ -[UARPDynamicAssetPersonalization tssRequest:error:authListed:]
+ -[UARPSuperBinaryMetaDataTable addTLV:keyValueString:tlvArray:]
+ -[UARPSupportedAccessory setSupportsAuthListingInternally:]
+ -[UARPSupportedAccessory supportsAuthListingInternally]
+ OBJC_IVAR_$_UARPAccessoryHardwareIPv4._appleModelNumber
+ OBJC_IVAR_$_UARPAccessoryHardwareIPv6._appleModelNumber
+ OBJC_IVAR_$_UARPSuperBinaryAssetPayload._vendorVersionString
+ OBJC_IVAR_$_UARPSupportedAccessory._supportsAuthListingInternally
+ UARPPersonalizationTSSRequestWithSigningServerAuthListed
+ _OBJC_CLASS_$_NSCharacterSet
+ _UARPPersonalizationTSSRequestWithSigningServerAuthListed
+ __OBJC_$_INSTANCE_VARIABLES_UARPAccessoryHardwareIPv4
+ __OBJC_$_INSTANCE_VARIABLES_UARPAccessoryHardwareIPv6
+ __OBJC_$_PROP_LIST_UARPAccessoryHardwareIPv4
+ __OBJC_$_PROP_LIST_UARPAccessoryHardwareIPv6
+ _kUARPStringMetadataDeviceVendorVersionStringFile
+ _objc_msgSend$addTLV:keyValueString:tlvArray:
+ _objc_msgSend$appendCmapEventsArray:
+ _objc_msgSend$initWithAppleModelNumber:
+ _objc_msgSend$initWithEventsArray:appleModelNumber:
+ _objc_msgSend$initWithString:relativeToURL:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
+ _objc_msgSend$supportsAuthListingInternally
+ _objc_msgSend$tssRequest:error:authListed:
+ _objc_msgSend$whitespaceAndNewlineCharacterSet
- _objc_msgSend$appendCmapEvents:
- _objc_msgSend$initWithEvents:appleModelNumber:
- _objc_msgSend$tssRequest:error:
CStrings:
+ "%s: Failed to read vendor version string from file with error %@"
+ "%s: Failed to send UARP Message on connected socket: %s %i"
+ "%s: Remove received IM4M asset from Rx list %@"
+ "-[UARPSuperBinaryMetaDataTable tlvArrayWithKey:keyValue:payloadsURL:error:]"
+ "B36@0:8@16^@24B32"
+ "CMAP Sections must be Array."
+ "IPv4, <AMN = %@>"
+ "IPv6, <AMN = %@>"
+ "T@\"NSString\",R,V_appleModelNumber"
+ "TB,V_supportsAuthListingInternally"
+ "Vendor Version String File"
+ "_supportsAuthListingInternally"
+ "_vendorVersionString"
+ "addTLV:keyValueString:tlvArray:"
+ "appendCmapEventsArray:"
+ "initWithAppleModelNumber:"
+ "initWithEventsArray:appleModelNumber:"
+ "initWithString:relativeToURL:"
+ "setSupportsAuthListingInternally:"
+ "stringByTrimmingCharactersInSet:"
+ "supportsAuthListingInternally"
+ "tssRequest:error:authListed:"
+ "whitespaceAndNewlineCharacterSet"
- "%s: Failed to send UARP Message on connected socket"
- "CMAP Sections must be Dictionary."
- "IPv4"
- "IPv6"
```
