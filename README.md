# FaultTolerance
- [ ] Change `IRunner` interface into abstract class `Runner` with abstract `Run` method
- [ ] Move implementation of `ExceptionHandler.DoAction` into `Runner` class (SRP)
- [x] Method chaining

# SyncTool
- [x] Full implementation of `ConflictSeeker.GetConflicts`
- [ ] Extract resolving policy into `RsolverPolicy` (bad idea)
- [x] Abstract from file system
- [x] Tests
- [x] Integration with file system
- [ ] Make DirectoryWrapper(string, DirectoryWrapper) private
