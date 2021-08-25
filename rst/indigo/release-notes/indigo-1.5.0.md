# Indigo 1.5.0


*18 Aug 2021*


## Summary


### New features

* WASM support. See [how to build](https://github.com/epam/Indigo#how-to-build-indigo-wasm).

     *WebAssembly support makes possible to use Indigo in a WASM aware web-browser. 
     At least Firefox, Chrome and Safary support this technology.*

* Now Indigo uses CMake build system. See [how to build](https://github.com/epam/Indigo/blob/master/README.md#build-instruction)
* Implemented the internal json-based Ketcher format [[feature]](https://github.com/epam/Indigo/issues/180).

     *KET is an interchange format between Ketcher and Indigo based applications. 
     Currently it supports standard v2000 features, v3000 is partially supported.
     Also it has some Ketcher's extended features such as simple graphics.*

* Supported reactions for Ketcher format [[feature]](https://github.com/epam/Indigo/issues/396).
* Ketcher format r-groups [[feature]](https://github.com/epam/Indigo/issues/307).
* Added the C++ unittests [[feature]](https://github.com/epam/Indigo/issues/403).
* Added the multiple integration tests [[feature]](https://github.com/epam/Indigo/tree/master/api/tests/integration).
* Added Bingo Elastic Java API [[feature]](https://github.com/epam/Indigo/pull/198).
* Bingo Elastic python: reactions [[feature]](https://github.com/epam/Indigo/issues/259).

### Bug fixes and improvements

* Selection support issues [[fix]](https://github.com/epam/Indigo/pull/353).
* WASM memory issues [[fix]](https://github.com/epam/Indigo/pull/342).
* .NET Indigo nuget error: Unable to load DLL 'indigo' [[fix]](https://github.com/epam/Indigo/issues/450).
* Migrating to standard C++11 containers has started. Changed AutoPtr to [std::unique_ptr](https://github.com/epam/Indigo/issues/418) and [std::shared_ptr](https://github.com/epam/Indigo/issues/419).
* Refactored molecule check function and changed the result format [[improvement]](https://github.com/epam/Indigo/issues/390).
* Bingo-mssql compilation issues [[fix]](https://github.com/epam/Indigo/issues/189).
* Ionize segfault for deuterated molecule (if pKa-model-level >= 1) [[fix]](https://github.com/epam/Indigo/issues/153).
* SDF decomposition test segfault [[fix]](https://github.com/epam/Indigo/issues/431).
* Fingerprints differ between mac os x and other platforms [[fix]](https://github.com/epam/Indigo/issues/207).
* Added Bindgo CI for Postgres 9.6 [[fix]](https://github.com/epam/Indigo/pull/411).
* Reusable array shallow copy issue [[fix]](https://github.com/epam/Indigo/pull/385).
* Implemented the NodeJS wrapper for Indigo [[fix]](https://github.com/epam/Indigo/issues/245).
* List of exported symbols for libindigo.so [[fix]](https://github.com/epam/Indigo/pull/276).
* Miscelaneous C++11 related refactorings: added 'override', replaced plain C functions with corresponding from std:: ) [[improvement]](https://github.com/epam/Indigo/pull/335).
* Optimized the adding of elements to atoms and bonds arrays [[improvement]](https://github.com/epam/Indigo/pull/267).
* Exposed oneBitsList in .NET API [[fix]](https://github.com/epam/Indigo/pull/329).
* Implemented context manager and iterator for Bingo object [[improvement]](https://github.com/epam/Indigo/pull/241).
* CDX test failure [[fix]](https://github.com/epam/Indigo/pull/387).
* Java API - native libs loading [[fix]](https://github.com/epam/Indigo/pull/261).
