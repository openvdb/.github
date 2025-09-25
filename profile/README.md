# The OpenVDB GitHub Organization

Welcome to OpenVDB's GitHub organization, which hosts a collection of repositories that are related to the Academy Software Foundation's [OpenVDB project](https://www.openvdb.org/). These projects are currently not part of the core OpenVDB repository, but they are still part of the the same project (governed by a [Technical Steering Committee](https://www.openvdb.org/about)) and same [license/CLA/DCO](https://www.openvdb.org/license/).

## Repositories

### [fvdb-core](https://github.com/openvdb/fvdb-core)

The `fvdb-core` repository houses the core library and PyTorch extension for ƒVDB.  ƒVDB is a framework that provides differentiable, sparse volumetric operators built on top of NanoVDB and enables PyTorch users to utilize the NanoVDB data structure to build powerful and scalable spatial intelligence applications.


### [fvdb-examples](https://github.com/openvdb/fvdb-examples)

The `fvdb-examples` repository contains examples of how to use the ƒVDB library to build spatial intelligence networks or pipelines.  These are provided as reference for how to implement interesting or well-known methods and networks on top of ƒVDB including examples of pipelines that perform panoptic segmentation and depth reconstruction.


### [fvdb-reality-capture](https://github.com/openvdb/fvdb-reality-capture)

The `fvdb-reality-capture` repository contains examples of how to use the ƒVDB library to build reality capture pipelines centered on ƒVDB's 3D Gaussian splatting methods.  This repository houses utilities and examples that illustrate how to train and render 3D Gaussian splatting models using ƒVDB as well as interesting methods that build upon the 3D Gaussian scene representation such as meshing.


### [nanovdb-editor](https://github.com/openvdb/nanovdb-editor)

The `nanovdb-editor` repository contains a library, python bindings and a standalone GUI application that allows you to view and edit NanoVDB.


### [openvdb-maya](https://github.com/openvdb/openvdb-maya)

The `openvdb-maya` repository houses the OpenVDB Maya plugin which used to be in the [OpenVDB repository](https://github.com/AcademySoftwareFoundation/openvdb) but has been deprecated and is no longer maintained.  It is now provided in this repository as reference.
