## com.apple.MEValidationService

> `/System/Library/Frameworks/MediaExtension.framework/Versions/A/XPCServices/com.apple.MEValidationService.xpc/Contents/MacOS/com.apple.MEValidationService`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

-3235.10.1.0.0
-  __TEXT.__text: 0x1e88
-  __TEXT.__auth_stubs: 0x520
+3235.12.2.0.0
+  __TEXT.__text: 0x106c
+  __TEXT.__auth_stubs: 0x510
   __TEXT.__objc_stubs: 0xe0
-  __TEXT.__const: 0x38
+  __TEXT.__const: 0x10
   __TEXT.__cstring: 0x54e
-  __TEXT.__oslogstring: 0xfe0
+  __TEXT.__oslogstring: 0x15b
   __TEXT.__objc_methname: 0x82
-  __TEXT.__unwind_info: 0x80
-  __DATA_CONST.__auth_got: 0x298
-  __DATA_CONST.__got: 0x88
+  __TEXT.__unwind_info: 0x88
+  __DATA_CONST.__auth_got: 0x290
+  __DATA_CONST.__got: 0x70
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x70
   __DATA_CONST.__cfstring: 0xe0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 10
-  Symbols:   106
-  CStrings:  83
+  Symbols:   102
+  CStrings:  31
 
Symbols:
- ___error
- __xpc_error_connection_invalid
- __xpc_error_key_description
- __xpc_error_termination_imminent
Functions:
~ _main : 580 -> 368
~ sub_100000d3c -> sub_100000c68 : 224 -> 152
~ sub_100000e1c -> sub_100000d00 : 4236 -> 1980
~ sub_100001eb8 -> sub_1000014cc : 460 -> 228
~ sub_100002084 -> sub_1000015b0 : 1172 -> 596
~ sub_100002518 -> sub_100001804 : 932 -> 668
CStrings:
- "CheckHostApplicationHasRequiredSandboxAccess: invalid XPC message object"
- "CheckHostApplicationHasRequiredSandboxAccess: invalid file descriptor in XPC request"
- "CheckHostApplicationHasRequiredSandboxAccess: unable to obtain path from file descriptor"
- "CopyAndValidateBundlePlistDictionary: Info.plist is missing or invalid"
- "CopyAndValidateBundlePlistDictionary: SecCodeCheckValidityWithErrors failed with error : (%d)(%@) "
- "CopyAndValidateBundlePlistDictionary: SecCodeCreateWithAuditToken failed with error : %d"
- "CopyAndValidateBundlePlistDictionary: SecRequirementCreateWithString failed with error : %d"
- "CopyAndValidateBundlePlistDictionary: missing App Sandbox entitlement"
- "CopyAndValidateBundlePlistDictionary: missing format reader entitlement "
- "CopyAndValidateBundlePlistDictionary: read of code signing info failed with error %d"
- "CopyAndValidateBundlePlistDictionary: unable to read entitlements"
- "CopyFileDescriptorURLFromXPCRequest: invalid XPC message object"
- "CopyFileDescriptorURLFromXPCRequest: invalid file descriptor in XPC request"
- "CopyFileDescriptorURLFromXPCRequest: unable to obtain URL from file descriptor"
- "CopyFileDescriptorURLFromXPCRequest: unable to obtain path from file descriptor"
- "CreateFileExtensionsSetFromBundlePlist: Denied media extension control over file name extension %@"
- "CreateFileExtensionsSetFromBundlePlist: Unable to obtain set of file extensions to deny"
- "CreateFileExtensionsSetFromBundlePlist: format reader bundle contains invalid extensions"
- "CreateFileExtensionsSetFromBundlePlist: unable to create lower case extension string"
- "CreateRelativeDirectoryEnumeration: CFURLEnumeratorGetNextURL failed with error code %lld"
- "CreateRelativeDirectoryEnumeration: unable to create directory enumerator"
- "CreateRelativeDirectoryEnumeration: unexpected result from CFURLEnumeratorGetNextURL"
- "MEValidationService: DISABLED -- Exiting."
- "MEValidationService: Host application is denied read-access to related files"
- "MEValidationService: XPC error %s"
- "MEValidationService: XPC termination imminent"
- "MEValidationService: XPCConnectionHandler started"
- "MEValidationService: got request for relative file names"
- "MEValidationService: got request to open file descriptor"
- "MEValidationService: peer connection has gone invalid; exiting"
- "MEValidationService: reply message sent"
- "MEValidationService: request does not originate from an extension format reader"
- "MEValidationService: sandbox_init_with_parameters err:%d errorbuf:%s -- Exiting."
- "MEValidationService: starting up .... "
- "RequestRelativeFilenames: allowed file list is NULL"
- "RequestRelativeFilenames: file %@ has a file extension from deny-list"
- "RequestRelativeFilenames: unable to create parent directory URL"
- "RequestRelativeFilenames: unable to create set of valid file extensions"
- "RequestRelativeFilenames: unable to obtain URL from file descriptor"
- "RequestRelativeFilenames: unable to obtain plist dictionary for bundle"
- "RequestToOpenFileDescriptor: invalid relative file name string"
- "RequestToOpenFileDescriptor: requested file extension is not in allowed list"
- "RequestToOpenFileDescriptor: unable to create auxiliary file URL"
- "RequestToOpenFileDescriptor: unable to create auxiliary file path CFString"
- "RequestToOpenFileDescriptor: unable to create parent directory URL"
- "RequestToOpenFileDescriptor: unable to create set of valid file extensions"
- "RequestToOpenFileDescriptor: unable to make CFString for name of file to open"
- "RequestToOpenFileDescriptor: unable to obtain URL from file descriptor"
- "RequestToOpenFileDescriptor: unable to obtain name of file to open"
- "RequestToOpenFileDescriptor: unable to obtain plist dictionary for bundle"
- "RequestToOpenFileDescriptor: unable to open auxiliary file path, errno = %d"
- "RequestToOpenFileDescriptor: unable to store auxiliary file path"
```
