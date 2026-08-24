## spotlightknowledged

> `/System/Library/Frameworks/CoreSpotlight.framework/spotlightknowledged`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2333.50.1.0.0
-  __TEXT.__text: 0xddb24
+2333.55.0.0.0
+  __TEXT.__text: 0xde210
   __TEXT.__auth_stubs: 0x1c00
-  __TEXT.__objc_stubs: 0xd6c0
-  __TEXT.__objc_methlist: 0x65b8
-  __TEXT.__const: 0x712
+  __TEXT.__objc_stubs: 0xd740
+  __TEXT.__objc_methlist: 0x6600
+  __TEXT.__const: 0x702
   __TEXT.__gcc_except_tab: 0x540c
-  __TEXT.__cstring: 0x8791
-  __TEXT.__oslogstring: 0x83ea
-  __TEXT.__objc_classname: 0xa4e
-  __TEXT.__objc_methname: 0xfad5
+  __TEXT.__cstring: 0x87a8
+  __TEXT.__oslogstring: 0x847e
+  __TEXT.__objc_classname: 0xa4f
+  __TEXT.__objc_methname: 0xfbf9
   __TEXT.__objc_methtype: 0x1736
   __TEXT.__dlopen_cstrs: 0x5e
-  __TEXT.__unwind_info: 0x2de0
+  __TEXT.__unwind_info: 0x2df0
   __DATA_CONST.__auth_got: 0xe18
   __DATA_CONST.__got: 0x850
   __DATA_CONST.__auth_ptr: 0x18

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x2c0
-  __DATA_CONST.__objc_intobj: 0x738
+  __DATA_CONST.__objc_intobj: 0x768
   __DATA_CONST.__objc_arraydata: 0xb20
   __DATA_CONST.__objc_arrayobj: 0x6a8
   __DATA_CONST.__objc_dictobj: 0x280
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA.__objc_const: 0xaff8
-  __DATA.__objc_selrefs: 0x3d80
-  __DATA.__objc_ivar: 0x74c
+  __DATA.__objc_const: 0xb098
+  __DATA.__objc_selrefs: 0x3db0
+  __DATA.__objc_ivar: 0x75c
   __DATA.__objc_data: 0x2b70
   __DATA.__data: 0x558
   __DATA.__bss: 0xe08

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3762
+  Functions: 3774
   Symbols:   715
-  CStrings:  5273
+  CStrings:  5286
 
CStrings:
+ "### Unable to determine journal file size: %d, %s, %d"
+ "###purgeJournalsProactive Total journal size %lld (qc: %lu) exceeds %lld, skipping journal %s"
+ "<%@:%p:%u; n: %llu pfd: %d offset: %lld jsz: %lld, tsz: %lld err: %d (%@)>"
+ "<%@:%p:%u; n: %llu pfd: %d offset: %lld jsz:%lld, tsz: %lld csz: %lld err: %d (%@)>"
+ "Tq,N,V_journalSizeGetBelowLimit"
+ "Tq,N,V_maxJournalSizeInQueue"
+ "_journalSizeGetBelowLimit"
+ "_journal_file_size"
+ "_maxJournalSizeInQueue"
+ "_totalJournalSize"
+ "deleteFirstJournal:"
+ "journalSizeGetBelowLimit"
+ "maxJournalSizeInQueue"
+ "purgeJournalsProactive"
+ "setJournalSizeGetBelowLimit:"
+ "setMaxJournalSizeInQueue:"
+ "\x81\xc3"
- "%"
- "<%@:%p:%u; n: %llu pfd: %d offset: %lld sz: %lld csz: %lld err: %d (%@)>"
- "<%@:%p:%u; n: %llu pfd: %d offset: %lld sz: %lld err: %d (%@)>"
- "\x81\xb3"
```
