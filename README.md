# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the background of your project?
Background is that we are provided the test and train dataset and we need to create a CNN model for Melanoma detection
- What is the business probem that your project is trying to solve?
Melanoma Detection
- What is the dataset that is being used?
CNN_assignment



## Conclusions
- Conclusion 1 from the analysis
9 classes found
- Conclusion 2 from the analysis
Initial Model was overfitting  so had to choose the right data augumentation strategy
- Conclusion 3 from the analysis
 Which class has the least number of samples? **actinic keratosis and seborrheic keratosis**
 Which classes dominate the data in terms proportionate number of samples? **pigmented benign keratosis**
- Conclusion 4 from the analysis
The class rebalance helped in reducing the overfititng of data thus the loss is
being reduced but it reduced the accuracy asw well.
We tried without the ImageDataGenerator which created data to over fit.
Then we introduced dropout and ImageDataGenerator which reduced the over fit.
At last, we tried Batch Normalization and Augumentation which really helped in carry forward.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->