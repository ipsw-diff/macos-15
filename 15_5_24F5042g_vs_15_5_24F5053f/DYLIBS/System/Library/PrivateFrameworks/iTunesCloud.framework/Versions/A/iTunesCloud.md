## iTunesCloud

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Versions/A/iTunesCloud`

```diff

-4024.600.4.0.0
+4024.600.5.0.0
   __TEXT.__text: 0x2dd274
   __TEXT.__auth_stubs: 0x1280
   __TEXT.__objc_methlist: 0x1731c
   __TEXT.__const: 0x26598
   __TEXT.__dlopen_cstrs: 0x2ff
   __TEXT.__gcc_except_tab: 0x3290
-  __TEXT.__cstring: 0x167c1
+  __TEXT.__cstring: 0x167b1
   __TEXT.__oslogstring: 0x1e2e2
   __TEXT.__ustring: 0x8e
   __TEXT.__unwind_info: 0x6238
   __TEXT.__eh_frame: 0x84
-  __TEXT.__objc_classname: 0x3aa9
-  __TEXT.__objc_methname: 0x33940
+  __TEXT.__objc_classname: 0x3aa1
+  __TEXT.__objc_methname: 0x33938
   __TEXT.__objc_methtype: 0x78c6
   __TEXT.__objc_stubs: 0x1a740
   __DATA_CONST.__got: 0xf50

   - /usr/lib/libsqlite3.dylib
   Functions: 9646
   Symbols:   20610
-  CStrings:  13711
+  CStrings:  13712
 
Symbols:
+ +[ICBGTaskScheduler sharedTaskScheduler]
+ -[ICBGTaskScheduler .cxx_destruct]
+ -[ICBGTaskScheduler _init]
+ -[ICBGTaskScheduler _loadSavedTaskInfo]
+ -[ICBGTaskScheduler _postExpiredEvents]
+ -[ICBGTaskScheduler _saveTaskInfo]
+ -[ICBGTaskScheduler _scheduleNextTask]
+ -[ICBGTaskScheduler cancelTask:]
+ -[ICBGTaskScheduler hasScheduledTask:]
+ -[ICBGTaskScheduler registerForTask:handler:]
+ -[ICBGTaskScheduler scheduleRecurringTask:withInterval:afterDelay:withUserData:]
+ -[ICBGTaskScheduler scheduleTask:afterDelay:withUserData:]
+ OBJC_IVAR_$_ICBGTaskScheduler._lock
+ OBJC_IVAR_$_ICBGTaskScheduler._queue
+ OBJC_IVAR_$_ICBGTaskScheduler._registered
+ OBJC_IVAR_$_ICBGTaskScheduler._taskHandlers
+ OBJC_IVAR_$_ICBGTaskScheduler._taskInfoDictionaries
+ _OBJC_CLASS_$_ICBGTaskScheduler
+ _OBJC_METACLASS_$_ICBGTaskScheduler
+ __38-[ICBGTaskScheduler _scheduleNextTask]_block_invoke
+ __39-[ICBGTaskScheduler _postExpiredEvents]_block_invoke
+ __OBJC_$_CLASS_METHODS_ICBGTaskScheduler
+ __OBJC_$_CLASS_PROP_LIST_ICBGTaskScheduler
+ __OBJC_$_INSTANCE_METHODS_ICBGTaskScheduler
+ __OBJC_$_INSTANCE_VARIABLES_ICBGTaskScheduler
+ __OBJC_CLASS_RO_$_ICBGTaskScheduler
+ __OBJC_METACLASS_RO_$_ICBGTaskScheduler
+ ___38-[ICBGTaskScheduler _scheduleNextTask]_block_invoke
+ ___39-[ICBGTaskScheduler _postExpiredEvents]_block_invoke
+ ___40+[ICBGTaskScheduler sharedTaskScheduler]_block_invoke
- +[ICBackgroundTaskScheduler sharedTaskScheduler]
- -[ICBackgroundTaskScheduler .cxx_destruct]
- -[ICBackgroundTaskScheduler _init]
- -[ICBackgroundTaskScheduler _loadSavedTaskInfo]
- -[ICBackgroundTaskScheduler _postExpiredEvents]
- -[ICBackgroundTaskScheduler _saveTaskInfo]
- -[ICBackgroundTaskScheduler _scheduleNextTask]
- -[ICBackgroundTaskScheduler cancelTask:]
- -[ICBackgroundTaskScheduler hasScheduledTask:]
- -[ICBackgroundTaskScheduler registerForTask:handler:]
- -[ICBackgroundTaskScheduler scheduleRecurringTask:withInterval:afterDelay:withUserData:]
- -[ICBackgroundTaskScheduler scheduleTask:afterDelay:withUserData:]
- OBJC_IVAR_$_ICBackgroundTaskScheduler._lock
- OBJC_IVAR_$_ICBackgroundTaskScheduler._queue
- OBJC_IVAR_$_ICBackgroundTaskScheduler._registered
- OBJC_IVAR_$_ICBackgroundTaskScheduler._taskHandlers
- OBJC_IVAR_$_ICBackgroundTaskScheduler._taskInfoDictionaries
- _OBJC_CLASS_$_ICBackgroundTaskScheduler
- _OBJC_METACLASS_$_ICBackgroundTaskScheduler
- __46-[ICBackgroundTaskScheduler _scheduleNextTask]_block_invoke
- __47-[ICBackgroundTaskScheduler _postExpiredEvents]_block_invoke
- __OBJC_$_CLASS_METHODS_ICBackgroundTaskScheduler
- __OBJC_$_CLASS_PROP_LIST_ICBackgroundTaskScheduler
- __OBJC_$_INSTANCE_METHODS_ICBackgroundTaskScheduler
- __OBJC_$_INSTANCE_VARIABLES_ICBackgroundTaskScheduler
- __OBJC_CLASS_RO_$_ICBackgroundTaskScheduler
- __OBJC_METACLASS_RO_$_ICBackgroundTaskScheduler
- ___46-[ICBackgroundTaskScheduler _scheduleNextTask]_block_invoke
- ___47-[ICBackgroundTaskScheduler _postExpiredEvents]_block_invoke
- ___48+[ICBackgroundTaskScheduler sharedTaskScheduler]_block_invoke
CStrings:
+ "ICBGTaskScheduler"
+ "ICBGTaskScheduler.m"
+ "T@\"ICBGTaskScheduler\",R,N"
+ "com.apple.mediaservices.ICBGTaskScheduler.queue"
- "ICBackgroundTaskScheduler.m"
- "T@\"ICBackgroundTaskScheduler\",R,N"
- "com.apple.mediaservices.ICBackgroundTaskScheduler.queue"
```
