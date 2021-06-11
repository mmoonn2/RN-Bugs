# RN-Bugs

Modify the func at line 746 in RCTCxxBridge.mm from

(NSArray<RCTModuleData *> *)_initializeModules:(NSArray<id< RCTBridgeModule > > *)modules
withDispatchGroup:(dispatch_group_t)dispatchGroup
lazilyDiscovered:(BOOL)lazilyDiscovered
to
(NSArray<RCTModuleData *> *)_initializeModules:(NSArray *)modules
withDispatchGroup:(dispatch_group_t)dispatchGroup
lazilyDiscovered:(BOOL)lazilyDiscovered


