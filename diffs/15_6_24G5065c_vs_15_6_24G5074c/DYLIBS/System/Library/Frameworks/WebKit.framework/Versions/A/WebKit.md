## WebKit

> `/System/Library/Frameworks/WebKit.framework/Versions/A/WebKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-621.3.7.0.0
-  __TEXT.__text: 0xfda748
+621.3.8.0.0
+  __TEXT.__text: 0xfda768
   __TEXT.__auth_stubs: 0x180c0
   __TEXT.__objc_methlist: 0x12cd4
   __TEXT.__const: 0x35c0

   __TEXT.__cstring: 0x30d04e
   __TEXT.__swift_as_entry: 0x18
   __TEXT.__swift_as_ret: 0x10
-  __TEXT.__gcc_except_tab: 0x5da38
+  __TEXT.__gcc_except_tab: 0x5da40
   __TEXT.__oslogstring: 0x42600
   __TEXT.__ustring: 0xb00
   __TEXT.__unwind_info: 0x26148
Functions:
~ __ZNK6WebKit12CoreIPCError4toIDEv : 344 -> 376
CStrings:
+ "20621.3.8"
- "20621.3.7"
```
