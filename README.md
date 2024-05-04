# Classification of macular degenerative pathologies from OCT images with speckle noise 
Final Project for BME 548L: Machine Learning and Imaging (Spring 2024, Duke University)

Brent Savage


[Comlpeted as a requirement towards Master of Engineering (MEng) in Photonics and Optical Sciences]

## Document Descriptions:

### OCT Data:

1. ***OCT Database Links.txt:*** text file with links (Google Drive) to all relevant OCT image databases, original and modified, used in this project

### Project Documents:

1. ***BrentSavage_BME548L_FinalPresentation.pptx:*** slide deck for in-class presentation (May 2, 2024)

3. ***BrentSavage_BME548L_FinalPresentation.pdf:*** pdf version of slide deck

### Resources:

1. Age-related macular degeneration.pd: review article on age-related macular degeneration

2. ECE 542 HW#2: homework completed by Brent Savage for ECE 542: Holography and Coherent Imaging (Fall 2023, Duke University) outlining speckle noise simulation

3. OCT reveiw.pdf: reivew article on Optical Coherence Tomography

4. Speckle Control for elec-holo.pdf: Optical Engineering article that includes speckle contrast formulation
 
### Source Code:
1. ***SpeckleNoiseSimulation.ipynb:*** demonstrating the addition of speckle noise to OCT images

2. ***SpeckleContrastSimulation.ipynb:*** demonstrating the evaluation of speckle contrast in OCT images

3. ***DataSetResize.ipynb:*** resizing the OCT dataset to be 256 x 256 pixel images

4. ***AddingSpeckleNoise.ipynb:*** adding speckle noise to the resized OCT images

5. ***DenoisingAutoencoder.ipnyb:*** speckle noise images denoised using an autoencoder to recover original images

6. ***VGG1Classification.ipnyb:*** recovered images classified by VGG-11 network
    
## Original Data:

The original dataset used for this project can be found here: https://data.mendeley.com/datasets/rscbjbr9sj/2
