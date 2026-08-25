## softwareupdated

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Support/softwareupdated`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_classrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2171.140.7.0.0
-  __TEXT.__text: 0xb0564
+2171.140.14.501.1
+  __TEXT.__text: 0xb0524
   __TEXT.__auth_stubs: 0x1bf0
-  __TEXT.__objc_stubs: 0x5a20
+  __TEXT.__objc_stubs: 0x5a00
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x26b4
   __TEXT.__const: 0x778c8
   __TEXT.__gcc_except_tab: 0x8b4
-  __TEXT.__cstring: 0x181cc
+  __TEXT.__cstring: 0x181b6
   __TEXT.__objc_classname: 0x4af
-  __TEXT.__objc_methname: 0x6178
+  __TEXT.__objc_methname: 0x6162
   __TEXT.__objc_methtype: 0x18ae
   __TEXT.__oslogstring: 0x486e
   __TEXT.__ustring: 0x4

   __DATA_CONST.__got: 0x428
   __DATA_CONST.__auth_ptr: 0x68
   __DATA_CONST.__const: 0x3808
-  __DATA_CONST.__cfstring: 0xc9e0
+  __DATA_CONST.__cfstring: 0xc9c0
   __DATA_CONST.__objc_classlist: 0x110
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x88

   __DATA_CONST.__objc_dictobj: 0x258
   __DATA_CONST.__objc_arrayobj: 0xd8
   __DATA.__objc_const: 0x35e0
-  __DATA.__objc_selrefs: 0x1ba8
+  __DATA.__objc_selrefs: 0x1ba0
   __DATA.__objc_ivar: 0x23c
   __DATA.__objc_data: 0xaa0
   __DATA.__data: 0xab0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpartition2_dynamic.dylib
   Functions: 2170
-  Symbols:   4221
-  CStrings:  4709
+  Symbols:   4220
+  CStrings:  4707
 
Symbols:
- _objc_msgSend$cStringUsingEncoding:
Functions:
~ -[UMEventRecorder recordPostUpdateEvent:additionalInfo:withCallback:] : 2076 -> 2016
~ _Shift : 356 -> 352
CStrings:
+ "%s: failed to decode migratorMetrics, reporting encoded metrics instead"
- "%s: bad decoded metrics"
- "%s: failed to find APFSDecodeMetricsString, reporting encoded metrics"
- "cStringUsingEncoding:"
```
