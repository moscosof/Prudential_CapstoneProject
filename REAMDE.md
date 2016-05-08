
#Prudential Life Insurance Assessment

The purpose of this project is to predict the rating in the existing Prudential Life Insurance assessment. 
If we can find out the significant attributes that determine the assessment, Prudential could streamline the process
to make it quicker and less labor intensive.  The task is to predict “Response”, an ordinal variable with 8 levels relating
to the final decision associated with an application.  Since, “Response” is an ordinal variable; I have chosen to apply 
Classification Tree and Random Forest method for the analysis.  I decided to add a binomial output variable called ‘Approved’ 
that is set to 1 when Response = 8. Otherwise Approved = 0.  I could predict ‘Approved’ using Logistic Regression and figure
out which independent variables are significant.<br><br>

R code sources are located at https://github.com/moscosof/Prudential_CapstoneProject
<br><br>
Reference for details in R code output in html format:<br>
Classification Tree:    https://moscosof.github.io/Prudential_CapstoneProject/ClassTree.html<br>
Random Forest:          https://moscosof.github.io/Prudential_CapstoneProject/RandomForest.html<br>
Logistic Regression:    https://moscosof.github.io/Prudential_CapstoneProject/Binomial_glm.html<br>



