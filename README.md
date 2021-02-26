# Defect Prediction

Our research focuses on applying machine learning techniques to reason on the impact of software features on the defectiveness of software modules or classes. We are mostly interested in the Java programming language. 

## Motivation

Defect prediction is a research field that combines machine learning techniques to predict software defects in source code. In these lines, our research focuses on the explanation of software features applied to predict defects in projects. Thus, a variety of software features helps the machine learning models to predict the defects. For instance, common software features relate to CK metrics. As a result, our research may help developers to anticipate defects in software systems during different development stages. 

## Software Features

There are many software features, a.k.a. software properties, we can use for defect prediction. For the survey, you need to learn a little bit about the following:

* Weighted Methods for Class (WMC): Assigns a weight to each method of a given class. We can weigh the methods based on several characteristics, such as:

  * Lines of Code

  * Cyclomatic Complexity

  * Number of parameters

  * Among others

    High WMC values indicate that the code complexity is high. To exemplify the WMC, the image below shows a simple *ATM* class where the WMC is equaled to 7 (denoted by the total number of methods in the class). ![WMC](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/WMC.png) 

* Coupling Between Objects (CBO): Defines a count of the number of classes that are coupled to a particular class. When the CBO is high, it is more difficult to understand and maintain the class. The following image exemplifies a CBO case. Here, coupling varies between the three classes. As such, the _ATM_ represents a CBO of 2, while the _Account_ counts for 1 and _Bank_ has a CBO of 0.  ![CBO](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/CBO.png)

* Number of Attributes (NOA): Represents the total number of attributes in a target class. An attribute or field of a class is typically a constant or variable. To exemplify the NOA, the following image shows a class named _Account_, where the number of attributes is equal to 8. As in the case of the other features, higher values may contribute to defects in the source code. ![NOA](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/NOA.png)

* Documentation and comments: Represents the density of comments and documentation per line of code. The documentation counts for *docstrings* and software documentation in *markdown* format. This feature is problematic when there is a lack of proper documentation or code comments. As an example, the image below shows a software repository in GitHub with little to no documentation. ![DOC](https://raw.githubusercontent.com/gesteves91/survey-defect-prediction/main/img/DOC.png)     

## References

Santos,  G.  E.  and  Figueiredo,  E.  (2020).   Failure  ofone, fall of many:  An exploratory study of softwarefeatures for defect prediction.  In20th IEEE Interna-tional Working Conference on Source Code Analysisand Manipulation, SCAM 2020, Adelaide, Australia, September 28 - October 2, 2020, pages 98–109.

Santos, G. E., Figueiredo, E., Veloso, A., Viggiato, M., and Ziviani, N. (2020). Understanding machine learning software defect predictions. Automated Software Engineering. 27(3):369–392.