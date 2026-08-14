## CoreHAP

> `/System/Library/PrivateFrameworks/CoreHAP.framework/Versions/A/CoreHAP`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-1278.6.26.0.0
-  __TEXT.__text: 0x1c0338
+1278.6.30.0.0
+  __TEXT.__text: 0x1c0e1c
   __TEXT.__auth_stubs: 0x11a0
-  __TEXT.__objc_methlist: 0x13140
+  __TEXT.__objc_methlist: 0x13180
   __TEXT.__const: 0x6d0
-  __TEXT.__gcc_except_tab: 0x5b64
-  __TEXT.__cstring: 0x104e9
-  __TEXT.__oslogstring: 0x1dd90
-  __TEXT.__unwind_info: 0x5aa0
+  __TEXT.__gcc_except_tab: 0x5b70
+  __TEXT.__cstring: 0x10577
+  __TEXT.__oslogstring: 0x1de6f
+  __TEXT.__unwind_info: 0x5ab8
   __TEXT.__objc_classname: 0x2d51
-  __TEXT.__objc_methname: 0x2543a
-  __TEXT.__objc_methtype: 0x8d3b
-  __TEXT.__objc_stubs: 0x175a0
+  __TEXT.__objc_methname: 0x2554d
+  __TEXT.__objc_methtype: 0x8d7b
+  __TEXT.__objc_stubs: 0x17620
   __DATA_CONST.__got: 0xa08
   __DATA_CONST.__const: 0x1ce8
   __DATA_CONST.__objc_classlist: 0x940
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x320
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6b58
+  __DATA_CONST.__objc_selrefs: 0x6b78
   __DATA_CONST.__objc_protorefs: 0xc0
   __DATA_CONST.__objc_superrefs: 0x7c0
   __DATA_CONST.__objc_arraydata: 0x208
   __AUTH_CONST.__auth_got: 0x8e0
   __AUTH_CONST.__const: 0x4290
-  __AUTH_CONST.__cfstring: 0xd500
-  __AUTH_CONST.__objc_const: 0x214a8
+  __AUTH_CONST.__cfstring: 0xd580
+  __AUTH_CONST.__objc_const: 0x21558
   __AUTH_CONST.__objc_intobj: 0x510
   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH.__objc_data: 0x5460
-  __DATA.__objc_ivar: 0x1438
+  __DATA.__objc_ivar: 0x1448
   __DATA.__data: 0x25aa
   __DATA.__bss: 0x401
   __DATA.__common: 0x20

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libnetwork.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7352
-  Symbols:   16221
-  CStrings:  10627
+  Functions: 7358
+  Symbols:   16235
+  CStrings:  10644
 
Symbols:
+ +[HAP2AccessoryServerTransportCoAP stringFromCoAPAddress:]
+ -[HAP2AccessorySessionInfo .cxx_destruct]
+ -[HAP2AccessorySessionInfo description]
+ -[HAP2AccessorySessionInfo initWithNumIPs:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:]
+ -[HAP2AccessorySessionInfo ipAddress]
+ -[HAP2AccessorySessionInfo resetWithNumIPs:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:]
+ -[HAP2AccessorySessionInfo resolveAttempted]
+ -[HAP2AccessorySessionInfo serviceName]
+ -[HAPAccessoryServerHAP2Adapter setSessionInfoWithNumIPsResolved:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:]
+ GCC_except_table4314
+ GCC_except_table4378
+ GCC_except_table4386
+ GCC_except_table4397
+ GCC_except_table4437
+ GCC_except_table4438
+ GCC_except_table4439
+ GCC_except_table4440
+ GCC_except_table4521
+ GCC_except_table4522
+ GCC_except_table4523
+ GCC_except_table4524
+ GCC_except_table4525
+ GCC_except_table4531
+ GCC_except_table4532
+ GCC_except_table4534
+ GCC_except_table4544
+ GCC_except_table4551
+ GCC_except_table4554
+ GCC_except_table4557
+ GCC_except_table4561
+ GCC_except_table4565
+ GCC_except_table4594
+ GCC_except_table4595
+ GCC_except_table4614
+ GCC_except_table4624
+ GCC_except_table4632
+ GCC_except_table4635
+ GCC_except_table4897
+ GCC_except_table4901
+ GCC_except_table4935
+ GCC_except_table4939
+ GCC_except_table4941
+ GCC_except_table4943
+ GCC_except_table5100
+ GCC_except_table5110
+ GCC_except_table5111
+ GCC_except_table5112
+ GCC_except_table5113
+ GCC_except_table5119
+ GCC_except_table5153
+ GCC_except_table5154
+ GCC_except_table5155
+ GCC_except_table5175
+ GCC_except_table5187
+ GCC_except_table5195
+ GCC_except_table5197
+ GCC_except_table5211
+ GCC_except_table5424
+ GCC_except_table5441
+ GCC_except_table5444
+ GCC_except_table5447
+ GCC_except_table5448
+ GCC_except_table5450
+ GCC_except_table5480
+ GCC_except_table5502
+ GCC_except_table5506
+ GCC_except_table5515
+ GCC_except_table5519
+ GCC_except_table5523
+ GCC_except_table5527
+ GCC_except_table5531
+ GCC_except_table5539
+ GCC_except_table5541
+ GCC_except_table5545
+ GCC_except_table5607
+ GCC_except_table5608
+ GCC_except_table5609
+ GCC_except_table5610
+ GCC_except_table5668
+ GCC_except_table5669
+ GCC_except_table5683
+ GCC_except_table5689
+ GCC_except_table5702
+ GCC_except_table5705
+ GCC_except_table5711
+ GCC_except_table5714
+ GCC_except_table5721
+ GCC_except_table5724
+ GCC_except_table5738
+ GCC_except_table5745
+ GCC_except_table5751
+ GCC_except_table5760
+ GCC_except_table5762
+ GCC_except_table5768
+ GCC_except_table5769
+ GCC_except_table5784
+ GCC_except_table5786
+ GCC_except_table5794
+ GCC_except_table5809
+ GCC_except_table5819
+ GCC_except_table5820
+ GCC_except_table5823
+ GCC_except_table5829
+ GCC_except_table5833
+ GCC_except_table5835
+ GCC_except_table5837
+ GCC_except_table5841
+ GCC_except_table5986
+ GCC_except_table6042
+ GCC_except_table6045
+ GCC_except_table6049
+ GCC_except_table6055
+ GCC_except_table6062
+ GCC_except_table6063
+ GCC_except_table6083
+ GCC_except_table6084
+ GCC_except_table6085
+ GCC_except_table6133
+ GCC_except_table6136
+ GCC_except_table6139
+ GCC_except_table6167
+ GCC_except_table6173
+ GCC_except_table6193
+ GCC_except_table6210
+ GCC_except_table6211
+ GCC_except_table6212
+ GCC_except_table6225
+ GCC_except_table6226
+ GCC_except_table6227
+ GCC_except_table6241
+ GCC_except_table6244
+ GCC_except_table6250
+ GCC_except_table6256
+ GCC_except_table6268
+ GCC_except_table6274
+ GCC_except_table6283
+ GCC_except_table6292
+ GCC_except_table6296
+ GCC_except_table6304
+ GCC_except_table6308
+ GCC_except_table6310
+ GCC_except_table6314
+ GCC_except_table6335
+ GCC_except_table6337
+ GCC_except_table6338
+ GCC_except_table6364
+ GCC_except_table6528
+ GCC_except_table6591
+ GCC_except_table6623
+ GCC_except_table6626
+ GCC_except_table6790
+ GCC_except_table6853
+ GCC_except_table6923
+ GCC_except_table6984
+ GCC_except_table6986
+ GCC_except_table6988
+ GCC_except_table6991
+ GCC_except_table6993
+ GCC_except_table6995
+ GCC_except_table6998
+ GCC_except_table7024
+ GCC_except_table7027
+ GCC_except_table7028
+ GCC_except_table7047
+ GCC_except_table7051
+ GCC_except_table7054
+ GCC_except_table7056
+ GCC_except_table7058
+ GCC_except_table7061
+ GCC_except_table7065
+ GCC_except_table7066
+ GCC_except_table7070
+ GCC_except_table7118
+ GCC_except_table7125
+ GCC_except_table7219
+ GCC_except_table7235
+ GCC_except_table7237
+ GCC_except_table7239
+ GCC_except_table7244
+ GCC_except_table7246
+ GCC_except_table7248
+ GCC_except_table7251
+ GCC_except_table7255
+ GCC_except_table7260
+ OBJC_IVAR_$_HAP2AccessoryServerTransportCoAP._resolveAttempted
+ OBJC_IVAR_$_HAP2AccessorySessionInfo._ipAddress
+ OBJC_IVAR_$_HAP2AccessorySessionInfo._resolveAttempted
+ OBJC_IVAR_$_HAP2AccessorySessionInfo._serviceName
+ _objc_msgSend$initWithNumIPs:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:
+ _objc_msgSend$ipAddress
+ _objc_msgSend$rangeOfString:
+ _objc_msgSend$resetWithNumIPs:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:
+ _objc_msgSend$resolveAttempted
+ _objc_msgSend$serviceName
+ _objc_msgSend$setSessionInfoWithNumIPsResolved:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:
- -[HAP2AccessorySessionInfo initWithNumIPs:numIPsTried:numBonjourNames:]
- -[HAP2AccessorySessionInfo resetWithNumIPs:numIPsTried:numBonjourNames:]
- -[HAPAccessoryServerHAP2Adapter setSessionInfoWithNumIPsResolved:numIPsTried:numBonjourNames:]
- GCC_except_table4309
- GCC_except_table4373
- GCC_except_table4381
- GCC_except_table4392
- GCC_except_table4429
- GCC_except_table4432
- GCC_except_table4433
- GCC_except_table4435
- GCC_except_table4515
- GCC_except_table4516
- GCC_except_table4517
- GCC_except_table4518
- GCC_except_table4519
- GCC_except_table4526
- GCC_except_table4527
- GCC_except_table4529
- GCC_except_table4536
- GCC_except_table4539
- GCC_except_table4549
- GCC_except_table4552
- GCC_except_table4556
- GCC_except_table4560
- GCC_except_table4589
- GCC_except_table4590
- GCC_except_table4609
- GCC_except_table4619
- GCC_except_table4622
- GCC_except_table4630
- GCC_except_table4892
- GCC_except_table4896
- GCC_except_table4930
- GCC_except_table4934
- GCC_except_table4936
- GCC_except_table4938
- GCC_except_table5095
- GCC_except_table5101
- GCC_except_table5105
- GCC_except_table5107
- GCC_except_table5108
- GCC_except_table5114
- GCC_except_table5148
- GCC_except_table5149
- GCC_except_table5150
- GCC_except_table5170
- GCC_except_table5182
- GCC_except_table5185
- GCC_except_table5192
- GCC_except_table5206
- GCC_except_table5419
- GCC_except_table5431
- GCC_except_table5439
- GCC_except_table5440
- GCC_except_table5442
- GCC_except_table5443
- GCC_except_table5475
- GCC_except_table5497
- GCC_except_table5501
- GCC_except_table5505
- GCC_except_table5514
- GCC_except_table5518
- GCC_except_table5522
- GCC_except_table5526
- GCC_except_table5534
- GCC_except_table5536
- GCC_except_table5540
- GCC_except_table5602
- GCC_except_table5603
- GCC_except_table5604
- GCC_except_table5605
- GCC_except_table5663
- GCC_except_table5664
- GCC_except_table5678
- GCC_except_table5684
- GCC_except_table5697
- GCC_except_table5700
- GCC_except_table5701
- GCC_except_table5709
- GCC_except_table5716
- GCC_except_table5719
- GCC_except_table5733
- GCC_except_table5740
- GCC_except_table5746
- GCC_except_table5755
- GCC_except_table5757
- GCC_except_table5763
- GCC_except_table5764
- GCC_except_table5779
- GCC_except_table5781
- GCC_except_table5789
- GCC_except_table5804
- GCC_except_table5805
- GCC_except_table5814
- GCC_except_table5818
- GCC_except_table5824
- GCC_except_table5828
- GCC_except_table5830
- GCC_except_table5832
- GCC_except_table5836
- GCC_except_table5981
- GCC_except_table6037
- GCC_except_table6040
- GCC_except_table6044
- GCC_except_table6050
- GCC_except_table6057
- GCC_except_table6058
- GCC_except_table6074
- GCC_except_table6078
- GCC_except_table6080
- GCC_except_table6128
- GCC_except_table6129
- GCC_except_table6131
- GCC_except_table6162
- GCC_except_table6163
- GCC_except_table6188
- GCC_except_table6205
- GCC_except_table6206
- GCC_except_table6207
- GCC_except_table6215
- GCC_except_table6221
- GCC_except_table6222
- GCC_except_table6236
- GCC_except_table6239
- GCC_except_table6245
- GCC_except_table6251
- GCC_except_table6263
- GCC_except_table6264
- GCC_except_table6278
- GCC_except_table6286
- GCC_except_table6287
- GCC_except_table6299
- GCC_except_table6303
- GCC_except_table6305
- GCC_except_table6309
- GCC_except_table6330
- GCC_except_table6332
- GCC_except_table6333
- GCC_except_table6359
- GCC_except_table6523
- GCC_except_table6586
- GCC_except_table6618
- GCC_except_table6621
- GCC_except_table6785
- GCC_except_table6848
- GCC_except_table6911
- GCC_except_table6962
- GCC_except_table6964
- GCC_except_table6966
- GCC_except_table6985
- GCC_except_table6987
- GCC_except_table6989
- GCC_except_table6992
- GCC_except_table7018
- GCC_except_table7021
- GCC_except_table7022
- GCC_except_table7041
- GCC_except_table7042
- GCC_except_table7043
- GCC_except_table7045
- GCC_except_table7046
- GCC_except_table7050
- GCC_except_table7053
- GCC_except_table7060
- GCC_except_table7064
- GCC_except_table7112
- GCC_except_table7119
- GCC_except_table7213
- GCC_except_table7229
- GCC_except_table7231
- GCC_except_table7233
- GCC_except_table7236
- GCC_except_table7238
- GCC_except_table7240
- GCC_except_table7243
- GCC_except_table7245
- GCC_except_table7254
- _objc_msgSend$initWithNumIPs:numIPsTried:numBonjourNames:
- _objc_msgSend$resetWithNumIPs:numIPsTried:numBonjourNames:
- _objc_msgSend$setSessionInfoWithNumIPsResolved:numIPsTried:numBonjourNames:
CStrings:
+ "%@ '%@' - Close with error %@ and IP: %@"
+ "%@ '%@' - resolver failure with error %@ and IP: %@"
+ "%@ '%{private}@' - Opening finished with error %@ and IP: %@"
+ "(Unknown)"
+ "@60@0:8Q16Q24Q32@40@48B56"
+ "Coordinator: lost accessory: %@ with error: %@ and isDiscovering: %@"
+ "Num IP Addresses: %lu, Num IP Addresses Tried: %lu, Num Bonjour Names: %lu, IP Address: %@, Service Name: %@ Resolve Attmpt: %@"
+ "T@\"NSString\",R,N,V_ipAddress"
+ "T@\"NSString\",R,N,V_serviceName"
+ "TB,R,N,V_resolveAttempted"
+ "["
+ "]"
+ "_resolveAttempted"
+ "initWithNumIPs:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:"
+ "ipAddress"
+ "rangeOfString:"
+ "resetWithNumIPs:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:"
+ "resolveAttempted"
+ "serviceName"
+ "setSessionInfoWithNumIPsResolved:numIPsTried:numBonjourNames:ipAddress:serviceName:resolveAttempted:"
+ "v60@0:8Q16Q24Q32@\"NSString\"40@\"NSString\"48B56"
+ "v60@0:8Q16Q24Q32@40@48B56"
+ "\xd1"
- "@40@0:8Q16Q24Q32"
- "initWithNumIPs:numIPsTried:numBonjourNames:"
- "resetWithNumIPs:numIPsTried:numBonjourNames:"
- "setSessionInfoWithNumIPsResolved:numIPsTried:numBonjourNames:"
- "v40@0:8Q16Q24Q32"
- "\xc1"
```
