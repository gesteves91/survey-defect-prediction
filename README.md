# Defect Prediction

Our research focuses on applying machine learning techniques to reason on the impact of software features for the defectiveness of software modules or classes. We are mostly interested on the Java programming language. 

## Motivation

Bla bla bla



## Software Features

There are many software features, a.k.a. software properties, we can use for defect prediction. For the survey, you need to learn a little bit about the following:

* Weighted Methods for Class (WMC):  Assigns a weigh to each method of a given class. We can weigh the methods based on several characteristics, such as:

  * Lines of Code

  * Cyclomatic Complexity

  * Number of parameters

  * Among others

    High WMC values indicates that the code complexity is high. To exemplify the WMC, the image below shows a simple ATM class where the WMC is equals to 7 (denoted by the total number of methods in the class).  ![WMC](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/WMC.png) 

* Coupling Between Objects (CBO): Defines a count of the number of classes that are coupled to a particular class. When the CBO is high, it is more difficult to understand and maintain the class. The following image exemplifies a CBO case. Here, coupling varies between the three classes. As such, the ATM represents a CBO of 2, while the Account counts for 1 and Bank has a CBO of 0.  ![CBO](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/CBO.png)

* Number of Attributes (NOA): 

* 

