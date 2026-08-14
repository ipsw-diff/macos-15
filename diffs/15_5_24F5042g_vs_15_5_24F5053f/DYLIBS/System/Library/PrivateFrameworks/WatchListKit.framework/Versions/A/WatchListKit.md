## WatchListKit

> `/System/Library/PrivateFrameworks/WatchListKit.framework/Versions/A/WatchListKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-850.50.1.0.0
+850.50.2.0.0
   __TEXT.__text: 0x66af0
   __TEXT.__auth_stubs: 0x630
-  __TEXT.__objc_methlist: 0x6a64
+  __TEXT.__objc_methlist: 0x6a7c
   __TEXT.__const: 0x19c
   __TEXT.__cstring: 0x7100
   __TEXT.__oslogstring: 0x563f
   __TEXT.__gcc_except_tab: 0xf5c
   __TEXT.__unwind_info: 0x1bc0
   __TEXT.__objc_classname: 0x125a
-  __TEXT.__objc_methname: 0xed2b
-  __TEXT.__objc_methtype: 0x19a6
-  __TEXT.__objc_stubs: 0x8ce0
+  __TEXT.__objc_methname: 0xed96
+  __TEXT.__objc_methtype: 0x19a9
+  __TEXT.__objc_stubs: 0x8d00
   __DATA_CONST.__got: 0x808
   __DATA_CONST.__const: 0xc18
   __DATA_CONST.__objc_classlist: 0x548
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3468
+  __DATA_CONST.__objc_selrefs: 0x3478
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x498
   __DATA_CONST.__objc_arraydata: 0x618
   __AUTH_CONST.__auth_got: 0x328
   __AUTH_CONST.__const: 0x27e0
   __AUTH_CONST.__cfstring: 0x9b40
-  __AUTH_CONST.__objc_const: 0x10e90
+  __AUTH_CONST.__objc_const: 0x10ec0
   __AUTH_CONST.__objc_intobj: 0x378
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH.__objc_data: 0x34d0
-  __DATA.__objc_ivar: 0x9e4
+  __DATA.__objc_ivar: 0x9e8
   __DATA.__data: 0x620
   __DATA.__bss: 0x4d0
   __DATA.__common: 0x5

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2665
-  Symbols:   6528
-  CStrings:  4602
+  Functions: 2667
+  Symbols:   6532
+  CStrings:  4606
 
Symbols:
+ +[NSURL(WLKAdditions) wlk_URLWithServerConfig:endpoint:relativeToBaseURL:queryParameters:suppressParameterEncoding:ignoreUserLocation:]
+ -[WLKURLRequestProperties ignoreUserLocation]
+ -[WLKURLRequestProperties setIgnoreUserLocation:]
+ OBJC_IVAR_$_WLKURLRequestProperties._ignoreUserLocation
+ _objc_msgSend$ignoreUserLocation
+ _objc_msgSend$wlk_URLWithServerConfig:endpoint:relativeToBaseURL:queryParameters:suppressParameterEncoding:ignoreUserLocation:
- +[NSURL(WLKAdditions) wlk_URLWithServerConfig:endpoint:relativeToBaseURL:queryParameters:suppressParameterEncoding:]
- _objc_msgSend$wlk_URLWithServerConfig:endpoint:relativeToBaseURL:queryParameters:suppressParameterEncoding:
CStrings:
+ "@52@0:8@16@24B32@36B44B48"
+ "TB,N,V_ignoreUserLocation"
+ "_ignoreUserLocation"
+ "ignoreUserLocation"
+ "setIgnoreUserLocation:"
+ "wlk_URLWithServerConfig:endpoint:relativeToBaseURL:queryParameters:suppressParameterEncoding:ignoreUserLocation:"
- "@48@0:8@16@24B32@36B44"
- "wlk_URLWithServerConfig:endpoint:relativeToBaseURL:queryParameters:suppressParameterEncoding:"
```
