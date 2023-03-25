# RSA-for-Object-Scene-Perception

- 'Python_extractFeatures' folder is to extract features of a given image from a selected neural network trained on the object (ImageNet) or scene classification (Places365) or semantic segmentation (COCOpascal).
- 'MATLAB_extractRDMs' folder is to extract representational dissimilarity matrices (RDMs) for RSA.
  - Inside '/figures' folder you can find the results. According to the partial correlation, the models do not explain the observed patterns in the feature space. I probably need to collect a better set of images to control the 'object', 'scene', and 'both' conditions.

The project was supervised by Dr. Stefania Bracci.

## Example Image Set

![obj_scene_ copy](https://user-images.githubusercontent.com/44211738/227697445-05e02f62-4e04-4dc8-97bb-09c6b473db77.png)

## Example Feature Extraction (Alexnet trained on Imagenet)

- RDMs for models and features:
![example](https://user-images.githubusercontent.com/44211738/167296896-ce5ec294-7b7d-4586-9837-251480525473.png)

- RSA results: 
![example_Alexnet(Imagenet)](https://user-images.githubusercontent.com/44211738/167297020-40a7301f-9bf6-4d9a-b97c-fc9ca1c30744.png)
