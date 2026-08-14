## Dyld

> `/System/Library/PrivateFrameworks/Dyld.framework/Versions/A/Dyld`

```diff

-1284.13.0.0.0
-  __TEXT.__text: 0x4b084
-  __TEXT.__auth_stubs: 0x1320
+1284.15.0.0.0
+  __TEXT.__text: 0x4ca58
+  __TEXT.__auth_stubs: 0x13e0
   __TEXT.__objc_methlist: 0x534
-  __TEXT.__const: 0x1d78
-  __TEXT.__cstring: 0x1296
+  __TEXT.__const: 0x1d88
+  __TEXT.__cstring: 0x1336
   __TEXT.__gcc_except_tab: 0x8cc
   __TEXT.__swift5_typeref: 0x9a3
   __TEXT.__swift5_fieldmd: 0xcec

   __TEXT.__swift5_proto: 0x124
   __TEXT.__swift5_types: 0xfc
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xe58
+  __TEXT.__unwind_info: 0xe60
   __TEXT.__eh_frame: 0x15b8
   __TEXT.__objc_classname: 0x39
   __TEXT.__objc_methname: 0x548
   __TEXT.__objc_methtype: 0xad
   __TEXT.__objc_stubs: 0x780
-  __DATA_CONST.__got: 0x280
-  __DATA_CONST.__const: 0xc8
+  __DATA_CONST.__got: 0x288
+  __DATA_CONST.__const: 0xe8
   __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x2d0
   __DATA_CONST.__objc_protorefs: 0x18
-  __AUTH_CONST.__auth_got: 0x9a0
+  __AUTH_CONST.__auth_got: 0xa00
   __AUTH_CONST.__const: 0x2000
   __AUTH_CONST.__cfstring: 0x40
   __AUTH_CONST.__objc_const: 0x1700

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1272
-  Symbols:   931
-  CStrings:  294
+  Functions: 1285
+  Symbols:   961
+  CStrings:  310
 
Symbols:
+ __ZN10AAREncoder10addSymLinkENSt3__117basic_string_viewIcNS0_11char_traitsIcEEEES4_
+ __ZN12PropertyList10Dictionary15addObjectForKeyINS_6StringEJNSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEEEERT_NS3_17basic_string_viewIcS6_EEDpOT0_
+ __ZN12PropertyList10Dictionary15addObjectForKeyINS_6StringEJPKcEEERT_NSt3__117basic_string_viewIcNS7_11char_traitsIcEEEEDpOT0_
+ __ZN12PropertyList10Dictionary15addObjectForKeyINS_6StringEJRNSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEEEERT_NS3_17basic_string_viewIcS6_EEDpOT0_
+ __ZN12PropertyList10Dictionary15addObjectForKeyINS_7IntegerEJRjEEERT_NSt3__117basic_string_viewIcNS6_11char_traitsIcEEEEDpOT0_
+ __ZN12PropertyList10Dictionary15addObjectForKeyINS_7IntegerEJRmEEERT_NSt3__117basic_string_viewIcNS6_11char_traitsIcEEEEDpOT0_
+ __ZN12PropertyList10Dictionary15addObjectForKeyINS_7IntegerEJyEEERT_NSt3__117basic_string_viewIcNS5_11char_traitsIcEEEEDpOT0_
+ __ZN12PropertyList10Dictionary15addObjectForKeyIS0_JEEERT_NSt3__117basic_string_viewIcNS4_11char_traitsIcEEEEDpOT0_
+ __ZN12PropertyList10Dictionary18insertObjectForKeyENSt3__117basic_string_viewIcNS1_11char_traitsIcEEEERNS_6ObjectE
+ __ZN12_GLOBAL__N_119addSubCacheFileInfoEyRN12PropertyList5ArrayEP17dyld_cache_headerRNS_12CacheMappingENSt3__112basic_stringIcNS7_11char_traitsIcEENS7_9allocatorIcEEEE
+ __ZN12_GLOBAL__N_17mapFileENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES6_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendEPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B8nn190102ENS_24__uninitialized_size_tagEmRKS4_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B8nn190102ILi0EEEPKc
+ __ZNSt3__1plIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_12basic_stringIT_T0_T1_EEPKS6_RKS9_
+ __ZSt28__throw_bad_array_new_lengthB8nn190102v
+ __ZdlPv
+ __Znwm
+ ____ZN12_GLOBAL__N_113scavengeCacheEPKcR10ByteStream_block_invoke
+ _abort
+ _asprintf
+ _basename_r
+ _dirname_r
+ _open
+ _scavengeCache
+ _strdup
+ _uuid_is_null
+ _uuid_unparse_upper
+ scavengeCache
CStrings:
+ "%u"
+ "../uuids/"
+ ".plist"
+ "CacheScavenger.cpp"
+ "caches/names/"
+ "caches/uuids/"
+ "dscs"
+ "mapping != cacheMappings.end()"
+ "maps"
+ "names"
+ "prot"
+ "psze"
+ "scavengeCache"
+ "snme"
+ "uuids"
+ "voff"
```
