# Image Classification Project

## Project Overview
This project is the main coursework for a machine learning module I took in university. The task was image classification with a binary output - happy vs sad. 

This readme file will not contain the full details of the project - these may be found in the [project report](Assignment_Report.pdf). 

The final grade received for this submission was 94/100.

## Data 
The training and test datasets are located within the [data](./data) folder. However, the labels for the test data are not available as these are withheld by the course instructor. 

The training dataset contains a total of 2,500 observations and 2,304 features. Of these, 2,048 features were pre-extracted from the fc7 layer of the [CaffeNet](https://caffe.berkeleyvision.org/) CNN, while the remaining 256 features were GIST features. `confidence` labels were included to indicate the confidence level that each image was correctly labeled. When all 3 labellers were in agreement of an image's classification, the confidence was 1. Otherwise, it was 0.66. The test dataset contains only the 2,048 CaffeNet CNN features and the 256 GIST features.

## Output
The output of this project was an array of label predictions for the test data, which may be found in the [output](./output) folder.

## License
This project is licensed under the [MIT License](LICENSE.md). You are free to use the code and resources for educational or personal purposes.

## Contact
Please feel free to contact me regarding any questions or feedback regarding this project. I can be reached at ongcrong@yahoo.com.

Thank you for taking the time to look at this project!