# CodeAlpha_Titanic-Classification

### TITANIC CLASSIFICATION 

Make a system which tells whether the person will be saved from sinking. What factors were most likely to lead to success: socioeconomic status, age, gender and more.


### Dataset Description
![image](https://github.com/FjRabbi/CodeAlpha_Titanic-Classification/assets/72760867/0ab3450f-ba3e-414c-910e-de0a52af9c0d)
</br>

The factors used for prediction (passenger class, sex, age, number of siblings/spouses aboard, number of parents/children aboard, fare, and embarked port) and several other factors are considered for survival prediction in the Titanic dataset. </br>
</br>
These factors were processed during the initial data preprocessing steps and are indirectly included in the model's training:</br>

<strong>Passenger Class (Pclass):</strong> This variable is an indicator of socio-economic status, with 1st class being higher status than 2nd class, and so on. Passengers in higher classes likely had a higher chance of survival due to their proximity to lifeboats and priority in evacuation.</br>
<strong>Sex:</strong> As mentioned, women and children were given priority for lifeboats, so being female could increase the likelihood of survival.</br>
<strong>Age:</strong> Younger passengers, especially children, were also given priority for lifeboats, so age could impact survival chances.</br>
<strong>Number of Siblings/Spouses (SibSp):</strong> The presence of family members could impact survival chances, as families might have stayed together and helped each other during the evacuation.</br>
<strong>Number of Parents/Children (Parch):</strong> Similar to SibSp, the presence of parents or children could impact survival chances, as families might have stayed together.</br>
<strong>Fare:</strong> The fare could be an indicator of socio-economic status, with higher fares potentially indicating higher status and potentially higher chances of survival.</br>
<strong>Embarked Port:</strong> The port of embarkation could be related to other factors not explicitly mentioned, such as nationality or socio-economic status, which could impact survival chances.</br>

![image](https://github.com/FjRabbi/CodeAlpha_Titanic-Classification/assets/72760867/723980d3-bf25-44b3-ab27-0aaddf7a65fd)
</br>

The 'FamilySize' feature is used as it can potentially capture additional information about a passenger's likelihood of survival. Here's why it might be useful:
</br>
<strong>Rescue Priority:</strong> During the Titanic disaster, women and children were given priority for lifeboats. Having a larger family size (e.g., parents with children) might indicate a higher priority for rescue, thus potentially increasing the chances of survival.</br>
<strong>Support System: </strong>Having family members onboard could provide emotional support and assistance, which might increase the likelihood of survival in a stressful situation.</br>
<strong>Shared Tickets:</strong> In some cases, family members might share the same ticket or fare, which could indicate a closer relationship and potentially affect survival chances.</br>
<strong>Group Behavior:</strong> Family groups might behave differently in emergencies compared to individual passengers, which could impact survival outcomes.</br>
