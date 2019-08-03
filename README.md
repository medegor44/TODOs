# FaultTolerance
- [ ] Change `IRunner` interface into abstract class `Runner` with abstract `Run` method
- [ ] Move implementation of `ExceptionHandler.DoAction` into `Runner` class (SRP)

# SyncTool
- [x] Full implementation of `ConflictSeeker.GetConflicts`
- [ ] Extract resolving policy into `RsolverPolicy`
- [x] Abstract from file system
- [ ] Tests
- [x] Integration with file system
- [ ] Make DirectoryWrapper(string, DirectoryWrapper) private
