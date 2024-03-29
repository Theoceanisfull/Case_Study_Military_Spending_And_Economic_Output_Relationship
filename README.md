# EXPLORING THE IMPACT OF MILITARY SPENDING ON ECONOMIC OUTPUT: A DATA EXPLORATION

**Purpose:**
The purpose of this project is to investigate the relationship between military spending and economic output in the United States. The aim is to analyze existing data to determine whether military expenditure contributes to an increase or decrease in economic output. By conducting this analysis, we seek to provide insights into the potential economic ramifications of military spending policies.

**Hypothesis Statement:**
Based on contrasting claims from prominent organizations, we hypothesize that the relationship between military spending and economic output is multifaceted. The War Prevention Initiative posits that military spending decreases a nation's economic output, suggesting that resources allocated to defense detract from productive investment. Conversely, the Rand Corporation argues that military spending stimulates economic growth, suggesting that investments in defense infrastructure and technology foster innovation and productivity gains.

**Expert Narratives:**
According to RAND research report, “The applied macroeconomics literature consistently finds that defense spending has a positive effect on growth" (2024).  

According to a War Prevention Initiative meta-analysis, “Over a 20-year period, a 1% increase in military spending will decrease a country’s economic growth by 9%" (2017).

## Key Findings

1.1 Initial analysis reveals a negative correlation coefficient of -0.74 between military spending and economic growth, implying an inverse relationship where increased economic growth coincides with decreased military spending, and vice versa. The causal direction of this correlation remains unclear.

1.2 Annual GDP growth rates exhibit significant fluctuations year-to-year, contributing to a volatile pattern that complicates correlation with other variables, whereas military spending tends to change gradually and linearly over time.

1.3 Over the period from 1980 to 2020, the average GDP per capita growth rate stands at 1.7%, with military spending constituting an average of 3.7% of GDP. Notably, the 1980s witnessed both peak military spending and highest economic growth, while the 2000s saw the lowest levels of both.

1.4 Military spending below 4.5% of GDP corresponds to an average GDP growth rate of 1.35% over three decades, whereas exceeding 4.5% of GDP correlates with a 2.37% average growth rate over ten years.

1.5 Despite a historical decline in military spending from 1980 to 2020, the GDP per capita growth maintained an upward linear trajectory, suggesting a complex relationship where other factors likely influenced economic growth concurrently with changes in military expenditure.

1.6 While the data remains inconclusive regarding the precise impact of increasing military spending on economic growth, a cursory examination suggests that periods of elevated military expenditure coincide with consistently higher economic growth rates compared to periods of low military spending and economic stagnation.

**Conclusion:**
These findings underscore the need for further research and analysis to better understand the intricate dynamics between military spending and economic growth, emphasizing the importance of considering additional factors and variables that may contribute to fluctuations in economic performance.

## Data Exploration: Initial Observations
<img width="537" alt="image" src="https://github.com/Theoceanisfull/Case_Study_Military_Spending_And_Economic_Output_Relationship/assets/161080575/0ccae67f-e070-44b0-9162-0497fb8d3758">

2.1 Tax Revenue (1980 – 2020): 
[Max: 28.5 %] 
[Min: 23.37% Average: 26%] 
[Year 2020: 26.2%] 

2.2 Military Spending (1980 -2021):
[Max: 6.8%]
[Min: 3.1%]
[Average: 4.5%]
[Year 2020: 3.7%]

2.3 Education Spending (2000 – 2020):
[Max: 6.7%]
[Min: 4.8%]
[Average: 5.9%]
[Year 2020: 5.4%]

2.4 GDP Growth Rate Per Capita (1980 – 2020):
[Max: 6.3%]
[Min: -3.7%]
[Average: 1.7%]
[Year 2019: 1.8%]
[Year 2020: -3.7%]

## DATA EXPLORATION: CORRELATION MATRIX 
<img width="524" alt="image" src="https://github.com/Theoceanisfull/Case_Study_Military_Spending_And_Economic_Output_Relationship/assets/161080575/887bd804-8d90-4d1f-b7b2-d965c2700e10">

**3.1 Tax Revenue (1980 – 2020) VS. Military Spending (1980 -2020)**
(-0.59) Overall, this correlation coefficient suggests that there is a relationship between military spending and tax revenue, with higher military spending associated with lower tax revenue, on average. However, further analysis is needed to determine the causality and the specific factors influencing this relationship. 
[NOTE: THIS VARIABLE IS JUST USED TO BASELINE DATA ANALYSIS, AND NOT A PART OF THE PROJECT OUTCOMES]

**3.2 GDP Growth Rate (1980-2020) VS. Military Spending (1980-2020)**
(-0.74) This negative correlation suggests that higher military spending is associated with lower GDP growth, on average. However, it's essential to note that correlation does not imply causation. Further analysis, such as regression modeling or causal inference techniques, would be necessary to establish the directionality and causality of the relationship between military spending and GDP growth.

**3.3 GDP Growth Rate (2000-2020) VS. Education Spending (2020 – 2020)**
(-0.47) The negative sign of the correlation coefficient indicates the direction of the relationship: as education spending increases, GDP growth tends to decrease. However, The negative correlation might also be influenced by timing and lag effects. For instance, increased education spending may initially lead to a decline in GDP growth as resources are diverted from other sectors or as educational reforms take time to yield tangible economic benefits. However, in the long term, investments in education may contribute positively to GDP growth. Further analysis is required. 
[NOTE: THIS VARIABLE IS JUST USED TO BASELINE DATA ANALYSIS, AND NOT A PART OF THE PROJECT OUTCOMES]
<img width="3288" alt="image" src="https://github.com/Theoceanisfull/Case_Study_Military_Spending_And_Economic_Output_Relationship/assets/161080575/a02ab946-cbf6-4a91-a325-da3e2d480ce7">

## DATA EXPLORATION: LINEAR REGRESSION: SCENARIOS

### GDP PER CAPITA VS MILITARY SPENDING
<img align="center" width="393" alt="image" src="https://github.com/Theoceanisfull/Case_Study_Military_Spending_And_Economic_Output_Relationship/assets/161080575/73c1d34b-ca62-47fa-ad8d-6a4194b750db">

4.1 Since 1980, Military Spending as a Percentage of GDP decreased from the range of 5-6% to 3-4% by the late 2010s.

4.2 Concurrently, there has been a consistent average annual GDP growth rate of 1.7%.  

4.3 Positive compounding effect resulted in linear increase in GDP over time despite some years being negative

4.4 This raises the question: Did the decrease in military spending coincide with an increase in GDP over time, 
creating the appearance that high military spending decreases GDP while low military spending increases it?


  ### GDP YEARLY GROWTH RATE VS MILITARY SPENDING
<img aling="right" width="382" alt="image" src="https://github.com/Theoceanisfull/Case_Study_Military_Spending_And_Economic_Output_Relationship/assets/161080575/fa7df20b-1b45-4368-9b81-809e041fb740">











