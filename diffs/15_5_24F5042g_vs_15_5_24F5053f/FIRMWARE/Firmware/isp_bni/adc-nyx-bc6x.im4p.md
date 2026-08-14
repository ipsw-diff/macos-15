## adc-nyx-bc6x.im4p

> `Firmware/isp_bni/adc-nyx-bc6x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.text_env`
- `__TEXT._rtk_mtab`
- `__TEXT.__data_copy`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x802fec
+  __TEXT.__text: 0x8035f8
   __TEXT.__const: 0x1fd554
   __TEXT.text_env: 0x28718
   __TEXT._rtk_mtab: 0x2b8
-  __TEXT.__cstring: 0xdd288
+  __TEXT.__cstring: 0xdd2f8
   __TEXT.__data_copy: 0x180000
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0

   __DATA.__zerofill: 0xf42020
   Functions: 0
   Symbols:   0
-  CStrings:  24513
+  CStrings:  24520
 
CStrings:
+ "20:32:59"
+ "CBufferPoolDynamicManager"
+ "LCDRV %s L%d Ch%d pAF is NULL during Suspend\n"
+ "LENSC: Ch%zu Blocking State Change Request Completed\n"
+ "LensControllerBlockingStartStop"
+ "acquire_sema"
+ "acquired"
+ "ch %d fc %d AEStatsUpdated == 0"
+ "h->m_stateBlockUntil[pCmd->ch] == LC_CHANNEL_TOT"
+ "h->m_stateChangeCompleteSemaExt[pCmd->ch] == NULLSEMA"
+ "pAF != nullptr"
+ "pCmd->signal != NULLSEMA"
+ "queueDepth %zu > 1"
+ "queueDepth > 1"
+ "release_sema"
- "20:42:52"
- "AuxThreadPostAllMsg"
- "GetAuxThreadPacket"
- "LCDRV Ch%d Stop Z Position is not supported!\n"
- "LCDRV [DEBUG] Ch%d Aux Thread Signal Received - %zu pending items\n"
- "[DEBUG] %s L%d Ch%d pAF becomes NULL - PKT = %d\n"
- "[DEBUG] %s L%d Ch%d pAF is NULL during Suspend\n"
- "[DEBUG] %s L%d Ch%zu POST to Aux Thread\n"
```
