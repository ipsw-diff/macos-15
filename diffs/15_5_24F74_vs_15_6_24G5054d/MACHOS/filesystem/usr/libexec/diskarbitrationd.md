## diskarbitrationd

> `/usr/libexec/diskarbitrationd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-490.120.6.0.1
-  __TEXT.__text: 0x1b724
+490.140.7.0.1
+  __TEXT.__text: 0x1bc2c
   __TEXT.__auth_stubs: 0x16e0
-  __TEXT.__objc_stubs: 0x520
+  __TEXT.__objc_stubs: 0x540
   __TEXT.__init_offsets: 0x8
   __TEXT.__objc_methlist: 0xc8
-  __TEXT.__cstring: 0x31cd
+  __TEXT.__cstring: 0x3215
   __TEXT.__const: 0x78
   __TEXT.__oslogstring: 0xb
-  __TEXT.__gcc_except_tab: 0xd8
+  __TEXT.__gcc_except_tab: 0xdc
   __TEXT.__objc_classname: 0x2b
-  __TEXT.__objc_methname: 0x475
+  __TEXT.__objc_methname: 0x486
   __TEXT.__objc_methtype: 0x102
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x600
+  __TEXT.__unwind_info: 0x5f8
   __DATA_CONST.__auth_got: 0xb80
-  __DATA_CONST.__got: 0x140
+  __DATA_CONST.__got: 0x160
   __DATA_CONST.__auth_ptr: 0x10
-  __DATA_CONST.__const: 0xd90
-  __DATA_CONST.__cfstring: 0x1ea0
+  __DATA_CONST.__const: 0xd68
+  __DATA_CONST.__cfstring: 0x1f40
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x168
-  __DATA.__objc_selrefs: 0x188
+  __DATA.__objc_selrefs: 0x190
   __DATA.__objc_ivar: 0xc
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x178
-  __DATA.__bss: 0xdf0
+  __DATA.__bss: 0xdf8
   __DATA.__common: 0xc8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/FSKit.framework/Versions/A/FSKit

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 524
-  Symbols:   417
-  CStrings:  674
+  Functions: 522
+  Symbols:   421
+  CStrings:  678
 
Symbols:
+ _CFStringCreateCopy
+ _optarg
+ _opterr
+ _optind
+ _optreset
- _CFStringTrimWhitespace
CStrings:
+ "-"
+ "0E239BC6-F960-3107-89CF-1C97F78BB46B"
+ "FSBundleID"
+ "Failed to copy option argument"
+ "bundleIdentifier"
+ "msdos-efi"
+ "o:s:"
- "-s"
- "com.apple.fskit.%@"
- "s"
```
