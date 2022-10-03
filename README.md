# Forest-Cover-Classification
Building a neural network using TensorFlow to identify different forest cover types. Practice tuning hyper-parameters. 
![forest covers photo](https://github.com/jaimeggb/Forest-Cover-Classification/blob/main/other_resources/forest%20cover.png)

## Description: 
This project uses deep learning to predict forest cover type (the most common kind of tree cover) based only on cartographic variables. The actual forest cover type for a given 30 x 30 meter cell was determined from **US Forest Service (USFS) Region 2 Resource Information System** data. The covertypes are the following:

1. Spruce/Fir
2. Lodgepole Pine
3. Ponderosa Pine
4. Cottonwood/Willow
5. Aspen
6. Douglas-fir
7. Krummholz

Independent variables are derived from data obtained from the **US Geological Survey** and **USFS**. The original data is raw and has not been scaled or preprocessed. It contains binary columns of data for qualitative independent variables such as wilderness areas and soil type.

This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so existing forest cover types are mainly a result of ecological processes rather than forest management practices.

Project Objectives:
- Develop a classifiers for this multi-class classification problem.
- Use TensorFlow with Keras to build classifier model
- Use knowledge of hyperparameter tuning to improve the performance of my model as well as keras tuner to give suggestions for params
- Test and analyze performance of the model
- Create clean and modular code
