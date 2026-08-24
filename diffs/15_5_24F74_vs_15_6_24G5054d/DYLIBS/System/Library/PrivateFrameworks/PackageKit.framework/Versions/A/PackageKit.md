## PackageKit

> `/System/Library/PrivateFrameworks/PackageKit.framework/Versions/A/PackageKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-1474.120.3.0.0
-  __TEXT.__text: 0x86010
-  __TEXT.__auth_stubs: 0x2000
-  __TEXT.__objc_methlist: 0x77dc
+1474.140.5.0.0
+  __TEXT.__text: 0x868f4
+  __TEXT.__auth_stubs: 0x20f0
+  __TEXT.__objc_methlist: 0x7814
   __TEXT.__const: 0x320
-  __TEXT.__cstring: 0x1161d
+  __TEXT.__cstring: 0x11977
   __TEXT.__constg_swiftt: 0x188
   __TEXT.__swift5_typeref: 0x7c
   __TEXT.__swift5_reflstr: 0x21
   __TEXT.__swift5_fieldmd: 0x5c
   __TEXT.__swift5_types: 0x8
-  __TEXT.__gcc_except_tab: 0x1364
+  __TEXT.__gcc_except_tab: 0x13c4
   __TEXT.__oslogstring: 0x19
   __TEXT.__dof_PackageKi: 0x1ba4
-  __TEXT.__unwind_info: 0x2050
+  __TEXT.__unwind_info: 0x2058
   __TEXT.__eh_frame: 0x40
   __TEXT.__objc_classname: 0x1091
-  __TEXT.__objc_methname: 0x11c0a
-  __TEXT.__objc_methtype: 0x2538
-  __TEXT.__objc_stubs: 0xdea0
-  __DATA_CONST.__got: 0x998
-  __DATA_CONST.__const: 0xc68
+  __TEXT.__objc_methname: 0x11d3c
+  __TEXT.__objc_methtype: 0x2547
+  __TEXT.__objc_stubs: 0xdf20
+  __DATA_CONST.__got: 0x9a0
+  __DATA_CONST.__const: 0xc78
   __DATA_CONST.__objc_classlist: 0x448
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4520
+  __DATA_CONST.__objc_selrefs: 0x4540
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x3a8
   __DATA_CONST.__objc_arraydata: 0x68
-  __AUTH_CONST.__auth_got: 0x1010
+  __AUTH_CONST.__auth_got: 0x1088
   __AUTH_CONST.__const: 0x17a0
-  __AUTH_CONST.__cfstring: 0xb760
-  __AUTH_CONST.__objc_const: 0xbb48
+  __AUTH_CONST.__cfstring: 0xb780
+  __AUTH_CONST.__objc_const: 0xbba8
   __AUTH_CONST.__objc_intobj: 0x450
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH.__objc_data: 0x2af0
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x9f8
+  __DATA.__objc_ivar: 0xa00
   __DATA.__data: 0x810
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0x230

   - /usr/lib/swift/libswift_time.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2796
-  Symbols:   7366
-  CStrings:  5393
+  Functions: 2801
+  Symbols:   7394
+  CStrings:  5412
 
Symbols:
+ -[PKShoveOptions setStompReplacementPaths:]
+ -[PKShoveOptions stompReplacementPaths]
+ -[PKSignedContainer _secureAppGroupContainerWithIdentifier:outSandboxHandle:]
+ -[PKSignedContainer secureAppGroupContainerIdentifier]
+ -[PKSignedContainer setSecureAppGroupContainerIdentifier:]
+ GCC_except_table30
+ GCC_except_table31
+ OBJC_IVAR_$_PKShoveOptions._stompReplacementPaths
+ OBJC_IVAR_$_PKSignedContainer._secureAppGroupContainerIdentifier
+ _CONTAINER_PERSONA_PRIMARY
+ _PKSO_CODERKEY_StompReplacementPaths
+ _container_copy_sandbox_token
+ _container_error_copy_unlocalized_description
+ _container_get_identifier
+ _container_get_path
+ _container_query_create
+ _container_query_free
+ _container_query_get_last_error
+ _container_query_get_single_result
+ _container_query_operation_set_flags
+ _container_query_set_class
+ _container_query_set_group_identifiers
+ _container_query_set_persona_unique_string
+ _objc_msgSend$_secureAppGroupContainerWithIdentifier:outSandboxHandle:
+ _objc_msgSend$secureAppGroupContainerIdentifier
+ _objc_msgSend$setSecureAppGroupContainerIdentifier:
+ _objc_msgSend$setStompReplacementPaths:
+ _objc_msgSend$stompReplacementPaths
+ _sandbox_extension_consume
+ _sandbox_extension_release
+ _xpc_string_create
- GCC_except_table28
- GCC_except_table29
- _objc_msgSend$launch
CStrings:
+ "%@ %d.%@"
+ "<%@: %p>\n    Source: %@\n    Destination: %@\n    Options: 0x%08lX\n    Forced Replace Path Count: %ld\n    Stomp Replacement Paths: %@"
+ "@32@0:8@16^q24"
+ "NO_SECURE_CONTAINER"
+ "PKSignedContainer-UnarchiveOperations"
+ "PackageKit: A secure extraction container (%s) was requested, but its not available."
+ "PackageKit: Althought the (%s) is apple-signed, a secure container was not provided.Therefore, the contents will not be marked as trusted by System Policy."
+ "PackageKit: Assessment of %s failed (%s)"
+ "PackageKit: Cannot cleanup old sandbox directory:(%s). Opening a file-descriptor against it failed. %s"
+ "PackageKit: Cannot cleanup old sandbox directory:(%s): %s"
+ "PackageKit: Could not set okay=%d on %s (%s)"
+ "PackageKit: Current process cannot access secure AppGroup container (%s) using query. %s"
+ "PackageKit: Failed to create sandbox directory. %s"
+ "PackageKit: Failed to open sandbox directory. %s"
+ "PackageKit: Failed to trust XIP payload using System Policy: %s"
+ "PackageKit: Signed container at %s does not have Apple signature. Unable to unarchive."
+ "PackageKit: Signed container at %s has trust level %d."
+ "PackageKit: Signed container at %s is not trusted by SPInstallationPolicy. %s"
+ "PackageKit: Unable to consume sandbox extension token for secure AppGroup container: %s"
+ "PackageKit: Unable to get sandbox extension token for secure AppGroup container: %s"
+ "StompReplacementPaths"
+ "T@\"NSString\",&,V_secureAppGroupContainerIdentifier"
+ "TB,V_stompReplacementPaths"
+ "_secureAppGroupContainerIdentifier"
+ "_secureAppGroupContainerWithIdentifier:outSandboxHandle:"
+ "_stompReplacementPaths"
+ "secureAppGroupContainerIdentifier"
+ "setSecureAppGroupContainerIdentifier:"
+ "setStompReplacementPaths:"
+ "stompReplacementPaths"
- "<%@: %p>\n    Source: %@\n    Destination: %@\n    Options: 0x%08lX    Forced Replace Path Count: %ld"
- "Assessment of %s failed (%s)"
- "Could not set okay=%d on %s (%s)"
- "PKSignedContainer.m"
- "PackageKit: Failed to verify XIP archive with System Policy: %s"
- "Shove not found in PackageKit.framework's resources"
- "Signed container at %s does not have Apple signature. Unable to unarchive."
- "Signed container at %s has trust level %d."
- "Signed container at %s is not trusted by SPInstallationPolicy. %s"
- "TemporaryItems"
- "launch"
```
