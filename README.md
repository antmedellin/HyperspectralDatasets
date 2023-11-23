# HyperspectralDatasets
List of Open Source Hyperspectral Datasets

This list includes publicly available hyperspectral datasets. If you know of any other datasets that should be included in this list, please let me know by opening an issue or submitting a pull request.

This list contains hyperspectral datasets that have annotations for the data. 

## Medical 

- [Heidelberg Porcine HyperSPECTRAL Imaging Dataset (HeiPorSPECTRAL)](https://www.heiporspectral.org/)
    - Resolution: 480x640x100 (x,y,channels)
        - TIVITA HSI Camera
    - Spectral Range: 500-1000 nm
    - 5,758 images
    - Classes: 20 
    - Published: 24 June 2023
- [HyperBlood](https://zenodo.org/records/3984905)
    - Resolution: 696x520x128 
        - SOC-710 Surface Optic
    - Spectral Range: 377-1046 nm
    - 14 images
    - Classes: 8
    - Published: 14 August 2020
- [Placenta](https://zenodo.org/records/8045940)
    - 101 images
    - Resolution: 1024x1024
        - Senop HSC-2, Senop Oy camera
        - Number of bands: 38-78
    - Spectral Range: 515-900 nm
    - Classes: 5
    - Published: 26 July 2023


## Satellite/Aerial

- [Hyperspectral Remote Sensing Scenes](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)
    - Indian Pines
        - Resolution: 145x145x224
        - Spectral Range: 400-2500 nm (AVIRIS sensor)
        - Classes: 16
    - Salinas
        - Resolution: 512x217x224
        - Spectral Range: 0.4-2.5 e-6 m
        - Classes: 16
    - Pavia Centre and University
        - Resolution: 1096x1096x103 (ROSIS sensor)
        - Classes: 9
    - Cuprite (No ground truth)
        - AVIRIS sensor
    - Kennedy Space Center
        - AVIRIS sensor
        - Classes: 13
    - Botswana
        - 242 spectral bands (Hyperion sensor)
        - Classes: 14
- [WHU-Hi](http://rsidea.whu.edu.cn/resource_WHUHi_sharing.htm)
    - WHU-Hi-LongKou, WHU-Hi-HanChuan 
        - Resolution: 550x400x270
        - Spectral Range: 400-1000 nm
        - Classes: 9, 8
    - WHU-Hi-HongHu 
        - Resolution: 940x475x270
        - Spectral Range: 400-1000 nm
        - Classes: 11
    - PublishedL 2020
- [Houston](https://hyperspectral.ee.uh.edu/?page_id=459)
    - Resolution: 144 bands
    - Spectral Range: 380-1050 nm
    - Classes: 16
    - Published: 2013

## Urban and Off-Road

- [LIB-HSI](https://data.csiro.au/collection/csiro%3A55630v4)
    - Specim IQ Hyperspectral Camera
    - 393 training images, 45 validation images, 75 test images
    - Published 13 Feb 2023
- [Virginia Tech Trees](https://figshare.com/articles/dataset/Labeled_Hyperspectral_and_RGB_Images_of_Several_Tree_Species/14113193)
    - Published: 29 Oct 2021
- [HyKo](https://wp.uni-koblenz.de/hyko/)
    - Sensors 
        - 2 Cameras Ximea with IMEC chip 
        - MQ022HG-IM-SM4X4-VIS (VIS)
                - 510x254x16
        - MQ022HG-IM-SM5X5-NIR (NIR) 
                - 407x214x25
        - Spectrometer
            - 225-1000 nm
            - 2500 spectral bands
            - Qmini Wide spectrometer by RGB Photonics
        - LIDAR: Velodyne HDL-32E
        - RGB Camera
    - Spectral Range: 400-1000 nm
        - VIS 470-630 nm
        - NIR 600-975 nm
    - Published 2017
- [HSI-Drive](https://ipaccess.ehu.eus/HSI-Drive/)
    - Resolution: 2048x1088x25
        - IMEC sensor, CMV2K SSM5x5 NIR
    - Spectral Range: 600-975 nm
    - 276 annotated images, 752 total images
    - Classes: 10 
    - Published 2021
- [HSI-Road](https://github.com/NUST-Machine-Intelligence-Laboratory/hsi_road)
    - Resolution: 25 bands + 3 rgb
    - Spectral Range: 600-960 nm 
    - 3799 scenes
    - Published: 2020
- [Hyperspectral City V1.0](https://arxiv.org/pdf/1907.10270v4.pdf)
    - 2019 Hyperspectral City Challenge
    - Not sure where to find the data
    - Resolution: 1400x1800x125
        - LightGene Hyperspectral Sensor
    - Spectral Range: 450-950 nm
    - 300 labeled images, 367 training 55 testing images
    - Classes: 10
    - Published: 2020
- [Hyperspectral City V2.0](https://zenodo.org/records/7013301)
    - Resolution: 1889x1422x128
    - Spectral Range 450-950 nm
    - 1330 images
    - Published: 19 July 2021

- [Hyper-Drive](https://river-lab.github.io/hyper_drive_data/)
    - Resolution:
        - Fused: 1012x1666x33  
        - 3 cameras: 660-1700nm
            - VNIR: 215x407x24
                - IMEC Camera 
            - SWIR: 168x211x9
                - IMEC Camera
            - RGB: 2054, 2464,3
                - Allied Vision Camera
        - Point Spectra: 1x384
            - VIS-NIR: 500-1100 nm with 256 spectral bands
            - NIR: 950-1700 nm with 128 spectral bands 
    - Spectral Range: 
        - VNIR: 660-9000nm
        - SWIR: 1100-1700nm
    - 504 labeled images, 12,874 total images
    - Classes: 11
    - Published: 26 Sept 2023
- [Hyperspectral Terrain Classification](https://pdfs.semanticscholar.org/58df/41289fd4975fb2cf46e5dc3ff8716c22dcbe.pdf)
    - Not sure where to find the data
    - 2 Cameras Ximea with IMEC chip 
        - MQ022HG-IM-SM4X4-VIS (VIS)
                - 510x254x16
        - MQ022HG-IM-SM5X5-NIR (NIR) 
                - 407x214x25
    - Spectral Range: 
        - VIS 470-620 nm
        - NIR 600-1000 nm
    - Published: 2017
- [Target Classification](https://arxiv.org/ftp/arxiv/papers/1611/1611.03130.pdf)
    - Not sure where to find the data
    - 30 images
    - Hyperspectral camera + RGB
        - 25 + 3 bands
        - MQ022HG-IM-SM5X5-NIR (NIR) 
            - 2048x1088x25
        - Flea3 FL3-U3-32S2C-CS
            - 2080x1552x3
    - Spectral Range: 600-975 nm
    - Classes: 8
    - Published: 2016
- [HS-SOD](https://github.com/gistairc/HS-SOD)
    - Salient Object Detection
    - 60 images
    - Resolution: 768x1024x81
    - Spectral Range: 380-720 nm



## Food 
- [Honey Database](https://auckland.figshare.com/articles/dataset/Hyperspectral_Imaging_Honey_Database/12170475)
    - Resolution: 520x696x128
    - Spectral Range: 400-1000 nm 
        - SOC-710 Surface Optic
    - 8700 total instances
    - Classes: 21
    - Published: 22 April 2020
- [Indoor Objects](https://users.ics.forth.gr/~greg/Docs/2017-EI1-Kfot.pdf)
    - Not sure where to find the data
    - Resolution: 256x512x16
        - Ximea camera with IMEC snapshot mosaic sensor
    - Spectral Range: 470-630 nm
    - Classed: 10
    - Published: 2017


## Unannotated Datasets
- [Hyperspec](http://vision.seas.harvard.edu/hyperspec/index.html)
    - 50 images of indoor and outdoor scenes
    - Published: 2011
- [Airport-Beach-Urban](http://xudongkang.weebly.com/data-sets.html)
    - 13 images
    - Published: 2017
- [HyperCube (Urban Hyperspectral Image)](https://erdc-library.erdc.dren.mil/jspui/handle/11681/2925)
    - Resolution: 307x307x210 (HYDICE sensor)
    - Spectral Range: 400-2500 nm
- [Cubert](https://cloud.cubert-gmbh.de/index.php/s/3oECVGWpC1NpNqC)
    - Various Cameras and Scenes
- [Foster et al.](https://figshare.com/articles/dataset/Fifty_hyperspectral_reflectance_images_of_outdoor_scenes/14877285)
    - Resolution: 1344x1024
    - Spectral Range: 400-720 nm
    - 50 images outdoor scenes
    - Published: 6 June 2022
- [Slovenian Beehive](https://zenodo.org/records/4399186)
    - 4 Cameras from SPECIM
        - FX10
        - FX17
        - SWIR
        - MWIR
- [Face Recognition](https://www.researchgate.net/publication/220509000_Studies_on_Hyperspectral_Face_Recognition_in_Visible_Spectrum_With_Feature_Band_Selection)
    - not sure where to find the data
    - Resolution: 33 bands
    - Spectral Range: 400 - 720 nm
    - 300 images
    - Published 2010
- [Standford Scenes](https://www.citedi.mx/percepcionremota/portal/files/documents/HA17082207.pdf)
    - not sure where to find the data
    - Includes faces and outdoor scenes
    - Sensors
        - 2 HySpex cameras
            - HySpex VNIR-1600
                - 160 bands
            - HySpex SWIR-320m-e
                - 256 bands
    - Spectral range: 400-2500 nm
- [Columbia Real-World Materials and Objects](https://cave.cs.columbia.edu/repository/Multispectral)
    - Resolution: 512x512x31
        - Apogee Alta U260
    - Spectral Range: 400-720 nm
    - 32 images
    - Published: 2008
- [FS-FLIM](https://datashare.ed.ac.uk/handle/10283/4380)
    - Lung tissue
    - Resolution: 256x256x512
        - across 32 time points
    - Spectral Range: 500-780 nm
    - 100 4D images (time is fourth dimension)

