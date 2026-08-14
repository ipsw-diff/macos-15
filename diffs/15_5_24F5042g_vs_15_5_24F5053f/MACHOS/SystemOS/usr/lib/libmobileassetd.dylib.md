## libmobileassetd.dylib

> `/usr/lib/libmobileassetd.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`
- `__DATA.__s_async_hook`

```diff

-1487.120.46.0.0
-  __TEXT.__text: 0x2b5e40
+1487.120.52.0.0
+  __TEXT.__text: 0x2b6840
   __TEXT.__auth_stubs: 0x2330
-  __TEXT.__objc_stubs: 0x226e0
-  __TEXT.__objc_methlist: 0x105c4
+  __TEXT.__objc_stubs: 0x22720
+  __TEXT.__objc_methlist: 0x105e4
   __TEXT.__const: 0x485e
-  __TEXT.__cstring: 0x37b46
-  __TEXT.__objc_methname: 0x3dc0d
+  __TEXT.__cstring: 0x37c36
+  __TEXT.__objc_methname: 0x3dc77
   __TEXT.__objc_classname: 0xe8a
   __TEXT.__objc_methtype: 0x3bf5
-  __TEXT.__oslogstring: 0x4b6db
-  __TEXT.__gcc_except_tab: 0x2fc8
+  __TEXT.__oslogstring: 0x4b7c0
+  __TEXT.__gcc_except_tab: 0x2fe4
   __TEXT.__swift5_typeref: 0x1093
   __TEXT.__constg_swiftt: 0x14fc
   __TEXT.__swift5_fieldmd: 0xfec

   __DATA_CONST.__got: 0x670
   __DATA_CONST.__auth_ptr: 0x968
   __DATA_CONST.__const: 0x6948
-  __DATA_CONST.__cfstring: 0x2b980
+  __DATA_CONST.__cfstring: 0x2ba00
   __DATA_CONST.__objc_classlist: 0x3f8
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x98e8
+  __DATA_CONST.__objc_selrefs: 0x98f8
   __DATA_CONST.__objc_intobj: 0x558
   __DATA_CONST.__objc_arraydata: 0xb98
   __DATA_CONST.__objc_arrayobj: 0x270

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 8466
-  Symbols:   15204
-  CStrings:  16217
+  Functions: 8468
+  Symbols:   15208
+  CStrings:  16224
 
Symbols:
+ -[DownloadManager getBaseURLOverrideForAssetType:]
+ -[MADAutoAssetControlManager atomicInstanceUUIDForNewSetJob:forReason:]
+ -[MADAutoAssetControlManager isAtomicEntry:desiredForAutoAssetSetEntries:]
+ -[MADAutoAssetJob rebuildLastestDescriptorsOnFilesystem:]
+ GCC_except_table162
+ GCC_except_table173
+ GCC_except_table213
+ GCC_except_table447
+ GCC_except_table638
+ GCC_except_table642
+ GCC_except_table648
+ GCC_except_table650
+ GCC_except_table664
+ GCC_except_table797
+ _objc_msgSend$atomicInstanceUUIDForNewSetJob:forReason:
+ _objc_msgSend$getBaseURLOverrideForAssetType:
+ _objc_msgSend$isAtomicEntry:desiredForAutoAssetSetEntries:
+ _objc_msgSend$rebuildLastestDescriptorsOnFilesystem:
- -[MADAutoAssetControlManager atomicInstanceUUIDForNewSetJob:]
- -[MADAutoAssetJob rebuildLastestOnFS:]
- GCC_except_table161
- GCC_except_table172
- GCC_except_table212
- GCC_except_table446
- GCC_except_table637
- GCC_except_table641
- GCC_except_table647
- GCC_except_table649
- GCC_except_table663
- GCC_except_table796
- _objc_msgSend$atomicInstanceUUIDForNewSetJob:
- _objc_msgSend$rebuildLastestOnFS:
CStrings:
+ "%@:rebuildLastestDescriptorsOnFilesystem"
+ "%@:requestDownloadManagerCatalogLookup"
+ "%{public}@ {%{public}@}\n[BUILD-DESCRIPTORS] cleared latestAssetDescriptorOnFilesystemBySpecifier"
+ "%{public}@ {%{public}@}\n[BUILD-DESCRIPTORS] downloaded descriptor is not really on the filesystem - not adding to latestAssetDescriptorOnFilesystemBySpecifier list | latestDownloadedDescriptor:%{public}@"
+ "%{public}@ {%{public}@}\n[BUILD-DESCRIPTORS] latest downloaded descriptor is not really on the filesystem - not adding to latestAssetDescriptorOnFilesystemBySpecifier list | latestDownloadedDescriptor:%{public}@,"
+ "%{public}@ {%{public}@}\n[BUILD-DESCRIPTORS] latest version on filesystem | assetSpecifier:%{public}@ | assetVersion:%{public}@"
+ "%{public}@ {%{public}@} | SIMULATE_OPERATION(%lld) | call to registerCatalogDownloadJob postponed"
+ "%{public}@ {%{public}@} | SIMULATE_OPERATION(%{public}@) | call to registerCatalogDownloadJob postponed"
+ "Starting built-in MobileAsset brain built Apr  6 2025 19:19:18"
+ "Starting downloaded MobileAsset brain (version: %@) built Apr  6 2025 19:19:18"
+ "Using Knox url from asset to construct asset download URL: %{public}@"
+ "Using base url from request to construct asset download URL: %{public}@"
+ "Using baseURL from supplied override to construct asset download URL: %{public}@"
+ "atomicInstanceUUIDForNewSetJob(%@)"
+ "atomicInstanceUUIDForNewSetJob:forReason:"
+ "getBaseURLOverrideForAssetType:"
+ "isAtomicEntry:desiredForAutoAssetSetEntries:"
+ "rebuildLastestDescriptorsOnFilesystem:"
+ "{%{public}@} (%{public}@)\n[SET-DECIDE-FOUND] considering potential descriptors | potentialDescriptorCount:%lu,alreadyOnFilesystem:%{public}@"
+ "{%{public}@} (%{public}@)\n[SET-DECIDE-FOUND] set-catalog lookup summary | catalogCount:%lu | patchDescriptorCount:%lu | fullDescriptorCount:%lu"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSelector} | lookup-cache non-pallas disabled | selector:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:recordLookupResult:forSelector:} | auto-asset-lookup-cache non-pallas disabled | selector:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:recordLookupResult:forSetConfiguration:} | by-set-configuration non-pallas disabled | selector:%{public}@"
+ "{isAtomicEntry:desiredForAutoAssetSetEntries} nil atomic-entry provided"
+ "{isAtomicEntry:desiredForAutoAssetSetEntries} nil auto-asset-set-entries provided"
- "%{public}@ {%{public}@:rebuildLastestOnFS} latest downloaded descriptor is not really on filesystem. Not adding to latestAssetDescriptorOnFilesystemBySpecifier list. Descriptor :%{public}@,"
- "%{public}@ {%{public}@:rebuildLastestOnFS} latest version on filesystem | assetVersion:%{public}@, for assetSpecifier:%{public}@,"
- "%{public}@ {%{public}@:requestDownloadManagerCatalogLookup} downloaded descriptor is not really on filesystem. Not adding to latestAssetDescriptorOnFilesystemBySpecifier list. Descriptor: %{public}@"
- "%{public}@ {%{public}@:requestDownloadManagerCatalogLookup} latest version on filesystem | assetVersion:%{public}@, for assetSpecifier:%{public}@,"
- "%{public}@ {%{public}@:requestDownloadManagerCatalogLookup} | SIMULATE_OPERATION(%lld) | call to registerCatalogDownloadJob postponed"
- "%{public}@ {%{public}@:requestDownloadManagerCatalogLookup} | SIMULATE_OPERATION(%{public}@) | call to registerCatalogDownloadJob postponed"
- "DownloadServerBaseURLOverride"
- "Starting built-in MobileAsset brain built Mar 21 2025 21:13:14"
- "Starting downloaded MobileAsset brain (version: %@) built Mar 21 2025 21:13:14"
- "Using Knox url from asset: %{public}@"
- "Using base url from default: %{public}@"
- "Using base url from request: %{public}@"
- "Using value set in asset specific default(%@) for baseURL(%@)"
- "Using value set in global default(%@) for baseURL(%@) for asset %@"
- "atomicInstanceUUIDForNewSetJob:"
- "rebuildLastestOnFS:"
- "{%{public}@} (%{public}@)\n[SET-DECIDE-FOUND] considering potential descriptors | potentialDescriptorCount:%{public}lu,alreadyOnFilesystem:%{public}@"
- "{{public}@} (%{public}@)\n[SET-DECIDE-FOUND] set-catalog lookup summary: %{public}@:catalogCount:%{public}lu,patchDescriptorCount:%{public}lu,fullDescriptorCount:%{public}lu"
```
