# Binary  Classifier
## Mentors:- 
Archana Gahiwad\
Navid Panchi

##  Team Members:- 
Krushnakant Ghogare\
Jaideep Bedarkar             
Sanket Gajbhaiye\
Mrinank Chopda\
Satyam Gupta

## Introduction:
Classifier ,basically what the name suggests is ,the program which classifies between 
the objects. Binary or binomial classification is the task of classifying the elements of a given set into two groups. Binary classifier is the model which helps in classifying between two objects using machine learning algorithm .Our classifier classifies between a [SEDAN](https://www.cartrade.com/new-cars/sedan-cars/best-sedans-in-india) and [SUV](https://www.cartrade.com/new-cars/suv-cars/best-suvs-in-india) car using concept of logistic regression .It has been coded in PYTHON language which is most suitable for coding machine learning algorithms in terms of flexibility and availability of libraries (For ex:-[NUMPY](http://www.numpy.org/) ,   [SCIPY](https://www.scipy.org/),etc). 

## Machine Learning:
Machine learning is an application of  artificial intelligence (AI) which provides system the ability to learn and improve without being explicitly programmed .The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly. Machine learning can be classified broadly  as:\

a) Supervised Learning
- I) Linear Regression
- II) Logistic Regression
                                            
b) Unsupervised Learning\
c) Reinforcement Learning

## PRE-REQUISITE FOR THE PROJECT :
**Python programming Language:**\
Before starting the project we studied basics of python programming language from 
[py4e.com](https://www.py4e.com/lessons) source .It provided us good hands on  knowledge necessary to code the ML algorithm.\
**Machine Learning algorithm:**\
It also required to have a good understanding of what machine learning is ?
And what it’s implementation is about ,as well as necessity of it .Special focus
should be  given to understand the GRADIENT DESCENT algorithm and its implementation. We studied it from the course provided by [coursera](https://www.coursera.org/learn/machine-learning) ,which was teached by Andrew Ng.\
**Collection Of Dataset:**\
Dataset is the  collection of the data about the categories in which your classifier
is going to classify things. A good dataset is as important  as  it is to have an efficient and smooth code for good accuracy of the classification . Try to collect , unique and vast variety of data as much as possible  as it makes your classifier more efficient and accurate.\
**Assumptions:**\
I) As it is a binary classifier ,it will have only two categories which will have their own label ,either 0 or 1.
So we have assumed 0 for sedan cars and 1 suv cars ,although it can have vice versa labels.\
II) For the output of sigmoid function ,value>=0.5 is rounded of to 1 and value<0.5 is taken as 0.\

## INSTALLATIONS:

I) **[Anaconda](https://anaconda.org/anaconda/python)**        :  try to have latest version of it ,others will work also .it is the suggested  environment for coding python programs .\
II) **[Opencv library](https://pypi.org/project/opencv-python/)** :   it is a library which enables us to read the picture                                      and convert  it into matrix form of  elements having  value between 0-255.  

 ## Explanation Of The Code:
 
1)**Rename_Reshape():**-This is the function for converting each image to a specified size (or   pixel) as it is mandatory to    have equal size of all the images  to avoid  calculation  error . It imports PIL and OS libraries as they have required       functions to resize image.


![](https://github.com/satyamgupta2708/binaryclassifier/blob/master/rename.png)

2)**label():**- This is the function for creating a excel sheet with csv extension having
                   label(0 or 1) for each image against their name. It helps the machine to 
                   know which image is SUV and which is sedan .
                   
![](https://github.com/satyamgupta2708/binaryclassifier/blob/master/csv.png)

3) Pre_process():-This is the function in which a list is created which contains matrix of
                            images in dataset as well as hundred randomly flipped images .also     
                            in this function we have stored label of each image along with its 
                          matrix . We have also used csv reader to read the csv file formed above.
                          
![](https://github.com/satyamgupta2708/binaryclassifier/blob/master/pre.png)   


                          
                          
      

 



 
