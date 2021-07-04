# StackOverFlow surveys

StackOverFlow conducted surveys over the years with respondents using their website, many attributes were collected and stored in csv files. This project aims at conducting a light exploratory data analysis by consolidating data over the years and answer some predefined questions.


## Questions

#### Question 1
What were the most used programming languages over the years?

Over the last 5 years, Javascript was undoubtedly the mostly used programming language according to respondents' answers in the surveys.
The bar plots visualization below also show a trend following the #1 language; it can be observed that css and html programming languages have been trending over the last 3 years as well.



![Bar plots of programming languages](pics/programming_overYrs.png)
___

#### Question 2
How did the Job satisfaction varied over time for full-time employees using StackOverFlow?

The bar plots below, although the discrepancies and differences in sample sizes, show a large number of satisfied employees at their companies. Nevertheless, it will be more beneficial to standardize the number of that categories and compute proportions to have a better idea of any changes over the years.

![Bar plots of full-time employed Job satisfaction over the years](pics/job_sats_overYrs.png)

___
#### Question 3

Does satisfaction of full-time employed StackOverFlow respondents varies over the years? does it increase or decrease? is the change statistically significant?

the answer to those questions, lies first in understanding that differences in sample size from year to year should be standardized (proportions computation). Afterward, the various categories of job satisfactions are plotted over the years to visually inspect the line plots. Finally, a chi square test is conducted to determine whether the satisfaction varies over the years? And if it does. is the change in proportions statistically significant?

![Line plots of full-time employed Job satisfaction over the years](pics/JobSat_percentagesOverYrs.png)
___
## Project's Tools
Juptyer, Gitbash/Github, Atom text editor, Python libraries: Numpy, Pandas, Re, Matplotlib, Seaborn, Scipy
