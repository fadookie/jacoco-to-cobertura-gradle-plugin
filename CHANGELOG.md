<h2 class="github">Changelog</h2>

This list is not intended to be all-encompassing - it will document major and breaking changes with their rationale when appropriate:

### v1.1.0
- Add split by package property to split in multiple xml files (to avoid Gitlab 10MB limit per file). H/T @DrewCarlson
- Fix: replace getByName with findByName for avoiding exception in KMM project. H/T @DrewCarlson

### v1.0.2
- Fix: support sources from kotlin multiplatform projects

### v1.0.1
- Fix: multiple sourceinfo entries support in the jacoco report
 
### v1.0.0
- Initial major release
- configuration change  [Breaking]: `intputFile` and `outputFile` now take a File as param instead of string path

### v0.9.1
- Initial preview release
