## ScreenSharing

> `/System/Library/PrivateFrameworks/ScreenSharing.framework/Versions/A/ScreenSharing`

```diff

-714.4.6.0.0
-  __TEXT.__text: 0x1128cc
+714.5.1.0.0
+  __TEXT.__text: 0x11610c
   __TEXT.__auth_stubs: 0x2930
-  __TEXT.__objc_methlist: 0xde18
-  __TEXT.__cstring: 0x295ff
+  __TEXT.__objc_methlist: 0xdea8
+  __TEXT.__cstring: 0x29d82
   __TEXT.__const: 0x33d0
-  __TEXT.__oslogstring: 0x138d3
-  __TEXT.__gcc_except_tab: 0xdbc
+  __TEXT.__oslogstring: 0x13e37
+  __TEXT.__gcc_except_tab: 0xf0c
   __TEXT.__ustring: 0x166
-  __TEXT.__unwind_info: 0x2870
+  __TEXT.__unwind_info: 0x28c8
   __TEXT.__objc_classname: 0xe26
-  __TEXT.__objc_methname: 0x24394
-  __TEXT.__objc_methtype: 0x5ce6
-  __TEXT.__objc_stubs: 0x19d00
+  __TEXT.__objc_methname: 0x2465a
+  __TEXT.__objc_methtype: 0x5d13
+  __TEXT.__objc_stubs: 0x19e80
   __DATA_CONST.__got: 0xbc0
   __DATA_CONST.__const: 0x5b0
   __DATA_CONST.__objc_classlist: 0x320
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x1b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8460
+  __DATA_CONST.__objc_selrefs: 0x84c0
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x300
   __DATA_CONST.__objc_arraydata: 0x3b8
   __AUTH_CONST.__auth_got: 0x14a8
-  __AUTH_CONST.__const: 0x14e0
-  __AUTH_CONST.__cfstring: 0x7660
-  __AUTH_CONST.__objc_const: 0x12010
-  __AUTH_CONST.__objc_intobj: 0xd8
+  __AUTH_CONST.__const: 0x1510
+  __AUTH_CONST.__cfstring: 0x7840
+  __AUTH_CONST.__objc_const: 0x12100
+  __AUTH_CONST.__objc_intobj: 0xf0
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH.__objc_data: 0x1ef0
   __AUTH.__data: 0x18
-  __DATA.__objc_ivar: 0xffc
+  __DATA.__objc_ivar: 0x100c
   __DATA.__data: 0x1770
   __DATA.__bss: 0x7bc
   __DATA.__common: 0x2

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5262
-  Symbols:   11588
-  CStrings:  11608
+  Functions: 5301
+  Symbols:   11624
+  CStrings:  11691
 
Symbols:
+ -[SSFrameBufferRenderView feedbackLayerNeedsCartesianCoordinates]
+ -[SSFrameBufferRenderView setFeedbackLayerNeedsCartesianCoordinates:]
+ -[SSSession generateIDSAVCNegotiatorInfo]
+ -[SSSession setUseAVCMediaStreamsWithAppleID:]
+ -[SSSession startIDSAVCMediaStreams:idsSession:]
+ -[SSSession useAVCMediaStreamsWithAppleID]
+ -[SSSessionView AVConferenceNegotiatorAnswer]
+ -[SSSessionView avcMediaDeviceOrientation]
+ -[SSSessionView setAVConferenceNegotiatorAnswer:]
+ -[SSSessionView setAvcMediaDeviceOrientation:]
+ -[SSSessionView ssSession:deviceRotation:deviceOrientation:]
+ GCC_except_table294
+ GCC_except_table295
+ GCC_except_table303
+ GCC_except_table397
+ GCC_except_table401
+ GCC_except_table402
+ GCC_except_table730
+ GCC_except_table731
+ GCC_except_table732
+ GCC_except_table735
+ GCC_except_table736
+ GCC_except_table737
+ GCC_except_table763
+ GCC_except_table764
+ OBJC_IVAR_$_SSFrameBufferRenderView._feedbackLayerNeedsCartesianCoordinates
+ OBJC_IVAR_$_SSSession._useAVCMediaStreamsWithAppleID
+ OBJC_IVAR_$_SSSessionView._AVConferenceNegotiatorAnswer
+ OBJC_IVAR_$_SSSessionView._avcMediaDeviceOrientation
+ __48-[SSSession startIDSAVCMediaStreams:idsSession:]_block_invoke
+ ___48-[SSSession startIDSAVCMediaStreams:idsSession:]_block_invoke
+ ___48-[SSSession startIDSAVCMediaStreams:idsSession:]_block_invoke_2
+ ___62-[SSSession remoteVideoClient:remoteVideoAttributesDidChange:]_block_invoke
+ ___62-[SSSession remoteVideoClient:remoteVideoAttributesDidChange:]_block_invoke_2
+ ___block_descriptor_56_e8_32o40o_e5_v8?0l
+ _objc_msgSend$AVConferenceNegotiatorAnswer
+ _objc_msgSend$avcMediaDeviceOrientation
+ _objc_msgSend$feedbackLayerNeedsCartesianCoordinates
+ _objc_msgSend$generateIDSAVCNegotiatorInfo
+ _objc_msgSend$initWithIDSDestination:options:error:
+ _objc_msgSend$setAVConferenceNegotiatorAnswer:
+ _objc_msgSend$setAvcMediaDeviceOrientation:
+ _objc_msgSend$setFeedbackLayerNeedsCartesianCoordinates:
+ _objc_msgSend$setUseAVCMediaStreamsWithAppleID:
+ _objc_msgSend$ssSession:deviceRotation:deviceOrientation:
+ _objc_msgSend$startIDSAVCMediaStreams:idsSession:
+ _objc_msgSend$useAVCMediaStreamsWithAppleID
- -[SSFrameBufferAVCMediaView sendMouseButtonEvent:withButton:withState:]
- GCC_except_table292
- GCC_except_table293
- GCC_except_table301
- GCC_except_table396
- GCC_except_table722
- GCC_except_table723
- GCC_except_table724
- GCC_except_table727
- GCC_except_table728
- GCC_except_table729
CStrings:
+ "-[SSSession generateIDSAVCNegotiatorInfo]"
+ "-[SSSession remoteVideoClient:remoteVideoAttributesDidChange:]_block_invoke"
+ "-[SSSession startIDSAVCMediaStreams:idsSession:]"
+ "-[SSSession startIDSAVCMediaStreams:idsSession:]_block_invoke"
+ "-[SSSessionView ssSession:deviceRotation:deviceOrientation:]"
+ "/Library/Preferences/com.apple.RemoteManagement.plist"
+ "AVCAnswer"
+ "AVCAudioStream int returned %s"
+ "AVCMediaEncoding version %d messageType %d"
+ "AVCMediaStream touch feedback layer"
+ "AVCNegotiatorInfo"
+ "AVCVideoStream initWithIDSDestination error: %s"
+ "AVConferenceNegotiatorAnswer"
+ "Invalid audio answer %p"
+ "Invalid video answer %p"
+ "SafeViewScreenShare"
+ "SafeViewVideoRefreshRate"
+ "Start the legacyAVConference call"
+ "T@\"NSDictionary\",&,V_AVConferenceNegotiatorAnswer"
+ "TB,N,V_feedbackLayerNeedsCartesianCoordinates"
+ "TB,N,V_useAVCMediaStreamsWithAppleID"
+ "TI,R"
+ "Ti,N,V_avcMediaDeviceOrientation"
+ "_AVConferenceNegotiatorAnswer"
+ "_avcMediaDeviceOrientation"
+ "_feedbackLayerNeedsCartesianCoordinates"
+ "_useAVCMediaStreamsWithAppleID"
+ "accept message had neither key"
+ "audioAnswer"
+ "audioConfig failed isValid check"
+ "audioOffer"
+ "avcMediaDeviceOrientation"
+ "check videoconfig"
+ "configForAudio failed isValidAudioConfig check"
+ "configForVideo1 failed isValidVideoConfig check"
+ "deviceRotation delegate called with rotation of %u  orientation of %u"
+ "did not get either AVConference dictionary"
+ "did not have AVCNegotiator info"
+ "done initializing streams"
+ "encodings not yet set"
+ "erorr code %ld error string %s"
+ "error serializing %s"
+ "feedbackLayerNeedsCartesianCoordinates"
+ "generateIDSAVCNegotiatorInfo"
+ "going to init AVConference for legacy iOS connection"
+ "got negotiator answer - using AVC media streams"
+ "handleDisplayInfo"
+ "handleDisplayInfo2"
+ "ignoring since not AppleID address"
+ "info.orientation %d"
+ "initWithIDSDestination:options:error:"
+ "invalid osType in prefs"
+ "legacy AVConference touch feedback layer"
+ "new height %u new width %u"
+ "new rotation %d"
+ "no touch feedback layer"
+ "old height %u old width %u"
+ "orientation changed, send a message to the assistance cursor"
+ "override OS filter %s with %s"
+ "send IDS share screen invite"
+ "serverToViewerAudioKey"
+ "serverToViewerVideoKey"
+ "set video stream frame rate to %lu"
+ "setAVConferenceLayerRotation %u forScreen: %ld"
+ "setAVConferenceNegotiatorAnswer:"
+ "setAvcMediaDeviceOrientation:"
+ "setFeedbackLayerNeedsCartesianCoordinates:"
+ "setUseAVCMediaStreamsWithAppleID:"
+ "ssSession:deviceRotation:deviceOrientation:"
+ "start media streams"
+ "startAVConferenceCallWithRemoteDictionary %p %s"
+ "startIDSAVCMediaStreams"
+ "startIDSAVCMediaStreams:idsSession:"
+ "tvOS"
+ "tvOS2"
+ "unable to create AVC video negotiator: %s"
+ "unable to create audio config: %s"
+ "unable to create video config1: %s"
+ "unable to set video answer with error %s"
+ "useAVCMediaStreamsWithAppleID"
+ "v32@0:8@\"SSSession\"16I24i28"
+ "v32@0:8@16I24i28"
+ "video offer length %lu"
+ "video size w %f h %f"
+ "videoAnswer"
+ "videoConfig not valid for direction"
+ "videoOffer"
+ "viewerToServerAudioKey"
+ "viewerToServerVideoKey"
- "**error serializing %s"
- "avconferenceAccept dictionary is nil - need to update iOS device"
- "going to init AVConference for iOS connection"
- "send IDS invite"
- "startAVConferenceCallWithRemoteDictionary %p"
- "version %d messageType %d"
```
