# FaultTolerance
- [ ] Change `IRunner` interface into abstract class `Runner` with abstract `Run` method
- [ ] Move implementation of `ExceptionHandler.DoAction` into `Runner` class (SRP)
- [x] Method chaining

# SyncTool
- [x] Full implementation of `ConflictSeeker.GetConflicts`
- [x] Extract resolving policy into `RsolverPolicy` (bad idea) (actually not)
- [x] Abstract from file system
- [x] Tests
- [x] Integration with file system
- [ ] Make DirectoryWrapper(string, DirectoryWrapper) private

- [ ] Rename ResolvingPolicy -> ResolutionsFactory
- [ ] Add logging decorator for resolutions
- [ ] Add LoggingResolutionsFactory
