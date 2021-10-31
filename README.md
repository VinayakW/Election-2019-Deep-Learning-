# Election-2019-Deep Learning
EDA(Data analysis &amp; Visualization) &amp; Deep learning model on Election 2019 dataset.

# Task Performed -

1. Importing the packages and reading the dataset.
2. Cleaning the dataset.
3. EDA & Pre-processing.
4. Encoding the data.
5. Model Creation.
6. Cross validation.
7. Conclusion.
8. Results.
  
# Conclusion -

**GENDER**
 - Out of total 2263 candidates 12.2 % candidates are female while 87.8 % candidates are male.
 - Numerically 277 candidates are female and 1986 candidates are male.
 - The winning % of male candidates is 23.3% & that of female candidates is 27.4%.


As the data describes the involvement/participation of female candidates is comparitively less than that male candidates.Slight encouragement should be provided to the female group in terms of participating in the election. This can be a good approach as it can bring the issues and policies related to the female group in front.

**CRIMINAL RECORDS**
- It can be obsevered that the count of candidates having 0 criminal cases is higher as compared to the count of candidates having cases.
- The party having highest number of criminal cases is BJP, also one of the candidate in this party has 240 criminal cases on him which is highest among all.
- It can also be observed that there is a candidate of INC party who managed to win the election despite of having more than 200 criminal cases on him.
- Similarly there is a candidate of BJP who managed to win the election despite of having more than 50 criminal cases on him.

A politician is the leader who leads the society, one who motivates the people, one who contributes in the progress of a country.If a politican with a criminal record/background leads the nation it can effect all the above mentioned factors and also it can result in creating a bad impact or image of the nation.

**AGE**
- The maximum number of candidates belong to age band of 40-60 years for both male & female.
- The age of youngest candidate is 25 years for both male and female.
- While the age of oldest candidate in male group is 86 years and that of female group is 81 years.

As the data describes most number of candidates belong to age group of 40-60 years. Also it can be noticed that the participation of young candidates is comparitievely low. The young age group should also be encouraged to be the part of election and contribute in leading the nation as they can bring forward the education related issues which are essential if a country is looking for rapid development and growth.

**CATEGORY**
- The count of general category candidates is higher than that of other two categories.
- The winning % of general category candidates is higher than other category candidates.

As the data describes the ratio of general category candidates is high as compared to other categories. It would be helpfull if candidates from other categories also actively participate as it would bring more issues related to their category in front.

**EDUCATION**
- The record of educated candidate is high, this is also a good sign from the perspective of progress of the country.
- Similarly if the educated/highly educated candidates winning ratio increases there is a chance that the progress will be faster.

Education plays an important role in terms of progress of a country. An educated leader will certainly upbring technology,infrastructure,bussiness, etc related policies which will obviously lift up the nations progress. So it is a positive sign or it can be said it is plus factor if the leaders of the nation are educated.

**PARTY**
- There are total 133 parties involved in election.
- BJP and INC has highest number of candidates.
- INC(INDIAN NATIONAL CONGRESS) & BJP(BHARTIYA JANTA PARTY) are the two parties which have highest count of participating in election.
- Constituency wise BJP has highest count of getting involved in election.
- State wise INC has highest count of getting involved in election.
- INC and BJP beat other parties in terms of participating in elections.
- There are some parties like DMK , VCK , LJP which have 100% winnings.
- BJP has the highest winnings as compared to other parties followed by INC.

As the data describes the candidates from BJP (Bhartiya Janta Party) has won most number of seats by beating all other parties which were fighting election against them.
# Results -
**Initially the model interpretted low training error and high testing error i.e the model was overfitting in nature. Too many epochs can lead to overfitting of the model, whereas too few may result in underfitting the model. Early stopping is a method that allows you to specify exact number of training epochs and stop training once the model performance stops improving. Hence for handling overfitting of the model we have used "Early stop" regularisation technique here. Eventually we have achieved a overall accuracy of 93% and average accuracy of approx 82%.**
