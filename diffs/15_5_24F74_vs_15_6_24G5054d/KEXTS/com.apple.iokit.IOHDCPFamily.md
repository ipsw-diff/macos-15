## com.apple.iokit.IOHDCPFamily

> `com.apple.iokit.IOHDCPFamily`

```diff

-68.0.0.0.0
+70.0.0.0.0
   __TEXT.__const: 0x38
-  __TEXT.__cstring: 0x4547
+  __TEXT.__cstring: 0x458a
   __TEXT.__os_log: 0x1626
-  __TEXT_EXEC.__text: 0xf45c
+  __TEXT_EXEC.__text: 0xf494
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xc8
   __DATA.__common: 0x178

   __DATA_CONST.__kalloc_type: 0x340
   Functions: 382
   Symbols:   949
-  CStrings:  448
+  CStrings:  449
 
Symbols:
+ __ZN29IOHDCP2TransmitterAuthSession9cpDesiredE16IOHDCPAuthPolicyj
- __ZN29IOHDCP2TransmitterAuthSession9cpDesiredE16IOHDCPAuthPolicy
Functions:
~ __ZN29IOHDCP2TransmitterAuthSession9cpDesiredE16IOHDCPAuthPolicy -> __ZN29IOHDCP2TransmitterAuthSession9cpDesiredE16IOHDCPAuthPolicyj : 244 -> 252
~ __ZN29IOHDCP2TransmitterAuthSession13handleMessageEP14IOHDCP2Message : 5188 -> 5196
~ __ZN31IOHDCP2DPTransmitterAuthSession30fillRepeaterAuth_Stream_ManageEPN14IOHDCP2Message29DP_RepeaterAuth_Stream_ManageE : 420 -> 424
~ __ZN31IOHDCP2DPTransmitterAuthSession13handleMessageEP14IOHDCP2Message : 4212 -> 4248
CStrings:
+ "12111211111211122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222"
+ "ret = setTimeoutMS(110) == 0 "
+ "ret = setTimeoutMS(16) == 0 "
- "1211121111121112222222222222222222222222222222222222222222222222222222222222222222222222222222222222222"
- "ret = setTimeoutMS(7) == 0 "
```
