# Iris-verification

This project is an Iris verification system. It has different modules which are-

1) Eye Localization
2) Iris segmentation
3) Polar to cartesian transformation
4) Feature vector calculation
5) Verification

# Localization

Here the Iris notebook must be run, and it creates the output in a folder called "located eyesP".

![localization](https://user-images.githubusercontent.com/41861674/111117342-67020280-858d-11eb-9461-99da45b7fec0.png)

Example of the eye localization performed on the images

# Rest of project

Here, the "Ordering Dataset" notebook needs to be run first to create the necessary dataset in the format we require. After which, "rest of the project" notebook needs to be run. Which performs the rest of the modules. 

Note: It is necessary that OCTAVE be installed and added to the environment path variables on the system in order to be able to use it within python.


![cropped eye](https://user-images.githubusercontent.com/41861674/111118348-ab41d280-858e-11eb-9537-3d0bd76fdb55.png)

Cropped eye

![cross entropy threshholding performed in OCTAVE](https://user-images.githubusercontent.com/41861674/111118359-ae3cc300-858e-11eb-8e18-2e4f5a1dabb2.png)

Crossentropy thresholding performed in OCTAVE

![final blur image](https://user-images.githubusercontent.com/41861674/111118365-b137b380-858e-11eb-86ec-fe3ee309a462.png)

Final blur image

![hough transform on blured image](https://user-images.githubusercontent.com/41861674/111118370-b432a400-858e-11eb-99bc-068269743ca5.png)

Hough transform applied on blur image

![iris segmentation](https://user-images.githubusercontent.com/41861674/111118377-b694fe00-858e-11eb-889f-8e7c49047140.png)

Iris segmentation representation

![polar to cartesian and histogram normalized](https://user-images.githubusercontent.com/41861674/111118386-bac11b80-858e-11eb-91c8-983d2989921d.png)

Polar to cartesian conversion and histogram normalization
