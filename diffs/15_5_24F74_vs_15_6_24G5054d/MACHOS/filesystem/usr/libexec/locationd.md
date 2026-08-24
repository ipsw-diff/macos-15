## locationd

> `/usr/libexec/locationd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2964.0.4.0.0
-  __TEXT.__text: 0x77f54c
+2964.0.7.0.0
+  __TEXT.__text: 0x77f48c
   __TEXT.__auth_stubs: 0x3a30
   __TEXT.__objc_stubs: 0x104a0
   __TEXT.__init_offsets: 0x164
   __TEXT.__objc_methlist: 0x11898
   __TEXT.__const: 0x1b6a7
-  __TEXT.__oslogstring: 0xa6127
-  __TEXT.__cstring: 0x89f37
+  __TEXT.__oslogstring: 0xa62a7
+  __TEXT.__cstring: 0x8a34a
   __TEXT.__gcc_except_tab: 0x3d3a4
-  __TEXT.__objc_methname: 0x1dfe8
+  __TEXT.__objc_methname: 0x1e00a
   __TEXT.__objc_classname: 0x2f0e
   __TEXT.__objc_methtype: 0x10564
   __TEXT.__ustring: 0x346

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 28398
   Symbols:   1411
-  CStrings:  25379
+  CStrings:  25380
 
Functions:
~ sub_10011c9a0 : 1752 -> 1196
~ sub_10011e374 -> sub_10011e148 : 356 -> 712
~ sub_1003c8d44 -> sub_1003c8c7c : 764 -> 772
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.6.Internal.sdk/usr/local/include/boost/uuid/detail/random_provider_posix.ipp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.6.Internal.sdk/usr/local/include/boost/uuid/string_generator.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.6.Internal.sdk/usr/local/include/google/protobuf/repeated_field.h"
+ "15:46:01"
+ "Jun  3 2025"
+ "Jun  3 2025 15:46:43"
+ "checkLocationServicesStatusAndEnableExpensiveScansIfNecessary"
+ "{\"msg%{public}.0s\":\"Got a usable location\", \"location\":%{public, location:Encrypted_CLClientLocation}.*P}"
+ "{\"msg%{public}.0s\":\"location services was toggled on, and this service is authorized, doing an initial high-accuracy scan\", \"duration\":%{public}d}"
+ "{\"msg%{public}.0s\":\"location services was toggled on, but the service isn't authorized, so not scanning\", \"status\":%{public, location:CLAuthorizationStatus}lld}"
- "-[CLCountryTracker locationManager:didUpdateLocations:]"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.5.Internal.sdk/usr/local/include/boost/uuid/detail/random_provider_posix.ipp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.5.Internal.sdk/usr/local/include/boost/uuid/string_generator.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.5.Internal.sdk/usr/local/include/google/protobuf/repeated_field.h"
- "04:27:58"
- "Apr 19 2025"
- "Apr 19 2025 04:28:53"
- "Got a usable location <%{sensitive}+.8lf,%{sensitive}+.8lf>, acc %.2f, timestamp %.2f, lifespan %.2f, confidence %d"
- "checkLocationServicesStatus"
```
