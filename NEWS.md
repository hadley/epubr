# epubr 0.4.0

* Enhanced function documentation details.
* Added `epub_meta` for strictly parsing EPUB metadata without reading the full file contents.
* When working with a vector of EPUB files, functions now cleanup each unzipped archive temp directory with `unlink` immediately after use, rather than after all files are read into memory or by overwriting files in a single temp directory.
* Added initial introduction vignette content.
* Minor function refactors.
* Minor bug fixes.
* Added unit tests.

# epubr 0.3.0

* Refactor functions.
* Further reduce package dependencies.
* Update unit tests and documentation.

# epubr 0.2.0

* Refactor functions.
* Move contextual and e-book collection-specific functionality to other packages.
* Make any other remaining edge-case related options hidden arguments so that general usage of `epubr` functions is not too inflexible.
* Reduce package dependencies.
* Add basic unit tests.
* Add example public domain EPUB book for examples and testing.
* Update readme and documentation.

# epubr 0.1.0

* Added initial package scaffolding and function.
