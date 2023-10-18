# SAS-Interview-Questions

DSD (delimiter-sensitive data): It recognizes two consecutive delimeters as a missing value; it allows you to include delimiters within quoted strings.

Missover: This option prevents SAS from going to a new input line if it does not find values for all of the variables in the current line of data, so you don't get messy results.

Firstobs: This option tells SAS on what line you want it to start reading your raw data file.

Linear Regression: Linear Regression is an approach for modeling the relationship between a scalar dependent variable Y and one or more explanatory variables X.

1) Simple Linear Regression

	Y = B0 + B1X1 + e

Here X1 is explanatory variable

2) Multiple Linear Regression

	Y = B0 + B1X1 + B2X2 + e

Here X1 & X2 both are explanatory variables

PROC REG DATA = commrent;
MODEL rental_rates = age;
RUN;
