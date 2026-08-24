## watchdogd

> `/usr/libexec/watchdogd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-299.100.5.0.0
+299.120.2.0.0
   __TEXT.__text: 0xbef8
   __TEXT.__auth_stubs: 0xe80
   __TEXT.__objc_stubs: 0xb40
   __TEXT.__const: 0x98
-  __TEXT.__cstring: 0x4953
+  __TEXT.__cstring: 0x4952
   __TEXT.__oslogstring: 0x2a1
   __TEXT.__objc_classname: 0x1
   __TEXT.__gcc_except_tab: 0x5c
CStrings:
+ "service %s enroll successful"
- "service %s enroll succcessful"
```
