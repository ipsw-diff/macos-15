## spctl

> `/usr/sbin/spctl`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-620.120.4.0.0
+620.120.7.0.0
   __TEXT.__text: 0xc000
   __TEXT.__auth_stubs: 0x940
   __TEXT.__objc_stubs: 0xec0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x7e8
   __TEXT.__const: 0x4bb
-  __TEXT.__cstring: 0x18cb
+  __TEXT.__cstring: 0x18ca
   __TEXT.__oslogstring: 0x81b
   __TEXT.__objc_classname: 0xf3
   __TEXT.__objc_methname: 0x1698
CStrings:
+ "iTerm.app"
- "iTerm2.app"
```
