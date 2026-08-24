## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/Versions/A/CoreSpeechFoundation`

```diff

-3405.29.3.0.0
-  __TEXT.__text: 0xb7000
+3406.12.1.0.0
+  __TEXT.__text: 0xb8224
   __TEXT.__auth_stubs: 0x1ba0
-  __TEXT.__objc_methlist: 0xb8e0
+  __TEXT.__objc_methlist: 0xb9a0
   __TEXT.__const: 0x848
   __TEXT.__dlopen_cstrs: 0xc6
   __TEXT.__constg_swiftt: 0x240
   __TEXT.__swift5_typeref: 0x185
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_types: 0x1c
-  __TEXT.__cstring: 0x12ecc
+  __TEXT.__cstring: 0x130cd
   __TEXT.__swift5_fieldmd: 0x128
   __TEXT.__swift5_reflstr: 0x84
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_proto: 0x8
-  __TEXT.__gcc_except_tab: 0x31fc
-  __TEXT.__oslogstring: 0xcd7a
-  __TEXT.__unwind_info: 0x3108
+  __TEXT.__gcc_except_tab: 0x32a4
+  __TEXT.__oslogstring: 0xcf7c
+  __TEXT.__unwind_info: 0x3148
   __TEXT.__eh_frame: 0xe8
-  __TEXT.__objc_classname: 0x1a52
-  __TEXT.__objc_methname: 0x1f027
-  __TEXT.__objc_methtype: 0x42ce
-  __TEXT.__objc_stubs: 0xfa40
-  __DATA_CONST.__got: 0xba0
-  __DATA_CONST.__const: 0xe70
+  __TEXT.__objc_classname: 0x1a74
+  __TEXT.__objc_methname: 0x1f19b
+  __TEXT.__objc_methtype: 0x4304
+  __TEXT.__objc_stubs: 0xfae0
+  __DATA_CONST.__got: 0xb88
+  __DATA_CONST.__const: 0xea8
   __DATA_CONST.__objc_classlist: 0x690
   __DATA_CONST.__objc_catlist: 0x58
-  __DATA_CONST.__objc_protolist: 0x188
+  __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x65d0
+  __DATA_CONST.__objc_selrefs: 0x6610
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x4d8
   __DATA_CONST.__objc_arraydata: 0x198
   __AUTH_CONST.__auth_got: 0xde8
-  __AUTH_CONST.__const: 0x31b0
-  __AUTH_CONST.__cfstring: 0x8680
-  __AUTH_CONST.__objc_const: 0x12178
+  __AUTH_CONST.__const: 0x3230
+  __AUTH_CONST.__cfstring: 0x86a0
+  __AUTH_CONST.__objc_const: 0x122a8
   __AUTH_CONST.__objc_dictobj: 0x1e0
   __AUTH_CONST.__objc_intobj: 0x300
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_floatobj: 0x1b0
   __AUTH.__objc_data: 0x4258
   __AUTH.__data: 0x2d0
-  __DATA.__objc_ivar: 0xc00
-  __DATA.__data: 0x12a8
-  __DATA.__bss: 0xc30
+  __DATA.__objc_ivar: 0xc0c
+  __DATA.__data: 0x1308
+  __DATA.__bss: 0xc50
   __DATA.__common: 0x68
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
-  - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4520
-  Symbols:   10540
-  CStrings:  8200
+  Functions: 4539
+  Symbols:   10578
+  CStrings:  8237
 
Symbols:
+ +[CSSecureSessionHandler sharedHandler]
+ +[CSSecureSessionHandler siriEnablementSessionAssertionUUID]
+ -[CSAudioProvider secureSessionAssertionUUID]
+ -[CSAudioProvider setSecureSessionAssertionUUID:]
+ -[CSAudioRecorder CSSystemDaemonDisconnected]
+ -[CSLaunchAgentXPCClient activateSecureSession:error:]
+ -[CSLaunchAgentXPCClient duckAudioDeviceWithDeviceID:duckedLevel:rampDuration:]
+ -[CSLaunchAgentXPCClient resetAVVC]
+ -[CSLaunchAgentXPCClient setAlertSoundFromURL:forType:]
+ -[CSLaunchAgentXPCClient userSessionActivateMonitor:didReceivedUserSessionActiveHasChanged:]
+ -[CSSecureSessionHandler .cxx_destruct]
+ -[CSSecureSessionHandler CSAudioServerCrashMonitorDidReceiveServerCrash:]
+ -[CSSecureSessionHandler CSAudioServerCrashMonitorDidReceiveServerRestart:]
+ -[CSSecureSessionHandler CSSiriEnabledMonitor:didReceiveEnabled:]
+ -[CSSecureSessionHandler CSSystemDaemonStateMonitorDidReceiveSysDaemonCrash:]
+ -[CSSecureSessionHandler CSSystemDaemonStateMonitorDidReceiveSysDaemonRestartFromCrash:]
+ -[CSSecureSessionHandler _activateSecureSessionIfNeeded]
+ -[CSSecureSessionHandler _deactivateSecureSessionIfNeeded]
+ -[CSSecureSessionHandler acquireSecureSessionAssertionWithUUID:]
+ -[CSSecureSessionHandler assertionSet]
+ -[CSSecureSessionHandler init]
+ -[CSSecureSessionHandler queue]
+ -[CSSecureSessionHandler releaseAllSecureSessionAssertions]
+ -[CSSecureSessionHandler releaseSecureSessionAssertionWithUUID:]
+ -[CSSecureSessionHandler setAssertionSet:]
+ -[CSSecureSessionHandler setQueue:]
+ -[CSSecureSessionHandler start]
+ -[CSSystemDaemonStateMonitor currentSystemDaemonState]
+ GCC_except_table1005
+ GCC_except_table1012
+ GCC_except_table1290
+ GCC_except_table1319
+ GCC_except_table1408
+ GCC_except_table1410
+ GCC_except_table1411
+ GCC_except_table1413
+ GCC_except_table1414
+ GCC_except_table1415
+ GCC_except_table1418
+ GCC_except_table1584
+ GCC_except_table1800
+ GCC_except_table1801
+ GCC_except_table1802
+ GCC_except_table1803
+ GCC_except_table1807
+ GCC_except_table1810
+ GCC_except_table1811
+ GCC_except_table1820
+ GCC_except_table1828
+ GCC_except_table1829
+ GCC_except_table1893
+ GCC_except_table1898
+ GCC_except_table1970
+ GCC_except_table2010
+ GCC_except_table2011
+ GCC_except_table2013
+ GCC_except_table2014
+ GCC_except_table2021
+ GCC_except_table2031
+ GCC_except_table2044
+ GCC_except_table2087
+ GCC_except_table2158
+ GCC_except_table2256
+ GCC_except_table2293
+ GCC_except_table2431
+ GCC_except_table2435
+ GCC_except_table2503
+ GCC_except_table2514
+ GCC_except_table2516
+ GCC_except_table2521
+ GCC_except_table2523
+ GCC_except_table2538
+ GCC_except_table2545
+ GCC_except_table2547
+ GCC_except_table2565
+ GCC_except_table2586
+ GCC_except_table2626
+ GCC_except_table2685
+ GCC_except_table2687
+ GCC_except_table2688
+ GCC_except_table270
+ GCC_except_table280
+ GCC_except_table2830
+ GCC_except_table2958
+ GCC_except_table2966
+ GCC_except_table2985
+ GCC_except_table2988
+ GCC_except_table2990
+ GCC_except_table2991
+ GCC_except_table3014
+ GCC_except_table3056
+ GCC_except_table3149
+ GCC_except_table3174
+ GCC_except_table3207
+ GCC_except_table3208
+ GCC_except_table3209
+ GCC_except_table3210
+ GCC_except_table3233
+ GCC_except_table3246
+ GCC_except_table339
+ GCC_except_table3403
+ GCC_except_table3463
+ GCC_except_table3477
+ GCC_except_table3519
+ GCC_except_table3520
+ GCC_except_table3553
+ GCC_except_table3554
+ GCC_except_table3556
+ GCC_except_table3559
+ GCC_except_table3560
+ GCC_except_table3561
+ GCC_except_table3581
+ GCC_except_table3584
+ GCC_except_table3586
+ GCC_except_table3587
+ GCC_except_table3588
+ GCC_except_table3590
+ GCC_except_table3623
+ GCC_except_table3625
+ GCC_except_table3626
+ GCC_except_table3627
+ GCC_except_table3628
+ GCC_except_table363
+ GCC_except_table3685
+ GCC_except_table3733
+ GCC_except_table3739
+ GCC_except_table3794
+ GCC_except_table3795
+ GCC_except_table3802
+ GCC_except_table3803
+ GCC_except_table3804
+ GCC_except_table3805
+ GCC_except_table3807
+ GCC_except_table3808
+ GCC_except_table382
+ GCC_except_table383
+ GCC_except_table3830
+ GCC_except_table3831
+ GCC_except_table3832
+ GCC_except_table3834
+ GCC_except_table3835
+ GCC_except_table3836
+ GCC_except_table3837
+ GCC_except_table3838
+ GCC_except_table3839
+ GCC_except_table384
+ GCC_except_table3840
+ GCC_except_table3841
+ GCC_except_table385
+ GCC_except_table3852
+ GCC_except_table386
+ GCC_except_table3865
+ GCC_except_table3866
+ GCC_except_table3867
+ GCC_except_table3870
+ GCC_except_table3872
+ GCC_except_table3873
+ GCC_except_table3874
+ GCC_except_table3875
+ GCC_except_table3877
+ GCC_except_table3880
+ GCC_except_table3883
+ GCC_except_table3887
+ GCC_except_table3888
+ GCC_except_table3909
+ GCC_except_table391
+ GCC_except_table3911
+ GCC_except_table3914
+ GCC_except_table3916
+ GCC_except_table3917
+ GCC_except_table3918
+ GCC_except_table3925
+ GCC_except_table3927
+ GCC_except_table3931
+ GCC_except_table3932
+ GCC_except_table3962
+ GCC_except_table3966
+ GCC_except_table4066
+ GCC_except_table4073
+ GCC_except_table4115
+ GCC_except_table4173
+ GCC_except_table4243
+ GCC_except_table4255
+ GCC_except_table4260
+ GCC_except_table4295
+ GCC_except_table4361
+ GCC_except_table439
+ GCC_except_table443
+ GCC_except_table444
+ GCC_except_table445
+ GCC_except_table446
+ GCC_except_table447
+ GCC_except_table531
+ GCC_except_table641
+ GCC_except_table644
+ GCC_except_table645
+ GCC_except_table647
+ GCC_except_table651
+ GCC_except_table803
+ GCC_except_table812
+ GCC_except_table882
+ GCC_except_table883
+ GCC_except_table890
+ GCC_except_table905
+ GCC_except_table906
+ GCC_except_table907
+ GCC_except_table911
+ GCC_except_table912
+ GCC_except_table913
+ GCC_except_table914
+ GCC_except_table915
+ GCC_except_table922
+ GCC_except_table928
+ GCC_except_table937
+ OBJC_IVAR_$_CSAudioProvider._secureSessionAssertionUUID
+ OBJC_IVAR_$_CSSecureSessionHandler._assertionSet
+ OBJC_IVAR_$_CSSecureSessionHandler._queue
+ _OBJC_CLASS_$_CSSecureSessionHandler
+ _OBJC_METACLASS_$_CSSecureSessionHandler
+ __OBJC_$_CLASS_METHODS_CSSecureSessionHandler
+ __OBJC_$_INSTANCE_METHODS_CSSecureSessionHandler
+ __OBJC_$_INSTANCE_VARIABLES_CSSecureSessionHandler
+ __OBJC_$_PROP_LIST_CSSecureSessionHandler
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSSystemDaemonStateMonitorDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSSystemDaemonStateMonitorDelegate
+ __OBJC_$_PROTOCOL_REFS_CSSystemDaemonStateMonitorDelegate
+ __OBJC_CLASS_PROTOCOLS_$_CSSecureSessionHandler
+ __OBJC_CLASS_RO_$_CSSecureSessionHandler
+ __OBJC_LABEL_PROTOCOL_$_CSSystemDaemonStateMonitorDelegate
+ __OBJC_METACLASS_RO_$_CSSecureSessionHandler
+ __OBJC_PROTOCOL_$_CSSystemDaemonStateMonitorDelegate
+ ___39+[CSSecureSessionHandler sharedHandler]_block_invoke
+ ___45-[CSAudioRecorder CSSystemDaemonDisconnected]_block_invoke
+ ___54-[CSSystemDaemonStateMonitor currentSystemDaemonState]_block_invoke
+ ___59-[CSSecureSessionHandler releaseAllSecureSessionAssertions]_block_invoke
+ ___60+[CSSecureSessionHandler siriEnablementSessionAssertionUUID]_block_invoke
+ ___64-[CSSecureSessionHandler acquireSecureSessionAssertionWithUUID:]_block_invoke
+ ___64-[CSSecureSessionHandler releaseSecureSessionAssertionWithUUID:]_block_invoke
+ ___initValNSWorkspaceSessionDidBecomeActiveNotification_block_invoke
+ ___initValNSWorkspaceSessionDidResignActiveNotification_block_invoke
+ _objc_msgSend$CSSystemDaemonDisconnected
+ _objc_msgSend$_activateSecureSessionIfNeeded
+ _objc_msgSend$_deactivateSecureSessionIfNeeded
+ _objc_msgSend$acquireSecureSessionAssertionWithUUID:
+ _objc_msgSend$activateSecureSession:error:
+ _objc_msgSend$duckAudioDeviceWithDeviceID:duckedLevel:rampDuration:
+ _objc_msgSend$releaseAllSecureSessionAssertions
+ _objc_msgSend$releaseSecureSessionAssertionWithUUID:
+ _objc_msgSend$resetAVVC
+ _objc_msgSend$siriEnablementSessionAssertionUUID
+ _softLinkOnceNSWorkspaceSessionDidBecomeActiveNotification
+ _softLinkOnceNSWorkspaceSessionDidResignActiveNotification
+ siriEnablementSessionAssertionUUID.onceToken
+ siriEnablementSessionAssertionUUID.siriEnablementSessionAssertionUUID
- +[CSMacUserSessionMonitor sharedInstance]
- -[CSAudioProvider activateSecureSession:]
- -[CSAudioRecorder CSSiriEnabledMonitor:didReceiveEnabled:]
- -[CSAudioRecorder activateSecureSession:]
- -[CSLaunchAgentXPCClient activateSecureSession:]
- -[CSLaunchAgentXPCClient macUserSessionMonitor:sessionActive:]
- -[CSMacUserSessionMonitor _handleSessionActive:]
- -[CSMacUserSessionMonitor _handleSessionResign:]
- -[CSMacUserSessionMonitor _notifySessionActive:]
- -[CSMacUserSessionMonitor _registerUserSessionNotification]
- -[CSMacUserSessionMonitor _startMonitoringWithQueue:]
- -[CSMacUserSessionMonitor _stopMonitoring]
- -[CSMacUserSessionMonitor _unregisterUserSessionNotification]
- -[CSMacUserSessionMonitor init]
- GCC_except_table1017
- GCC_except_table1024
- GCC_except_table1302
- GCC_except_table1331
- GCC_except_table1420
- GCC_except_table1422
- GCC_except_table1423
- GCC_except_table1425
- GCC_except_table1426
- GCC_except_table1427
- GCC_except_table1430
- GCC_except_table1596
- GCC_except_table1812
- GCC_except_table1813
- GCC_except_table1815
- GCC_except_table1819
- GCC_except_table1822
- GCC_except_table1823
- GCC_except_table1832
- GCC_except_table1838
- GCC_except_table1840
- GCC_except_table1841
- GCC_except_table1905
- GCC_except_table1910
- GCC_except_table1982
- GCC_except_table2023
- GCC_except_table2025
- GCC_except_table2026
- GCC_except_table2033
- GCC_except_table2034
- GCC_except_table2043
- GCC_except_table2056
- GCC_except_table2099
- GCC_except_table2168
- GCC_except_table2266
- GCC_except_table2303
- GCC_except_table2439
- GCC_except_table2443
- GCC_except_table2511
- GCC_except_table2522
- GCC_except_table2524
- GCC_except_table2529
- GCC_except_table2531
- GCC_except_table2548
- GCC_except_table2555
- GCC_except_table2557
- GCC_except_table2575
- GCC_except_table2596
- GCC_except_table2636
- GCC_except_table2695
- GCC_except_table2697
- GCC_except_table2698
- GCC_except_table281
- GCC_except_table2840
- GCC_except_table291
- GCC_except_table2968
- GCC_except_table2986
- GCC_except_table2995
- GCC_except_table2998
- GCC_except_table3000
- GCC_except_table3001
- GCC_except_table3024
- GCC_except_table3066
- GCC_except_table3157
- GCC_except_table3182
- GCC_except_table3215
- GCC_except_table3216
- GCC_except_table3217
- GCC_except_table3218
- GCC_except_table3241
- GCC_except_table3254
- GCC_except_table3387
- GCC_except_table3447
- GCC_except_table3461
- GCC_except_table350
- GCC_except_table3503
- GCC_except_table3504
- GCC_except_table3537
- GCC_except_table3538
- GCC_except_table3540
- GCC_except_table3543
- GCC_except_table3544
- GCC_except_table3545
- GCC_except_table3565
- GCC_except_table3568
- GCC_except_table3570
- GCC_except_table3571
- GCC_except_table3572
- GCC_except_table3574
- GCC_except_table3607
- GCC_except_table3609
- GCC_except_table3610
- GCC_except_table3611
- GCC_except_table3612
- GCC_except_table3669
- GCC_except_table3717
- GCC_except_table3723
- GCC_except_table374
- GCC_except_table3778
- GCC_except_table3779
- GCC_except_table3786
- GCC_except_table3787
- GCC_except_table3788
- GCC_except_table3789
- GCC_except_table3791
- GCC_except_table3792
- GCC_except_table3814
- GCC_except_table3816
- GCC_except_table3817
- GCC_except_table3818
- GCC_except_table3819
- GCC_except_table3820
- GCC_except_table3821
- GCC_except_table3822
- GCC_except_table3833
- GCC_except_table3845
- GCC_except_table3846
- GCC_except_table3847
- GCC_except_table3848
- GCC_except_table3849
- GCC_except_table3850
- GCC_except_table3851
- GCC_except_table3853
- GCC_except_table3854
- GCC_except_table3855
- GCC_except_table3856
- GCC_except_table3857
- GCC_except_table3858
- GCC_except_table3861
- GCC_except_table3889
- GCC_except_table3890
- GCC_except_table3892
- GCC_except_table3893
- GCC_except_table3897
- GCC_except_table3898
- GCC_except_table3899
- GCC_except_table3906
- GCC_except_table3913
- GCC_except_table393
- GCC_except_table3943
- GCC_except_table3947
- GCC_except_table395
- GCC_except_table396
- GCC_except_table397
- GCC_except_table402
- GCC_except_table4047
- GCC_except_table405
- GCC_except_table4054
- GCC_except_table4096
- GCC_except_table4154
- GCC_except_table4224
- GCC_except_table4236
- GCC_except_table4241
- GCC_except_table4276
- GCC_except_table4342
- GCC_except_table450
- GCC_except_table454
- GCC_except_table455
- GCC_except_table456
- GCC_except_table457
- GCC_except_table458
- GCC_except_table542
- GCC_except_table652
- GCC_except_table655
- GCC_except_table656
- GCC_except_table658
- GCC_except_table662
- GCC_except_table814
- GCC_except_table824
- GCC_except_table894
- GCC_except_table895
- GCC_except_table902
- GCC_except_table925
- GCC_except_table929
- GCC_except_table930
- GCC_except_table931
- GCC_except_table934
- GCC_except_table935
- GCC_except_table936
- GCC_except_table938
- GCC_except_table939
- GCC_except_table940
- GCC_except_table949
- _NSWorkspaceSessionDidBecomeActiveNotification
- _NSWorkspaceSessionDidResignActiveNotification
- _OBJC_CLASS_$_CSMacUserSessionMonitor
- _OBJC_CLASS_$_NSWorkspace
- _OBJC_METACLASS_$_CSMacUserSessionMonitor
- __OBJC_$_CLASS_METHODS_CSMacUserSessionMonitor
- __OBJC_$_INSTANCE_METHODS_CSMacUserSessionMonitor
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAudioSessionProviding
- __OBJC_CLASS_RO_$_CSMacUserSessionMonitor
- __OBJC_METACLASS_RO_$_CSMacUserSessionMonitor
- ___41+[CSMacUserSessionMonitor sharedInstance]_block_invoke
- ___41-[CSAudioProvider activateSecureSession:]_block_invoke
- ___48-[CSMacUserSessionMonitor _notifySessionActive:]_block_invoke
- ___58-[CSAudioRecorder CSSiriEnabledMonitor:didReceiveEnabled:]_block_invoke
- _objc_msgSend$_notifySessionActive:
- _objc_msgSend$_registerUserSessionNotification
- _objc_msgSend$_unregisterUserSessionNotification
- _objc_msgSend$activateSecureSession:
- _objc_msgSend$macUserSessionMonitor:sessionActive:
CStrings:
+ "%s Acquire Secure Session Assertion with UUID: %@"
+ "%s Calling AVVTC %@ secure session under system daemon took: %f"
+ "%s Cannot acquire secure session assertion when current user is inactive"
+ "%s Release Secure Session Assertion with UUID: %@"
+ "%s SetAlertSound failed under system daemon"
+ "%s SetAlertURL is failed with error: %@"
+ "%s Successfully activated secure session? %@, err: %@"
+ "%s Successfully deactivated secure session? %@, err: %@"
+ "%s UUID is nil"
+ "%s alert URL is nil"
+ "%s alertURL: %@, forType: %d"
+ "%s releasing All the secureAssertions when audio server daemons crash"
+ "%s releasing All the secureAssertions when system daemon crashes"
+ "-[CSAudioRecorder setAlertSoundFromURL:forType:force:]"
+ "-[CSLaunchAgentXPCClient activateSecureSession:error:]"
+ "-[CSLaunchAgentXPCClient resetAVVC]"
+ "-[CSLaunchAgentXPCClient setAlertSoundFromURL:forType:]"
+ "-[CSSecureSessionHandler CSAudioServerCrashMonitorDidReceiveServerCrash:]"
+ "-[CSSecureSessionHandler CSSystemDaemonStateMonitorDidReceiveSysDaemonCrash:]"
+ "-[CSSecureSessionHandler _activateSecureSessionIfNeeded]"
+ "-[CSSecureSessionHandler _deactivateSecureSessionIfNeeded]"
+ "-[CSSecureSessionHandler acquireSecureSessionAssertionWithUUID:]_block_invoke"
+ "-[CSSecureSessionHandler releaseSecureSessionAssertionWithUUID:]_block_invoke"
+ "B28@0:8B16^@20"
+ "CSSecureSessionHandler"
+ "CSSystemDaemonDisconnected"
+ "CSSystemDaemonStateMonitorDelegate"
+ "Secure Session Handler Queue"
+ "T@\"NSMutableSet\",&,N,V_assertionSet"
+ "T@\"NSUUID\",&,N,V_secureSessionAssertionUUID"
+ "_activateSecureSessionIfNeeded"
+ "_assertionSet"
+ "_deactivateSecureSessionIfNeeded"
+ "_secureSessionAssertionUUID"
+ "acquireSecureSessionAssertionWithUUID:"
+ "activate"
+ "activateSecureSession:error:"
+ "alertURL"
+ "assertionSet"
+ "audioDeviceID"
+ "currentSystemDaemonState"
+ "deactivate"
+ "duckAudioDeviceWithDeviceID:duckedLevel:rampDuration:"
+ "duckLevel"
+ "rampDuration"
+ "releaseAllSecureSessionAssertions"
+ "releaseSecureSessionAssertionWithUUID:"
+ "resetAVVC"
+ "secureSessionAssertionUUID"
+ "setAssertionSet:"
+ "setSecureSessionAssertionUUID:"
+ "siriEnablementSessionAssertionUUID"
+ "v24@0:8@\"CSSystemDaemonStateMonitor\"16"
- "%s Notify Mac User session %@"
- "%s Siri enabled : %{public}d"
- "%s invalid call for systemDaemon not supported platforms"
- "-[CSAudioRecorder CSSiriEnabledMonitor:didReceiveEnabled:]"
- "-[CSAudioRecorder activateSecureSession:]"
- "-[CSLaunchAgentXPCClient activateSecureSession:]"
- "-[CSMacUserSessionMonitor _notifySessionActive:]"
- "CSMacUserSessionMonitor"
- "_handleSessionActive:"
- "_handleSessionResign:"
- "_notifySessionActive:"
- "_registerUserSessionNotification"
- "_unregisterUserSessionNotification"
- "activateSecureSession:"
- "inactive"
- "macUserSessionMonitor:sessionActive:"
```
