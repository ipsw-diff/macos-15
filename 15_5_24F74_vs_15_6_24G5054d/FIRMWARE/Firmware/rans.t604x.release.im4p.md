## rans.t604x.release.im4p

> `Firmware/rans.t604x.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.idle_hooks`
- `__DATA.__const`
- `__DATA.__data`

```diff

   __TEXT.text_first: 0x4488
-  __TEXT.__text: 0x1e0bd8
+  __TEXT.__text: 0x1e14b8
   __TEXT.shared: 0xe954
   __TEXT.read: 0x75b0
-  __TEXT.__const: 0x6078
+  __TEXT.__const: 0x6068
   __TEXT.idle_hooks: 0x10
-  __TEXT.__cstring: 0x23fe7
+  __TEXT.__cstring: 0x241ba
   __TEXT.__chain_starts: 0x0
   __TEXT.__constructor: 0x0
   __TEXT._rtk_mtab: 0x540

   __DATA.__zerofill: 0x5b32c8
   Functions: 0
   Symbols:   0
-  CStrings:  3923
+  CStrings:  3931
 
CStrings:
+ "2077.140.13"
+ "2077.140.13~182"
+ "AppleStorageFirmware-2077.140.13~182"
+ "Illegal Sort Mode"
+ "MassScan: previous pilot scan was %d seconds ago, avoid scan this time"
+ "MassScan: previous scan was %d seconds ago, avoid scan this time"
+ "NPT BAD input state %u - expected %u or %u or %u"
+ "NPT NEW request, adding bands according to band sequence number with validityX100 < %u"
+ "NPT band %4u skipping: already in GCmust list"
+ "NPT band %4u skipping: validity > threshold"
+ "NPT band %4u, flow %u, seq %u, flags 0x%x, v %6u, GC must %u"
+ "NPT status %u, sort mode %u, flow selector %u, wAmpX100 %u, validityThresholdX100 = %u, n %u, newExtraMiB %u, #gcMust %u, out #bands %u, out SLC MiB %u"
+ "Null ptr passed for band seq sort preconditioning!"
+ "Null ptr passed for validity sort preconditioning!"
+ "[%2d,%2d] Panic Log write failed err=%s"
+ "async message CROSS_TEMP from msp: %u, thresholdCrossed: %u, measuredTemp %u"
+ "cross temp init tunnel %d, %d, %d, %d"
+ "sort mode %u not expected"
- "2077.120.76"
- "2077.120.76~361"
- "AppleStorageFirmware-2077.120.76~361"
- "MassScan: previous pilot scan was %lld seconds ago, avoid scan this time"
- "MassScan: previous scan was %lld seconds ago, avoid scan this time"
- "NPT BAD input state %u - expected %u or %u"
- "NPT status %u, wAmpX100 %u, n %u, newExtraMiB %u, #gcMust %u, out #bands %u, out SLC MiB %u"
- "Panic Log write mismatch. Expected: %d, got %d  lba: %x, wCmdeLogPage %d"
- "Unrecognized type %u"
- "cross temp init defaults %d, %d, %d, %d"
```
