# Decision trees & dtreeviz tutorial

### Discussion

Decision trees are the fundamental building block of gradient boosting machines and Random Forests, probably the two most popular machine learning models for structured data. Visualizing decision trees is a tremendous aid when learning how these models work and when interpreting models. Unfortunately, current visualization packages are rudimentary and not immediately helpful to the novice. 

So here cames **dtreeviz** to the rescue. **dtreeviz** is a python library for decision tree visualization and model interpretation.  Currently supports [scikit-learn](https://scikit-learn.org/stable), [XGBoost](https://xgboost.readthedocs.io/en/latest) and [Spark MLlib](https://spark.apache.org/mllib/) trees.

This notebook shows an introduction to sklearn's DecisionTreeRegressor. And also, how to display and interpretate it properly using **dtreeviz**. We will use [tips dataset](https://github.com/mwaskom/seaborn-data/blob/master/tips.csv).

Clicking [here](https://github.com/parrt/dtreeviz) you'll open dtreeviz oficial repository. You could find things like:
* [installation guide.](https://github.com/parrt/dtreeviz#install) 
* [useful resources.](https://github.com/parrt/dtreeviz#useful-resources)
