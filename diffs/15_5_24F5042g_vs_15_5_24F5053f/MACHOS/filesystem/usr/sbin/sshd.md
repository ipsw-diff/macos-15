## sshd

> `/usr/sbin/sshd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-346.120.1.0.0
-  __TEXT.__text: 0x24434
-  __TEXT.__auth_stubs: 0xfd0
+346.120.3.0.0
+  __TEXT.__text: 0x24598
+  __TEXT.__auth_stubs: 0xfe0
   __TEXT.__const: 0x1bfc0
-  __TEXT.__cstring: 0x5ec6
+  __TEXT.__cstring: 0x5eef
   __TEXT.__unwind_info: 0x580
-  __DATA_CONST.__auth_got: 0x7e8
+  __DATA_CONST.__auth_got: 0x7f0
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__auth_ptr: 0x28
   __DATA_CONST.__const: 0x1b60

   - /usr/lib/libpam.2.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 434
-  Symbols:   286
-  CStrings:  960
+  Functions: 435
+  Symbols:   287
+  CStrings:  964
 
Symbols:
+ _strncasecmp
Functions:
~ sub_10000a920 : 2292 -> 2536
+ sub_100014d3c
CStrings:
+ "OpenSSH_9.9p2"
+ "address="
+ "group="
+ "localaddress="
+ "localport="
- "OpenSSH_9.9p1"
```
