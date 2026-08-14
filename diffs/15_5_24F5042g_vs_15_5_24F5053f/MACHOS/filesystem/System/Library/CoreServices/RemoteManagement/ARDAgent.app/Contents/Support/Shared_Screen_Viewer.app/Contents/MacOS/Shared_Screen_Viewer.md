## Shared Screen Viewer

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Support/Shared Screen Viewer.app/Contents/MacOS/Shared Screen Viewer`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-709.4.4.0.0
-  __TEXT.__text: 0x104cc8
+709.5.1.0.0
+  __TEXT.__text: 0x108370
   __TEXT.__auth_stubs: 0x2420
-  __TEXT.__objc_stubs: 0x18840
-  __TEXT.__objc_methlist: 0xd7b0
+  __TEXT.__objc_stubs: 0x189c0
+  __TEXT.__objc_methlist: 0xd840
   __TEXT.__objc_classname: 0xcea
-  __TEXT.__objc_methname: 0x22dd2
-  __TEXT.__objc_methtype: 0x5dd1
-  __TEXT.__cstring: 0x2722a
-  __TEXT.__oslogstring: 0x13049
+  __TEXT.__objc_methname: 0x23098
+  __TEXT.__objc_methtype: 0x5dfe
+  __TEXT.__cstring: 0x279ad
+  __TEXT.__oslogstring: 0x135ad
   __TEXT.__const: 0x3340
-  __TEXT.__gcc_except_tab: 0xc40
+  __TEXT.__gcc_except_tab: 0xd90
   __TEXT.__ustring: 0x126
-  __TEXT.__unwind_info: 0x2520
+  __TEXT.__unwind_info: 0x2578
   __DATA_CONST.__auth_got: 0x1220
   __DATA_CONST.__got: 0x930
   __DATA_CONST.__auth_ptr: 0x10
-  __DATA_CONST.__const: 0x1468
-  __DATA_CONST.__cfstring: 0x6c40
+  __DATA_CONST.__const: 0x1498
+  __DATA_CONST.__cfstring: 0x6e20
   __DATA_CONST.__objc_classlist: 0x2d0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x1b8

   __DATA_CONST.__objc_superrefs: 0x2a8
   __DATA_CONST.__objc_arraydata: 0x3b0
   __DATA_CONST.__objc_arrayobj: 0xa8
-  __DATA_CONST.__objc_intobj: 0xd8
+  __DATA_CONST.__objc_intobj: 0xf0
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_floatobj: 0x10
-  __DATA.__objc_const: 0x110f0
-  __DATA.__objc_selrefs: 0x7ef0
-  __DATA.__objc_ivar: 0xf0c
+  __DATA.__objc_const: 0x111e0
+  __DATA.__objc_selrefs: 0x7f50
+  __DATA.__objc_ivar: 0xf1c
   __DATA.__objc_data: 0x1c20
   __DATA.__data: 0x1750
   __DATA.__bss: 0x724

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4927
+  Functions: 4960
   Symbols:   896
-  CStrings:  11064
+  CStrings:  11147
 
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
