# A Complete Cycle of Credit Risk Modelling 

As a Machine learning project, We aim to use data science techniques to model three important notions in Credit risk management :
Probability of Default (PD), Loss Given Default (LGD) and Exposure at Default (EAD).

The data set used for this purpose, is a <b>portofolio of 466285 loans</b> open-source data (on Kaggle) and our purpose is to build models that are compliant with Basel II and Basel III Bank's regulations.

The Data set is well describe in the DataPreparation file !!! And there is a link to download it.

At the end of this work, we compute the <b>Expected Loss (EL)</b> and the <b>Regulatory Capital (F- IRB) </b>  that will be expected by the regulations for this loans portfolio.

The main Data Science techniques used in this project are :

- Weight of evidence   - Information value   - Fine classing   - Coarse classing   - Linear regression - Logistic regression

- Area Under the Curve  - Receiver Operating Characteristic Curve - Gini Coefficient - Kolmogorov-Smirnov - Assessing Population Stability


The work is subdivide as it follows :

>>>> <b> I - DATA PREPARATION </b>
      
            Import, Explore, Preprocess (formatting, dealing with missing values..)
 
>>>> <b> II - PD Model </b>
           
         - Data Preparation : format Independent / Dependent variables, identification of Good (non-defaulter)/ Bad (defaulter)
         - We will use the Logistic Regression model to estimate the PD
         - A section will cover PD monitoring
    
>>>> <b> III - LGD Model </b>

         - We will use a two stage model : First stage , Logistic Regression and at the secong stage Linear Regression 

>>>>     <b> - EAD Model </b>
                    
         - We will use a Linear Regression modeling


           
    

