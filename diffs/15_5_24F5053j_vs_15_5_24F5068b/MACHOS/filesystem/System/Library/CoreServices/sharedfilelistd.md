## sharedfilelistd

> `/System/Library/CoreServices/sharedfilelistd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`

```diff

-302.3.0.0.0
+302.4.0.0.0
   __TEXT.__text: 0x19288
   __TEXT.__auth_stubs: 0x720
   __TEXT.__objc_stubs: 0x2c20

   __TEXT.__objc_classname: 0x1f8
   __TEXT.__objc_methname: 0x355a
   __TEXT.__objc_methtype: 0xab6
-  __TEXT.__cstring: 0xb55
+  __TEXT.__cstring: 0xb53
   __TEXT.__gcc_except_tab: 0xf4
   __TEXT.__unwind_info: 0x5f0
   __DATA_CONST.__auth_got: 0x3a0
CStrings:
+ "file:"
- "file://"
```
