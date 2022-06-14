# Awesome Remote Sensing Relative Radiometric Normalization (RNN) Datasets
These datasets were used for Change Detection (CD) and Relative Radiometric Normalization (RRN) of multi-temporal satellite images . Datasets details can be found at [A. Moghimi, A. Mohammadzadeh, T. Celik and M. Amani, "A. Moghimi, A. Mohammadzadeh, T. Celik and M. Amani, "A Novel Radiometric Control Set Sample Selection Strategy for Relative Radiometric Normalization of Multitemporal Satellite Images," in IEEE Transactions on Geoscience and Remote Sensing, vol. 59, no. 3, pp. 2503-2519, March 2021, doi: 10.1109/TGRS.2020.2995394.] which is at https://ieeexplore.ieee.org/abstract/document/9133139; cite if you use These datasets. ![Test Image 1](https://github.com/ArminMoghimi/Awesome-Remote-Sensing-Relative-Radiometric-Normalization-Datasets/blob/master/Datasets.jpg)

False color composites (NIR/Red/Green) of seven datasets and corresponding normalized subject images: (a) subject images; (b) reference images; and (c) normalized subject images by the proposed method. 

Dataset 1 is composed of a bitemporal Landsat 7 (ETM+) scene (300*400 pixels) over Lago Mulargia in the Province of Cagliari (Italy) acquired on 5 September 2002 (Subject image) and 19 May 2003 (reference image). It is available on GitHub repository as named (Dataset 1).

Dataset 2 includes two images (700*700 pixels) acquired by Landsat 7 (ETM+) and Landsat 5 (TM) satellites on 5th September 1990 (subject image) and 28 May 2003 (reference image), respectively, over Palm Jumeirah in Dubai city (United Arab Emirates). It is available on GitHub repository as named (Dataset 2).

Dataset 3 is composed of two images (2000*2000 pixels) acquired by Landsat 7 (ETM+) and Landsat 5 (TM) satellites on 20 June 1978 (subject image) and 21 April 2003 (reference image), respectively, over Hamoun Lake in the Southwestern Farah Province / Northwestern of Nimruz Province (Afghanistan).link for download: https://drive.google.com/file/d/1-YNu4R0cZLJo2gGwaCPqxdsXlFcH8LtU/view?usp=sharing

Dataset 4 includes a bitemporal IRS-P6 (LISS-3) scene (1100*1100 pixels) over Varzaqan City in the East Azerbaijan Province (Iran) acquired on 8 July 1998 (subject image) and 8 May 2007 (reference image).It is available on GitHub repository as named (Dataset 4).

dataset 5 is composed of two images (2000*2000 pixels) acquired by WorldView-2 and WorldView-3 satellites on 9 June 2011 (subject image) and 7 July 2015 (reference image), respectively, over the town of Bzin in the northwestern of Shiraz Province (Iran). It will be added after permission. 

Dataset 6 is composed of a bitemporal Sentinel 2B scenes (2000*2000 pixels) over Haditha Dam in the Haditha city (Iraq) acquired on 21 August 2015 (subject image) and 4 October 2016 (reference image).link for download: https://drive.google.com/file/d/1EATKFXss4mgm9RES-5kn51CgzP-SkNnd/view?usp=sharing

Dataset 7 comprises of a pair of the full scene ASTER (4927*5575 pixels) over West of the Isfahan city (Iran) acquired on 27 March 1998 (subject image) and 29 September 2007 (reference image). link for download: https://www.earthdata.nasa.gov/

The thermal bands (including the band 10 to 14 in the ASTER images and band 6 in the Landsat 7/5 images) and the cirrus band (band 10 of Sentinel 2B images) were discarded for RRN. The 30m/pixel bands (six short wave infrared (SWIR) bands) of ASTER images were sharpened to the 30m/pixel of the three visual near-infrared (VNIR) bands by PCA fusion technique PCA-based pan-sharpening technique. The spatial resolution of 20m/pixel and 60m/pixel bands of the sentinel 2 images were enhanced to 10m/pixel by the Sen2Res model which is available in the Sentinel Application Platform (SNAP) open-source software. For dataset 5, first, spectral bands of WorldView2 and WorldView3 images were sharpened to 31cm/pixel and 40cm/pixel panchromatic bands, respectively with the PCA-based pan-sharpening technique. Then, both of them were resampled to 40cm/pixel by nearest-neighbor resampling.

if you use These datasets, Please cite 
A. Moghimi, A. Mohammadzadeh, T. Celik and M. Amani, "A Novel Radiometric Control Set Sample Selection Strategy for Relative Radiometric Normalization of Multitemporal Satellite Images," in IEEE Transactions on Geoscience and Remote Sensing, vol. 59, no. 3, pp. 2503-2519, March 2021, doi: 10.1109/TGRS.2020.2995394.

 
