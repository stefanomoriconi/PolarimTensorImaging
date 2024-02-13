# PolarimetricTensorImaging
Generate Polarimetric Tensor Imaging (PTI) together with an Embedded DEMO for Visualisation and Interaction in 3D Slicer.

![PTI_DEMO_example_red](https://github.com/stefanomoriconi/PolarimetricTensorImaging/assets/35454056/bea0c5e2-556b-42b7-a033-895ef5d26458)



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
