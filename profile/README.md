# The OpenVDB GitHub Organization

The OpenVDB GitHub organization is a collection of repositories that are related to the Academy Software Foundation's [OpenVDB project](https://www.openvdb.org/).

The OpenVDB GitHub organization is administered by the Academy Software Foundation and the OpenVDB Project's Technical Steering Committee.  Individual repositories can be administered by other groups of contributors to the OpenVDB Project with permission from the OpenVDB Project's Technical Steering Committee but all contribution guidelines and codes of conduct is the same as [OpenVDB](https://github.com/AcademySoftwareFoundation/openvdb).

## Repositories

### [openvdb-maya](https://github.com/openvdb/openvdb-maya)

The `openvdb-maya` repository houses the OpenVDB Maya plugin which used to be in the [OpenVDB repository](https://github.com/AcademySoftwareFoundation/openvdb) but has been deprecated and is no longer maintained.  It is now provided in this repository as reference.

### [fvdb](https://github.com/openvdb/fvdb)

The `fvdb` repository houses the core library and PyTorch extension for ƒVDB.  ƒVDB is a framework that provides differentiable, sparse volumetric operators built on top of NanoVDB and enables PyTorch users to utilize the NanoVDB data structure to build powerful and scalable spatial intelligence applications.

### [fvdb-applications](https://github.com/openvdb/fvdb-applications)

The `fvdb-applications` repository contains examples of how to use the ƒVDB library to build spatial intelligence networks or pipelines.  These are provided as reference for how to implement interesting or well-known methods and networks on top of ƒVDB including examples of pipelines that perform panoptic segmentation and depth reconstruction.


### [fvdb-realitycapture](https://github.com/openvdb/fvdb-realitycapture)

The `fvdb-realitycapture` repository contains examples of how to use the ƒVDB library to build reality capture pipelines centered on ƒVDB's 3D Gaussian splatting methods.  This repository houses utilities and examples that illustrate how to train and render 3D Gaussian splatting models using ƒVDB as well as interesting methods that build upon the 3D Gaussian scene representation such as meshing.


### [nanovdb-editor](https://github.com/openvdb/nanovdb-editor)

The `nanovdb-editor` repository contains a library, python bindings and a standalone GUI application that allows you to view and edit NanoVDB.
