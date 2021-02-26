# Defect Prediction

Our research focuses on applying machine learning techniques to reason on the impact of software features for the defectiveness of software modules or classes. We are mostly interested on the Java programming language. 

## Motivation

Defect prediction is a research field that combines machine learning techniques to predict software defects in source code. In these lines, our research focus on the explanation of software features applied to predict defects in projects. Thus, a variety of software features help the machine learning models to predict the defects. For instance, common software features relate to CK metrics. As a result, our research may help developers to anticipate defects in software systems during different development stages. 

## Software Features

There are many software features, a.k.a. software properties, we can use for defect prediction. For the survey, you need to learn a little bit about the following:

* Weighted Methods for Class (WMC):  Assigns a weigh to each method of a given class. We can weigh the methods based on several characteristics, such as:

  * Lines of Code

  * Cyclomatic Complexity

  * Number of parameters

  * Among others

    High WMC values indicates that the code complexity is high. To exemplify the WMC, the image below shows a simple _ATM_ class where the WMC is equals to 7 (denoted by the total number of methods in the class).  ![WMC](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/WMC.png) 

* Coupling Between Objects (CBO): Defines a count of the number of classes that are coupled to a particular class. When the CBO is high, it is more difficult to understand and maintain the class. The following image exemplifies a CBO case. Here, coupling varies between the three classes. As such, the _ATM_ represents a CBO of 2, while the _Account_ counts for 1 and _Bank_ has a CBO of 0.  ![CBO](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/CBO.png)

* Number of Attributes (NOA): Represents the total number of attributes in a target class. An attribute or field of a class is typically a constant or variable. To exemplify the NOA, the following image shows a class named _Account_, where the number of attributes is equal to 8. As in the case of the other features, higher values may contribute to defects in the source code. ![NOA](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/NOA.png)

* Documentation and comments: Represents the density of comments and documentation per lines of code. The documentation counts for _docstrings_ and software documentation in _markdown_ format. This feature is problematic when there is lack of proper documentation or code comments. As a example, the image below shows a software repository in GitHub with little to no documentation. ![DOC](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/DOC.png)     

## References

