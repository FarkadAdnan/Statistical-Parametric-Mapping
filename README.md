# Statistical-Parametric-Mapping-
The FIL Methods Group
-  By:Farkad Adnan فرقد عدنان -
- https://linktr.ee/farkadadnan

 - E-mail: farkad.hpfa95@gmail.com 
- inst : farkadadnan 
- #farkadadnan , #farkad_adnan , فرقد عدنان# 
- FaceBook: كتاب عالم الاردوينو 
- inst : arduinobook
1. #كتاب_عالم_الاردوينو
2. #كتاب_عالم_الآردوينو 

* facebook : https://www.facebook.com/profile.php?id=100002145048612
* instagram:  https://www.instagram.com/farkadadnan/
* linkedin : https://www.linkedin.com/in/farkad-adnan-499972121/

 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>

# Introduction
Statistical Parametric Mapping refers to the construction and assessment of spatially extended statistical processes used to test hypotheses about functional imaging data. These ideas have been instantiated in a free and open source software that is called SPM.
* The SPM software package has been designed for the analysis of brain imaging data sequences. The sequences can be a series of images from different cohorts, or time-series from the same subject. The current release is designed for the analysis of fMRI, PET, SPECT, EEG and MEG.

![coreg](https://user-images.githubusercontent.com/35774039/189548607-47f600f0-4eac-4e59-83e8-4985b5fddfc3.png)
![forward](https://user-images.githubusercontent.com/35774039/189548608-497b2a72-25bc-4bd9-b891-0bd7ee87e641.png)
![mesh](https://user-images.githubusercontent.com/35774039/189548609-b40c8e1b-f453-4fd5-a8a1-8e57516b1c4d.png)




# Getting Started

 The data sets are provided with instructions on how to use SPM to analyse them. These tutorials therefore give practical instructions on how to implement the various methodologies. Our methods have been written up in books, technical reports and journal papers which are available from our Online Bibliography. This groups documentation according to year, category, author and keyword.

# History
 * The SPM suite and associated theory was originally developed by Karl Friston for the routine statistical analysis of functional neuroimaging data from Positron Emission Tomography (PET), while at the Medical Research Council Cyclotron Unit. Now known as SPMclassic, this software was made available to the emerging functional imaging community in 1991, to promote collaboration and a common analysis scheme across laboratories.

* SPM'94 was the first major revision of the SPM software. SPM'94 was written primarily by Karl Friston during the summer of 1994, with invaluable conceptual and technical help from John Ashburner, Jon Heather, Andrew Holmes and Jean-Baptiste Poline. SPM'95, SPM'96, SPM'99, SPM2, SPM5, SPM8 and SPM12 are based on SPM'94, and represent the ongoing theoretical advances and technical improvements.


![image](https://user-images.githubusercontent.com/35774039/189548266-1501ce9d-cd57-4d4a-95e4-c286198397ec.png)

# SPM5

![image](https://user-images.githubusercontent.com/35774039/189548287-7fbf29f7-5da6-48ff-894e-51c31acec45b.png)

# SPM2

![image](https://user-images.githubusercontent.com/35774039/189548300-7031b0e6-e1ed-48f9-8459-4db6faf3a7db.png)

# SPM99
![image](https://user-images.githubusercontent.com/35774039/189548305-6e795698-8f6b-4ea4-862b-674e819b2c4e.png)

# flowchart
![flow](https://user-images.githubusercontent.com/35774039/189548378-0bb66dd5-391d-40e2-987d-9c9d95f39e88.png)

# bms
![Slide1](https://user-images.githubusercontent.com/35774039/189548391-7fc52561-290d-416e-8f52-c6e5e65494f5.png)

![Slide2](https://user-images.githubusercontent.com/35774039/189548400-ff787799-5b1a-4e4f-b8c6-29e8393b8aa3.png)
![Slide3](https://user-images.githubusercontent.com/35774039/189548401-b304d6ea-c76f-418c-bf14-8c8f378d5d74.png)
![Slide4](https://user-images.githubusercontent.com/35774039/189548402-18281f2e-153f-41e0-b9eb-039e75f269b0.png)
![Slide5](https://user-images.githubusercontent.com/35774039/189548405-7302aa63-b457-44ba-8004-8e82b57ab06c.png)
![Slide6](https://user-images.githubusercontent.com/35774039/189548407-e6389292-513d-403d-b276-5d6d3f07d84a.png)
#   Output Files

This routine produces spatial normalisation parameters (* seg sn.mat les) by default. Thesen can be used for writing spatially normalised versions of your data, via the "Normalise: Write" option. This mechanism may produce superior results than the "Normalise: Estimate" option (but probably not as good as those produced using DARTEL).

# Gaussians per class
The number of Gaussians used to represent the intensity distribution for each tissue class can be greater than one. In other words, a tissue probability map may be shared by several clusters. The assumption of a single Gaussian distribution for each class does not hold for a number of reasons. In particular, a voxel may not be purely of one tissue type, and instead contain signal from a number of di_erent tissues (partial volume e_ects). Some partial volume voxels could fall at the interface between di_erent classes, or they may fall in the middle of structures such as the thalamus, which may be considered as being either grey or white matter. Various other image segmentation approaches use additional clusters to model such partial volume e_ects. These generally assume that a pure tissue class has a Gaussian intensity distribution, whereas intensity distributions for partial volume voxels are broader, falling between the intensities of the pure classes. Unlike these partial volume segmentation approaches, the model adopted here simply assumes that the intensity distribution of each class may not be Gaussian, and assigns belonging probabilities according to these non-Gaussian distributions. Typical numbers of Gaussians could be two for grey matter, two for white matter, two for CSF, and four for everything else



# face_timing

![face_timing](https://user-images.githubusercontent.com/35774039/189548463-0a1d2707-8f27-4441-80a5-43caf48fb714.png)
![famous_lag](https://user-images.githubusercontent.com/35774039/189548470-ff3d99c1-5228-46f1-b82c-eae2358c093e.png)
![face_stim](https://user-images.githubusercontent.com/35774039/189548477-20cb1d02-d3ca-4b44-a393-d3214f0288ba.png)

* fir_covariance
![fir_covariance](https://user-images.githubusercontent.com/35774039/189548497-23c2ae6a-732c-4735-aed2-de7ac75f012d.png)

* fieldmap_results1
![fieldmap_results1](https://user-images.githubusercontent.com/35774039/189548511-d3b98114-cadb-4dff-bfd0-ebcdea9aeb36.png)
 # segmentation
 ![seg1](https://user-images.githubusercontent.com/35774039/189548558-ac080938-aff1-44be-b896-804199b46bee.png)
![seg2](https://user-images.githubusercontent.com/35774039/189548561-92d83465-67d4-4692-8c4a-832130a95a67.png)

* eeg_review_buttons
![eeg_review_buttons](https://user-images.githubusercontent.com/35774039/189548568-480c49db-ab3b-4699-b07d-8241fc65edfb.png)
![slide14](https://user-images.githubusercontent.com/35774039/189548580-c46a52c9-5d3a-466e-8f5b-8fe21295ec9a.png)

# Results

![Fig16](https://user-images.githubusercontent.com/35774039/189548649-98f9c0f5-22c2-4286-b9bf-f562f80d9133.png)
![Fig10](https://user-images.githubusercontent.com/35774039/189548651-76e8bbaa-98f9-4954-8ec3-07c033cdf185.png)


# References
* [1]J. Andersson, J. Ashburner, and K.J. Friston. A global estimator unbiased by local changes. NeuroImage, 13(6):1193{1206, 2001.
* [2] J. Andersson, C. Hutton, J. Ashburner, R. Turner, and K.J. Friston. Modelling geometric deformations in EPI time series. NeuroImage, 13(5):903{919, 2001.
* [3] J. Ashburner. A fast dieomorphic image registration algorithm. NeuroImage, 38(1):95{113, 2007.
* [4] J. Ashburner, J. Andersson, and K.J. Friston. Image registration using a symmetric prior - in three-dimensions. Human Brain Mapping, 9(4):212{225, 2000.
* [5] J. Ashburner and K.J. Friston. The role of registration and spatial normalization in detecting activations in functional imaging. Clinical MRI/Developments in MR, 7(1):26{28, 1997.
* [6] J. Ashburner and K.J. Friston. Nonlinear spatial normalization using basis functions. Human Brain Mapping, 7(4):254{266, 1999.
* [7] J. Ashburner and K.J. Friston. Voxel-based morphometry { the methods. NeuroImage,
11:805{821, 2000.
* [8] J. Ashburner and K.J. Friston. Why voxel-based morphometry should be used. NeuroImage, 14(6):1238{1243, 2001.
* [9] J. Ashburner and K.J. Friston. Unied segmentation. NeuroImage, 26:839{851, 2005.
* [10] J. Ashburner, P. Neelin, D. L. Collins, A. C. Evans, and K.J. Friston. Incorporating prior knowledge into image registration. NeuroImage, 6:344{352, 1997.
* [11] S. Baillet, J.C. Mosher, and R.M. Leahy. Electromagnetic brain mapping. IEEE Sign. Proc. Mag., 18:14{30, 2001.
* [12] P.J. Besl and N.D. McKay. A method for registration of 3-d shapes. IEEE Trans. Pat. Anal. and Mach. Intel., 142:239{256, 1992.
* [13] C. Buchel and K.J. Friston. Modulation of connectivity in visual pathways by attention: Cor- tical interactions evaluated with structural equation modelling and fMRI. Cerebral Cortex, 7:768{778, 1997.



