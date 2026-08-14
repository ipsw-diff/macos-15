## GeoServices

> `/System/Library/PrivateFrameworks/GeoServices.framework/Versions/A/GeoServices`

```diff

-1986.24.9.12.31
+1986.25.3.6.2
   __TEXT.__text: 0x1706d64
   __TEXT.__auth_stubs: 0x2c80
   __TEXT.__objc_methlist: 0xd10e4

   __TEXT.__const: 0x7f96e
   __TEXT.__cstring: 0x930c1
   __TEXT.__dlopen_cstrs: 0x1f9
-  __TEXT.__oslogstring: 0x1a29d
+  __TEXT.__oslogstring: 0x1a2a5
   __TEXT.__ustring: 0x156
   __TEXT.__unwind_info: 0x5aca0
   __TEXT.__objc_classname: 0x13f85
CStrings:
+ "Fetching coarse location for coordinate %{sensitive,geo:coordinate}.*P"
+ "Found matching polygon in underlying data. Snapping to representative point (%{sensitive,geo:coordinate}.*P)."
+ "Location is outside of the Mercator projection's bounds (%.2f -> %.2f). Snapping to nearest pole (%{sensitive,geo:coordinate}.*P)"
+ "Returning grid-snapped fallback location (%{sensitive,geo:coordinate}.*P)"
- "Fetching coarse location for coordinate %{private,geo:coordinate}.*P"
- "Found matching polygon in underlying data. Snapping to representative point (%{private,geo:coordinate}.*P)."
- "Location is outside of the Mercator projection's bounds (%.2f -> %.2f). Snapping to nearest pole (%{private,geo:coordinate}.*P)"
- "Returning grid-snapped fallback location (%{private,geo:coordinate}.*P)"
```
