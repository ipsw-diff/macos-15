## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 8.5.9.0.0
-  __TEXT.__text: 0x871368
+  __TEXT.__text: 0x8713a0
   __TEXT.__auth_stubs: 0x4580
   __TEXT.__objc_methlist: 0x2032c
   __TEXT.__const: 0xb5613
Functions:
~ sub_19cd36cc8 -> sub_19cd71cc8 : 88 -> 76
~ -[AMSDelegateAction description] : 200 -> 216
~ -[AMSDialogAction description] : 324 -> 352
~ -[AMSDialogRequest description] : 244 -> 260
~ -[AMSMediaTokenService _tokenRequestWithError:] : 1304 -> 1292
~ -[AMSURLProtocolHandler _handleResponse:task:] : 1576 -> 1608
~ __ZNK3AMS10DeviceInfo12getBuildTypeEv : 44 -> 32
CStrings:
+ "<private>"
- "seed"
```
