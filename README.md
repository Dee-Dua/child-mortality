# Investigation of the Global Child Mortality Rate from Gapminder.

## Dataset
I have attempted to investigate the Global Child Mortality Rate and the effect
of various indices such as, Income, BMI of women, Fertility Rate of Women and
Mean Years in School for women of reproductive age (15 to 44) on the rate of
Child Mortality. The dataset is built for this analysis using downloaded data
from "Gapminder". 5 comma separated value files, bmi_women.csv,
child_mortality.csv, income.csv, mean_years_school.csv, and woman_fertility.csv
contain the respective data for various countries from 1990 through 2010.
I have built a pandas DataFrame using the above files, containing 7 columns -
1> Country
2> Year: From 1990 through 2010
3> Child Mortality Rate: Death of children under five years of age per 1,000
live births
4> Income: Gross domestic product per person adjusted for differences in
purchasing power (in international dollars, fixed 2011 prices, PPP based on
2011 ICP)
5> BMI of women: The mean BMI (Body Mass Index) of the female population,
counted in kilogram per square meter; this mean is calculated as if each country
has the same age composition as the world population.
6> Babies per woman: Total Fertility Rate, which is the number of children that
would be born to each woman with prevailing age-specific fertility rates
7> Mean Years in School: the mean years spent in school by women of reproductive
age (15 to 44)


## Summary of Findings
In the exploration, the dataset used in this project gives the following
correlations:
1> Child Mortality Rate has fallen drastically since the 1800s.
2> The Child Mortality Rate is lower for countries with higher gross domestic
product per person.
3> The Child Mortality Rate is higher for lower women's BMI.
4> The Child Mortality Rate increases as the mean total number of children that
women have in their lifetime increases.
5> The Child Mortality Rate reduces as number of years spent in school by women
increases.
6> As the number of years spent in school by women increases, women's total
fertility decreases.
7> As the number of years spent in school by women increases, the income
(i.e. gdp per person) and the BMI of women increases.
8> A steady increase in the Global Mean income is seen, except for the sharp drop
during the great recession of 2008.
9> A steady rise in the mean of women's BMI as well as mean years in school for
women can be seen globally.
10> A steady decline in the mean of women's total fertility can be seen globally.
11> The above dataset shows that there is significant difference between the
average of the highest income and average of the lowest income countries in all
years.

References
https://www.gapminder.org/data/
https://matplotlib.org/devdocs/api/_as_gen/matplotlib.axes.Axes.plot.html
https://brohrer.github.io/matplotlib_ticks.html
https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf
https://www.edureka.co/blog/wp-content/uploads/2018/10/Jupyter_Notebook_CheatSheet_Edureka.pdf
https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed
https://stackoverflow.com
https://wordvice.com/how-to-present-study-limitations-and-alternatives/
