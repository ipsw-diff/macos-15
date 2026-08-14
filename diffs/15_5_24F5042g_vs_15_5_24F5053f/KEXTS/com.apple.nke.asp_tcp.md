## com.apple.nke.asp_tcp

> `com.apple.nke.asp_tcp`

```diff

-289.0.0.0.0
+290.0.0.0.0
   __TEXT.__const: 0xa0
-  __TEXT.__cstring: 0x28c6
-  __TEXT_EXEC.__text: 0x7d2c
+  __TEXT.__cstring: 0x287c
+  __TEXT_EXEC.__text: 0x7bb8
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x378
   __DATA.__common: 0x20

   __DATA_CONST.__kalloc_type: 0x440
   Functions: 114
   Symbols:   268
-  CStrings:  259
+  CStrings:  258
 
Symbols:
+ CheckReqQueueSize.kalloc_type_view_2958
+ CheckReqQueueSize.kalloc_type_view_2966
+ CheckSendSleep.kalloc_type_view_6080
+ CheckSendSleep.kalloc_type_view_6096
+ CheckSendSleep.kalloc_type_view_6118
+ CheckSendSleep.kalloc_type_view_6134
+ Detach.kalloc_type_view_3494
+ FreeCBPTR.kalloc_type_view_3538
+ FreeCBPTR.kalloc_type_view_3545
+ FreeReplyInfo.kalloc_type_view_5529
+ GetReqInfo.kalloc_type_view_2459
+ GetReqInfo.kalloc_type_view_2505
+ Request.kalloc_type_view_4557
+ Request.kalloc_type_view_4565
+ Request.kalloc_type_view_4764
+ SendSleepPkt.kalloc_type_view_6059
+ asp_tcp_get_read_thread.kalloc_type_view_3120
- CheckReqQueueSize.kalloc_type_view_2970
- CheckReqQueueSize.kalloc_type_view_2978
- CheckSendSleep.kalloc_type_view_6108
- CheckSendSleep.kalloc_type_view_6124
- CheckSendSleep.kalloc_type_view_6146
- CheckSendSleep.kalloc_type_view_6162
- Detach.kalloc_type_view_3510
- FreeCBPTR.kalloc_type_view_3554
- FreeCBPTR.kalloc_type_view_3561
- FreeReplyInfo.kalloc_type_view_5557
- GetReqInfo.kalloc_type_view_2462
- GetReqInfo.kalloc_type_view_2508
- Request.kalloc_type_view_4573
- Request.kalloc_type_view_4581
- Request.kalloc_type_view_4785
- SendSleepPkt.kalloc_type_view_6087
- asp_tcp_get_read_thread.kalloc_type_view_3132
Functions:
~ _asp_tcp_usr_detach : 1016 -> 1008
~ _asp_tcp_user_sorecv : 1116 -> 1084
~ _HoldPendingReqs : 332 -> 288
~ _CancelOneRequestLocked : 252 -> 200
~ _UserSend : 2084 -> 2004
~ _FreeReplyInfo : 148 -> 96
~ _asp_tcp_read_thread : 3184 -> 3132
~ _ReplayPendingReqs : 856 -> 804
CStrings:
+ "1112212222221222"
- "11122122222212222"
- "FreeReplyInfo: freeing a replyInfo that has use count of %d != 0, so %p\n"
```
