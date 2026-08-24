## libwebrtc.dylib

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebCore.framework/Versions/A/Frameworks/libwebrtc.dylib`

```diff

-621.2.5.11.8
-  __TEXT.__text: 0xa8820c
+621.3.6.1.0
+  __TEXT.__text: 0xa88464
   __TEXT.__auth_stubs: 0x13e0
   __TEXT.__objc_methlist: 0x14e4
   __TEXT.__const: 0xb3468
-  __TEXT.__cstring: 0x544e7
+  __TEXT.__cstring: 0x54eb0
   __TEXT.__gcc_except_tab: 0x1820
   __TEXT.__unwind_info: 0x3660
   __TEXT.__eh_frame: 0x1178

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 18198
-  Symbols:   23188
+  Functions: 18201
+  Symbols:   23191
   CStrings:  9503
 
Symbols:
+ __ZN6dcsctp15OutstandingData23ExpireOutstandingChunksEN6webrtc9TimestampE
+ __ZNSt3__15dequeIN6dcsctp15OutstandingData4ItemENS_9allocatorIS3_EEE12emplace_backIJN6webrtc11StrongAliasINS1_20OutgoingMessageIdTagEjEENS1_4DataENS8_9TimestampENS1_14MaxRetransmitsESD_NS1_11LifecycleIdEEEERS3_DpOT_
+ __ZNSt3__15dequeIN6dcsctp15OutstandingData4ItemENS_9allocatorIS3_EEED2B8sn190102Ev
Functions:
~ __ZN6dcsctp15OutstandingData13AbandonAllForERKNS0_4ItemE : 1032 -> 832
+ __ZNSt3__15dequeIN6dcsctp15OutstandingData4ItemENS_9allocatorIS3_EEE12emplace_backIJN6webrtc11StrongAliasINS1_20OutgoingMessageIdTagEjEENS1_4DataENS8_9TimestampENS1_14MaxRetransmitsESD_NS1_11LifecycleIdEEEERS3_DpOT_
+ __ZN6dcsctp15OutstandingData23ExpireOutstandingChunksEN6webrtc9TimestampE
+ __ZNSt3__16__treeIN6dcsctp23UnwrappedSequenceNumberIN6webrtc11StrongAliasINS1_6TSNTagEjEEEENS_4lessIS7_EENS_9allocatorIS7_EEE12__find_equalIS7_EERPNS_16__tree_node_baseIPvEENS_21__tree_const_iteratorIS7_PNS_11__tree_nodeIS7_SF_EElEERPNS_15__tree_end_nodeISH_EESI_RKT_
~ __ZN6dcsctp24TransmissionControlBlock19SendBufferedPacketsERNS_10SctpPacket7BuilderEN6webrtc9TimestampE : 1608 -> 1416
~ __ZN6dcsctp24TransmissionControlBlockD2Ev : 1384 -> 988
~ _vp8e_init : 512 -> 524
```
