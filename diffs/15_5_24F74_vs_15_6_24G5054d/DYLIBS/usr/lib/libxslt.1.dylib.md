## libxslt.1.dylib

> `/usr/lib/libxslt.1.dylib`

```diff

-21.7.0.0.0
-  __TEXT.__text: 0x226c8
-  __TEXT.__auth_stubs: 0xdc0
-  __TEXT.__cstring: 0x7210
+21.8.0.0.0
+  __TEXT.__text: 0x2277c
+  __TEXT.__auth_stubs: 0xdd0
+  __TEXT.__cstring: 0x7272
   __TEXT.__const: 0xc0
   __TEXT.__unwind_info: 0x4d0
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__const: 0x228
-  __AUTH_CONST.__auth_got: 0x6e0
+  __AUTH_CONST.__auth_got: 0x6e8
   __AUTH_CONST.__const: 0x40
   __AUTH.__data: 0x20
   __DATA.__data: 0x48

   __DATA.__common: 0x14
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 387
-  Symbols:   662
-  CStrings:  890
+  Functions: 388
+  Symbols:   664
+  CStrings:  892
 
Symbols:
+ _xmlCopyDoc
+ _xsltCleanupSourceDoc
Functions:
~ _xsltDocumentFunction : 1484 -> 1620
+ _xsltCleanupSourceDoc
~ _xsltApplyStylesheetInternal : 2008 -> 1896
CStrings:
+ "document() : failed to copy style doc\n"
+ "document() : failed to create xsltDocument\n"
```
