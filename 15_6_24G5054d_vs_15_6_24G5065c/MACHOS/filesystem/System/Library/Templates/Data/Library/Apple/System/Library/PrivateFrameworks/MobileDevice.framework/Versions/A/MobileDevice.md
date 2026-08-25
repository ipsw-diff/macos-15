## MobileDevice

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/MobileDevice.framework/Versions/A/MobileDevice`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_MobileDev`
- `__TEXT.__dof_afc`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH.__data`
- `__DATA.__objc_protorefs`
- `__DATA.__data`

```diff

 1784.140.4.0.0
-  __TEXT.__text: 0x284c1c
+  __TEXT.__text: 0x2850dc
   __TEXT.__auth_stubs: 0x4030
-  __TEXT.__objc_methlist: 0x3d74
-  __TEXT.__const: 0x1017ec
-  __TEXT.__cstring: 0x749d7
+  __TEXT.__objc_methlist: 0x3df4
+  __TEXT.__const: 0x1018ec
+  __TEXT.__cstring: 0x749d6
   __TEXT.__gcc_except_tab: 0x3cdc
   __TEXT.__oslogstring: 0x96a
   __TEXT.__ustring: 0x15a
   __TEXT.__dof_MobileDev: 0x1ac1
   __TEXT.__dof_afc: 0x6d7
-  __TEXT.__unwind_info: 0x6868
+  __TEXT.__unwind_info: 0x6888
   __TEXT.__eh_frame: 0x6a4
-  __TEXT.__objc_classname: 0xdfc
-  __TEXT.__objc_methname: 0x708d
-  __TEXT.__objc_methtype: 0x2439
-  __TEXT.__objc_stubs: 0x5840
+  __TEXT.__objc_classname: 0xe13
+  __TEXT.__objc_methname: 0x7174
+  __TEXT.__objc_methtype: 0x2453
+  __TEXT.__objc_stubs: 0x58c0
   __DATA_CONST.__got: 0x380
   __DATA_CONST.__const: 0x7448
-  __DATA_CONST.__objc_classlist: 0x290
+  __DATA_CONST.__objc_classlist: 0x298
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b48
+  __DATA_CONST.__objc_selrefs: 0x1b88
   __AUTH_CONST.__auth_got: 0x2030
   __AUTH_CONST.__const: 0x8688
   __AUTH_CONST.__cfstring: 0x3b4c0
-  __AUTH_CONST.__objc_const: 0x70a0
-  __AUTH.__objc_data: 0x19a0
+  __AUTH_CONST.__objc_const: 0x71c0
+  __AUTH.__objc_data: 0x19f0
   __AUTH.__data: 0x338
   __DATA.__objc_protorefs: 0x28
-  __DATA.__objc_classrefs: 0x380
-  __DATA.__objc_superrefs: 0x288
-  __DATA.__objc_ivar: 0x4a8
+  __DATA.__objc_classrefs: 0x388
+  __DATA.__objc_superrefs: 0x290
+  __DATA.__objc_ivar: 0x4b4
   __DATA.__data: 0x1af8
   __DATA.__bss: 0x41b8
   __DATA.__common: 0x10c0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libssl.35.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9483
-  Symbols:   13799
-  CStrings:  15971
+  Functions: 9496
+  Symbols:   13828
+  CStrings:  15987
 
Symbols:
+ -[RamrodHostMessagePlist .cxx_destruct]
+ -[RamrodHostMessagePlist chunks]
+ -[RamrodHostMessagePlist dealloc]
+ -[RamrodHostMessagePlist hasSpaceAvailable]
+ -[RamrodHostMessagePlist initWithPropertyList:error:]
+ -[RamrodHostMessagePlist invalidate]
+ -[RamrodHostMessagePlist length]
+ -[RamrodHostMessagePlist sendToSocket:]
+ -[RamrodHostMessagePlist streamError]
+ -[RamrodHostMessagePlist write:maxLength:]
+ OBJC_IVAR_$_RamrodHostMessagePlist._chunks
+ OBJC_IVAR_$_RamrodHostMessagePlist._length
+ OBJC_IVAR_$_RamrodHostMessagePlist._streamError
+ _OBJC_CLASS_$_NSOutputStream
+ _OBJC_CLASS_$_RamrodHostMessagePlist
+ _OBJC_METACLASS_$_NSOutputStream
+ _OBJC_METACLASS_$_RamrodHostMessagePlist
+ __OBJC_$_INSTANCE_METHODS_RamrodHostMessagePlist
+ __OBJC_$_INSTANCE_VARIABLES_RamrodHostMessagePlist
+ __OBJC_$_PROP_LIST_RamrodHostMessagePlist
+ __OBJC_CLASS_RO_$_RamrodHostMessagePlist
+ __OBJC_METACLASS_RO_$_RamrodHostMessagePlist
+ _objc_msgSend$initWithCapacity:
+ _objc_msgSend$initWithPropertyList:error:
+ _objc_msgSend$sendToSocket:
+ _objc_msgSend$writePropertyList:toStream:format:options:error:
+ _ramrod_message_plist_create
+ _ramrod_message_plist_send
+ _ramrod_send_bytes
CStrings:
+ "RamrodHostMessagePlist"
+ "T@\"NSArray\",R,C,V_chunks"
+ "TQ,R,V_length"
+ "_chunks"
+ "_length"
+ "_streamError"
+ "chunks"
+ "hasSpaceAvailable"
+ "i20@0:8i16"
+ "initWithCapacity:"
+ "initWithPropertyList:error:"
+ "q32@0:8r*16Q24"
+ "restore library built Jun 17 2025 at 22:02:37"
+ "sendToSocket:"
+ "sock %3d: CFPropertyListCreateData: %s"
+ "streamError"
+ "write:maxLength:"
+ "writePropertyList:toStream:format:options:error:"
- "restore library built Jun  3 2025 at 00:14:20"
- "sock %3d: CFPropertyListCreateData: %s\n"
```
