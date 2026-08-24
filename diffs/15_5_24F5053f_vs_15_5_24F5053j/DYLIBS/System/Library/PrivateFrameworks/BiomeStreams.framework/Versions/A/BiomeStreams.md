## BiomeStreams

> `/System/Library/PrivateFrameworks/BiomeStreams.framework/Versions/A/BiomeStreams`

```diff

-166.22.1.0.0
-  __TEXT.__text: 0x49169c
+166.23.0.1.0
+  __TEXT.__text: 0x491774
   __TEXT.__auth_stubs: 0x2140
   __TEXT.__objc_methlist: 0x1584c
   __TEXT.__const: 0xaa324
-  __TEXT.__cstring: 0x353e8
+  __TEXT.__cstring: 0x353f8
   __TEXT.__gcc_except_tab: 0x1524
   __TEXT.__oslogstring: 0xc310
   __TEXT.__dlopen_cstrs: 0x680

   __TEXT.__unwind_info: 0xcdc0
   __TEXT.__eh_frame: 0xdb78
   __TEXT.__objc_classname: 0x281a
-  __TEXT.__objc_methname: 0x1da32
+  __TEXT.__objc_methname: 0x1da3c
   __TEXT.__objc_methtype: 0x3e26
   __TEXT.__objc_stubs: 0x11ea0
   __DATA_CONST.__got: 0x1120
Symbols:
+ -[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:timestamp:storeEvent:]
+ __94-[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:timestamp:storeEvent:]_block_invoke
+ ___94-[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:timestamp:storeEvent:]_block_invoke
+ _objc_msgSend$receiveInputForSubscription:streamIdentifier:timestamp:storeEvent:
- -[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:storeEvent:]
- __84-[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:storeEvent:]_block_invoke
- ___84-[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:storeEvent:]_block_invoke
- _objc_msgSend$receiveInputForSubscription:streamIdentifier:storeEvent:
Functions:
~ -[BMDaemon sendEventWithStreamIdentifier:timestamp:account:remoteName:storeEvent:] : 3004 -> 3008
~ __82-[BMDaemon sendEventWithStreamIdentifier:timestamp:account:remoteName:storeEvent:]_block_invoke.48 : 280 -> 284
~ __38-[BMComputePublisherServer subscribe:]_block_invoke.19 : 196 -> 200
~ -[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:storeEvent:] -> -[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:timestamp:storeEvent:] : 832 -> 892
~ -[BMComputeSubscription initialBookmarkTimestamp] : 120 -> 144
~ -[BMComputePublisherClient _handleEventWithPayload:] : 984 -> 1104
CStrings:
+ "-[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:timestamp:storeEvent:]"
+ "receiveInputForSubscription:streamIdentifier:timestamp:storeEvent:"
- "-[BMComputePublisherServer receiveInputForSubscription:streamIdentifier:storeEvent:]"
- "receiveInputForSubscription:streamIdentifier:storeEvent:"
```
