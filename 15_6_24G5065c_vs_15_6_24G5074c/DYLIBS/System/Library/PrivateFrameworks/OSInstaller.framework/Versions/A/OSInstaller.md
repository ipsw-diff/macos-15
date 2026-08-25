## OSInstaller

> `/System/Library/PrivateFrameworks/OSInstaller.framework/Versions/A/OSInstaller`

```diff

-1591.140.4.0.0
-  __TEXT.__text: 0x5ffbc
+1591.140.6.501.1
+  __TEXT.__text: 0x60150
   __TEXT.__auth_stubs: 0x10b0
-  __TEXT.__objc_methlist: 0x370c
-  __TEXT.__cstring: 0xff65
+  __TEXT.__objc_methlist: 0x3724
+  __TEXT.__cstring: 0xffcb
   __TEXT.__gcc_except_tab: 0x23bc
   __TEXT.__ustring: 0x34
-  __TEXT.__const: 0x148
+  __TEXT.__const: 0x158
   __TEXT.__oslogstring: 0xe11
-  __TEXT.__unwind_info: 0xce8
+  __TEXT.__unwind_info: 0xcf0
   __TEXT.__eh_frame: 0xb4
   __TEXT.__objc_classname: 0x663
-  __TEXT.__objc_methname: 0xa87a
+  __TEXT.__objc_methname: 0xa8a1
   __TEXT.__objc_methtype: 0x9cf
-  __TEXT.__objc_stubs: 0x9a00
+  __TEXT.__objc_stubs: 0x9a40
   __DATA_CONST.__got: 0x7d0
   __DATA_CONST.__const: 0x270
   __DATA_CONST.__objc_classlist: 0x1f0
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2b10
+  __DATA_CONST.__objc_selrefs: 0x2b20
   __DATA_CONST.__objc_superrefs: 0x160
   __DATA_CONST.__objc_arraydata: 0x170
   __AUTH_CONST.__auth_got: 0x868
   __AUTH_CONST.__const: 0xa20
-  __AUTH_CONST.__cfstring: 0x64a0
+  __AUTH_CONST.__cfstring: 0x64c0
   __AUTH_CONST.__objc_const: 0x5720
   __AUTH_CONST.__objc_arrayobj: 0x168
   __AUTH_CONST.__objc_dictobj: 0x78

   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpartition2_dynamic.dylib
-  Functions: 1423
-  Symbols:   3816
-  CStrings:  3816
+  Functions: 1425
+  Symbols:   3822
+  CStrings:  3820
 
Symbols:
+ +[OSIUtilities enableDarkRebootAndPersist:]
+ +[OSIUtilities isDarkBoot]
+ GCC_except_table42
+ GCC_except_table49
+ _kDarkBootSysctl
+ _objc_msgSend$enableDarkRebootAndPersist:
+ _objc_msgSend$isDarkBoot
- GCC_except_table40
CStrings:
+ "-[OSITemplateMigrationController performTasks:]"
+ "Couldn't set %s: %d"
+ "Template Migration: Perform Tasks was invoked with no required tasks."
+ "enableDarkRebootAndPersist:"
+ "isDarkBoot"
- "Couldn't set dark reboot sysctl: %d"
```
