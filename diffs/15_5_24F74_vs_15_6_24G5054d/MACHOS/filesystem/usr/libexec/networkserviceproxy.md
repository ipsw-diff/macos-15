## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-868.120.4.0.0
-  __TEXT.__text: 0xc0dac
+868.140.2.0.0
+  __TEXT.__text: 0xc1070
   __TEXT.__auth_stubs: 0x1630
-  __TEXT.__objc_stubs: 0xba40
+  __TEXT.__objc_stubs: 0xba60
   __TEXT.__objc_methlist: 0x4c04
   __TEXT.__const: 0x340
   __TEXT.__dlopen_cstrs: 0x64
   __TEXT.__gcc_except_tab: 0x3c9c
   __TEXT.__oslogstring: 0xee04
-  __TEXT.__cstring: 0xc64c
-  __TEXT.__objc_methname: 0xe9b1
+  __TEXT.__cstring: 0xc675
+  __TEXT.__objc_methname: 0xe9fc
   __TEXT.__objc_classname: 0xc28
-  __TEXT.__objc_methtype: 0x2714
+  __TEXT.__objc_methtype: 0x2753
   __TEXT.__unwind_info: 0x1808
   __DATA_CONST.__auth_got: 0xb28
   __DATA_CONST.__got: 0x690
-  __DATA_CONST.__const: 0x2090
+  __DATA_CONST.__const: 0x20c0
   __DATA_CONST.__cfstring: 0x7b40
   __DATA_CONST.__objc_classlist: 0x2b0
   __DATA_CONST.__objc_catlist: 0x8

   __DATA_CONST.__objc_arrayobj: 0xd8
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0xa918
-  __DATA.__objc_selrefs: 0x34d0
+  __DATA.__objc_selrefs: 0x34d8
   __DATA.__objc_ivar: 0x97c
   __DATA.__objc_data: 0x1ae0
   __DATA.__data: 0xb58

   - /usr/lib/libnetwork.dylib
   - /usr/lib/libnetworkextension.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2090
+  Functions: 2092
   Symbols:   581
-  CStrings:  5679
+  CStrings:  5681
 
CStrings:
+ "-[NSPPrivacyTokenManager fetchPairedPrivateAccessTokensForChallenge:overrideAttester:configurationFetchDate:configurationETag:tokenKey:originNameKey:selectedOrigin:pairedChallenge:overridePairedAttester:pairedTokenKey:auditToken:bundleID:allowTools:systemTokenClient:accessToken:completionHandler:]"
+ "fetchDate:isWithinStart:end:etag:"
+ "fetchPairedPrivateAccessTokensForChallenge:overrideAttester:configurationFetchDate:configurationETag:tokenKey:originNameKey:selectedOrigin:pairedChallenge:overridePairedAttester:pairedTokenKey:auditToken:bundleID:allowTools:systemTokenClient:accessToken:completionHandler:"
+ "v136@0:8@16@24@32@40@48@56@64@72@80@88@96@104B112B116@120@?128"
- "-[NSPPrivacyTokenManager fetchPairedPrivateAccessTokensForChallenge:overrideAttester:tokenKey:originNameKey:selectedOrigin:pairedChallenge:overridePairedAttester:pairedTokenKey:auditToken:bundleID:allowTools:systemTokenClient:accessToken:completionHandler:]"
- "fetchPairedPrivateAccessTokensForChallenge:overrideAttester:tokenKey:originNameKey:selectedOrigin:pairedChallenge:overridePairedAttester:pairedTokenKey:auditToken:bundleID:allowTools:systemTokenClient:accessToken:completionHandler:"
```
