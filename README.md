# cement slump - Regression

The concrete slump test measures the consistency of fresh concrete before it sets. It is performed to check the workability of freshly made concrete, and therefore the ease with which concrete flows. It can also be used as an indicator of an improperly mixed batch.

![Types_of_concrete_slump](https://user-images.githubusercontent.com/86251750/145757745-637cc992-ccb6-46c3-bae4-a9d3b737e869.jpg)

Our data set consists of various cement properties and the resulting slump test metrics in cm. Later on the set concrete is tested for its compressive strength 28 days later.

Input variables (7)(component kg in one M^3 concrete):

• Cement

• Slag

• Fly ash

• Water

• SP

• Coarse Aggr.

• Fine Aggr.

Output variables (3):

• SLUMP (cm)

• FLOW (cm)

• 28-day Compressive Strength (Mpa)

Data Source: https://archive.ics.uci.edu/ml/datasets/Concrete+Slump+Test

Credit: Yeh, I-Cheng, "Modeling slump flow of concrete using second-order regressions and artificial neural networks," Cement and Concrete Composites, Vol.29, No. 6, 474-480, 2007.

**Evalution with Support Vector Regressor after grid search**

    mean_absolute_error : 2.512801221076172
    Root_mean_squarred_error : 3.178210305119806



***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)

