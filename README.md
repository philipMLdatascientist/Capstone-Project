### Project Title

Machine Learning and Deep Learning to Predict Patient Mortality

https://github.com/philipMLdatascientist/Capstone-Project/blob/main/MIMMIC.ipynb

**Author**
 
Philip Hernandez, APRN

#### Executive summary 

It is critical to predict mortality of in-hospital patients. Consequently, it is difficult to accurately predict mortality of a given patient population within a specific period. The goal of this project is to predict in-hospital mortality of critically-ill patients with sufficient accuracy and identify the specific factors that contribute to the model's predictive power.

#### Rationale

The recent pandemic has highlighted the value of timely and expert management of scarce critical care beds and the medical/nursing/support staff and equipment required for these beds. These expensive and scarce resources demand that efficient evidence-based management using all available methodology including artificial intelligence be investigated.

#### Research Question

Can patient demographics, medical history, admission context, and clinical/laboratory data be used to create a machine/deep learning model to accurately predict in-hospital patient mortality?

#### Data Sources

This is an investigation using the Medical Information Mart for Intensive Care (MIMIC) database. MIMIC is a large, single-center database comprising information relating to patients admitted to critical care units at a large tertiary care hospital. Data includes vital signs, medications, laboratory measurements, observations and notes charted by care providers, fluid balance, procedure codes, diagnostic codes, imaging reports, hospital length of stay, survival data, and more. This database is associated with 53,423 distinct hospital admissions for adult patients over a 11-year period from 2001 and 2012. The tertiary center is Beth Israel Deaconess Medical Center in Boston, Massachusetts and the data base is administered by the Laboratory for Computational Physiology at Massachusetts Institute of Technology.

#### Methodology

I will be using cloud-based SQL to access the relational databases, exploratory data analysis to explore and clean the data, possibly use natural language processing to find important clinical information within the daily progress notes, model different machine/deep learning algorithms using ensemble methodologies, feature engineering, ETL pipelines, and compare/contrast the predictive power of different models.

#### Expected Results

I expect that patients with higher acuity scores, outlier demographics, or demonstrate extremes of clinical/laboratory data are most likely to have a higher probability of in-hospital mortality.

# Impression

- Unfortunately, every single model had produced a negative R2. Therefore, I can conclude that each model (given its constraints and the data that was provided) fits very poorly.
- The models are insufficient to recommend any changes to hospital practices and more data is needed to be able to predict in-hospital patient mortatilty.
