############
Indigo 1.4.1
############

*27 Dec 2020*

*******
Summary
*******

**New features and improvements**:

* License changed to Apache 2.0
* Initial version of Bingo ElasticSearch plugin for Java was added. `See details <https://github.com/epam/Indigo/blob/master/api/plugins/bingo-elastic/java/README.md>`__ 
* Initial version of Bingo ElasticSearch plugin for Python was added. `See details <https://github.com/epam/Indigo/blob/master/api/plugins/bingo-elastic/python/README.md>`__
* Indigo.NET switched to .NET Standard 2.0 format and became truly cross-platform, supporting Windows, Linux and macOS on all .NET
  runtimes supporting .NET Standard 2.0. 
* Indigo REST API service sources published
* Support of `ECFP`, `FCFP` fingerprints added
* Python wheels added to PyPi as `epam.indigo`
* Preliminary support of new molecules and reactions JSON format added
* Method `check` for validating molecules and reactions added
* CI for native libraries and wrappers for Python, Java and .NET moved to Github Actions engine
* `iterateSDF` with files over 4GB support added
* 32-bit x86 libraries were removed from binary packages, although you can still build the manually.
* Python 2 support dropped, but you can still build Indigo Python 2 wrapper manually
* API functional tests added
* Java API cleanup
* Support for building in Visual Studio 2019, macOS 10.14 and 10.15 added
* Added support for isotopic information in Gross formula

**Bugfixes**: 

* Python renderer usage (`github issue <https://github.com/epam/Indigo/issues/136>`__)
* Molecule corruption after `atom.remove` (`github issue <https://github.com/epam/Indigo/issues/177>`__)
* `indigo.loadMolecule("ARS")` crashes (`github issue <https://github.com/epam/Indigo/issues/162>`__)
* Python `iterateTautomers` bug (`github issue <https://github.com/epam/Indigo/issues/143>`__)
* Fixes for tautomer fingerprints calculation
* Fixes in SMARTS rendering
* Added saving chirality flag


