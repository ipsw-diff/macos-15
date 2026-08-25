## LiveFS

> `/System/Library/PrivateFrameworks/LiveFS.framework/Versions/A/LiveFS`

```diff

-531.140.7.0.2
+531.140.9.0.3
   __TEXT.__text: 0x200e8
   __TEXT.__auth_stubs: 0x630
   __TEXT.__objc_methlist: 0x1f8c

   __TEXT.__gcc_except_tab: 0xd1c
   __TEXT.__unwind_info: 0xa40
   __TEXT.__objc_classname: 0x334
-  __TEXT.__objc_methname: 0x42d9
+  __TEXT.__objc_methname: 0x42e2
   __TEXT.__objc_methtype: 0x2aac
   __TEXT.__objc_stubs: 0x2860
   __DATA_CONST.__got: 0x188
Symbols:
+ -[LiveFSUserClient configureUserClient:pid:pidversion:supportBlockResource:]
- -[LiveFSUserClient configureUserClient:pid:pidversion:supportKOIO:]
CStrings:
+ "configureUserClient:pid:pidversion:supportBlockResource:"
- "configureUserClient:pid:pidversion:supportKOIO:"
```
