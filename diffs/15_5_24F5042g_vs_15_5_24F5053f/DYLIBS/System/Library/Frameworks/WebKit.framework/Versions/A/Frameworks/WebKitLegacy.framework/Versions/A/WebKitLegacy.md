## WebKitLegacy

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebKitLegacy.framework/Versions/A/WebKitLegacy`

```diff

-621.2.1.11.5
-  __TEXT.__text: 0x1838cc
-  __TEXT.__auth_stubs: 0x8d70
+621.2.3.11.1
+  __TEXT.__text: 0x1838e0
+  __TEXT.__auth_stubs: 0x8d60
   __TEXT.__objc_methlist: 0x10248
   __TEXT.__const: 0x672
-  __TEXT.__gcc_except_tab: 0x104e4
+  __TEXT.__gcc_except_tab: 0x104b0
   __TEXT.__cstring: 0x264f3
   __TEXT.__oslogstring: 0x141
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x8aa0
+  __TEXT.__unwind_info: 0x8aa8
   __TEXT.__objc_classname: 0x1d89
   __TEXT.__objc_methname: 0x1cfb1
   __TEXT.__objc_methtype: 0xa35c

   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x368
   __DATA_CONST.__objc_arraydata: 0x38
-  __AUTH_CONST.__auth_got: 0x46d0
+  __AUTH_CONST.__auth_got: 0x46c8
   __AUTH_CONST.__const: 0x5690
   __AUTH_CONST.__cfstring: 0xe540
   __AUTH_CONST.__objc_const: 0x11378

   __DATA_DIRTY.__objc_ivar: 0x110
   __DATA_DIRTY.__objc_data: 0x46a0
   __DATA_DIRTY.__data: 0x40
-  __DATA_DIRTY.__bss: 0x320
+  __DATA_DIRTY.__bss: 0x328
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/Carbon.framework/Versions/A/Carbon

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 7504
+  Functions: 7505
   Symbols:   15734
   CStrings:  8560
 
Symbols:
+ __ZN24WebResourceLoadScheduler12preconnectToERN7WebCore11FrameLoaderEONS0_15ResourceRequestENS0_23StoredCredentialsPolicyENS0_14LoaderStrategy28ShouldPreconnectAsFirstPartyEON3WTF8FunctionIFvRKNS0_13ResourceErrorEEEE
+ __ZN7WebCore16FontCascadeFonts11primaryFontERKNS_22FontCascadeDescriptionEPNS_12FontSelectorE
+ __ZN7WebCore16FontCascadeFonts23realizeFallbackRangesAtERKNS_22FontCascadeDescriptionEPNS_12FontSelectorEj
+ __ZNK7WebCore11FontCascade11primaryFontEv
+ __ZNK7WebCore13MediaStrategy32createMediaRecorderPrivateWriterENS_26MediaRecorderContainerTypeERNS_34MediaRecorderPrivateWriterListenerE
- __ZN24WebResourceLoadScheduler12preconnectToERN7WebCore11FrameLoaderERKN3WTF3URLENS0_23StoredCredentialsPolicyENS0_14LoaderStrategy28ShouldPreconnectAsFirstPartyEONS3_8FunctionIFvRKNS0_13ResourceErrorEEEE
- __ZN3JSC2VM14clearExceptionEv
- __ZN7WebCore16FontCascadeFonts11primaryFontERKNS_22FontCascadeDescriptionE
- __ZN7WebCore16FontCascadeFonts23realizeFallbackRangesAtERKNS_22FontCascadeDescriptionEj
- __ZNK7WebCore13MediaStrategy32createMediaRecorderPrivateWriterERKN3WTF6StringERNS_34MediaRecorderPrivateWriterListenerE
```
