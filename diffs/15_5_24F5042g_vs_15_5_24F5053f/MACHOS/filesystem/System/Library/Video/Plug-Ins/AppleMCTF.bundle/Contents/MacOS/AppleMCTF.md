## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/Contents/MacOS/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-803.63.1.0.0
-  __TEXT.__text: 0x567b0
+803.71.1.0.0
+  __TEXT.__text: 0x56ad0
   __TEXT.__auth_stubs: 0xce0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x8
-  __TEXT.__cstring: 0x1f293
+  __TEXT.__cstring: 0x1f090
   __TEXT.__const: 0x118f8
   __TEXT.__gcc_except_tab: 0x490
   __TEXT.__objc_methname: 0xb
-  __TEXT.__unwind_info: 0x588
+  __TEXT.__unwind_info: 0x580
   __DATA_CONST.__auth_got: 0x680
   __DATA_CONST.__got: 0x440
   __DATA_CONST.__auth_ptr: 0x10

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 500
+  Functions: 499
   Symbols:   349
-  CStrings:  2415
+  CStrings:  2409
 
CStrings:
+ "%lld %d AVE %s: %s:%d fail to emit %d %d 0x%x %d | Proc: %lld Drop: %lld"
+ "%lld %d AVE %s: %s:%d fail to emit %d %d 0x%x %d | Proc: %lld Drop: %lld\n"
+ "%lld %d AVE %s: %s:%d frame drop %d %d 0x%x"
+ "%lld %d AVE %s: %s:%d frame drop %d %d 0x%x\n"
+ "20:31:17"
+ "803.71.1"
+ "Apr 10 2025"
- "%lld %d AVE %s: %s:%d ERROR: VTEncoderSessionEmitEncodedFrame failed. %d %d %d"
- "%lld %d AVE %s: %s:%d ERROR: VTEncoderSessionEmitEncodedFrame failed. %d %d %d\n"
- "%lld %d AVE %s: %s:%d m_VTEncoderSession has already been invalidated. Dropping frame %d %d"
- "%lld %d AVE %s: %s:%d m_VTEncoderSession has already been invalidated. Dropping frame %d %d\n"
- "%lld %d AVE %s: H264FrameRec ERROR: FigBlockBufferCreateWithMemoryBlock failed."
- "%lld %d AVE %s: H264FrameRec ERROR: FigBlockBufferCreateWithMemoryBlock failed.\n"
- "%lld %d AVE %s: H264FrameRec ERROR: FigSampleBufferCreate failed."
- "%lld %d AVE %s: H264FrameRec ERROR: FigSampleBufferCreate failed.\n"
- "%lld %d AVE %s: H264FrameRec: DROP F %d infoFlagsOut %d"
- "%lld %d AVE %s: H264FrameRec: DROP F %d infoFlagsOut %d\n"
- "22:27:58"
- "803.63.1"
- "Mar 26 2025"
```
