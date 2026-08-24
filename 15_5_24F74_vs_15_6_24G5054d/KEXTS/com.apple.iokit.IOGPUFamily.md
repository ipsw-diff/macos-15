## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

### Sections with Same Size but Changed Content

- `__TEXT.__os_log`

```diff

-104.5.0.0.0
-  __TEXT.__cstring: 0x5806
+104.6.2.0.0
+  __TEXT.__cstring: 0x57e6
   __TEXT.__os_log: 0x3d1d
   __TEXT.__const: 0xd4
-  __TEXT_EXEC.__text: 0x3f0a8
+  __TEXT_EXEC.__text: 0x3f048
   __TEXT_EXEC.__auth_stubs: 0x0
-  __DATA.__data: 0x4b0
-  __DATA.__common: 0x7d0
+  __DATA.__data: 0x410
+  __DATA.__common: 0x7c8
   __DATA.__bss: 0x9
   __DATA_CONST.__auth_got: 0x678
   __DATA_CONST.__got: 0xf8

   __DATA_CONST.__kalloc_var: 0xf00
   __DATA_CONST.__assert: 0x78
   Functions: 1899
-  Symbols:   3147
-  CStrings:  802
+  Symbols:   3144
+  CStrings:  800
 
Symbols:
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2258
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2264
+ __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_297
+ __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_314
+ __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_327
+ __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_339
+ __ZZN24IOGPUClientSharedMachine4freeEvE20kalloc_type_view_132
+ __ZZN5IOGPU4freeEvE20kalloc_type_view_840
+ __ZZN5IOGPU5startEP9IOServiceE20kalloc_type_view_317
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2273
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2279
- __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_299
- __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_316
- __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_329
- __ZZN24IOGPUClientSharedMachine20mapClientSharedForIdEjPPvE20kalloc_type_view_341
- __ZZN24IOGPUClientSharedMachine4freeEvE20kalloc_type_view_134
- __ZZN5IOGPU4freeEvE20kalloc_type_view_847
- __ZZN5IOGPU5startEP9IOServiceE20kalloc_type_view_324
- _gIOGPUResourceLimitOverride
- _sysctl__debug_iogpu_rsrc_limit
- _sysctl__iogpu_rsrc_limit
Functions:
~ __ZN11IOGPUDevice12new_resourceEP20IOGPUNewResourceArgsP26IOGPUNewResourceReturnDatayPj : 2640 -> 2568
~ _GLOBAL__sub_I_IOGPU.cpp : 236 -> 212
CStrings:
+ "%s: PID %d may be leaking IOGPUResource (count=%d)\n"
- "%s: PID %d likely leaking IOGPUResource (count=%d)\n"
- "Resource Limit Count"
- "rsrc_limit"
```
