## MailUI

> `/System/Library/PrivateFrameworks/MailUI.framework/Versions/A/MailUI`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-3826.600.15.1.1
-  __TEXT.__text: 0x2300d4
+3826.600.32.0.0
+  __TEXT.__text: 0x2300d0
   __TEXT.__auth_stubs: 0x3e10
   __TEXT.__objc_methlist: 0xe884
   __TEXT.__cstring: 0xe425

   __TEXT.__unwind_info: 0x5388
   __TEXT.__eh_frame: 0x1b80
   __TEXT.__objc_classname: 0x1ade
-  __TEXT.__objc_methname: 0x2b2ca
+  __TEXT.__objc_methname: 0x2b2b7
   __TEXT.__objc_methtype: 0x7161
   __TEXT.__objc_stubs: 0x190e0
   __DATA_CONST.__got: 0x1d18

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 11285
   Symbols:   12901
-  CStrings:  9826
+  CStrings:  9825
 
Functions:
~ __78-[MUIMessageListUnbundledSectionDataSource _configureCell:atIndexPath:itemID:]_block_invoke.17.cold.1 : 256 -> 252
CStrings:
+ "Failed to obtain messageListItem for itemID:%{public}@ at indexPath:%{public}@ in messageList:%p with error:%{public}@"
- "Failed to obtain messageListItem for itemID:%{public}@ at indexPath:%{public}@ in messageList:%p with error:%@"
- "T@\"EMCategory\",R,N"
```
