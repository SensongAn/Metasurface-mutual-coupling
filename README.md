# Rectangular shaped meta-atoms

The input parameters, simulation environment and results are defined below:  
Please cite our paper (https://arxiv.org/abs/2102.01761) if you are using this dataset.

-   **Material:** The meta-atoms are constructed with silicon (n=1.67) nanoblocks on top of fused silica (n=1.45) substrate.

-   **Thickness:** Thicknesses of the nanoblocks are 270 nm.

-   **Lattice size:** Each nanoblock is placed in a square
    shaped lattice with the side length of 800 nm.                         

-   **Polarization:** Linear-polarized incidence with the polarization direction
    indicated in the figure below.

-   **Wavelength:** Working wavelength is 1.55 um.

-   **Input parameters:** Due to the size limit, each input 2D image is parameterized into a 1x18 vector containing the length and width of each rectangular nanoblock showing in the figure below. Combined input parameters can be found in the "dimension" matrix.

-   **Simulation tool:** All data are derived with the frequency domain solver
    in commercial simulation package CST MICROWAVE STUDIO.

-   **Result:** Real parts and imaginary parts of the transmission spectra of
    each meta-atom are included in the “real_part” and “imaginary_part” matrix, respectively.
    
    ![image](https://github.com/SensongAn/Metasurface-mutual-coupling/blob/main/pics/coupling_rectangle.jpg)
