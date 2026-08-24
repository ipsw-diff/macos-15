## spindump

> `/usr/sbin/spindump`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-383.8.0.0.0
-  __TEXT.__text: 0xe0a84
-  __TEXT.__auth_stubs: 0x1450
-  __TEXT.__objc_stubs: 0x4840
+383.17.0.0.0
+  __TEXT.__text: 0xe211c
+  __TEXT.__auth_stubs: 0x1460
+  __TEXT.__objc_stubs: 0x4820
   __TEXT.__objc_methlist: 0xca4
   __TEXT.__const: 0x2a8
-  __TEXT.__oslogstring: 0x2f523
-  __TEXT.__cstring: 0x18bdb
+  __TEXT.__oslogstring: 0x2f663
+  __TEXT.__cstring: 0x18cb2
   __TEXT.__objc_classname: 0x146
   __TEXT.__objc_methtype: 0x593
-  __TEXT.__gcc_except_tab: 0x31a0
-  __TEXT.__objc_methname: 0x47e4
-  __TEXT.__unwind_info: 0x14f0
-  __DATA_CONST.__auth_got: 0xa38
+  __TEXT.__gcc_except_tab: 0x3570
+  __TEXT.__objc_methname: 0x47b2
+  __TEXT.__unwind_info: 0x1510
+  __DATA_CONST.__auth_got: 0xa40
   __DATA_CONST.__got: 0x330
   __DATA_CONST.__auth_ptr: 0x40
-  __DATA_CONST.__const: 0x1f10
-  __DATA_CONST.__cfstring: 0xc440
+  __DATA_CONST.__const: 0x1f70
+  __DATA_CONST.__cfstring: 0xc500
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x88

   __DATA_CONST.__objc_arraydata: 0x48
   __DATA_CONST.__objc_arrayobj: 0x48
   __DATA.__objc_const: 0x2560
-  __DATA.__objc_selrefs: 0x12d8
+  __DATA.__objc_selrefs: 0x12d0
   __DATA.__objc_ivar: 0x284
   __DATA.__objc_data: 0x5f0
   __DATA.__data: 0x1c

   - /usr/lib/libsystemstats.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2464
-  Symbols:   439
-  CStrings:  4720
+  Functions: 2480
+  Symbols:   440
+  CStrings:  4729
 
Symbols:
+ ___snprintf_chk
CStrings:
+ "\n%s [%d] output exceeded %llu bytes, truncating"
+ "\n%s [%d] timed out after %llus, truncating"
+ "%s [%d]: No ddt output for resource exhaustion report"
+ "%s [%d]: No lsof output for resource exhaustion report"
+ "%{public}s [%d]: No ddt output for resource exhaustion report"
+ "%{public}s [%d]: No lsof output for resource exhaustion report"
+ "Child %s [%d] output exceeded %llu bytes"
+ "Child %s [%d] timed out after %llus"
+ "Child [%d] exited"
+ "No ddt output for resource exhaustion report"
+ "No lsof output for resource exhaustion report"
+ "Unable to format: %s [%d]: No ddt output for resource exhaustion report"
+ "Unable to format: %s [%d]: No lsof output for resource exhaustion report"
+ "Unable to format: Child %s [%d] output exceeded %llu bytes"
+ "Unable to format: Child %s [%d] timed out after %llus"
+ "Unable to format: Child [%d] exited"
+ "Unable to format: No ddt output for resource exhaustion report"
+ "Unable to format: No lsof output for resource exhaustion report"
+ "Unable to format: Waiting for child %s [%d]..."
+ "Waiting for child %s [%d]..."
- "%s [%d]: Unable to convert ddt output to NSString: %s"
- "%s [%d]: Unable to convert lsof output to NSString: %s"
- "%{public}s [%d]: Unable to convert ddt output to NSString: %s"
- "%{public}s [%d]: Unable to convert lsof output to NSString: %s"
- "Unable to convert ddt output to NSString: %s"
- "Unable to convert lsof output to NSString: %s"
- "Unable to format: %s [%d]: Unable to convert ddt output to NSString: %s"
- "Unable to format: %s [%d]: Unable to convert lsof output to NSString: %s"
- "Unable to format: Unable to convert ddt output to NSString: %s"
- "Unable to format: Unable to convert lsof output to NSString: %s"
- "initWithBytesNoCopy:length:encoding:freeWhenDone:"
```
