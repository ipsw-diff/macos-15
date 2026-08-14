## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-100150.120.1.0.0
-  __TEXT.__text: 0xb6a50
+100150.120.2.0.0
+  __TEXT.__text: 0xb6a68
   __TEXT.__auth_stubs: 0x22b0
   __TEXT.__objc_methlist: 0x150
   __TEXT.__cstring: 0xebf0
Functions:
~ ___IOUSBDeviceDescriptionCreateFromFile : 452 -> 476
CStrings:
+ "OSKEXT_BUILD_DATE 21:45:16 Apr 13 2025"
- "OSKEXT_BUILD_DATE 18:18:29 Apr  6 2025"
```
