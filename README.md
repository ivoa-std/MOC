[![PDF-Preview](https://img.shields.io/badge/Preview-PDF-blue)](../../releases/download/auto-pdf-preview/MOC-draft.pdf)

# MOC
This document describes the Multi-Order Coverage map method (MOC) to specify arbitrary coverages for sky regions and/or time coverages and potentially other dimensions. The goal is to be able to provide a very fast comparison mechanism between coverages. The mechanism is based on a discretization of space and time dimensions. The system is based on the definition of a specific storage of the map coverage using predefined cells hierarchically grouped which makes it easy to produce and use for exploring astronomical collections. There are already a few applications and libraries which are taking advantage of this new standard.

## Document Status

### Latest Stable

The current IVOA Recommendation is [REC-2.0](https://www.ivoa.net/documents/MOC/index.html).  Prior versions are available on the [IVOA Documents page](https://www.ivoa.net/documents/index.html).

### Making Changes

Changes to this document are made via pull requests to the `master` branch of this repository.  A [PDF preview](https://github.com/ivoa-std/MOC/releases/download/auto-pdf-preview/MOC-draft.pdf "PRE-RELEASE, DO NOT PUBLISH") of the latest `master` version is available by clicking the badge on top.

When cloning your fork of this repository, use `--recurse-submodules` to include its submodules.

    git clone --recurse-submodules https://github.com/[your github user]/MOC.git

Then: run "make" and hope you have all the necessary tools installed.

More more information, see the [ivoatex README](https://github.com/ivoa-std/ivoatex#readme) and the IVOA note [IVOATeX Document Preparation System](https://ivoa.net/documents/Notes/IVOATex/).

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
<br />The IVOA Architecture document is licensed under the
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
Creative Commons Attribution-ShareAlike 4.0 International License</a>.
