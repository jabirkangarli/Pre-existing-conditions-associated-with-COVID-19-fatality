# Pre-existing-conditions-associated-with-COVID-19-fatality


Main hypothesis: The existence of pre-existing conditions or habits related to the respiratory tract increase the probability of fatality
Alternative hypothesis: the fatal outcome is not necessarily related to conditions related to the respiratory tract.



We will be using the following dataset from Kaggle:
#####https://www.kaggle.com/tanmoyx/covid19-patient-precondition-dataset?select=covid.csv



The dataset holds information about pre-existing conditions of patients from Mexico, such as asthma, obesity, hypertension, cardiovascular disease, Chronic obstructive pulmonary disease (copd), smoking habits, etc., and it was initially released by the Mexican government. The dataset contains also information such as age, gender, icu (intensive care unit) and date of death information which we can turn into a binary variable “death”.


The Coronavirus pandemic caught us all off-guard and one thing we learned from it is that our healthcare systems come short of providing a safety plan in case of such events. During the course of the pandemic there were multiple reports that certain demographic and clinical characteristics may lead infected patients to more severe symptoms.
In order to observe associations between the pre-existing conditions and the fatality of the virus, we will use a binary logistic regression with variable “death” as the depended one.
Our main hypothesis is that the existence of pre-existing conditions or habits related to the respiratory tract such as pneumonia, asthma, copd and smoking habit increase the probability of fatality.
