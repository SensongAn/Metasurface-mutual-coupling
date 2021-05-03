This dataset contains the local responses of target meta-atoms while accounting for the influences of their neighbors:
![image](https://github.com/SensongAn/Metasurface-mutual-coupling/blob/main/pics/coupling_demo.png)

Please cite our paper (https://arxiv.org/abs/2102.01761) if you are using this dataset.

# Rectangular-shaped meta-atoms

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
    the target meta-atoms are included in the “real_part” and “imaginary_part” matrix, respectively.
    
    ![image](https://github.com/SensongAn/Metasurface-mutual-coupling/blob/main/pics/coupling_rectangle.jpg)
    
    
# Freeform-shaped meta-atoms

-   **Material:** The meta-atoms are constructed with high index (n=5) nanoblocks on top of low index (n=1.4) substrate.

-   **Thickness:** Thicknesses of the nanoblocks are 1 um.

-   **Lattice size:** Each nanoblock is placed in a square
    shaped lattice with the side length of 2.8 um.                         

-   **Polarization:** Linear-polarized incidence with the polarization direction
    indicated in the figure below.

-   **Wavelength:** Working wavelength is 5.45 um (equivalent to 55 THz).

-   **Input parameters:** Each 2D image (64 by 320) contains the cross-section of a group of meta-atoms. Combined images can be found in the matrix "pattern".

-   **Simulation tool:** All data are derived with the frequency domain solver
    in commercial simulation package CST MICROWAVE STUDIO.

-   **Result:** Real parts and imaginary parts of the transmission spectra of
    the target meta-atoms are included in the “real_part” and “imaginary_part” matrix, respectively.
    
    ![image](https://github.com/SensongAn/Metasurface-mutual-coupling/blob/main/pics/coupling_freeform.jpg)
    
    
# Freeform-shaped meta-atoms (extend to 2D mutual coupling problems)

-   **Material:** The meta-atoms are constructed with high index (n=5) nanoblocks on top of low index (n=1.4) substrate.

-   **Thickness:** Thicknesses of the nanoblocks are 1 um.

-   **Lattice size:** Each nanoblock is placed in a square
    shaped lattice with the side length of 2.8 um.                         

-   **Polarization:** Linear-polarized incidence with the polarization direction
    indicated in the figure below.

-   **Wavelength:** Working wavelength is 5.45 um (equivalent to 55 THz).

-   **Input parameters:** Each 2D image (320 by 320) contains the cross-section of a group of meta-atoms. Combined images can be found in the matrix "pattern".

-   **Simulation tool:** All data are derived with the frequency domain solver
    in commercial simulation package CST MICROWAVE STUDIO.

-   **Result:** Real parts and imaginary parts of the transmission spectra of
    the target meta-atoms are included in the “real_part” and “imaginary_part” matrix, respectively.
    
    ![image](https://github.com/SensongAn/Metasurface-mutual-coupling/blob/main/pics/coupling_freeform_2D1.jpg)
