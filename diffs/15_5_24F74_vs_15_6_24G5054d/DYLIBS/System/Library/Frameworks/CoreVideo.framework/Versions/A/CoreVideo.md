## CoreVideo

> `/System/Library/Frameworks/CoreVideo.framework/Versions/A/CoreVideo`

```diff

-682.6.0.0.0
-  __TEXT.__text: 0x48130
+692.1.0.0.0
+  __TEXT.__text: 0x480c0
   __TEXT.__auth_stubs: 0x1920
   __TEXT.__cstring: 0x133a1
   __TEXT.__objc_databytes: 0x483
Symbols:
+ __ZN20CVMetalBufferBacking4initEP15CVBufferBackingPv
- __ZN20CVMetalBufferBacking4initEP13CVImageBufferP15CVBufferBackingPv
Functions:
~ __ZN18CVMetalBufferCache35createBufferBackingFromImageBackingEPK13__CFAllocatorP13CVImageBufferP14CVImageBackingPi : 652 -> 628
~ __ZN20CVMetalBufferBacking5allocEPK13__CFAllocator : 144 -> 148
~ __ZN20CVMetalBufferBackingC1EPKv : 60 -> 64
~ __ZN20CVMetalBufferBacking8finalizeEv : 196 -> 148
~ __ZN20CVMetalBufferBacking4initEP13CVImageBufferP15CVBufferBackingPv -> __ZN20CVMetalBufferBacking4initEP15CVBufferBackingPv : 280 -> 232
```
