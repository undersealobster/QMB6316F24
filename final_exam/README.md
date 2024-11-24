# Final Examination

## Due Friday, December 6, 2024 at 11:59 PM in your GitHub repository.

Complete the exercise described in the pdf above and enter your answers in 
the spaces below.

*Please see the revised version of the pdf copy of the question paper, uploaded Nov. 23, 2024.*

## Part A: Data Handling and Preliminary Regression Modelling

### Question 1

a) Read in the \texttt{airplane\_sales.csv} dataset and store it in a data frame called \texttt{airplane\_sales} in your workspace. 


```

Enter the required code here.

```

b) Calculate and copy the printed output from a \texttt{summary} of the data. 
Use this to get familiar with the contents of the dataset. 


```

Copy your results here.


```

c) Estimate a regression model to predict \texttt{price} as a function of \texttt{age}. 
Copy the printed estimation output from the \texttt{summary} command. 


```

Copy your results here.


```


### Question 2

a) Read in the \texttt{airplane\_specs.csv} dataset and store it 
in a data frame called \texttt{airplane\_specs} in your workspace. 


```

Enter the required code here.

```

b)  Form a dataset \texttt{airplane\_sales\_specs.csv} 
by \texttt{merge}ing the data frames 
\texttt{airplane\_sales.csv} and \texttt{airplane\_specs.csv}. 
Store the new dataset in a data frame called 
\texttt{airplane\_sales\_specs} in your workspace. 


```

Enter the required code here.

```


c) Calculate and copy the printed output from a \texttt{summary} of the data. 
Use this to get familiar with the contents of the dataset. 


```

Copy your results here.


```


d) Estimate a regression model to predict \texttt{price} as a function of 
\texttt{age}, \texttt{pass}, \texttt{wtop}, \texttt{fixgear}, 
and \texttt{tdrag}. 
Copy the printed estimation output from the \texttt{summary} command. 


```

Copy your results here.


```




### Question 3

a) Read in the \texttt{airplane\_perf.csv} dataset and store it 
in a data frame called \texttt{airplane\_perf} in your workspace. 


```

Enter the required code here.

```

b) Form a dataset \texttt{airplane\_full.csv} 
by \texttt{merge}ing all three datasets. 
Store the new dataset 
in a data frame called \texttt{airplane\_full} in your workspace. 


```

Enter the required code here.

```

c) Calculate and copy the printed output from a \texttt{summary} 
of the new variables. 
Use this to get familiar with the contents of the dataset. 


```

Copy your results here.


```


d) Estimate a regression model to predict \texttt{price} as a function of 
\texttt{age}, \texttt{pass}, \texttt{wtop}, \texttt{fixgear}, 
and \texttt{tdrag}, 
as well as \texttt{horse}, \texttt{fuel}, \texttt{ceiling}, and \texttt{cruise}.
Copy the printed estimation output from the \texttt{summary} command. 


```

Copy your results here.


```






## Part B: Advanced Regression Modelling


### Question 4

a) Create new variables 
	\texttt{log\_price}, \texttt{log\_age}, \texttt{log\_horse}, 
	\texttt{log\_fuel}, \texttt{log\_ceiling}, and \texttt{log\_cruise}
	from the variables 
	\texttt{price}, \texttt{age}, \texttt{horse}, 
	\texttt{fuel}, \texttt{ceiling}, and \texttt{cruise}, 
	using the logarithm function \texttt{log()} in \texttt{R} 
	to create these new variables. 


```

Enter the required code here.

```

b) Calculate and copy the printed output from a \texttt{summary} 
of the new variables. 
Use this to get familiar with the contents of the dataset. 


```

Copy your results here.


```


c) Estimate a regression model to predict \texttt{log\_price} as a function of 
	\texttt{log\_age}, \texttt{pass}, \texttt{wtop}, \texttt{fixgear}, 
	and \texttt{tdrag}, 
	as well as 
	\texttt{log\_horse}, \texttt{log\_fuel}, \texttt{log\_ceiling}, 
	and \texttt{log\_cruise}. 
	Copy the printed estimation output from the \texttt{summary} command. 


```

Copy your results here.


```


d) If you notice that any coefficients are statistically insignificant, 
	estimate the model by removing them one at a time. 
	For each variable removed, 
	determine whether the variable should be removed 
	by considering the four specification criteria: 
		statistically significant $t$-statistics, 
		an increase in $\bar{R}^2$, 
		a good theoretical justification, and 
		no large change in the other coefficients.


```

Enter a description of your sequence of adjustments
to the regression model here.
Be sure to address the four specification criteria
described above.


```

Next regression model:

```

Copy your regression results here.


```

Next regression model, if necessary:

```

Copy your regression results here.


```

Next regression model, if necessary:

```

Copy your regression results here.


```

Next regression model, if necessary:

```

Copy your regression results here.


```



e) Print the output from a \texttt{summary} of the regression results
of your final regression model.


```

Copy your final regression results here.


```

f) Finally, for each of the variables in the datasets, 
	list those that are positively related to airplane prices,
	negatively related to airplane prices, 
	and statistically unrelated to airplane prices. 


```

Enter your response here.


```




## Part C: Version Control

### Question 5

Push your completed files to the \texttt{final\_exam} folder 
in your private GitHub repository.