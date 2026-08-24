## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

   __TEXT.__text: 0x12ef8
   __TEXT.__auth_stubs: 0x320
   __TEXT.__const: 0x23630
-  __TEXT.__cstring: 0xb6d
+  __TEXT.__cstring: 0xb7c
   __TEXT.__unwind_info: 0x200
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__auth_got: 0x190
```
