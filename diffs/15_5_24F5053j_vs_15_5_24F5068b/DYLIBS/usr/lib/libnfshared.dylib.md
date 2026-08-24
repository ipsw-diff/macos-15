## libnfshared.dylib

> `/usr/lib/libnfshared.dylib`

```diff

-355.3.0.0.0
-  __TEXT.__text: 0x24b78
+355.4.0.0.0
+  __TEXT.__text: 0x25010
   __TEXT.__auth_stubs: 0xae0
-  __TEXT.__objc_methlist: 0x1d1c
+  __TEXT.__objc_methlist: 0x1dc4
   __TEXT.__const: 0x1c8
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__cstring: 0x3dca
+  __TEXT.__cstring: 0x3dc5
   __TEXT.__oslogstring: 0x17b5
   __TEXT.__gcc_except_tab: 0x460
-  __TEXT.__unwind_info: 0x6b8
-  __TEXT.__objc_classname: 0x32c
-  __TEXT.__objc_methname: 0x3e27
-  __TEXT.__objc_methtype: 0x930
-  __TEXT.__objc_stubs: 0x2420
+  __TEXT.__unwind_info: 0x6e0
+  __TEXT.__objc_classname: 0x34e
+  __TEXT.__objc_methname: 0x3f46
+  __TEXT.__objc_methtype: 0x94d
+  __TEXT.__objc_stubs: 0x2480
   __DATA_CONST.__got: 0x1d8
   __DATA_CONST.__const: 0x3f8
-  __DATA_CONST.__objc_classlist: 0x108
+  __DATA_CONST.__objc_classlist: 0x110
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1160
+  __DATA_CONST.__objc_selrefs: 0x1190
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0xb8
+  __DATA_CONST.__objc_superrefs: 0xc0
   __DATA_CONST.__objc_arraydata: 0x3e8
   __AUTH_CONST.__auth_got: 0x580
   __AUTH_CONST.__const: 0x5c0
   __AUTH_CONST.__cfstring: 0x37a0
-  __AUTH_CONST.__objc_const: 0x35a8
+  __AUTH_CONST.__objc_const: 0x3710
   __AUTH_CONST.__objc_intobj: 0x1f8
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH.__objc_data: 0xa50
-  __DATA.__objc_ivar: 0x208
+  __AUTH.__objc_data: 0xaa0
+  __DATA.__objc_ivar: 0x218
   __DATA.__data: 0x408
   __DATA.__bss: 0x150
   __DATA.__common: 0x60

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 649
-  Symbols:   1654
-  CStrings:  1601
+  Functions: 662
+  Symbols:   1682
+  CStrings:  1615
 
Symbols:
+ -[NFXPCConnectionUserInfoDictionary .cxx_destruct]
+ -[NFXPCConnectionUserInfoDictionary clientName]
+ -[NFXPCConnectionUserInfoDictionary initWithServiceWhitelist:clientName:]
+ -[NFXPCConnectionUserInfoDictionary modifyObjectForKey:handler:]
+ -[NFXPCConnectionUserInfoDictionary objectForKey:]
+ -[NFXPCConnectionUserInfoDictionary objectForKeyedSubscript:]
+ -[NFXPCConnectionUserInfoDictionary objectsForKeys:notFoundMarker:]
+ -[NFXPCConnectionUserInfoDictionary removeObjectForKey:]
+ -[NFXPCConnectionUserInfoDictionary serviceWhitelist]
+ -[NFXPCConnectionUserInfoDictionary setObject:forKey:]
+ -[NFXPCConnectionUserInfoDictionary setObject:forKeyedSubscript:]
+ -[NSXPCConnection(NFUserInfo) NF_clientName]
+ -[NSXPCConnection(NFUserInfo) NF_serviceType]
+ OBJC_IVAR_$_NFXPCConnectionUserInfoDictionary._clientName
+ OBJC_IVAR_$_NFXPCConnectionUserInfoDictionary._data
+ OBJC_IVAR_$_NFXPCConnectionUserInfoDictionary._dataLock
+ OBJC_IVAR_$_NFXPCConnectionUserInfoDictionary._serviceWhitelist
+ _OBJC_CLASS_$_NFXPCConnectionUserInfoDictionary
+ _OBJC_METACLASS_$_NFXPCConnectionUserInfoDictionary
+ __OBJC_$_INSTANCE_METHODS_NFXPCConnectionUserInfoDictionary
+ __OBJC_$_INSTANCE_VARIABLES_NFXPCConnectionUserInfoDictionary
+ __OBJC_$_PROP_LIST_NFXPCConnectionUserInfoDictionary
+ __OBJC_$_PROP_LIST_NSXPCConnection_$_NFUserInfo
+ __OBJC_CLASS_RO_$_NFXPCConnectionUserInfoDictionary
+ __OBJC_METACLASS_RO_$_NFXPCConnectionUserInfoDictionary
+ _objc_msgSend$clientName
+ _objc_msgSend$objectsForKeys:notFoundMarker:
+ _objc_msgSend$serviceWhitelist
CStrings:
+ "@\"NFServiceWhitelistChecker\""
+ "NFXPCConnectionUserInfoDictionary"
+ "NF_clientName"
+ "NF_serviceType"
+ "T@\"NFServiceWhitelistChecker\",R,N,V_serviceWhitelist"
+ "T@\"NSNumber\",R,N"
+ "T@\"NSString\",R,N"
+ "T@\"NSString\",R,N,V_clientName"
+ "_dataLock"
+ "_serviceWhitelist"
+ "initWithServiceWhitelist:clientName:"
+ "modifyObjectForKey:handler:"
+ "objectsForKeys:notFoundMarker:"
+ "serviceType"
+ "serviceWhitelist"
- "ServiceWhitelist"
```
