# GAN
Our primary aim is to train a GAN model which can
find the relationship between two different domains (Learning to
Discover Cross-Domain Relations with Generative Adversarial
Networks).


## System Requirements

- keras
- git+https://www.github.com/keras-team/keras-contrib.git
- matplotlib
- numpy
- scipy
- pillow
- urllib
- skimage
- scikit-image
- gzip
- pickle
## System architecture

This covers the overall setps involved in GAN architecture
- Step-1
<img width="441" alt="step-2" src="https://user-images.githubusercontent.com/74253717/134242534-fac133db-c9ec-43db-90e8-2b33e83d77fb.PNG">

- Step-2
<img width="472" alt="step-3" src="https://user-images.githubusercontent.com/74253717/134242537-795798c6-c218-4cf7-9c09-c0ea2828a0d4.PNG">

- Step-3
<img width="480" alt="step-4" src="https://user-images.githubusercontent.com/74253717/134242541-bdf72b90-a013-4a3b-a043-6a5e71bc9e3d.PNG">

## Flow chart
Steps involved in GAN is shown via flowchart in
figure.

<img width="410" alt="flowChart" src="https://user-images.githubusercontent.com/74253717/134242479-307c36fb-25f3-4638-a950-1bce2d93af22.PNG">

## Model parameters
- metrics= accuracy
- batch size= 1
- epoch= 15
- Number of filters in the first layer of generator and discriminator=32
- Optimizer= Adam
- loss= Mean square error

## Results
 The results of GAN is shown in two cases in Table.
--          | Generator loss| Discriminator loss
------------- | -------------  |---------------
Case 1  | 2.667938   | 0.158142
Case 2  |2.844698  | 0.070919

The visulization of results is shown in figure

<img width="342" alt="result" src="https://user-images.githubusercontent.com/74253717/134242529-9678d6ad-7e80-42ae-86f9-28b3535ff8aa.PNG">

## Authors

- Maitry Trivedi
- Kevin Vora


