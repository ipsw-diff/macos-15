## CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-12403.2.0.0.0
-  __TEXT.__text: 0x64eda4
+12406.2.0.0.0
+  __TEXT.__text: 0x64f408
   __TEXT.__auth_stubs: 0x6b60
   __TEXT.__objc_stubs: 0xa5c0
   __TEXT.__init_offsets: 0x194
   __TEXT.__objc_methlist: 0x5d9c
   __TEXT.__const: 0x84417
-  __TEXT.__cstring: 0x2187a
-  __TEXT.__gcc_except_tab: 0x7488c
-  __TEXT.__oslogstring: 0x640c6
+  __TEXT.__cstring: 0x21891
+  __TEXT.__gcc_except_tab: 0x74914
+  __TEXT.__oslogstring: 0x6418f
   __TEXT.__objc_classname: 0x1563
   __TEXT.__objc_methname: 0xeff4
   __TEXT.__objc_methtype: 0xdcba
   __TEXT.__ustring: 0x3e2
-  __TEXT.__unwind_info: 0x24030
+  __TEXT.__unwind_info: 0x24038
   __TEXT.__eh_frame: 0x60
   __DATA_CONST.__auth_got: 0x35c8
   __DATA_CONST.__got: 0x1c48
   __DATA_CONST.__auth_ptr: 0x30
   __DATA_CONST.__const: 0x6da58
-  __DATA_CONST.__cfstring: 0xa860
+  __DATA_CONST.__cfstring: 0xa880
   __DATA_CONST.__objc_classlist: 0x240
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x290

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 28357
+  Functions: 28358
   Symbols:   2838
-  CStrings:  17030
+  CStrings:  17034
 
CStrings:
+ "#E %s%sMonitor mode requested repeatedly - ignore"
+ "#E %s%sMonitor mode retry attempts exceeded - ignore"
+ "#E %s%sMonitor mode retry called outside of monitor mode - ignore"
+ "#I %s%s%s%s | MonitorModeRetryControl: %s (retried %d)"
+ "#I %s%sEntering monitor mode"
+ "#I %s%sMonitor mode controlled retry triggered: %d attempt"
+ "#I Resetting RTT and sending CTM as RTT is not supported by the carrier. Call SubType: %s, TTYRTTSupported: %s, RTTOnlySupported: %s, IMSRegistered: %s"
+ "#I Resetting RTT for emergency call with normal setup."
+ "#I Sending CTM for RTT call: %s"
+ "#I Sending CTM for TTY call: %s"
+ "#I Set RTT/TTY as %s request for call %{public}s (and sending CTM for TTY call)"
+ "12406.2"
+ "12406.2~29"
+ "Ignoring TTY switch changes, because this carrier supports only RTT"
+ "monitor-mode-retry-cnt"
- "#I %s%s%s%s | MonitorMode: %s, RetryControl: %s"
- "#I %s%s%s%sengaging block on communication until next Monitor Mode retry"
- "#I %s%sEntering monitor mode with followMonitorModeRetries: %s"
- "#I %s%sMonitor mode controlled retry triggered"
- "#I Resetting TTY and sending CTM as TTY is not supported by the carrier. TTYSupported: %s, RTTSupported: %s, IMSRegistered: %s"
- "#I Sending CTM for RTT call"
- "#I Sending CTM for TTY call"
- "#I Sending CTM for TTY call - fallthrough"
- "#I Set TTY as %s request for call %{public}s and sending CTM for TTY call"
- "12403.2"
- "12403.2~14"
```
