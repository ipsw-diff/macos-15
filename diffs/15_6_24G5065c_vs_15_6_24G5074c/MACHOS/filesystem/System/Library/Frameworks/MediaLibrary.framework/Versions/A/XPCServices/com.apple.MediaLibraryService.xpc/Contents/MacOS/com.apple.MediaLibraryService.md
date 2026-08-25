## com.apple.MediaLibraryService

> `/System/Library/Frameworks/MediaLibrary.framework/Versions/A/XPCServices/com.apple.MediaLibraryService.xpc/Contents/MacOS/com.apple.MediaLibraryService`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-806.3.0.0.0
-  __TEXT.__text: 0x5b0c
-  __TEXT.__auth_stubs: 0x2b0
-  __TEXT.__objc_stubs: 0x1820
-  __TEXT.__objc_methlist: 0x684
+806.4.0.0.0
+  __TEXT.__text: 0x5828
+  __TEXT.__auth_stubs: 0x2a0
+  __TEXT.__objc_stubs: 0x1760
+  __TEXT.__objc_methlist: 0x67c
   __TEXT.__const: 0x88
-  __TEXT.__cstring: 0x1138
+  __TEXT.__cstring: 0x1067
   __TEXT.__gcc_except_tab: 0x1e0
-  __TEXT.__objc_methname: 0x1781
+  __TEXT.__objc_methname: 0x16ef
   __TEXT.__objc_classname: 0xac
   __TEXT.__objc_methtype: 0x4e4
   __TEXT.__unwind_info: 0x240
-  __DATA_CONST.__auth_got: 0x168
-  __DATA_CONST.__got: 0x178
+  __DATA_CONST.__auth_got: 0x160
+  __DATA_CONST.__got: 0x160
   __DATA_CONST.__const: 0x120
-  __DATA_CONST.__cfstring: 0xee0
+  __DATA_CONST.__cfstring: 0xe00
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0xa38
-  __DATA.__objc_selrefs: 0x720
+  __DATA.__objc_selrefs: 0x6f0
   __DATA.__objc_ivar: 0x44
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x248

   - /System/Library/PrivateFrameworks/iLifeMediaBrowser.framework/Versions/A/iLifeMediaBrowser
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 115
-  Symbols:   118
-  CStrings:  456
+  Functions: 114
+  Symbols:   114
+  CStrings:  443
 
Symbols:
- _ILAppDefFolderPluginIdentifier
- _OBJC_CLASS_$_NSFileManager
- _OBJC_CLASS_$_NSRunningApplication
- _realpath$DARWIN_EXTSN
CStrings:
- "MLMediaLoadAppFolders"
- "Not adding path %@ to appDefinedFolderPaths. App path is %@. Canonical path is %@."
- "_addAppDefinedFolderPaths"
- "appBasePath: %@"
- "appDefinedFolderPaths: %@"
- "appdef paths: %@"
- "bundleURL"
- "clientAppBundleURL: %@"
- "clientApplication: %@"
- "defaultManager"
- "hasPrefix:"
- "runningApplicationWithProcessIdentifier:"
- "stringWithFileSystemRepresentation:length:"
```
