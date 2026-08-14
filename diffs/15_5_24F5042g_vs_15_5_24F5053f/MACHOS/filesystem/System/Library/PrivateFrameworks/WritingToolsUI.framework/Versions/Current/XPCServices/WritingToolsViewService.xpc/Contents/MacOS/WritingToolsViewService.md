## WritingToolsViewService

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/Versions/Current/XPCServices/WritingToolsViewService.xpc/Contents/MacOS/WritingToolsViewService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-44.502.0.0.0
-  __TEXT.__text: 0x152008
-  __TEXT.__auth_stubs: 0x48c0
+44.504.1.0.0
+  __TEXT.__text: 0x1534d4
+  __TEXT.__auth_stubs: 0x48d0
   __TEXT.__objc_methlist: 0xe44
   __TEXT.__const: 0xaf04
-  __TEXT.__cstring: 0x703c
+  __TEXT.__cstring: 0x708c
   __TEXT.__swift5_typeref: 0x17c1a
   __TEXT.__constg_swiftt: 0x4860
   __TEXT.__swift5_reflstr: 0x2b16

   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__swift5_protos: 0x1c
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x44b0
-  __TEXT.__eh_frame: 0x62d4
-  __DATA_CONST.__auth_got: 0x2460
+  __TEXT.__unwind_info: 0x44a8
+  __TEXT.__eh_frame: 0x62dc
+  __DATA_CONST.__auth_got: 0x2468
   __DATA_CONST.__got: 0x1278
-  __DATA_CONST.__auth_ptr: 0x19c8
-  __DATA_CONST.__const: 0x70b0
+  __DATA_CONST.__auth_ptr: 0x1a10
+  __DATA_CONST.__const: 0x70d8
   __DATA_CONST.__objc_classlist: 0x138
   __DATA_CONST.__objc_protolist: 0xf0
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 6225
+  Functions: 6227
   Symbols:   374
-  CStrings:  1448
+  CStrings:  1447
 
CStrings:
+ "\n\nWhen generating an image, just show the image. DO NOT comment on the image or how you generated it, leaving the \"body\" field of the JSON output as an empty string if the description of the image is the only content you would put in that field. You should however include a \"refinements\" field with a list of potential refinements for the image. If the user requests text and an image, make sure you ACTUALLY generate the image.\n\n*Phase 1*: Understand input.\n\n1. Carefully read the user's prompt and decide if there is enough information to produce a personalized response.\n    - Take into account any attachments that the user may have provided.\n    - If you identify the missing information necessary to complete the document, passing them in the `"
- "\n\nWhen generating an image, just show the image. DO NOT comment on the image or how you generated it, leaving the \"body\" field of the JSON output blank if the description of the image is the only content you would put in that field. If the user requests text and an image, make sure you ACTUALLY generate the image.\n\n*Phase 1*: Understand input.\n\n1. Carefully read the user's prompt and decide if there is enough information to produce a personalized response.\n    - Take into account any attachments that the user may have provided.\n    - If you identify the missing information necessary to complete the document, passing them in the `"
- "ChatGPT Suggestions"
```
