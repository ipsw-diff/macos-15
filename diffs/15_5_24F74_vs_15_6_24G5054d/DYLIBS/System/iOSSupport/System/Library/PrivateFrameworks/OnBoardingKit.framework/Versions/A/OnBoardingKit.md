## OnBoardingKit

> `/System/iOSSupport/System/Library/PrivateFrameworks/OnBoardingKit.framework/Versions/A/OnBoardingKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-3941.4.0.0.0
-  __TEXT.__text: 0x30ae4
+3941.5.0.0.0
+  __TEXT.__text: 0x30c28
   __TEXT.__auth_stubs: 0x6f0
   __TEXT.__objc_methlist: 0x47cc
   __TEXT.__const: 0x566

   __TEXT.__objc_classname: 0x8d6
   __TEXT.__objc_methname: 0xbd83
   __TEXT.__objc_methtype: 0x149f
-  __TEXT.__objc_stubs: 0x8aa0
+  __TEXT.__objc_stubs: 0x8a80
   __DATA_CONST.__got: 0x3e0
   __DATA_CONST.__const: 0x628
   __DATA_CONST.__objc_classlist: 0x288

   __DATA_CONST.__objc_arraydata: 0xa0
   __AUTH_CONST.__auth_got: 0x388
   __AUTH_CONST.__const: 0x180
-  __AUTH_CONST.__cfstring: 0x1e40
+  __AUTH_CONST.__cfstring: 0x1e60
   __AUTH_CONST.__objc_const: 0x9d20
   __AUTH_CONST.__objc_intobj: 0x1e0
   __AUTH_CONST.__objc_arrayobj: 0x48

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 1384
-  Symbols:   3830
-  CStrings:  2608
+  Symbols:   3829
+  CStrings:  2609
 
Symbols:
- _objc_msgSend$addAccessoryButton:
Functions:
~ -[OBTextWelcomeController addSectionWithHeader:content:accessoryButton:] : 208 -> 256
~ +[OBPrivacyFlow _splashPlistFromBundle:forContentName:] : 252 -> 380
~ -[OBPrivacyFlow _splashLocalizedStringForKey:language:preferredDeviceType:] : 208 -> 356
CStrings:
+ "-seed"
```
