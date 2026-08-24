## Hypervisor

> `/System/Library/Frameworks/Hypervisor.framework/Versions/A/Hypervisor`

```diff

-210.6.2.0.0
-  __TEXT.__text: 0x6c7bc
+210.7.1.0.0
+  __TEXT.__text: 0x6d340
   __TEXT.__auth_stubs: 0x6c0
   __TEXT.__gcc_except_tab: 0x26ac
   __TEXT.__const: 0x1da4
-  __TEXT.__cstring: 0x1d8d
+  __TEXT.__cstring: 0x202d
   __TEXT.__oslogstring: 0x52
-  __TEXT.__unwind_info: 0x1618
+  __TEXT.__unwind_info: 0x1620
   __TEXT.__objc_classname: 0x5a
   __DATA_CONST.__got: 0xa8
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __AUTH_CONST.__auth_got: 0x368
-  __AUTH_CONST.__const: 0x3828
+  __AUTH_CONST.__const: 0x3850
   __AUTH_CONST.__objc_const: 0x2d0
   __AUTH.__objc_data: 0x190
   __AUTH.__thread_vars: 0x18

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2113
-  Symbols:   2746
-  CStrings:  522
+  Functions: 2118
+  Symbols:   2749
+  CStrings:  568
 
Symbols:
+ GCC_except_table1173
+ GCC_except_table1176
+ GCC_except_table1181
+ GCC_except_table1182
+ GCC_except_table1185
+ GCC_except_table1186
+ GCC_except_table1210
+ GCC_except_table1211
+ GCC_except_table1454
+ GCC_except_table1457
+ GCC_except_table1458
+ GCC_except_table1464
+ GCC_except_table1465
+ GCC_except_table1477
+ GCC_except_table1478
+ GCC_except_table1484
+ GCC_except_table1493
+ GCC_except_table1494
+ GCC_except_table1502
+ GCC_except_table1507
+ GCC_except_table1512
+ GCC_except_table1520
+ GCC_except_table1548
+ GCC_except_table1552
+ GCC_except_table1565
+ GCC_except_table1566
+ GCC_except_table1574
+ GCC_except_table1588
+ GCC_except_table1589
+ GCC_except_table1632
+ GCC_except_table1638
+ GCC_except_table1645
+ GCC_except_table1646
+ GCC_except_table1653
+ GCC_except_table1654
+ GCC_except_table1658
+ GCC_except_table1661
+ GCC_except_table1668
+ GCC_except_table1680
+ GCC_except_table1681
+ GCC_except_table91
+ GCC_except_table94
+ __ZN2Hv4Vcpu13get_clidr_el1Ev
+ __ZN6HvCore10Hypervisor16VcpuStateManager13get_clidr_el1Ev
+ __ZThn16_N6HvCore10Hypervisor16VcpuStateManager13get_clidr_el1Ev
+ __ZThn8_N2Hv4Vcpu13get_clidr_el1Ev
- GCC_except_table1169
- GCC_except_table1172
- GCC_except_table1175
- GCC_except_table1180
- GCC_except_table1183
- GCC_except_table1184
- GCC_except_table1208
- GCC_except_table1209
- GCC_except_table1452
- GCC_except_table1455
- GCC_except_table1456
- GCC_except_table1459
- GCC_except_table1462
- GCC_except_table1475
- GCC_except_table1476
- GCC_except_table1482
- GCC_except_table1485
- GCC_except_table1486
- GCC_except_table1500
- GCC_except_table1505
- GCC_except_table1508
- GCC_except_table1516
- GCC_except_table1546
- GCC_except_table1550
- GCC_except_table1556
- GCC_except_table1561
- GCC_except_table1572
- GCC_except_table1576
- GCC_except_table1583
- GCC_except_table1624
- GCC_except_table1636
- GCC_except_table1642
- GCC_except_table1643
- GCC_except_table1647
- GCC_except_table1648
- GCC_except_table1656
- GCC_except_table1657
- GCC_except_table1662
- GCC_except_table1678
- GCC_except_table1679
- GCC_except_table69
- GCC_except_table70
- GCC_except_table85
CStrings:
+ "GCR_EL1"
+ "PM"
+ "PMCCNTSVR_EL1"
+ "PMECR_EL1"
+ "PMEVCNTSVR0_EL1"
+ "PMEVCNTSVR10_EL1"
+ "PMEVCNTSVR11_EL1"
+ "PMEVCNTSVR12_EL1"
+ "PMEVCNTSVR13_EL1"
+ "PMEVCNTSVR14_EL1"
+ "PMEVCNTSVR15_EL1"
+ "PMEVCNTSVR16_EL1"
+ "PMEVCNTSVR17_EL1"
+ "PMEVCNTSVR18_EL1"
+ "PMEVCNTSVR19_EL1"
+ "PMEVCNTSVR1_EL1"
+ "PMEVCNTSVR20_EL1"
+ "PMEVCNTSVR21_EL1"
+ "PMEVCNTSVR22_EL1"
+ "PMEVCNTSVR23_EL1"
+ "PMEVCNTSVR24_EL1"
+ "PMEVCNTSVR25_EL1"
+ "PMEVCNTSVR26_EL1"
+ "PMEVCNTSVR27_EL1"
+ "PMEVCNTSVR28_EL1"
+ "PMEVCNTSVR29_EL1"
+ "PMEVCNTSVR2_EL1"
+ "PMEVCNTSVR30_EL1"
+ "PMEVCNTSVR3_EL1"
+ "PMEVCNTSVR4_EL1"
+ "PMEVCNTSVR5_EL1"
+ "PMEVCNTSVR6_EL1"
+ "PMEVCNTSVR7_EL1"
+ "PMEVCNTSVR8_EL1"
+ "PMEVCNTSVR9_EL1"
+ "PMIAR_EL1"
+ "PMICFILTR_EL0"
+ "PMICNTR_EL0"
+ "PMICNTSVR_EL1"
+ "PMMIR_EL1"
+ "PMSSCR_EL1"
+ "PMUACR_EL1"
+ "PMZR_EL0"
+ "RGSR_EL1"
+ "TFSRE0_EL1"
+ "TFSR_El1"
```
