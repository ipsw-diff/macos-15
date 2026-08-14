## libsystem_malloc.dylib

> `/usr/lib/system/libsystem_malloc.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-715.120.10.0.0
-  __TEXT.__text: 0x3abcc
+715.120.12.0.0
+  __TEXT.__text: 0x3abc0
   __TEXT.__auth_stubs: 0x710
   __TEXT.__const: 0x5b5
   __TEXT.__cstring: 0x96b1
Functions:
~ _xzm_main_malloc_zone_create : 5828 -> 5816
CStrings:
+ "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)body < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:2036)"
+ "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:2035)"
+ "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:2137)"
+ "BUG IN LIBMALLOC: malloc assertion \"data_start < ptr_start || data_start >= ptr_start + ptr_reservation_size\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:1089)"
- "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)body < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:2004)"
- "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:2003)"
- "BUG IN LIBMALLOC: malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:2105)"
- "BUG IN LIBMALLOC: malloc assertion \"data_start < ptr_start || data_start >= ptr_start + ptr_reservation_size\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc/src/xzone/xzone_segment.c:1057)"
```
