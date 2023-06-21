# Longitudinal-Data-Modeling
This was a final team project for coursework EPSY587 at UIUC(SP2023).

### Data
The data for this study is from the National Youth Longitudinal Study (6,287 observations of 7 variables with no missing data).
The NYLS survey was conducted over four years (from 1976 to 1980), and respondents answered a questionnaire every year.
Kids were asked to rate the wrongness of nine deviant behaviors, such as cheating on tests at school, marijuana use, and breaking into cars,
on a 4-Likert scale (1=“not wrong” to 4 = “very wrong”).
The same questionnaire was also given to their parents to gauge their approval of the same behaviors.

### Methods
The longitudinal data model was applied to model the NYLS survey data based on hierarchical linear modeling.
First, basic descriptive statistics and exploratory analysis of data are presented. 
Second, we applied the hierarchical linear model using the "lmer" and "lme" R functions.
The "age" variable was set as level 1, and the variables related to each individual (distinguished by "id" variable) were included as level 2.
The process of exploring and examining assumptions for the final model is presented.

### Result
The factors that influence children’s attitudes toward deviant behavior and found that as children get older, their attitudes
towards deviant behavior become less strict, and their moral codes begin to differ from those of their parents.
The results revealed that older male youth whose parents have relatively lower deviant behavior attitude scores tend to have
lower deviant behavior attitude scores. Specifically, the study found that girls, on average, show scores that are about 0.5
point higher than those of boys. The interaction of age and gender was also found to be positive,
suggesting that while growing up typically leads to lower scores, this effect is weaker for female youth.
These findings may shed light on efforts to prevent and address deviant behavior among youth.
However, further research is needed to better understand the underlying factors that contribute to deviant behavior among
youth and to develop effective strategies for prevention and intervention.
