# Data-science

# Iris Dataset Project 2019
This repository contains an exploration of the famous Iris Dataset as part of the assessment in the  Programming and Scripting module for the Higher Diploma in Data Analytics with Galway-Mayo Institute of Technology.


## 3. The Dataset
The Iris Dataset consists of 50 samples each of three different species of iris flower: setosa, versicolor and virginica. It contains four different measurements for each sample in centimetres - the length and width of sepals and petals - making it a multivariate dataset.

![Iris Species](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Machine+Learning+R/iris-machinelearning.png)

The data was collected by botanist Edgar Anderson in the Gaspé Peninsula and popularised when it was used by biologist and statistician Ronald Fisher in his 1936 paper *The Use of Multiple Measurements in Taxonomic Problems* to demonstrate how statistics can be used for classification. He argues that, based on some significant attribute differences between the species in this dataset, iris group membership could potentially be determined by sepal and petal measurements alone - a method that would become known as linear discriminant analysis. From here it is postulated that new iris flowers could be classified based on the statistical information gleaned from the dataset. 

The Iris Dataset remains a popular example as an introduction to exploratory data analysis, pattern recognition, and machine learning algorithms for the following reasons ([Brownlee, 2016](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)):
* It is a complete, balanced dataset in that there are no null values and each class is equally represented. 
* Each of the four features (sepal and petal length and width) are measured in the same units (centimetres).
* One iris species (setosa) is linearly separable from the other two. While the other species have some overlap, they are still largely distinguishable from one another in certain measurements. Thus, classification is relatively easy and, by extension, the predictive capability of the data is quite strong. 


## 4. Exploratory Data Analysis
*See Jupyter Notebook entitled **Iris Dataset Exploratory Analysis** for the code.*

Exploratory Data Analysis allows us to better understand the data through statistical and visual analysis in order to form hypotheses and uncover potential patterns in the data ([Douieb, 2017](https://www.quora.com/What-are-the-steps-include-in-data-exploration)). For this portion of the project, I will be using *pandas* to read the dataset and perform statistical investigations and a mixture of *matplotlib* and *seaborn* to illustrate patterns.
 
Generally, the first things to look at when confronted with a new dataset are the structure of the dataset and basic information about its contents ([Brownlee, 2016](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/); [Kadam, 2017](https://github.com/ashKadam/IrisDataAnalysis/blob/master/Iris.py); [Mittapalli, 2018](https://medium.com/@harimittapalli/exploratory-data-analysis-iris-dataset-9920ea439a3e); [Ng, 2019](https://www.ritchieng.com/machine-learning-iris-dataset/#)). *Pandas* allows us to see that the dataset is comprised of 150 rows and 5 columns; 4 of these columns are float datatypes containing the petal and sepal measurements and the last one is an object datatype that contains the species names. There are no null values in the dataset that need to be accounted for in later analysis. We can also see that the dataset is well balanced with each species accounting for 50 samples.

![Iris Dataset Information](Images/iris.info.species.PNG)

Below is a sample of 10 entries in the Iris Dataset:

![Iris Dataset Sample](Images/iris.sample.PNG)
