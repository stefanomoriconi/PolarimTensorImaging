# PolarimetricTensorImaging
Script to Generate Polarimetric Tensor Imaging together with an Embedded DEMO for Visualisation and Interaction in 3D Slicer.

![PTI_DEMO_example](https://github.com/stefanomoriconi/PolarimetricTensorImaging/assets/35454056/b20c8a47-f0e8-44d0-b656-4ba24a12eefc)


## Requirements

### Processing

* Matlab (R2021a, tested)
> [!TIP]
> `>> DEMO_3DSlicer_PolarimetricTensorImaging('HELP');`


* [Nifti I/O libraries](https://www.mathworks.com/matlabcentral/fileexchange/8797-tools-for-nifti-and-analyze-image)

> [!NOTE]
> After downloading the package, add the unzipped folder to Matlab search path with `addpath(...);`

### Visualisation

* [3D Slicer](https://www.slicer.org/) (v. 4.10.2, tested)

> [!IMPORTANT]
> Install add-on extensions: DTI Process, Slicer DMRI, UKFTractography

> [!WARNING]
> Check 3D Slicer Coordinate System of reference.
