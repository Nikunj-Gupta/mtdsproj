# Predicting blood pressure under circumstances of missing data: An analysis of missing data patterns and imputation methods using NHANES


The World Health Organization defines cardio-vascular disease (CVD) as “a group of disorders of the heart and blood vessels,” including coronary heart disease and stroke. (World Health Organization 2021) CVD is affected by “intermediate risk factors” such as raised blood pressure, raised blood glucose, raised blood lipids, and obesity. These are predominantly influenced by lifestyle and behaviour, including physical inactivity, unhealthy diets, high intake of salt, and tobacco and alcohol use. However, genetics and social/environmental factors such as poverty, stress, and racism also play an important role. Researchers studying the behavioural and environmental factors associated with these “intermediate risk factors” need access to high quality and detailed information on diet and physical activity. 

However, missing data are a pervasive problem in clinical and public health research, affecting both randomized trials and observational studies. Reasons for missing data can vary substantially across studies because of loss to follow-up, missed study visits, refusal to answer survey questions, or an unrecorded measurement during an office visit. One method of handling missing values is to simply delete observations for which there is missingness (called Complete Case Analysis). This is rarely used as deleting the data point containing missing data (List wise deletion) results in a smaller number of samples and thus affects accuracy. Additional methods of handling missing data exists, such as summarizing the variables with its observed values (Available Case Analysis). 

Motivated by the pervasiveness of missing data in the NHANES dataset, we will conduct an analysis of imputation methods under different simulated patterns of missing data. We will then apply these imputation methods to create a complete dataset upon which we can use ordinary least squares to predict blood pressure from diet and physical activity. 
