# salary-prediction-bias-analysis

Salary prediction and bias analysis using brazilian government data.

For this project, we use the brazilian dataset Annual List of Social Information (RAIS, in portuguese, Relação Anual de Informações Sociais). This public dataset contains multiple samples of job related informations of people all around the country (with no sensible informations), containing data such as, but not limited to:

* Education level - ranging from illiterate to PhD;
* Race - classifying the professional in any race formally accepted by the Brazilian Institute of Statistic and Geography (IBGE, in portuguese, Instituto Brasileiro de Geografia e Estatística);
* Gender - male, female or ignored;
* Disability - whether the professional has any disability or not, including a specific classification if there is one;
* Job role - using the Brazilian Classification of Occupations (CBO, in portuguese, Classificação Brasileira de Ocupações);
* Company area - area in which the company the professional work acts;
* Company size - range of employees the company has;
* City - cities where the professional live and work.

We have made a statistical analysis of the data we have, focusing on the Computer Science area, both for the professional as for the company they work. And we are also making predictions for the salary range of the professional, ranging from 2,5 to 12 minimum wages for professionals with at least a bachelors degree working in the state of São Paulo, in the area of IT, for IT companies. At the moment with 7 classes for the given range, we have around 46% precision. It is about 3 times better than random! It is still a work in progress, getting better at each moment.
