# Upskill
Project 10: Quality Prediction in a Mining Process

Explore real industrial data and help manufacturing plants to be more efficient
# Context

It is not always easy to find databases from real world manufacturing plants, specially mining plants. This database comes from one of the most important parts of a mining process: a flotation plant.
The main goal is to use this data to predict how much impurity is in the ore concentrate. As this impurity is measured every hour, if we can predict how much silica (impurity) is in the ore concentrate, we can help the engineers, giving them early information to take actions (empowering!). Hence, they will be able to take corrective actions in advance (reduce impurity, if it is the case) and also help the environment (reducing the amount of ore that goes to tailings as you reduce silica in the ore concentrate).

# Content

The first column shows time and date range (from march of 2017 until september of 2017). Some columns were sampled every 20 second. Others were sampled on a hourly base.
The second and third columns are quality measures of the iron ore pulp right before it is fed into the flotation plant. Column 4 until column 8 are the most important variables that impact in the ore quality in the end of the process. From column 9 until column 22, we can see process data (level and air flow inside the flotation columns, which also impact in ore quality. The last two columns are the final iron ore pulp quality measurement from the lab.
Target is to predict the last column, which is the % of silica in the iron ore concentrate.

# Expected submission

•	Is it possible to predict % Silica Concentrate every minute?
•	How many steps (hours) ahead can we predict % Silica in Concentrate? This would help engineers to act in predictive and optimized way, mitigating the % of iron that could have gone to tailings.
•	Is it possible to predict % Silica in Concentrate without using % Iron Concentrate column (as they are highly correlated)?

# Dataset
This dataset is about a flotation plant which is a process used to concentrate the iron ore. This process is very common in a mining plant.
# Data set Link:
https://drive.google.com/file/d/1N80d8eTDAf1JMQXGQbHDAUaMGRyA8QG3/view?usp=sharing 
