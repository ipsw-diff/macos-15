## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

-2894.140.11.0.0
-  __TEXT.__text: 0x51b74
-  __TEXT.__auth_stubs: 0x1ed0
+2894.140.11.0.1
+  __TEXT.__text: 0x5176c
+  __TEXT.__auth_stubs: 0x1ec0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x1f4
   __TEXT.__const: 0x2e0
-  __TEXT.__cstring: 0x155d2
+  __TEXT.__cstring: 0x14df7
   __TEXT.__launchd: 0x1
   __TEXT.__objc_methname: 0x8
   __TEXT.__objc_classname: 0x1ba
   __TEXT.__objc_methtype: 0x8
   __TEXT.__config: 0x3512
   __TEXT.__dof_launchd: 0x81d
-  __TEXT.__unwind_info: 0x1150
-  __DATA_CONST.__auth_got: 0xf68
+  __TEXT.__unwind_info: 0x1140
+  __DATA_CONST.__auth_got: 0xf60
   __DATA_CONST.__got: 0x188
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA_CONST.__const: 0x51d0
+  __DATA_CONST.__const: 0x51a0
   __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0xa8

   __DATA.__data: 0x890
   __DATA.__os_assumes_log: 0x8
   __DATA.__crash_info: 0x40
-  __DATA.__bss: 0xe58
+  __DATA.__bss: 0xe50
   __DATA.__common: 0x804
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libauditd.0.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1615
-  Symbols:   548
-  CStrings:  2661
+  Functions: 1610
+  Symbols:   547
+  CStrings:  2655
 
Symbols:
- _proc_track_dirty
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sun Jul  6 18:47:42 PDT 2025; root:libxpc_executables-2894.140.11.0.1~19/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sun Jul  6 18:47:42 PDT 2025; root:libxpc_executables-2894.140.11.0.1~19/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sun Jun 22 22:05:17 PDT 2025; root:libxpc_executables-2894.140.11~35/launchd/RELEASE_ARM64E"
- "B16@?0^{_launch_service_s={_launch_obj_header_s=^vB}^{_launch_service_static_s}{?={?=^{_launch_service_s}^^{_launch_service_s}}{?=^{_launch_service_s}^^{_launch_service_s}{qm_trace=*i*i}}{?=^{_launch_service_s}^^{_launch_service_s}}{?=^{_launch_service_s}^^{_launch_service_s}}{?=^{_launch_service_s}^^{_launch_service_s}}}{?={?=^{_launch_event_subscription_s}}{?=^{_launch_event_provider_s}}{?=^{_launch_endpoint_s}}{?=^{_launch_endpoint_s}}{?=^{_launch_endpoint_s}}{?=^{_launch_endpoint_s}}{?=^{_launch_endpoint_s}}{?=^{_launch_socket_s}}{_instances_s=^{_launch_service_s}^^{_launch_service_s}{qm_trace=*i*i}}^{_launch_domain_s}^{_launch_service_s}II^v^{dispatch_group_s}iiis*^{_launch_coalition_s}^{_launch_coalition_s}^{_launch_domain_s}^v^{dispatch_group_s}^{dispatch_group_s}^{_launch_job_s}ICiib1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}{?={_xpc_token_s=IIIIIiii}[16C]CI^********^v^v{?=^{_launch_pended_request_s}}{_launch_service_delegate_s=^?^?^?^?^?^?^v}***Q**[16C]*I*I*I^v^v{?=^{_launch_service_semaphore_s}}{?=^{_launch_service_rlimit_s}}[3i]Iii^{dispatch_source_s}^{dispatch_source_s}**SQi^{dispatch_source_s}II^{_launch_diagnostic_thread_s}^{dispatch_source_s}^{dispatch_source_s}II^{dispatch_source_s}I^{dispatch_source_s}*II^{?}IiiiiiQIIIIIII^{_launch_jetsam_stats_s}CQQ{?=^{_launch_envvar_s}}sCIiIISCQ{_launch_throttle_stats_s=BBIQ^v^v{_launch_exit_status_s=I{proc_exitreasonbasicinfo=IQQI}iQQb1b1b1}}I{?=*Qiii^{dispatch_source_s}^{dispatch_source_s}SSb8b24b1b1b1b1b1b1b1b1b1}{_launch_exit_status_s=I{proc_exitreasonbasicinfo=IQQI}iQQb1b1b1}{?=*^v*^v^{?}I^viisb1b1b1b1b1b1}ICIIiCC{?=II}**^{_os_opaque_64_map_s}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}[0c]}8"
- "Darwin Bootstrapper Version 7.0.0: Sun Jun 22 22:05:17 PDT 2025; root:libxpc_executables-2894.140.11~35/launchd/RELEASE_ARM64E"
- "Finding services to set shutdown-on-clean"
- "Running with outdated trial config: %s: curr=\"%s\", new=\"%s\""
- "Set shutdown-on-clean on %zu/%zu running services"
- "Set shutdown-on-clean: service=%s, flags=0x%x, error=%d"
- "trial shutdown-on-clean count = %zu"
```
