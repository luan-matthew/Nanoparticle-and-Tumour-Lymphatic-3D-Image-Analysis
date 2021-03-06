# 3D Image Analysis on Nanoparticles and Tumour Lymphatics
MATLAB scripts for quantifying nanoparticle intensities with respect to the tumour lymphatics in 3D images.

The MATLAB script np_dist_average.m quantifies 1. the average distance from lymphatic vessels to nanoparticles, and 2. the nanoparticle intensity at the lymphatic vessel wall. 

The MATLAB script np_colocalization_lymph_tumour_masking.m creates a mask of segmented tumour lymphatics and applies it to the nanoparticle image. The MATLAB script np_colocalization_lymph_tumour_intensity.m quantifies the nanoparticle intensity co-localized within the tumour lymphatic vessel as a function of vessel length. 

To run, these files require: 1. Image file of segmented lymphatic vessels, and 2. Image file of nanoparticle intensity. Image files are open with the function loadtiff.m which is found on the MathWorks File Exchange at the link: https://www.mathworks.com/matlabcentral/fileexchange/35684-multipage-tiff-stack

Lymphatic vessels were segmented using Ilasik (https://www.ilastik.org/ or https://github.com/ilastik).

ilastik: interactive machine learning for (bio)image analysis Stuart Berg, Dominik Kutra, Thorben Kroeger, Christoph N. Straehle, Bernhard X. Kausler, Carsten Haubold, Martin Schiegg, Janez Ales, Thorsten Beier, Markus Rudy, Kemal Eren, Jaime I Cervantes, Buote Xu, Fynn Beuttenmueller, Adrian Wolny, Chong Zhang, Ullrich Koethe, Fred A. Hamprecht & Anna Kreshuk in: Nature Methods, (2019)
