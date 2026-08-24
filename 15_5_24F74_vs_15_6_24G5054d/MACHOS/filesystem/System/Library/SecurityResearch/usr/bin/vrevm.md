## vrevm

> `/System/Library/SecurityResearch/usr/bin/vrevm`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_capture`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-199.120.7.0.0
-  __TEXT.__text: 0x641b4
-  __TEXT.__auth_stubs: 0x1a70
+199.140.7.0.0
+  __TEXT.__text: 0x6526c
+  __TEXT.__auth_stubs: 0x1a90
   __TEXT.__objc_methlist: 0x18c
-  __TEXT.__const: 0x2f8e
-  __TEXT.__cstring: 0x20a2
+  __TEXT.__const: 0x3096
+  __TEXT.__cstring: 0x2152
   __TEXT.__constg_swiftt: 0xac4
-  __TEXT.__swift5_typeref: 0xc6e
+  __TEXT.__swift5_typeref: 0xc80
   __TEXT.__swift5_builtin: 0x64
-  __TEXT.__swift5_reflstr: 0x8fb
-  __TEXT.__swift5_fieldmd: 0xfc4
+  __TEXT.__swift5_reflstr: 0x958
+  __TEXT.__swift5_fieldmd: 0x1018
   __TEXT.__swift5_assocty: 0x138
-  __TEXT.__oslogstring: 0x785
-  __TEXT.__objc_methname: 0xafe
+  __TEXT.__oslogstring: 0x7b5
+  __TEXT.__objc_methname: 0xab1
   __TEXT.__swift5_proto: 0x31c
   __TEXT.__swift5_types: 0x108
   __TEXT.__swift5_mpenum: 0x8

   __TEXT.__swift5_capture: 0xbc
   __TEXT.__objc_classname: 0x22
   __TEXT.__objc_methtype: 0x15a
-  __TEXT.__unwind_info: 0x1268
-  __TEXT.__eh_frame: 0x239c
-  __DATA_CONST.__auth_got: 0xd38
-  __DATA_CONST.__got: 0x4e0
+  __TEXT.__unwind_info: 0x1270
+  __TEXT.__eh_frame: 0x23b4
+  __DATA_CONST.__auth_got: 0xd48
+  __DATA_CONST.__got: 0x4d8
   __DATA_CONST.__auth_ptr: 0x5a0
-  __DATA_CONST.__const: 0x1d70
+  __DATA_CONST.__const: 0x1dc8
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA.__objc_const: 0x4b0
-  __DATA.__objc_selrefs: 0x460
+  __DATA.__objc_selrefs: 0x450
   __DATA.__objc_data: 0x2a0
-  __DATA.__data: 0x1960
+  __DATA.__data: 0x18e0
   __DATA.__common: 0x1e0
   __DATA.__bss: 0x6380
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1369
-  Symbols:   719
-  CStrings:  434
+  Functions: 1370
+  Symbols:   720
+  CStrings:  436
 
Symbols:
+ _$s22ArgumentParserInternal6OptionV12wrappedValue4name7parsing4help10completionACyqd__SgGs26_OptionalNilComparisonTypeV_AA17NameSpecificationVAA06SingleF15ParsingStrategyVAA0A4HelpVSgAA14CompletionKindVSgtcAIRszAA013ExpressibleByA0Rd__lufC
+ _$sSi22ArgumentParserInternal013ExpressibleByA0AAWP
+ _$ss22KeyedDecodingContainerV15decodeIfPresent_6forKeySiSgSim_xtKF
+ _$ss22KeyedEncodingContainerV15encodeIfPresent_6forKeyySiSg_xtKF
- _$ss018_bridgeAnyObjectToB0yypyXlSgF
- _OBJC_CLASS_$_NSData
- _OBJC_CLASS_$_NSJSONSerialization
CStrings:
+ "Rank to VirtMesh plugin."
+ "Set rank [%ld] to feature index [%ld]"
+ "VirtMesh has either rank or plugin path as nil"
+ "VirtMesh rank has to be set when plugin is preset, redo the modify with the rank set"
+ "setOptionalFeatures:atIndex:"
- "JSONObjectWithData:options:error:"
- "dataWithJSONObject:options:error:"
- "initWithContentsOfFile:options:error:"
```
