# Predicting_Maternal_Health_Risk-Group work
# INTRODUCTION

Pregnancy is a time of great change for a woman's body, marked by both significant physical and
emotional changes. According to the WHO, it was estimated that almost 300,000 women died
from pregnancy-related causes in 2017 with approximately 830 women dying from preventable
causes related to pregnancy and childbirth every day (WHO | Regional Office for Africa, 2023).
Hence, ensuring the well-being of both the expectant mother and the developing fetus is very
important during this time. The analysis used the Maternal Health Risk Dataset which consisted
of a collection of data that can be used to identify factors that may put a pregnant woman at
risk. A decision tree model was used to analyze the data and identify the most important risk
factors associated with maternal risk levels, with the primary aim of identifying significant
factors that effectively predict maternal health risk levels during pregnancy.

# AIM

To identify and explore the key factors that predict health maternal risk levels using the
Maternal Health Risk Dataset with a focus on a Decision Tree model.

# MATERIALS
We used the dataset of Maternal Health Risk obtained from the UC Irvine Machine Learning
Repository website. This dataset consists of 1013 participants and the features that were
explored include; age, diastolic blood pressure, systolic blood pressure, blood sugar, body
temperature, and heart rate with our target variable, “risk level”.

# RESULTS AND DISCUSSION
The decision tree model offers detailed risk level predictions, classifying pregnant women into
three distinct categories: low, mid, and high risk as seen in figure 1. These predictions are based
on specific thresholds applied to critical maternal health indicators. After running the decision
tree model, the model chose the feature that best discriminates between the different risk
levels on each split. The model predicted that a woman with blood sugar levels less than or
equal to 7.95 mmol/L has a mid-risk level for maternal health complications, given that the
systolic blood pressure is also less than or equal to 132.5 mmHg, and body temperature is less
than or equal to 99.5F. However, if any of these features is greater than the threshold value,
then the woman is likely to be at a high-risk level.

Women with blood sugar levels greater than 7.95 mmol/L were also predicted to be at mid-risk
for maternal health complications unless their systolic blood pressure was greater than 125.0
mmHg. In this case, their risk level increases to high. Whereas, women with systolic blood
pressure less than or equal to 125.0 mmHg are at mid-risk for maternal health complications
unless their heart rate is greater than 83 bpm then the risk level increases to high.
Women at an age less than or equal to 41 years old were predicted to be at low risk for
maternal health complications unless their systolic blood pressure was greater than 125.0
mmHg, then their risk level increased to high. Whereas, women at an age greater than 41 years
old are at high risk for maternal health complications, regardless of the other features.
According to the study (Cavazos-Rehg et al., 2014), on “Maternal age and risk of labor and
delivery complications”, women who were above the age of 40 were associated with increased
odds of maternal health risks such as mild preeclampsia, fetal distress, and poor fetal growth.

Overall, the model has shown systolic blood pressure as the most key factor with values equal
to or above 135.0 mmHg signifying a high risk. In addition, the model highlighted the relevance
of blood sugar levels, body temperature, and age in assessing maternal health risks. Hence, the
model aids in identifying pregnant women with high systolic blood pressure, increased blood
sugar levels, high body temperature, or advanced age as being at a high risk of experiencing
maternal health complications during pregnancy

# IMPLICATIONS
The success of the decision tree model development and performance bring about the
significant implications for healthcare, research, and public health. By taking in account
features such as blood sugar, systolic blood pressure, body temperature, heart rate, and age, the
model provides a practical method for assessing maternal health risk, which can be used by
professionals to identify mothers who are at high risk for complications during pregnancy and to
provide them with additional support and care . For instance, in a case where woman is

experiencing high blood pressure and have too much protein in her urine due to medical history
of chronic hypertention, or diabetes, kidney disease, or having twins or is a first time mom or
obese, this model can be used to predict if she is at a risk of developing a complication such as
Preeclampsia or have chances of having preterm delivery (CDC, 2023). And this can also help in
tracking the progress of pregnant women to check if they are developing any maternal
complication, thus aiding for the development of educational materials for them, so that they
can be aware of the risk factors for maternal health complications and take steps to reduce their
risk.

# CONCLUSION
The analysis aimed at identifying key factors key factors that predict health maternal risk levels.
Overall, the decision tree model provides a valuable tool for assessing maternal health risk
during pregnancy, considering factors like blood sugar, blood pressure, body temperature, age,
and heart rate. While the model effectively categorizes low and high risk cases, there is room
for improvement in mid-risk predictions. Nonetheless, its implications are significant, offering
healthcare professionals a means to identify and support high-risk pregnant women. It can also
aid in monitoring pregnant women's progress and promoting awareness of maternal health
risks. However, further research and refinement are recommended to enhance its performance
in high-risk cases.
