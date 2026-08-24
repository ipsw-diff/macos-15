## AppSandbox

> `/System/Library/PrivateFrameworks/AppSandbox.framework/Versions/A/AppSandbox`

```diff

-738.100.25.0.0
-  __TEXT.__text: 0xa29c
+738.140.2.0.0
+  __TEXT.__text: 0xa488
   __TEXT.__auth_stubs: 0x590
   __TEXT.__objc_methlist: 0x524
   __TEXT.__const: 0xe0
-  __TEXT.__oslogstring: 0x955
+  __TEXT.__oslogstring: 0x992
   __TEXT.__cstring: 0x199a
   __TEXT.__gcc_except_tab: 0x20c
-  __TEXT.__unwind_info: 0x250
+  __TEXT.__unwind_info: 0x258
   __TEXT.__objc_classname: 0x9e
-  __TEXT.__objc_methname: 0x18a7
+  __TEXT.__objc_methname: 0x18c4
   __TEXT.__objc_methtype: 0x228
-  __TEXT.__objc_stubs: 0x17c0
+  __TEXT.__objc_stubs: 0x17e0
   __DATA_CONST.__got: 0x1b8
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x728
+  __DATA_CONST.__objc_selrefs: 0x730
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__objc_arraydata: 0x60
   __AUTH_CONST.__auth_got: 0x2d8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 202
-  Symbols:   623
-  CStrings:  540
+  Functions: 204
+  Symbols:   625
+  CStrings:  543
 
Symbols:
+ GCC_except_table37
+ _objc_msgSend$getSigningInformation:error:
+ _sendConsentTelemetry
- GCC_except_table36
Functions:
~ -[AppSandboxRequest appsandboxContainerSync:] : 4568 -> 4696
+ _sendConsentTelemetry
~ -[AppSandboxRequest appsandboxContainerSync:].cold.6 : 132 -> 152
~ -[AppSandboxRequest appsandboxContainerSync:].cold.7 : 40 -> 132
+ -[AppSandboxRequest appsandboxContainerSync:].cold.9
CStrings:
+ "%{public}@ terminated"
+ "failed to get signing info: %{public}@"
+ "getSigningInformation:error:"
```
