## com.apple.iokit.IOHIDFamily

> `com.apple.iokit.IOHIDFamily`

```diff

-2115.140.3.0.0
+2115.140.4.0.0
   __TEXT.__cstring: 0x3f60
   __TEXT.__const: 0x1468
-  __TEXT.__os_log: 0x3132
-  __TEXT_EXEC.__text: 0x8bae0
+  __TEXT.__os_log: 0x3188
+  __TEXT_EXEC.__text: 0x8bc20
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xbea
   __DATA.__common: 0xaf0

   __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__kalloc_var: 0xa0
   Functions: 2964
-  Symbols:   4280
-  CStrings:  949
+  Symbols:   4282
+  CStrings:  951
 
Symbols:
+ __ZZN19IOHIDElementPrivate12createReportEhPvPjPPS_E11_os_log_fmt
+ __ZZN19IOHIDElementPrivate12createReportEhPvPjPPS_E11_os_log_fmt_0
+ __ZZN19IOHIDElementPrivate14setCalibrationEjjjjjjiE21kalloc_type_view_2073
- __ZZN19IOHIDElementPrivate14setCalibrationEjjjjjjiE21kalloc_type_view_2061
Functions:
~ __ZN21IOHIDElementContainer12createReportE15IOHIDReportTypehP24IOBufferMemoryDescriptor : 272 -> 356
~ _HIDProcessReportItem : 616 -> 676
~ __ZN19IOHIDElementPrivate12createReportEhPvPjPPS_ : 704 -> 880
CStrings:
+ "Not enough space in buffer to write report %d < %d\n"
+ "Overflow when calculating endBit\n"
```
