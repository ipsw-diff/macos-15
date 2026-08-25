## Metal

> `/System/Library/Frameworks/Metal.framework/Versions/A/Metal`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-368.51.0.0.0
-  __TEXT.__text: 0x1a56ec
+368.52.0.0.0
+  __TEXT.__text: 0x1a5830
   __TEXT.__auth_stubs: 0x1c50
   __TEXT.__objc_methlist: 0x18304
   __TEXT.__gcc_except_tab: 0x92d4
Functions:
~ __ZN25MTLMetalScriptBuilderImpl13resetInternalEb : 188 -> 268
~ __ZN25MTLMetalScriptBuilderImpl18addComputePipelineEP28MTLComputePipelineDescriptor : 612 -> 664
~ __ZN25MTLMetalScriptBuilderImpl17addRenderPipelineEP27MTLRenderPipelineDescriptor : 900 -> 964
~ __ZN25MTLMetalScriptBuilderImpl21addMeshRenderPipelineEP31MTLMeshRenderPipelineDescriptor : 1144 -> 1220
~ __ZN25MTLMetalScriptBuilderImpl21addTileRenderPipelineEP31MTLTileRenderPipelineDescriptor : 612 -> 664
CStrings:
+ "01:05:30"
+ "Jul  3 2025"
+ "Jul  3 2025 01:05:30"
- "01:09:06"
- "Jun  6 2025"
- "Jun  6 2025 01:09:06"
```
