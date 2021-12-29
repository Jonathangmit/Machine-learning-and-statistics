# Machine-learning-and-statistics


This is a GMIT coursework repository in which I have been tasked to perform work on data sets. It contains jupyter notebooks and other relevent files (such as image files). The 2 different notebooks are 
###### sci-kit learn (scikit-learn.ipynb)

1. A look at machine learning algorithms from the scikit learn package
1a K nearest neighbours
1b Logistic Regression
1c Linear regression

Data sets used for this were Palmer penguins and wine chemistry.

###### Scipy stats (scipy-stats.ipynb)

2. Perform Anova calculations on a chosen data set
the chose data set was looking at weight loss on 3 different diets.

### Install and run

These files run in the python environment thorough jupyter notebook.
If you do not have the python environment on your pc then I would suggest using Annaconda for Python

The notebooks require the palmer penguins data set (sci-kit learn) to be available and the pingoin data package (Anova). 

Clear (copy and paste) instructions on downloading of these are available in the requirements package.

Once those actions are complete the jupyter notebooks can be run in full by following the steps below.

1. Open jupyter notebook
2. Open the relevent file 
###### (scikit-learn.ipynb or scipy-stats.ipynb)
3. Click on the Kernel tab
4. Select restart and run all

from here the notebok should run in full with no intervention.

Feel free to play with the code in the notebook!!! Enjoy

### Credits

These projects were driven by the lectures suppied by Dr Ian McLoughlin as part of the GMIT Data Analytics Higher diploma.

Any online information used extensively during this project is linked within the relevant datapages.

### Tests

Depending on the test/train data selected in the programs an issue (warning) of number of iterations may arrise. I have increased the number of iterations to reduce this potential  but should it occur there is no harm in running that line and subsequent lines with a higher (max_iter) value to ensure the full notebok executes.

### Small diary of actions

##### Week 1 
Set of of Git hub repository for the course, adding some SKlearn work I did over the summer to ensure the page is loaded correctly and I am capable of pushing and pulling between PC and Git.
##### Week 2 
Added in the 2 x jupyter notebook file and added the requirements text file.
##### Week 3
pandas notebook started , working down through the sheet making notes and playing with the different items
numpy notebook worked on, using the real python examples
##### Week 4
scikit learn started with the example from the class
scikit learn using Knearest neighbours used
##### Week 5
Nearest neighbours finished (bar tidying)
##### Week 6/7
Logistic regression and further tidying after much drama with the annoconda package, many thanks Ian.
Starting looking at the t-test work also for the ANNOVA section of the module.
##### Weeks 8,9,10
Working theough the diet data set performing prelimnary analysis on the diet data set
Assing the suitability of the Data for anova study
Perfomring the anova study on the diet v weight loss
Perfomring anova on change in diet v change in BMI
##### Final weeks
Tidy up and additional commenting.

# Conclusion

I learnt a great deal about the potential for sci-kit learn to be used any number of fields where complex (sometimes incomplete) data exists. It has the potential to provide predictive insight about the subject matter which the data pertains too.

With the Anova section the direct application of the packages to a health issue demonstrated how not only scientifica insight could be achived within a scientific environment but also how these insights could be used to shape public policy (promotion of one diet type over another based on it's clear success over the others).

The problems solved in these notebooks range from identification of penguins based on physical characteristics, the provenence of wine based on available chemical analysis and the effectiveness of differing diets. I also learnt that the (in the case of my study) that calculating BMI had an effect of normalising the weightloss curve thus adding some merit to the (currently) much maligned BMI value.

Interestingly the stand out for the wine data set was that ultimately much of the identification of wine still came down to flavor (or the compunds assotiated with flavor) and colour. Which thankfully for me means that I should carry on tasting and drinking wine!.

Perhaps the biggest learning of all though with the datasets from an analysts point of view is that too many variables if just thrown in can not improve and potentially degrade the quality of prediction. In order to produce a good complex characterisation of a problem it is nessesary to break it down and asses its constituant parts first. Only then can you build more accurate and complex models.