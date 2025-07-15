# OCD-Patient-Data-Analysis

# About Dataset
The "OCD Patient Dataset: Demographics & Clinical Data" is a comprehensive collection of information pertaining to 1500 individuals diagnosed with Obsessive-Compulsive Disorder (OCD). This dataset encompasses a wide range of parameters, providing a detailed insight into the demographic and clinical profiles of these individuals.
Included in this dataset are key demographic details such as age, gender, ethnicity, marital status, and education level, offering a comprehensive overview of the sample population. Additionally, clinical information like the date of OCD diagnosis, duration of symptoms, and any previous psychiatric diagnoses are recorded, providing context to the patients' journeys.
The dataset also delves into the specific nature of OCD symptoms, categorizing them into obsession and compulsion types. Severity of these symptoms is assessed using the Yale-Brown Obsessive-Compulsive Scale (Y-BOCS) scores for both obsessions and compulsions. Furthermore, it documents any co-occurring mental health conditions, including depression and anxiety
diagnoses. Notably, the dataset outlines the medications prescribed to patients, offering valuable insights into the treatment approaches employed. It also records whether there is a family history of OCD, shedding light on potential genetic or environmental factors. Overall, this dataset serves as a valuable resource for researchers, clinicians, and mental health professionals seeking to gain a deeper understanding of OCD
and its manifestations within a diverse patient population.

# Summary 

In this project, I analyzed a dataset of OCD patients that included demographic information, clinical history, symptom severity scores, and treatment details.

I performed exploratory data analysis to understand the distribution of age, gender, education, ethnicity, and other demographic factors. I also visualized clinical features such as obsession and compulsion types, Y-BOCS scores, and duration of symptoms.

I then cleaned and preprocessed the data, handled missing values, and encoded categorical variables to prepare the data for machine learning.

Using Random Forest and XGBoost models, I identified the most important features that influence medication assignment. I also evaluated model performance using accuracy scores and a confusion matrix.

Overall, the project gave me a strong understanding of how different factors are related to OCD symptom severity and treatment patterns.

# Conclusion

From this analysis, I observed that:

- Obsession and compulsion scores are strongly correlated, as expected in OCD patients.
- Certain obsession and compulsion types appear more commonly in specific genders.
- Medication distribution showed that SSRIs are the most frequently prescribed.
- Patients with anxiety or depression diagnoses tend to have more severe symptoms.
- The machine learning model showed that Y-BOCS scores and symptom duration were key predictors in medication assignment.

This analysis helps uncover patterns that could support more personalized treatment planning or future research directions in mental health.


Looking ahead, this project can be expanded in several ways to bring more business value and operational impact:

1. **Predictive Treatment Recommendations**  
   I can enhance the model to not just predict medications, but recommend the most effective medication based on patient history, symptom severity, and comorbidities. This could support personalized care plans and reduce trial-and-error prescribing, saving time and cost.

2. **Integrate Real-Time Clinical Data**  
   If connected to a live clinical system (like an EHR), this model could assist clinicians during consultations, flag high-risk patients, or suggest next steps — improving service quality and decision-making.

3. **Build a Clinician-Facing Dashboard**  
   A dashboard can be developed using Streamlit or Power BI where doctors, analysts, or healthcare managers can interact with the data, filter by patient group, and see insights dynamically — making the tool more practical and accessible.

4. **Cost Analysis and Optimization**  
   By adding medication costs and treatment outcomes, I could extend the project to help identify the most cost-effective treatments. This would help in reducing healthcare spending while maintaining or improving care quality.

5. **Patient Risk Scoring System**  
   Using the model's outputs, I can build a risk scoring system to flag patients likely to have severe OCD or high relapse probability — helping mental health providers allocate resources more efficiently.

6. **Scalable Model for Other Disorders**  
   This analytical framework could be adapted for other mental health conditions (like anxiety, depression, PTSD), making it scalable across a wider set of use cases for healthcare businesses or insurance providers.

These enhancements would make the project not just a research tool but a real clinical and operational asset for healthcare organizations.
