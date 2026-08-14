## CaptiveNetworkSupport

> `/System/Library/SystemConfiguration/CaptiveNetworkSupport.bundle/Contents/MacOS/CaptiveNetworkSupport`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-491.120.3.0.0
-  __TEXT.__text: 0x246a4
+491.120.4.0.0
+  __TEXT.__text: 0x247a8
   __TEXT.__auth_stubs: 0x1000
   __TEXT.__const: 0x1c0
-  __TEXT.__oslogstring: 0x3cd3
+  __TEXT.__oslogstring: 0x3d15
   __TEXT.__cstring: 0x161d
   __TEXT.__unwind_info: 0x708
   __DATA_CONST.__auth_got: 0x800

   - /usr/lib/libbsm.0.dylib
   Functions: 590
   Symbols:   1059
-  CStrings:  802
+  CStrings:  805
 
Functions:
~ _CNPluginHandlerNetworkInformationChanged : 2036 -> 2296
CStrings:
+ "CaptiveNetworkSupport-491.120.4"
+ "current captive state: [%s]"
+ "new signatures: %@"
+ "old signatures: %@"
- "CaptiveNetworkSupport-491.120.3"
```
