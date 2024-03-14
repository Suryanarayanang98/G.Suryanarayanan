## Portfolio

### [Project 1 : Envisage 7.0 - Speed Painting Bot (Centre for Innovation Project)]()
* Brainstormed & Spearheaded the notion of using various motors to control & synchronize bot-painting technology efficiently.
* Designed 2 layered PCBs using EAGLE & assembled the components for a customized stepper motor driver.
* Code for Image processing was written in Python using OpenCV & NumPy libraries with the RMS averaging.
* Patent has been filed for this innovation & we have received an Indian Patent Application No. 201947026780.

### [Project 2 : Fundamentals of DL (Course Project)](https://github.com/Suryanarayanang98/CS-6910-Foundation_of_Deep_Learning)
#### SINGAN 
* Studied & presented the research paper SINGAN:  Learning a Generative Model from a Single Natural Image, ICCV 2019.
* Came up with innovative ideas like dynamic learning rate & scale factor enabling training faster with lesser scales.

#### Convolutional neural networks
* Experimented & trained CNNs with varying parameters to do Image classification CIFAR 10 datasets with 85% accuracy.
* Performed Occlusion experiment & Filter analysis to understand the CNN model’s learning & patches captured by filters.
![](/images/download.png)
![](/images/fliter.png)

### [Project 3 : Countries GDP Prediction](https://github.com/Suryanarayanang98/Countries-GDP)
The Goal of the project is to understand this dataset, geting insights from it and finally performing regression task on it to predict GDP of a country based on parameters like population, area, region, net migration etc.
![output](https://user-images.githubusercontent.com/64247956/84409420-083ce080-ac2b-11ea-8c45-833d0a61de8e.png)
In this project, we used countries_of_the_world dataset to build a <b>GDP</b> predictor. 5 different learning regressors (Linear Regression,SGD, SVM, Random Forest, and XGBoost) were tested, and we have acheived the best prediction performance using XGBoost on an average from the 7 Fold cross- validation, followed by Linear Regression, and then Random Forest , while SVM acheived the worst performance of the 5.

The best prediction performance was acheived using <b>XGBoost regressor</b>, using all features in the dataset, and resulted in the following metrics:
- Mean Absolute Error  <b> (MAE)</b> :0.3572660773680769
- Root mean Squared Error  <b>(RMSE)</b> :0.47540445296842687
- R-squared Score  <b>(R2_score)</b> :0.8332127481814264
