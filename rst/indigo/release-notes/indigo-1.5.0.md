# Indigo 1.5.0


*18 Aug 2021*


## Summary



**New features and improvements**:

* WASM support. See [[how to build]](https://github.com/epam/Indigo#how-to-build-indigo-wasm).
* Implemented the internal json-based ketcher format [[feature]](https://github.com/epam/Indigo/issues/180).
* Supported reactions for Ketcher format [[feature]](https://github.com/epam/Indigo/issues/396).
* Ketcher format r-groups [[feature]](https://github.com/epam/Indigo/issues/307).
* Selection support issues [[fix]](https://github.com/epam/Indigo/pull/353).
* WASM memory issues [[fix]](https://github.com/epam/Indigo/pull/342).
* Now Indigo uses CMake build system.
* .NET Indigo nuget error: Unable to load DLL 'indigo' [[fix]](https://github.com/epam/Indigo/issues/450).
* Migrating to standard C++11 containers has started. Changed AutoPtr to [std::unique_ptr](https://github.com/epam/Indigo/issues/418) and [std::shared_ptr](https://github.com/epam/Indigo/issues/419).
* Added the C++ unittests [[feature]](https://github.com/epam/Indigo/issues/403).
* Refactored molecule check function and changed the result format [[improvement]](https://github.com/epam/Indigo/issues/390).
* Bingo-mssql compilation issues [[fix]](https://github.com/epam/Indigo/issues/189).
* Added the multiple integration tests [[feature]](https://github.com/epam/Indigo/tree/master/api/tests/integration).
* Ionize segfault for deuterated molecule (if pKa-model-level >= 1) [[fix]](https://github.com/epam/Indigo/issues/153).
* SDF decomposition test segfault [[fix]](https://github.com/epam/Indigo/issues/431).
* Fingerprints difference between mac os x and other platforms [[fix]](https://github.com/epam/Indigo/issues/207).
* Added Bindgo CI for Postgres 9.6 [[fix]](https://github.com/epam/Indigo/pull/411).
* Reusable array shallow copy issue [[fix]](https://github.com/epam/Indigo/pull/385).
* Implemented the NodeJS wrapper for Indigo [[fix]](https://github.com/epam/Indigo/issues/245).
* Bingo Elastic python: reactions [[feature]](https://github.com/epam/Indigo/issues/259).
* List of exported symbols for libindigo.so [[fix]](https://github.com/epam/Indigo/pull/276).
* Miscelaneous C++11 related refactorings  [[improvement]](https://github.com/epam/Indigo/pull/335).
* Optimized the adding of elements to atoms and bonds arrays [[improvement]](https://github.com/epam/Indigo/pull/267).
* Exposed oneBitsList in .NET API [[fix]](https://github.com/epam/Indigo/pull/329).
* Implemented context manager and iterator for Bingo object [[improvement]](https://github.com/epam/Indigo/pull/241).
* CDX test failure [[fix]](https://github.com/epam/Indigo/pull/387).
* Java API - native libs loading [[fix]](https://github.com/epam/Indigo/pull/261).
* Added Bingo Elastic Java API [[feature]](https://github.com/epam/Indigo/pull/198).
