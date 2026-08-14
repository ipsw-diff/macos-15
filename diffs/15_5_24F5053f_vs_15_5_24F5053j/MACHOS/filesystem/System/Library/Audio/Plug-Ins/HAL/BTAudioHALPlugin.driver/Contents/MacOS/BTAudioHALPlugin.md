## BTAudioHALPlugin

> `/System/Library/Audio/Plug-Ins/HAL/BTAudioHALPlugin.driver/Contents/MacOS/BTAudioHALPlugin`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-185.6.1.0.1
-  __TEXT.__text: 0x88228
+185.7.1.0.0
+  __TEXT.__text: 0x88594
   __TEXT.__auth_stubs: 0x11d0
   __TEXT.__objc_stubs: 0x1e20
   __TEXT.__init_offsets: 0xa8
   __TEXT.__objc_methlist: 0xc9c
-  __TEXT.__gcc_except_tab: 0x2534
+  __TEXT.__gcc_except_tab: 0x252c
   __TEXT.__const: 0x1a0c
   __TEXT.__cstring: 0x4bb8
-  __TEXT.__oslogstring: 0x156e9
+  __TEXT.__oslogstring: 0x1576f
   __TEXT.__objc_classname: 0x113
   __TEXT.__objc_methname: 0x292b
   __TEXT.__objc_methtype: 0x76c

   - /usr/lib/libobjc.A.dylib
   Functions: 2820
   Symbols:   418
-  CStrings:  2699
+  CStrings:  2701
 
Functions:
~ sub_472a0 : 732 -> 764
~ sub_6d574 -> sub_6d594 : 4752 -> 5596
CStrings:
+ "USBc unified update saving update from %d volume for %@ is %f"
+ "USBc unified update saving update from %d volume for 'mainVolume' is %f"
```
