## com.apple.telemetry

> `/System/Library/UserEventPlugins/com.apple.telemetry.plugin/Contents/MacOS/com.apple.telemetry`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_intobj`

```diff

-498.120.2.0.0
-  __TEXT.__text: 0x8cf4
+498.140.3.0.0
+  __TEXT.__text: 0x903c
   __TEXT.__auth_stubs: 0x650
   __TEXT.__objc_stubs: 0x320
   __TEXT.__const: 0x150
-  __TEXT.__gcc_except_tab: 0x26c
+  __TEXT.__gcc_except_tab: 0x27c
   __TEXT.__cstring: 0x9ad
-  __TEXT.__oslogstring: 0x3fd4
+  __TEXT.__oslogstring: 0x42a3
   __TEXT.__objc_classname: 0x3
   __TEXT.__objc_methname: 0x202
-  __TEXT.__unwind_info: 0x158
+  __TEXT.__unwind_info: 0x148
   __DATA.__auth_got: 0x338
   __DATA.__got: 0xc0
   __DATA.__auth_ptr: 0x8

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsystemstats.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 148
+  Functions: 149
   Symbols:   134
-  CStrings:  258
+  CStrings:  262
 
CStrings:
+ "PMI adjustment: Have a pending change to rate %llu->%llu and/or override %d->%d, not checking daily budget"
+ "PMI adjustment: No compressed bytes written since last cleanup (%llu uncompressed), assuming compression ratio of 1.0. time_since_cleanup:%.0fs time_since_adjustment:%.0fs all_bytes_since_cleanup:%llu all_bytes_since_adjustment:%llu pmi_percent:%.0f%% pmi_interval:%llu quota:%llu"
+ "PMI adjustment: projected_pmi_remaining_compressed_bytes_written_in_the_day is 0, resetting to defaults. time_since_cleanup:%.0fs time_since_adjustment:%.0fs all_bytes_since_cleanup:%llu all_bytes_since_adjustment:%llu pmi_percent:%.0f%% pmi_interval:%llu quota:%llu"
+ "pmi_interval_to_equal_nonpmi_datarate:%llu (no non-PMI, so max)"
```
