## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_protos`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-555.48.1.2.0
-  __TEXT.__text: 0x2b038c
+555.48.1.8.0
+  __TEXT.__text: 0x2b08f4
   __TEXT.__auth_stubs: 0x33a0
-  __TEXT.__objc_stubs: 0x17740
-  __TEXT.__objc_methlist: 0x1487c
+  __TEXT.__objc_stubs: 0x17760
+  __TEXT.__objc_methlist: 0x14894
   __TEXT.__const: 0x6dbe8
-  __TEXT.__objc_methname: 0x2416f
-  __TEXT.__oslogstring: 0xd1a9
-  __TEXT.__cstring: 0x121ef
+  __TEXT.__objc_methname: 0x241c6
+  __TEXT.__oslogstring: 0xd1e5
+  __TEXT.__cstring: 0x122a6
   __TEXT.__objc_classname: 0x25c0
   __TEXT.__objc_methtype: 0x4a1a
   __TEXT.__gcc_except_tab: 0x16bc

   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__swift5_protos: 0xac
-  __TEXT.__unwind_info: 0x5b00
+  __TEXT.__unwind_info: 0x5b08
   __TEXT.__eh_frame: 0x2e18
   __DATA_CONST.__auth_got: 0x19e0
   __DATA_CONST.__got: 0xf68
-  __DATA_CONST.__auth_ptr: 0xbb8
-  __DATA_CONST.__const: 0x14ad8
-  __DATA_CONST.__cfstring: 0xe640
+  __DATA_CONST.__auth_ptr: 0xbf0
+  __DATA_CONST.__const: 0x14ae0
+  __DATA_CONST.__cfstring: 0xe680
   __DATA_CONST.__objc_classlist: 0xd30
   __DATA_CONST.__objc_catlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x290

   __DATA_CONST.__objc_dictobj: 0xa28
   __DATA_CONST.__objc_arrayobj: 0xc0
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA.__objc_const: 0x26940
-  __DATA.__objc_selrefs: 0x8d40
-  __DATA.__objc_ivar: 0x1498
+  __DATA.__objc_const: 0x26988
+  __DATA.__objc_selrefs: 0x8d50
+  __DATA.__objc_ivar: 0x149c
   __DATA.__objc_data: 0x7db8
   __DATA.__data: 0x8730
   __DATA.__common: 0xb30

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 9958
-  Symbols:   2070
-  CStrings:  10516
+  Functions: 9962
+  Symbols:   2071
+  CStrings:  10524
 
Symbols:
+ _kAPisProtoU13
CStrings:
+ "%@ WHERE impressionId = ? AND purpose = %lu AND event = %lu"
+ "%@ WHERE impressionId = ? AND purpose IN (%lu, %lu) AND event IN (%lu, %lu, %lu, %lu) AND timestamp >= ? AND timestamp < ? ORDER BY timestamp ASC"
+ "Error getting placed event."
+ "SELECT rowid, * FROM APDBAdSignalTrack WHERE triggerRowId = ? AND (opportunity + impression + click + conversion) < 4 LIMIT %ld OFFSET %ld"
+ "TB,R,V_isProtoU13"
+ "This is a Proto U13 user. No ad requests allowed to server."
+ "Unable to get placed event rows"
+ "_isProtoU13"
+ "isProtoU13"
+ "placedEventsForImpressionId:"
+ "signalTracksWithPendingCountsForTriggerRowId:limit:offset:"
- "%@ WHERE impressionId = ? AND purpose IN (%lu, %lu) AND event IN (%lu, %lu, %lu, %lu, %lu) AND timestamp >= ? AND timestamp < ? ORDER BY timestamp ASC"
- "SELECT rowid, * FROM APDBAdSignalTrack WHERE triggerRowId = ? LIMIT %ld OFFSET %ld"
- "signalTracksForTriggerRowId:limit:offset:"
```
