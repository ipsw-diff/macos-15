## com.apple.nke.asp_tcp

> `com.apple.nke.asp_tcp`

```diff

-290.0.0.0.0
+292.0.0.0.0
   __TEXT.__const: 0xa0
-  __TEXT.__cstring: 0x2886
-  __TEXT_EXEC.__text: 0x7bb8
+  __TEXT.__cstring: 0x28d0
+  __TEXT_EXEC.__text: 0x7d44
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x378
   __DATA.__common: 0x20

   __DATA_CONST.__kalloc_type: 0x440
   Functions: 114
   Symbols:   268
-  CStrings:  258
+  CStrings:  259
 
Symbols:
+ CheckReqQueueSize.kalloc_type_view_2970
+ CheckReqQueueSize.kalloc_type_view_2978
+ CheckSendSleep.kalloc_type_view_6112
+ CheckSendSleep.kalloc_type_view_6128
+ CheckSendSleep.kalloc_type_view_6150
+ CheckSendSleep.kalloc_type_view_6166
+ Detach.kalloc_type_view_3510
+ FreeCBPTR.kalloc_type_view_3554
+ FreeCBPTR.kalloc_type_view_3561
+ FreeReplyInfo.kalloc_type_view_5561
+ GetReqInfo.kalloc_type_view_2462
+ GetReqInfo.kalloc_type_view_2508
+ Request.kalloc_type_view_4577
+ Request.kalloc_type_view_4585
+ Request.kalloc_type_view_4789
+ SendSleepPkt.kalloc_type_view_6091
+ asp_tcp_get_read_thread.kalloc_type_view_3132
- CheckReqQueueSize.kalloc_type_view_2958
- CheckReqQueueSize.kalloc_type_view_2966
- CheckSendSleep.kalloc_type_view_6080
- CheckSendSleep.kalloc_type_view_6096
- CheckSendSleep.kalloc_type_view_6118
- CheckSendSleep.kalloc_type_view_6134
- Detach.kalloc_type_view_3494
- FreeCBPTR.kalloc_type_view_3538
- FreeCBPTR.kalloc_type_view_3545
- FreeReplyInfo.kalloc_type_view_5529
- GetReqInfo.kalloc_type_view_2459
- GetReqInfo.kalloc_type_view_2505
- Request.kalloc_type_view_4557
- Request.kalloc_type_view_4565
- Request.kalloc_type_view_4764
- SendSleepPkt.kalloc_type_view_6059
- asp_tcp_get_read_thread.kalloc_type_view_3120
Functions:
~ _asp_tcp_usr_detach : 1008 -> 1016
~ _asp_tcp_user_sorecv : 1084 -> 1116
~ _HoldPendingReqs : 288 -> 332
~ _CancelOneRequestLocked : 200 -> 252
~ _UserSend : 2004 -> 2084
~ _FreeReplyInfo : 96 -> 148
~ _asp_tcp_read_thread : 3132 -> 3184
~ _ReplayPendingReqs : 804 -> 856
~ _Reply : 1516 -> 1540
CStrings:
+ "11122122222212222"
+ "FreeReplyInfo: freeing a replyInfo that has use count of %d != 0, so %p\n"
- "1112212222221222"
```
