## linkd

> `/usr/libexec/linkd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-227.19.0.0.0
+227.20.0.0.0
   __TEXT.__text: 0x124188
   __TEXT.__auth_stubs: 0x27c0
   __TEXT.__objc_stubs: 0xa0
   __TEXT.__objc_methlist: 0xddc
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__const: 0x46fc
+  __TEXT.__const: 0x512c
   __TEXT.__cstring: 0x49a4
   __TEXT.__constg_swiftt: 0x2054
   __TEXT.__swift5_typeref: 0x3740

   __DATA.__objc_const: 0x22b0
   __DATA.__objc_selrefs: 0xcb8
   __DATA.__objc_data: 0x940
-  __DATA.__data: 0x5258
+  __DATA.__data: 0x4748
   __DATA.__common: 0xe08
   __DATA.__bss: 0x5270
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
CStrings:
+ "LinkProgrammaticInterface-227.20"
- "LinkProgrammaticInterface-227.19"
```
