<h1 align="center">Analysis of Satisfaction Survey Dataset</h1>

<div align="center">
   <a href="https://github.com/iamruveyda/Analysis-of-SatisfactionSurvey-Dataset/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/iamruveyda/Analysis-of-SatisfactionSurvey-Dataset?color=0E6655&style=flat-square"></a>
   <a><img alt="Code Size" src="https://img.shields.io/github/languages/code-size/iamruveyda/Analysis-of-SatisfactionSurvey-Dataset?color=ca3400&style=flat-square"></a> 
   <a><img alt="Repo Size" src="https://img.shields.io/github/repo-size/iamruveyda/Analysis-of-SatisfactionSurvey-Dataset?color=8B0000&style=flat-square"></a>
   <a><img src="https://img.shields.io/badge/repository%20creation%20date-Mar%2019,2023-2E4053?style=flat-square"></a>
</div>

<hr>

<table style="width:100%">
  <tr>
    <th>Languages</th>
    <td>
      <a>
        <img height="22" src="https://img.shields.io/badge/R-292A33?logo=R&logoColor=3776AB&style=flat-square">
      </a>     
    </td>
  </tr>
  <tr>
    <th>IDEs/Editors</th>
    <td>
      <a>
        <img height="22" src="https://img.shields.io/badge/RStudio-292A33?logo=RStudio&logoColor=75AADB&style=flat-square" />
        <img height="22" src="https://img.shields.io/badge/Jupyter-292A33?logo=jupyter&logoColor=F37626&style=flat-square" />
        <img height="22" src="https://img.shields.io/badge/Visual%20Studio%20Code-292A33?logo=visualstudiocode&logoColor=007ACC&style=flat-square">
      </a>
    </td>
  </tr>
  <tr>
    <th>Other</th>
    <td>
      <a>
        <img height="22" src="https://img.shields.io/badge/IBM%20SPSS%20Statistics-292A33?logo=IBM&logoColor=FFFFFF&style=flat-square">
      </a>
    </td>
  </tr>
  </table>

<hr>

# Overview

- [Overview](#overview)
  - [Dataset](#dataset)
  - [Subject Headings](#subject-headings)
    - [\[EN\]\_Factor_Analysis.ipynb](#en_factor_analysisipynb)
  - [Tips](#tips)
  - [References / Useful Links](#references--useful-links)

## Dataset

This dataset contains an airline passenger satisfaction survey.

<div align="left">
   <a href="https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction">
  <img src="https://img.shields.io/badge/Kaggle-1A1B27?logo=kaggle&logoColor=20BEFF&style=for-the-badge"></a>
</div>

</br>

<table>
<thead>
  <tr>
    <th>Variable Name</th>
    <th>Variable Description</th>
    <th>Values / Labels</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>idCount</td>
    <td></td>
    <td>1 - 103904</td>
  </tr>
  <tr>
    <td>id</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Gender</td>
    <td>Gender</td>
    <td>0 = Male<br>1 = Female</td>
  </tr>
  <tr>
    <td>CustomerType</td>
    <td>The customer type</td>
    <td>0 = Disloyal Customer<br>1 = Loyal Customer</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>Age</td>
    <td></td>
  </tr>
  <tr>
    <td>TypeOfTravel</td>
    <td>Purpose of the flight</td>
    <td>0 = Personal Travel<br>1 = Business Travel</td>
  </tr>
  <tr>
    <td>Class</td>
    <td>Travel class in the plane</td>
    <td>0 = Eco<br>1 = Eco Plus<br>2 = Business</td>
  </tr>
  <tr>
    <td>FlightDistance</td>
    <td>The flight distance of this journey</td>
    <td></td>
  </tr>
  <tr>
    <td>v1</td>
    <td>Inflight Wifi Service</td>
    <td></td>
  </tr>
  <tr>
    <td>v2</td>
    <td>Departure Arrival Time Convenient</td>
    <td></td>
  </tr>
  <tr>
    <td>v3</td>
    <td>Ease Of Online Booking</td>
    <td></td>
  </tr>
  <tr>
    <td>v4</td>
    <td>Gate Location</td>
    <td></td>
  </tr>
  <tr>
    <td>v5</td>
    <td>Food And Drink</td>
    <td></td>
  </tr>
  <tr>
    <td>v6</td>
    <td>Online Boarding</td>
    <td></td>
  </tr>
  <tr>
    <td>v7</td>
    <td>Seat Comfort</td>
    <td></td>
  </tr>
  <tr>
    <td>v8</td>
    <td>Inflight Entertainment</td>
    <td></td>
  </tr>
  <tr>
    <td>v9</td>
    <td>On Board Service</td>
    <td></td>
  </tr>
  <tr>
    <td>v10</td>
    <td>Leg Room Service</td>
    <td></td>
  </tr>
  <tr>
    <td>v11</td>
    <td>Baggage Handling</td>
    <td></td>
  </tr>
  <tr>
    <td>v12</td>
    <td>Checkin Service</td>
    <td></td>
  </tr>
  <tr>
    <td>v13</td>
    <td>Inflight Service</td>
    <td></td>
  </tr>
  <tr>
    <td>v14</td>
    <td>Cleanliness</td>
    <td></td>
  </tr>
  <tr>
    <td>DepartureDelayinMinutes</td>
    <td>Departure Delay in Minutes:</td>
    <td></td>
  </tr>
  <tr>
    <td>ArrivalDelayinMinutes</td>
    <td>Arrival Delay in Minutes</td>
    <td></td>
  </tr>
  <tr>
    <td>Satisfaction</td>
    <td>Satisfaction</td>
    <td>Neutral or Dissatisfied<br>Satisfied</td>
  </tr>
</tbody>
</table>

## Subject Headings

### [EN]\_Factor_Analysis.ipynb

## Tips

- Convert R Markdown File to R Script `sample.Rmd to sample.R`

```
knitr::purl("sample.Rmd")
```

- Convert R Markdown File to Jupyter Notebook `sample.Rmd to sample.ipynb`

```
devtools::install_github("mkearney/rmd2jupyter")

library(rmd2jupyter)
rmd2jupyter("sample.Rmd")
```

- Create sav File for SPSS

```
install.packages("haven")

library("haven")
write_sav(data, "data.sav")
```

## References / Useful Links

- Statistics
  - [Investopedia](https://www.investopedia.com/)
    - [The Correlation Coefficient](https://www.investopedia.com/terms/c/correlationcoefficient.asp)
  - [Statology](https://www.statology.org/)
    - [Bartlett’s Test of Sphericity](https://www.statology.org/bartletts-test-of-sphericity/)
- SPSS
  - [IBM SPSS Statistics documentation](https://www.ibm.com/docs/en/spss-statistics)
  - [SPSS TUTORIALS](https://www.spss-tutorials.com/)
    - [Factor Analysis](https://www.spss-tutorials.com/spss-factor-analysis-tutorial/)
- R Programming
  - [GeeksforGeeks](https://www.geeksforgeeks.org/)
    - [Correlation Matrix](https://www.geeksforgeeks.org/correlation-matrix-in-r-programming/)
    - [How to Calculate Cronbach’s Alpha?](https://www.geeksforgeeks.org/how-to-calculate-cronbachs-alpha-in-r/)
  - [Package \'psych\'](https://cran.r-project.org/web/packages/psych/psych.pdf)
  - [R Coder](https://r-coder.com/)
    - [Correlation Plot](https://r-coder.com/correlation-plot-r/)
