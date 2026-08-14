## sshd-session

> `/usr/libexec/sshd-session`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-346.120.1.0.0
-  __TEXT.__text: 0x6f3f4
+346.120.3.0.0
+  __TEXT.__text: 0x6f574
   __TEXT.__auth_stubs: 0x1a10
   __TEXT.__const: 0x1b328
-  __TEXT.__cstring: 0x15c1c
+  __TEXT.__cstring: 0x15c45
   __TEXT.__unwind_info: 0xe90
   __TEXT.__eh_frame: 0x68
   __DATA_CONST.__auth_got: 0xd08

   - /usr/lib/libpam.2.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1181
+  Functions: 1182
   Symbols:   452
-  CStrings:  3287
+  CStrings:  3291
 
CStrings:
+ "OpenSSH_9.9p2"
+ "address="
+ "group="
+ "localaddress="
+ "localport="
- "OpenSSH_9.9p1"
```
