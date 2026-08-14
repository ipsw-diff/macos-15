## com.apple.iokit.IOAccessoryManager

> `com.apple.iokit.IOAccessoryManager`

```diff

-1016.120.2.0.0
+1016.120.3.0.0
   __TEXT.__const: 0x328
-  __TEXT.__cstring: 0x108b5
-  __TEXT.__os_log: 0x107da
-  __TEXT_EXEC.__text: 0xf3098
+  __TEXT.__cstring: 0x108ab
+  __TEXT.__os_log: 0x107bc
+  __TEXT_EXEC.__text: 0xf2d9c
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x7e8
   __DATA.__common: 0x1630

   __DATA_CONST.__kalloc_type: 0x2440
   Functions: 4823
   Symbols:   7212
-  CStrings:  2787
+  CStrings:  2789
 
Functions:
~ __ZNK6IOPort18_isFeatureDisabledE17IOPortFeatureType : 3464 -> 2700
CStrings:
+ "%s::%s(): [Boot Arg] %s=%u\n"
+ "%s::%s(): [Boot Arg] %s=0x%08x\n"
+ "%s::%s(): [EDT] /defaults/%s=%u\n"
+ "[ERROR] %s::%s(): [EDT] Invalid value for /defaults/%s!\n"
- "%s::%s(): [%s%s%s] [EDT] /defaults/%s=%u\n\n"
- "[ERROR] %s::%s(): [%s%s%s] [EDT] Invalid value for /defaults/%s!\n\n"
```
