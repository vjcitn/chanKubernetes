# Bioconductor / AnVIL 

## Project Activities

This site summarizes ongoing [_Bioconductor_][] development activities
related to [_AnVIL_][]. **Note**: All resources on this page are under
development.

Learn more [about][] _Bioconductor_ and _AnVIL_.

[_Bioconductor_]: https://bioconductor.org
[_AnVIL_]: https://www.genome.gov/27569268/genomic-analysis-visualization-and-informatics-labspace-anvil/
[about]: /about

## Current activities

[AnVIL package][]

- This _R_ package currently provides both developer-oriented and
  user-oriented AnVIL-specific functionality.
  
- (available) Developer-oriented access to major AnVIL components (Terra,
  Leonardo, Dockstore, and Gen3) REST APIs.
  
- (under development) Developer- and user-oriented facilities for
  interacting with the Google cloud, e.g., `localize()`,
  `delocalize()`, `sync()`.
  
- (under development) User-oriented facilities for package
  installation from precompiled binaries.

[AnVIL package]: https://github.com/Bioconductor/AnVIL

[_Bioconductor_ containers][]

- (available) These Docker containers provide the system dependencies (e.g.,
  software libraries) to install 'all of' _Bioconductor_. The
  containers can be used locally or deployed in the _AnVIL_ /
  _Leonardo_ application. 
