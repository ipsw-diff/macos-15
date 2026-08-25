## AudioCodecs

> `/System/Library/Components/AudioCodecs.component/Contents/MacOS/AudioCodecs`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`

```diff

-746.7.4.0.0
-  __TEXT.__text: 0x5a8bd8
+746.7.6.0.0
+  __TEXT.__text: 0x5a8bf8
   __TEXT.__auth_stubs: 0x1550
   __TEXT.__const: 0x2fa3ec
   __TEXT.__cstring: 0xaf13
Symbols:
+ __ZN4apac18ProfileLevelConfig24GetLevelFromCodecConfigsENS_7ProfileERKNSt3__16vectorINS2_10unique_ptrINS_10IASCConfigENS2_14default_deleteIS5_EEEENS2_9allocatorIS8_EEEE
- __ZNK4apac18ProfileLevelConfig24GetLevelFromCodecConfigsERKNSt3__16vectorINS1_10unique_ptrINS_10IASCConfigENS1_14default_deleteIS4_EEEENS1_9allocatorIS7_EEEE
Functions:
~ __ZN4apac12GlobalConfig11DeserializeER16TBitstreamReaderIjE : 5964 -> 5968
~ _mp3d_BitBufEnsureBits : 408 -> 412
~ __ZN27MP3DecoderWrapper_SpiritDSP11DecodeFrameEPhiPii : 9732 -> 9756
~ __ZNK4apac18ProfileLevelConfig24GetLevelFromCodecConfigsERKNSt3__16vectorINS1_10unique_ptrINS_10IASCConfigENS1_14default_deleteIS4_EEEENS1_9allocatorIS7_EEEE -> __ZN4apac18ProfileLevelConfig24GetLevelFromCodecConfigsENS_7ProfileERKNSt3__16vectorINS2_10unique_ptrINS_10IASCConfigENS2_14default_deleteIS5_EEEENS2_9allocatorIS8_EEEE : 320 -> 316
~ __ZN11APACEncoder10InitializeER11ACParamList : 7556 -> 7560
CStrings:
+ "20:50:40"
+ "Jul 15 2025"
- "22:31:14"
- "Jun 17 2025"
```
