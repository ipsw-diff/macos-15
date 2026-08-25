## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/Versions/A/CoreSpotlight`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-2333.56.0.0.0
+2333.57.1.0.0
   __TEXT.__text: 0xe0fec
   __TEXT.__auth_stubs: 0x1ee0
   __TEXT.__objc_methlist: 0xc868

   __DATA_CONST.__objc_arraydata: 0xb98
   __AUTH_CONST.__auth_got: 0xf80
   __AUTH_CONST.__const: 0x36e8
-  __AUTH_CONST.__cfstring: 0x11440
+  __AUTH_CONST.__cfstring: 0x11460
   __AUTH_CONST.__objc_const: 0x12648
   __AUTH_CONST.__objc_intobj: 0x768
   __AUTH_CONST.__objc_doubleobj: 0x90

   __AUTH.__objc_data: 0x1590
   __AUTH.__data: 0x3a0
   __DATA.__objc_ivar: 0xbb0
-  __DATA.__data: 0x9e8
+  __DATA.__data: 0x9f8
   __DATA.__bss: 0x1320
   __DATA.__common: 0xc
   __DATA_DIRTY.__objc_data: 0x1680

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 5541
-  Symbols:   11310
+  Symbols:   11312
   CStrings:  8845
 
Symbols:
+ _defaultIndexName
+ _mobileMailIndexName
CStrings:
+ "Failed to serialize the queryUnderstanding dictionary for mds query. Error: %@"
- "Failed to serialize the queryUnderstanding dictionary for MDS query. Error: %@"
```
