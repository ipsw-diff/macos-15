## PasswordManagerBrowserExtensionHelper

> `/System/Library/CoreServices/PasswordManagerBrowserExtensionHelper.app/Contents/MacOS/PasswordManagerBrowserExtensionHelper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-7621.2.1.11.5
-  __TEXT.__text: 0x128e8
-  __TEXT.__auth_stubs: 0x950
-  __TEXT.__objc_stubs: 0x2480
+7621.2.3.11.1
+  __TEXT.__text: 0x1015c
+  __TEXT.__auth_stubs: 0x920
+  __TEXT.__objc_stubs: 0x2420
   __TEXT.__objc_methlist: 0xcec
-  __TEXT.__cstring: 0x11b5
-  __TEXT.__objc_methname: 0x2c9b
+  __TEXT.__cstring: 0x1055
+  __TEXT.__objc_methname: 0x2c72
   __TEXT.__objc_classname: 0x1d7
   __TEXT.__objc_methtype: 0x8b5
-  __TEXT.__const: 0x244
+  __TEXT.__const: 0x204
   __TEXT.__gcc_except_tab: 0x9c
-  __TEXT.__oslogstring: 0xd1f
+  __TEXT.__oslogstring: 0x21f
   __TEXT.__ustring: 0x2a2
-  __TEXT.__swift5_typeref: 0x128
   __TEXT.__constg_swiftt: 0x17c
+  __TEXT.__swift5_typeref: 0x128
   __TEXT.__swift5_reflstr: 0x58
   __TEXT.__swift5_fieldmd: 0x50
   __TEXT.__swift5_capture: 0x10
   __TEXT.__swift5_proto: 0xc
   __TEXT.__swift5_types: 0xc
-  __TEXT.__unwind_info: 0x490
+  __TEXT.__unwind_info: 0x450
   __TEXT.__eh_frame: 0x48
-  __DATA_CONST.__auth_got: 0x4b8
-  __DATA_CONST.__got: 0x2e0
+  __DATA_CONST.__auth_got: 0x4a0
+  __DATA_CONST.__got: 0x2d8
   __DATA_CONST.__auth_ptr: 0x80
-  __DATA_CONST.__const: 0x828
-  __DATA_CONST.__cfstring: 0x1200
+  __DATA_CONST.__const: 0x808
+  __DATA_CONST.__cfstring: 0x11a0
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x1940
-  __DATA.__objc_selrefs: 0xc40
+  __DATA.__objc_selrefs: 0xc30
   __DATA.__objc_ivar: 0xe0
   __DATA.__objc_data: 0x630
   __DATA.__data: 0x378
-  __DATA.__bss: 0x1c0
+  __DATA.__bss: 0x1b0
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 387
-  Symbols:   304
-  CStrings:  862
+  Functions: 331
+  Symbols:   300
+  CStrings:  786
 
Symbols:
- _$sSds7CVarArgsWP
- _$sSo13os_log_type_ta0A0E5debugABvgZ
- _NSStringFromRect
- __os_log_debug_impl
CStrings:
+ "Creating new session for client browser %@"
- ", "
- "Adding credential: user:%{sensitive}@ password:%{sensitive}@ protectionSpace:%{sensitive}@(url:%{sensitive}@)"
- "Attempting to decrypt before session key has been established"
- "Attempting to decrypt before session key has been established."
- "Beginning authentication request."
- "Client returned error in PAKE field: %{public}@."
- "Consuming Messages one-time code with GUID %@."
- "Creating new session for client browser %@ (%@)"
- "Data as UTF-8: %{sensitive}@"
- "Decoded ChallengePIN PAKE payload. messageNumber:%ld"
- "Decoded a non-Dictionary object."
- "Decoded dictionary: %{sensitive}@"
- "Decrypted dictionary data: %{sensitive}@"
- "Encrypted dictionary data: %{sensitive}@"
- "Error decoding or decrypting SDATA."
- "Error decrypting data. %d"
- "Error encoding JSON object: %{public}@"
- "Error encrypting data: %d"
- "Error generating Message 1 from Message 0."
- "Error generating Message 3 from Message 2."
- "Error generating salt and verifier: %d"
- "Error initializing SRP context: %d"
- "Error parsing 'msg' field from ChallengePIN input object."
- "Error serializing ChallengePIN response object: %{public}@"
- "Error serializing JSON object for stdout: %{public}@"
- "Error starting SRP authentication session: %d"
- "Expected to consume one-time code from Messages, but found a code with a different source."
- "Expecting %u bytes from %{public}@"
- "Failed authentication challenge. %{public}@"
- "Failed to encrypt SMSG data"
- "Generating salt and verifier for SRP session"
- "Handling SRP message 0"
- "Handling SRP message 2"
- "Increasing backoff to %4.2f sec from now."
- "Input object contains the following keys: %@"
- "Input object: %{sensitive}@"
- "Invalid message sequence number: %d"
- "Invalid username"
- "Message doesn't contain username, or contains invalid username for current session."
- "Missing 'cmd' key in input object."
- "Missing M field in Message 2"
- "Missing SMSG object payload."
- "Missing sequence number in PAKE payload."
- "Missing username field from message."
- "Missing username field in Message 0."
- "More than one result returned for query; using the first one. %{sensitive}@"
- "NO"
- "Negotiated protocol version %d"
- "Number of incorrect guesses exceeded. Beginning backoff at %4.2f."
- "Output SMSG %{sensitive}@"
- "Placing window over target window for \"%@\" with bounds %@"
- "Query response after auth: %{sensitive}@"
- "Received AddNew query. This is unsupported."
- "Received Delete query. This is unsupported."
- "Received Update query. This is unsupported."
- "Received command '%{public}@' from extension."
- "Running query: %{sensitive}@"
- "SRP Message 1: %{sensitive}@"
- "SRP Message 3: %{sensitive}@"
- "Session backoff data not found in Keychain"
- "Session was not verified"
- "Starting SRP authentication session"
- "Stored backoff interval is greater than max: %4.2f > %4.2f"
- "System was rebooted since last checking backoff data"
- "Time remaining %4.2f"
- "Unable to decode JSON object directly from data; attempting string encoding first."
- "Unable to decode JSON object.\n  1st error: %{public}@\n  2nd error: %{public}@"
- "Unable to generate initialization vector for encryption"
- "Updating Touch ID Status. old status:%ld, new status:%ld, auth required for clamshell:%{public}@"
- "User declined add."
- "User declined update."
- "Verifying session with M value from client"
- "Verifying session with verifier from client"
- "YES"
- "absoluteString"
- "auth"
- "componentsJoinedByString:"
```
