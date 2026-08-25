## libtclsqlite3.dylib

> `/System/Library/Tcl/sqlite3/libtclsqlite3.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-360.2.0.0.0
-  __TEXT.__text: 0xf01f4
+360.3.0.0.0
+  __TEXT.__text: 0xf0244
   __TEXT.__auth_stubs: 0xdd0
   __TEXT.__const: 0x8ac8
-  __TEXT.__cstring: 0xc03c
+  __TEXT.__cstring: 0xc059
   __TEXT.__oslogstring: 0x6d8
   __TEXT.__unwind_info: 0x1f00
   __DATA_CONST.__auth_got: 0x6e8

   - /usr/lib/libSystem.B.dylib
   Functions: 2606
   Symbols:   3123
-  CStrings:  2231
+  CStrings:  2232
 
Functions:
~ _sqlite3LockAndPrepare : 468 -> 472
~ _sqlite3WalCheckpoint : 3032 -> 3036
~ _accessPayload : 820 -> 824
~ _ptrmapPut : 396 -> 392
~ _sqlite3VdbeExec : 32900 -> 32896
~ _defragmentPage : 848 -> 844
~ _sqlite3Select : 9692 -> 9688
~ _sqlite3ExprCodeTarget : 5532 -> 5528
~ _agginfoPersistExprCb : 268 -> 264
~ _analyzeAggregate : 660 -> 704
~ _findOrCreateAggInfoColumn : 352 -> 392
~ _sqlite3ArrayAllocate : 152 -> 164
~ _aggregateIdxEprRefToColCallback : 128 -> 124
CStrings:
+ "more than %d aggregate terms"
```
