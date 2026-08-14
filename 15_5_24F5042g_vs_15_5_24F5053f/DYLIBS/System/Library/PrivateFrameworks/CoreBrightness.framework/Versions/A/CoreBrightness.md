## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/Versions/A/CoreBrightness`

```diff

-1902.120.16.0.0
-  __TEXT.__text: 0xd1ee8
-  __TEXT.__auth_stubs: 0x16e0
-  __TEXT.__objc_methlist: 0x6a3c
+1902.120.20.0.0
+  __TEXT.__text: 0xd2d04
+  __TEXT.__auth_stubs: 0x16d0
+  __TEXT.__objc_methlist: 0x6c44
   __TEXT.__const: 0x8f30
-  __TEXT.__gcc_except_tab: 0x18e0
-  __TEXT.__cstring: 0x8693
-  __TEXT.__oslogstring: 0x10959
+  __TEXT.__gcc_except_tab: 0x18d0
+  __TEXT.__cstring: 0x893f
+  __TEXT.__oslogstring: 0x109e8
   __TEXT.__dlopen_cstrs: 0xca
-  __TEXT.__unwind_info: 0x2bd8
-  __TEXT.__objc_classname: 0x8c9
-  __TEXT.__objc_methname: 0xd5f8
-  __TEXT.__objc_methtype: 0x3479
-  __TEXT.__objc_stubs: 0xad40
-  __DATA_CONST.__got: 0x388
-  __DATA_CONST.__const: 0xc70
-  __DATA_CONST.__objc_classlist: 0x320
+  __TEXT.__unwind_info: 0x2c08
+  __TEXT.__objc_classname: 0x8f3
+  __TEXT.__objc_methname: 0xd6fb
+  __TEXT.__objc_methtype: 0x34b4
+  __TEXT.__objc_stubs: 0xaf80
+  __DATA_CONST.__got: 0x3a0
+  __DATA_CONST.__const: 0xc88
+  __DATA_CONST.__objc_classlist: 0x328
   __DATA_CONST.__objc_catlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x88
+  __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3400
+  __DATA_CONST.__objc_selrefs: 0x3470
   __DATA_CONST.__objc_protorefs: 0x40
-  __DATA_CONST.__objc_superrefs: 0x310
-  __DATA_CONST.__objc_arraydata: 0x608
-  __AUTH_CONST.__auth_got: 0xb88
-  __AUTH_CONST.__const: 0x1de8
-  __AUTH_CONST.__cfstring: 0x9c40
-  __AUTH_CONST.__objc_const: 0x14940
-  __AUTH_CONST.__objc_intobj: 0x6c0
+  __DATA_CONST.__objc_superrefs: 0x318
+  __DATA_CONST.__objc_arraydata: 0x628
+  __AUTH_CONST.__auth_got: 0xb80
+  __AUTH_CONST.__const: 0x1db8
+  __AUTH_CONST.__cfstring: 0x9f80
+  __AUTH_CONST.__objc_const: 0x15bf8
+  __AUTH_CONST.__objc_intobj: 0x690
   __AUTH_CONST.__objc_arrayobj: 0x1e0
-  __AUTH_CONST.__objc_dictobj: 0x320
+  __AUTH_CONST.__objc_dictobj: 0x2f8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_floatobj: 0x20
-  __AUTH.__objc_data: 0xd20
-  __DATA.__objc_ivar: 0xe6c
-  __DATA.__data: 0x58575
-  __DATA.__bss: 0x1c0
+  __AUTH.__objc_data: 0xd70
+  __DATA.__objc_ivar: 0xe7c
+  __DATA.__data: 0x585d5
+  __DATA.__bss: 0x1b8
   __DATA_DIRTY.__objc_data: 0x1220
   __DATA_DIRTY.__data: 0x30
   __DATA_DIRTY.__bss: 0xa8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4183
-  Symbols:   7516
-  CStrings:  6253
+  Functions: 4208
+  Symbols:   7577
+  CStrings:  6308
 
Symbols:
+ -[CBPILNode cil]
+ -[CBPILNode initWithCILService:andMILService:]
+ -[CBPILNode mil]
+ -[CBPILParams controlType]
+ -[CBPILParams curveLux]
+ -[CBPILParams curveNits]
+ -[CBPILParams initWithCurveLux:curveNits:minHWDutyCycle:maxHWDutyCycle:knownNits:knownDutyCycle:transport:stateSource:controlType:]
+ -[CBPILParams initWithService:andControlType:]
+ -[CBPILParams knownDutyCycle]
+ -[CBPILParams knownNits]
+ -[CBPILParams stateSource]
+ -[CBPILParams transport]
+ -[PILABCurve initWithParams:]
+ -[PILABCurve initialiseCurveFrom:]
+ -[PILAutoBrightnessModule addHIDServiceClient:]
+ -[PILAutoBrightnessModule handleHIDEvent:from:]
+ -[PILAutoBrightnessModule initWithQueue:PILParams:calibration:andALSServiceClient:]
+ -[PILAutoBrightnessModule removeHIDServiceClient:]
+ -[PILAutoBrightnessModule transportOfType:]
+ -[PILContainer initWithPILNode:]
+ -[PILController addHIDServiceClient:]
+ -[PILController brightnessForDutyCycle:]
+ -[PILController getDutyCycle]
+ -[PILController handleHIDEvent:from:]
+ -[PILController maximumDutyCycle]
+ -[PILController minimumDutyCycle]
+ -[PILController removeHIDServiceClient:]
+ -[PILStateMonitor addHIDServiceClient:]
+ -[PILStateMonitor cilSource]
+ -[PILStateMonitor handleHIDEvent:from:]
+ -[PILStateMonitor handlePILHIDEvent:]
+ -[PILStateMonitor initWithQueue:cilSource:milSource:]
+ -[PILStateMonitor milSource]
+ -[PILStateMonitor removeHIDServiceClient:]
+ -[PILStateMonitor setCilSource:]
+ -[PILStateMonitor setMilSource:]
+ -[PILTransportAPDS dutyCycle]
+ -[PILTransportHID addHIDServiceClient:]
+ -[PILTransportHID dutyCycle]
+ -[PILTransportHID handleHIDEvent:from:]
+ -[PILTransportHID removeHIDServiceClient:]
+ -[PILTransportHID writeDataHID:]
+ -[PILTransportIOService dealloc]
+ -[PILTransportIOService dutyCycle]
+ -[PILTransportIOService getDutyCycleMin:andMax:]
+ -[PILTransportIOService getDutyCycleThreshold:]
+ -[PILTransportIOService initWithQueue:]
+ -[PILTransportIOService lookupPILServiceUntrusted]
+ -[PILTransportIOService readData:withSize:fromRegister:]
+ -[PILTransportIOService registerForAllMILNotifications]
+ -[PILTransportIOService setDutyCycle:]
+ -[PILTransportIOService setDutyCycleInternal:]
+ -[PILTransportIOService start]
+ -[PILTransportIOService stop]
+ -[PILTransportIOService unregisterForAllMILNotifications]
+ -[PILTransportIOService writeDataUntrusted:withSize:toRegister:withAddressSize:]
+ OBJC_IVAR_$_CBPILNode._cil
+ OBJC_IVAR_$_CBPILNode._mil
+ OBJC_IVAR_$_CBPILParams._controlType
+ OBJC_IVAR_$_CBPILParams._curveLux
+ OBJC_IVAR_$_CBPILParams._curveNits
+ OBJC_IVAR_$_CBPILParams._knownDutyCycle
+ OBJC_IVAR_$_CBPILParams._knownNits
+ OBJC_IVAR_$_CBPILParams._logHandle
+ OBJC_IVAR_$_CBPILParams._stateSource
+ OBJC_IVAR_$_CBPILParams._transport
+ OBJC_IVAR_$_PILContainer._node
+ OBJC_IVAR_$_PILStateMonitor._cilSource
+ OBJC_IVAR_$_PILStateMonitor._milSource
+ OBJC_IVAR_$_PILStateMonitor._pilPlugin
+ OBJC_IVAR_$_PILTransportAPDS._dutyCycle
+ OBJC_IVAR_$_PILTransportHID._dutyCycle
+ OBJC_IVAR_$_PILTransportHID._pilPlugin
+ OBJC_IVAR_$_PILTransportIOService._connect
+ OBJC_IVAR_$_PILTransportIOService._dutyCycle
+ OBJC_IVAR_$_PILTransportIOService._ioNotificationObject
+ OBJC_IVAR_$_PILTransportIOService._ioNotificationPort
+ OBJC_IVAR_$_PILTransportIOService._ioServiceArrivalIterator
+ OBJC_IVAR_$_PILTransportIOService._logHandle
+ OBJC_IVAR_$_PILTransportIOService._queue
+ OBJC_IVAR_$_PILTransportIOService._running
+ _IORegistryEntryCopyPath
+ _OBJC_CLASS_$_PILTransportIOService
+ _OBJC_METACLASS_$_PILTransportIOService
+ __36-[PILContainer addHIDServiceClient:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_PILTransportIOService
+ __OBJC_$_INSTANCE_VARIABLES_PILTransportIOService
+ __OBJC_$_PROP_LIST_CBPILParamsProtocol
+ __OBJC_$_PROP_LIST_PILTransportIOService
+ __OBJC_$_PROP_LIST_PILTransportProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBPILParamsProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBPILParamsProtocol
+ __OBJC_$_PROTOCOL_REFS_CBPILParamsProtocol
+ __OBJC_CLASS_PROTOCOLS_$_CBPILParams
+ __OBJC_CLASS_PROTOCOLS_$_PILController
+ __OBJC_CLASS_PROTOCOLS_$_PILStateMonitor
+ __OBJC_CLASS_PROTOCOLS_$_PILTransportIOService
+ __OBJC_CLASS_RO_$_PILTransportIOService
+ __OBJC_LABEL_PROTOCOL_$_CBPILParamsProtocol
+ __OBJC_METACLASS_RO_$_PILTransportIOService
+ __OBJC_PROTOCOL_$_CBPILParamsProtocol
+ ___32-[PILContainer initWithPILNode:]_block_invoke
+ ___block_descriptor_40_e8_32o_e29_v16?0r^{?=IIQQQQIBBBfffQIB}8l
+ _objc_msgSend$brightnessForDutyCycle:
+ _objc_msgSend$calibrationScalar
+ _objc_msgSend$cil
+ _objc_msgSend$cilSource
+ _objc_msgSend$controlType
+ _objc_msgSend$curveLux
+ _objc_msgSend$curveNits
+ _objc_msgSend$dataValueForField:
+ _objc_msgSend$dutyCycle
+ _objc_msgSend$getDutyCycle
+ _objc_msgSend$handlePILHIDEvent:
+ _objc_msgSend$initWithCILService:andMILService:
+ _objc_msgSend$initWithPILNode:
+ _objc_msgSend$initWithParams:
+ _objc_msgSend$initWithQueue:PILParams:calibration:andALSServiceClient:
+ _objc_msgSend$initWithQueue:cilSource:milSource:
+ _objc_msgSend$initWithService:andControlType:
+ _objc_msgSend$initialiseCurveFrom:
+ _objc_msgSend$integerValueForField:
+ _objc_msgSend$knownDutyCycle
+ _objc_msgSend$knownNits
+ _objc_msgSend$lookupPILServiceUntrusted
+ _objc_msgSend$maximumDutyCycle
+ _objc_msgSend$mil
+ _objc_msgSend$milSource
+ _objc_msgSend$minimumDutyCycle
+ _objc_msgSend$setCilSource:
+ _objc_msgSend$setMilSource:
+ _objc_msgSend$stateSource
+ _objc_msgSend$timestamp
+ _objc_msgSend$transport
+ _objc_msgSend$transportOfType:
+ _objc_msgSend$writeDataHID:
+ _objc_msgSend$writeDataUntrusted:withSize:toRegister:withAddressSize:
- -[CBPILNode initWithService:]
- -[CBPILNode pil]
- -[CBPILParams cilCurveLux]
- -[CBPILParams cilCurveNits]
- -[CBPILParams cilKnownDutyCycle]
- -[CBPILParams cilKnownNits]
- -[CBPILParams initWithLuxArray:nitsArray:lutSize:]
- -[CBPILParams initWithService:]
- -[CBPILParams loadParametersFromService:]
- -[CBPILParams milCurveLux]
- -[CBPILParams milCurveNits]
- -[CBPILParams milKnownDutyCycle]
- -[CBPILParams milKnownNits]
- -[PILABCurve initWithParams:andPilControlType:]
- -[PILABCurve initialiseCurveFrom:andPilControlType:]
- -[PILAutoBrightnessModule initWithQueue:PILParams:calibration:andALSServiceClient:andPILControlType:]
- -[PILContainer initWithParameters:]
- -[PILStateMonitor initWithQueue:andSource:]
- -[PILTransportHID getDutyCycleThreshold:]
- -[PILTransportHID lookupMILServiceTrusted]
- -[PILTransportHID lookupMILServiceUntrusted]
- -[PILTransportHID readData:withSize:fromRegister:]
- -[PILTransportHID registerForAllMILNotifications]
- -[PILTransportHID unregisterForAllMILNotifications]
- -[PILTransportHID writeDataTrusted:]
- -[PILTransportHID writeDataUntrusted:withSize:toRegister:withAddressSize:]
- OBJC_IVAR_$_CBPILNode._log
- OBJC_IVAR_$_CBPILNode._pil
- OBJC_IVAR_$_CBPILNode._service
- OBJC_IVAR_$_CBPILParams._cilCurveLux
- OBJC_IVAR_$_CBPILParams._cilCurveNits
- OBJC_IVAR_$_CBPILParams._cilKnownDutyCycle
- OBJC_IVAR_$_CBPILParams._cilKnownNits
- OBJC_IVAR_$_CBPILParams._log
- OBJC_IVAR_$_CBPILParams._milCurveLux
- OBJC_IVAR_$_CBPILParams._milCurveNits
- OBJC_IVAR_$_CBPILParams._milKnownDutyCycle
- OBJC_IVAR_$_CBPILParams._milKnownNits
- OBJC_IVAR_$_PILContainer._params
- OBJC_IVAR_$_PILStateMonitor._source
- OBJC_IVAR_$_PILTransportHID._connect
- OBJC_IVAR_$_PILTransportHID._ioNotificationObject
- OBJC_IVAR_$_PILTransportHID._ioNotificationPort
- OBJC_IVAR_$_PILTransportHID._ioServiceArrivalIterator
- OBJC_IVAR_$_PILTransportHID._milHIDSystemClient
- OBJC_IVAR_$_PILTransportHID._milPlugin
- OBJC_IVAR_$_PILTransportHID._queue
- PILEventCallback
- _IOHIDEventSystemClientRegisterEventCallback
- _IOHIDEventSystemClientSetMatching
- _PILEventCallback
- __42-[PILTransportHID lookupMILServiceTrusted]_block_invoke
- ___35-[PILContainer initWithParameters:]_block_invoke
- ___42-[CBALSServiceClient handleHIDEvent:from:]_block_invoke
- ___42-[PILTransportHID lookupMILServiceTrusted]_block_invoke
- ___45-[CBALSServiceClient removeHIDServiceClient:]_block_invoke
- ___block_descriptor_40_e8_32o_e31_v16?0r^{?=IIQQQQIBBBfffQIBQQ}8l
- ___block_descriptor_40_e8_32o_e39_v32?0^v8^v16^{__IOHIDServiceClient=}24l
- _milServiceArrivalCallback
- _objc_msgSend$cilCurveLux
- _objc_msgSend$cilCurveNits
- _objc_msgSend$cilKnownDutyCycle
- _objc_msgSend$cilKnownNits
- _objc_msgSend$initWithParameters:
- _objc_msgSend$initWithParams:andPilControlType:
- _objc_msgSend$initWithQueue:PILParams:calibration:andALSServiceClient:andPILControlType:
- _objc_msgSend$initWithQueue:andSource:
- _objc_msgSend$initialiseCurveFrom:andPilControlType:
- _objc_msgSend$lookupMILServiceTrusted
- _objc_msgSend$milCurveLux
- _objc_msgSend$milCurveNits
- _objc_msgSend$milKnownDutyCycle
- _objc_msgSend$milKnownNits
- _objc_msgSend$pil
- _objc_msgSend$writeDataTrusted:
- lookupMILServiceTrusted.once
CStrings:
+ "%s: found client for PIL Control: %{public}@"
+ "-[PILContainer initWithPILNode:]"
+ "/cil"
+ "/mil"
+ "@\"CBFloatArray\"16@0:8"
+ "@\"CBPILNode\""
+ "@\"HIDServiceClient\""
+ "@24@0:8I16I20"
+ "@28@0:8I16Q20"
+ "@40@0:8@16Q24Q32"
+ "@44@0:8@16@24S32@36"
+ "@72@0:8@\"CBFloatArray\"16@\"CBFloatArray\"24I32I36I40f44Q48Q56Q64"
+ "@72@0:8@16@24I32I36I40f44Q48Q56Q64"
+ "CBPILParamsProtocol"
+ "CILCalibrationValue"
+ "CILDutyCycle"
+ "CILMaximumAchievableAutoBrightness"
+ "CILMaximumAchievableBrightness"
+ "CILMaximumDutyCycle"
+ "CILMinimumAchievableAutoBrightness"
+ "CILMinimumAchievableBrightness"
+ "CILMinimumDutyCycle"
+ "CILStateSource"
+ "Controller Started"
+ "Controller Stopped"
+ "Controller updated with min duty cycle: %i and max duty cycle: %i"
+ "Failed to fetch PIL duty cycle threshold correctly; readSuccess 0x%x"
+ "Failed to set PIL Brightness correctly; writeSuccess 0x%x"
+ "Failed to set PIL Brightness correctly; writeSuccessMSB 0x%x writeSuccessLSB 0x%x"
+ "IODeviceTree"
+ "MILCalibrationValue"
+ "MILDutyCycle"
+ "MILMaximumAchievableAutoBrightness"
+ "MILMaximumAchievableBrightness"
+ "MILMaximumDutyCycle"
+ "MILMinimumAchievableAutoBrightness"
+ "MILMinimumAchievableBrightness"
+ "MILMinimumDutyCycle"
+ "MILStateSource"
+ "PIL Duty cycle overriden to %f, corresponding to %f PIL Brightness"
+ "PILCalibrationValue"
+ "PILDutyCycle"
+ "PILMaximumAchievableAutoBrightness"
+ "PILMaximumAchievableBrightness"
+ "PILMaximumDutyCycle"
+ "PILMinimumAchievableAutoBrightness"
+ "PILMinimumAchievableBrightness"
+ "PILMinimumDutyCycle"
+ "PILTransportIOService"
+ "T@\"CBFloatArray\",R"
+ "T@\"CBFloatArray\",R,V_curveLux"
+ "T@\"CBFloatArray\",R,V_curveNits"
+ "T@\"CBPILParams\",R,V_cil"
+ "T@\"CBPILParams\",R,V_mil"
+ "TI,R"
+ "TI,R,V_dutyCycle"
+ "TI,R,V_knownNits"
+ "TI,R,V_maximumDutyCycle"
+ "TI,R,V_minimumDutyCycle"
+ "TQ,R,V_controlType"
+ "TQ,R,V_stateSource"
+ "TQ,R,V_transport"
+ "TQ,V_cilSource"
+ "TQ,V_milSource"
+ "Tf,R,V_knownDutyCycle"
+ "[New PIL Event] eventTimestamp=%llu PILData.(pilEnablementStatus=%i) \n"
+ "_cil"
+ "_cilSource"
+ "_controlType"
+ "_curveLux"
+ "_curveNits"
+ "_dutyCycle"
+ "_mil"
+ "_milSource"
+ "_pilPlugin"
+ "_stateSource"
+ "aab-curve-lux"
+ "aab-curve-nits"
+ "brightnessForDutyCycle:"
+ "cil"
+ "cilSource"
+ "com.apple.CoreBrightness.CILNode"
+ "com.apple.CoreBrightness.MILNode"
+ "com.apple.CoreBrightness.PILTransportHID"
+ "com.apple.CoreBrightness.PILTransportIOService"
+ "controlType"
+ "curveLux"
+ "curveNits"
+ "dataValueForField:"
+ "dutyCycle"
+ "getDutyCycle"
+ "handlePILHIDEvent:"
+ "initWithCILService:andMILService:"
+ "initWithCurveLux:curveNits:minHWDutyCycle:maxHWDutyCycle:knownNits:knownDutyCycle:transport:stateSource:controlType:"
+ "initWithPILNode:"
+ "initWithParams:"
+ "initWithQueue:PILParams:calibration:andALSServiceClient:"
+ "initWithQueue:cilSource:milSource:"
+ "initWithService:andControlType:"
+ "initialiseCurveFrom:"
+ "integerValueForField:"
+ "known-dutycycle"
+ "known-nits"
+ "knownDutyCycle"
+ "knownNits"
+ "lookupPILServiceUntrusted"
+ "maximumDutyCycle"
+ "mil"
+ "milSource"
+ "minimumDutyCycle"
+ "service: %p relevant:%d"
+ "setCilSource:"
+ "setMilSource:"
+ "state-source"
+ "stateSource"
+ "transport"
+ "transport-type"
+ "transportOfType:"
+ "v16@?0r^{?=IIQQQQIBBBfffQIB}8"
+ "writeDataHID:"
- "%s: found client for MIL Control: %{public}@"
- "-[PILContainer initWithParameters:]"
- "@40@0:8@16{PILStateSource=QQ}24"
- "@40@0:8^f16^f24Q32"
- "@56@0:8@16@24@32@40Q48"
- "B32@0:8@16Q24"
- "Failed to fetch MIL duty cycle threshold correctly; readSuccess 0x%x"
- "Failed to set MIL Brightness correctly; writeSuccess 0x%x"
- "PIL Controller Started"
- "PIL Controller Stopped"
- "PIL Controller updated with min duty cycle: %i and max duty cycle: %i"
- "PIL not supported"
- "T@\"CBFloatArray\",R,V_cilCurveLux"
- "T@\"CBFloatArray\",R,V_cilCurveNits"
- "T@\"CBFloatArray\",R,V_milCurveLux"
- "T@\"CBFloatArray\",R,V_milCurveNits"
- "T@\"CBPILParams\",R,V_pil"
- "TI,R,V_cilKnownNits"
- "TI,R,V_milKnownNits"
- "Tf,R,V_cilKnownDutyCycle"
- "Tf,R,V_milKnownDutyCycle"
- "[New HID Event] eventTimestamp=%llu PILData.(pilEnablementStatus=%i) \n"
- "^{__IOHIDEventSystemClient=}"
- "_cilCurveLux"
- "_cilCurveNits"
- "_cilKnownDutyCycle"
- "_cilKnownNits"
- "_milCurveLux"
- "_milCurveNits"
- "_milHIDSystemClient"
- "_milKnownDutyCycle"
- "_milKnownNits"
- "_milPlugin"
- "_pil"
- "_source"
- "cil-aab-curve-lux"
- "cil-aab-curve-nits"
- "cil-known-dutycycle"
- "cil-known-nits"
- "cilCurveLux"
- "cilCurveNits"
- "cilKnownDutyCycle"
- "cilKnownNits"
- "com.apple.CoreBrightness.CBMILInterface"
- "com.apple.CoreBrightness.PILNode"
- "initWithLuxArray:nitsArray:lutSize:"
- "initWithParameters:"
- "initWithParams:andPilControlType:"
- "initWithQueue:PILParams:calibration:andALSServiceClient:andPILControlType:"
- "initWithQueue:andSource:"
- "initialiseCurveFrom:andPilControlType:"
- "lookupMILServiceTrusted"
- "lookupMILServiceUntrusted"
- "mil-aab-curve-lux"
- "mil-aab-curve-nits"
- "mil-known-dutycycle"
- "mil-known-nits"
- "milCurveLux"
- "milCurveNits"
- "milKnownDutyCycle"
- "milKnownNits"
- "pil"
- "v16@?0r^{?=IIQQQQIBBBfffQIBQQ}8"
- "writeDataTrusted:"
- "{PILStateSource=\"milSource\"Q\"cilSource\"Q}"
```
