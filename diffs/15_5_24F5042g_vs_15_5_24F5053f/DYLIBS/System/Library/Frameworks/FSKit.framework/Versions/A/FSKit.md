## FSKit

> `/System/Library/Frameworks/FSKit.framework/Versions/A/FSKit`

```diff

-531.120.13.0.0
-  __TEXT.__text: 0x42484
+531.120.18.0.0
+  __TEXT.__text: 0x42514
   __TEXT.__auth_stubs: 0xaa0
   __TEXT.__objc_methlist: 0x4324
   __TEXT.__const: 0x380

   __TEXT.__swift5_types: 0x8
   __TEXT.__swift_as_entry: 0x8
   __TEXT.__swift_as_ret: 0x8
-  __TEXT.__unwind_info: 0x1230
+  __TEXT.__unwind_info: 0x1238
   __TEXT.__eh_frame: 0x138
   __TEXT.__objc_classname: 0x825
   __TEXT.__objc_methname: 0x9386
   __TEXT.__objc_methtype: 0x325e
-  __TEXT.__objc_stubs: 0x5460
+  __TEXT.__objc_stubs: 0x5440
   __DATA_CONST.__got: 0x3e8
   __DATA_CONST.__const: 0x2c8
   __DATA_CONST.__objc_classlist: 0x208

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 1885
-  Symbols:   3698
+  Symbols:   3697
   CStrings:  2806
 
Symbols:
- _objc_msgSend$usedBytes
Functions:
~ -[FSStatFSResult encodeWithCoder:] -> -[FSStatFSResult setTotalBlocks:] : 300 -> 8
~ -[FSStatFSResult initWithCoder:] -> -[FSStatFSResult totalBlocks] : 324 -> 48
~ -[FSStatFSResult initWithFileSystemTypeName:] -> -[FSStatFSResult setAvailableBlocks:] : 132 -> 8
~ -[FSStatFSResult description] -> -[FSStatFSResult availableBlocks] : 144 -> 48
~ -[FSStatFSResult setBlockSize:] -> -[FSStatFSResult freeBlocks] : 8 -> 48
~ -[FSStatFSResult setIoSize:] -> -[FSStatFSResult usedBlocks] : 8 -> 48
~ -[FSStatFSResult setTotalBlocks:] -> -[FSStatFSResult totalBytes] : 8 -> 32
~ -[FSStatFSResult setAvailableBlocks:] -> -[FSStatFSResult availableBytes] : 8 -> 32
~ -[FSStatFSResult setFreeBlocks:] -> -[FSStatFSResult freeBytes] : 8 -> 32
~ -[FSStatFSResult setUsedBlocks:] -> -[FSStatFSResult usedBytes] : 8 -> 32
~ -[FSStatFSResult totalBytes] -> -[FSStatFSResult encodeWithCoder:] : 8 -> 188
~ -[FSStatFSResult setTotalBytes:] -> -[FSStatFSResult initWithCoder:] : 8 -> 324
~ -[FSStatFSResult availableBytes] -> -[FSStatFSResult initWithFileSystemTypeName:] : 8 -> 132
~ -[FSStatFSResult setAvailableBytes:] -> -[FSStatFSResult description] : 8 -> 144
```
