## CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-12406.2.0.0.0
-  __TEXT.__text: 0x64f408
+12408.0.0.0.0
+  __TEXT.__text: 0x64f8a8
   __TEXT.__auth_stubs: 0x6b60
   __TEXT.__objc_stubs: 0xa5c0
   __TEXT.__init_offsets: 0x194
   __TEXT.__objc_methlist: 0x5d9c
   __TEXT.__const: 0x84417
-  __TEXT.__cstring: 0x21891
-  __TEXT.__gcc_except_tab: 0x74914
-  __TEXT.__oslogstring: 0x6418f
+  __TEXT.__cstring: 0x218a7
+  __TEXT.__gcc_except_tab: 0x7499c
+  __TEXT.__oslogstring: 0x64233
   __TEXT.__objc_classname: 0x1563
-  __TEXT.__objc_methname: 0xeff4
-  __TEXT.__objc_methtype: 0xdcba
+  __TEXT.__objc_methname: 0xf011
+  __TEXT.__objc_methtype: 0xdcbd
   __TEXT.__ustring: 0x3e2
-  __TEXT.__unwind_info: 0x24038
+  __TEXT.__unwind_info: 0x24050
   __TEXT.__eh_frame: 0x60
   __DATA_CONST.__auth_got: 0x35c8
   __DATA_CONST.__got: 0x1c48

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 28358
+  Functions: 28360
   Symbols:   2838
-  CStrings:  17034
+  CStrings:  17037
 
CStrings:
+ "#I RTT capability dropped for call: %s [original: %s]"
+ "#I Setting this call (%s)'s Voice and TTY capability to %s"
+ "#I Updating TTY type to %s, ttyWithVoiceSupported=%s, supportsTTYWithVoice=%s"
+ "12408"
+ "12408~23"
+ "@36@0:8@16i24B28B32"
+ "getCallCapabilitiesUpdateForCall:simSlot:isEmergency:supportsTextWithVoiceForCall:"
+ "kIsTTYWithVoiceSupported"
+ "{CallInfo={CFSharedRef<const __CFUUID>=^{__CFUUID}}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}iCiCiiiBBBBBIIIIIIS{optional<CSIError>=(?=ci)B}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}i{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}iBCiBBiB{optional<unsigned int>=(?=cI)B}{optional<std::vector<unsigned int>>=(?=c{vector<unsigned int, std::allocator<unsigned int>>=^I^I{__compressed_pair<unsigned int *, std::allocator<unsigned int>>=^I}})B}{optional<bool>=(?=cB)B}iBIB{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}IIBBBBBBBB{optional<CallMetricRedial>=(?=c{CallMetricRedial=i{optional<std::chrono::time_point<std::chrono::steady_clock, std::chrono::duration<long long, std::ratio<1, 1000000000>>>>=(?=c{time_point<std::chrono::steady_clock, std::chrono::duration<long long, std::ratio<1, 1000000000>>>={duration<long long, std::ratio<1, 1000000000>>=q}})B}iQIB})B}{optional<CallMetricEmergency>=(?=c{CallMetricEmergency={optional<CallMetricEmNumListType>=(?=ci)B}{optional<CallMetricEmSIP380Procedure>=(?=cC)B}})B}}8@?0"
- "#I Updating TTY type to %s"
- "12406.2"
- "12406.2~29"
- "@32@0:8@16i24B28"
- "getCallCapabilitiesUpdateForCall:simSlot:isEmergency:"
- "{CallInfo={CFSharedRef<const __CFUUID>=^{__CFUUID}}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}iCiCiiiBBBBBIIIIIIS{optional<CSIError>=(?=ci)B}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}i{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}iBCiBBi{optional<unsigned int>=(?=cI)B}{optional<std::vector<unsigned int>>=(?=c{vector<unsigned int, std::allocator<unsigned int>>=^I^I{__compressed_pair<unsigned int *, std::allocator<unsigned int>>=^I}})B}{optional<bool>=(?=cB)B}iBIB{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}{basic_string<char, std::char_traits<char>, std::allocator<char>>={__compressed_pair<std::basic_string<char>::__rep, std::allocator<char>>=(__rep={__short=[23c][0C]b7b1}{__long=*Qb63b1})}}IIBBBBBBBB{optional<CallMetricRedial>=(?=c{CallMetricRedial=i{optional<std::chrono::time_point<std::chrono::steady_clock, std::chrono::duration<long long, std::ratio<1, 1000000000>>>>=(?=c{time_point<std::chrono::steady_clock, std::chrono::duration<long long, std::ratio<1, 1000000000>>>={duration<long long, std::ratio<1, 1000000000>>=q}})B}iQIB})B}{optional<CallMetricEmergency>=(?=c{CallMetricEmergency={optional<CallMetricEmNumListType>=(?=ci)B}{optional<CallMetricEmSIP380Procedure>=(?=cC)B}})B}}8@?0"
```
