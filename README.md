# OutcomesTAVIwithML
Machine learning based risk prediction of intrahospital clinical outcomes in patients undergoing TAVI

Abstract

Background: Currently, patient selection in TAVI is based upon a multidisciplinary heart team assessment of patient comorbidities and surgical risk stratification. In an era of increasing need for precision medicine and quickly expanding TAVI-indications, machine learning has shown promise in making accurate predictions of clinical outcomes. This study aims to predict different intrahospital clinical outcomes in patients undergoing TAVI using a machine learning-based approach. Main clinical outcomes include all-cause mortality, stroke, major vascular complications, paravalvular leakage, and new pacemaker implantations. 

Methods and results: The dataset consists of 451 consecutive patients undergoing elective TAVI between February 2014 and June 2016. The applied machine learning methods were neural networks, support vector machines, and random forests. Their performance was evaluated using 5-fold nested cross-validation. Considering all 83 features, the performance of all machine learning models in predicting all-cause intrahospital mortality (AUC 0.94 - 0.97) was significantly higher than both the STS risk score (p< 0.001), the STS/ACC TAVR score (p<0.001), and all machine learning models using baseline characteristics only (AUC 0.72-0.82). Using an Extreme Boosting Gradient, baseline Troponin T was found to be the most important feature among all input variables. Overall, after feature selection, there was slightly inferior performance. Stroke, major vascular complications, paravalvular leakage, and new pacemaker implantations could not be accurately predicted. 

Conclusions: Machine learning has the potential to improve patient selection and risk management of interventional cardiovascular procedures, as it is capable of making superior predictions compared to current logistic risk scores. 

In this GitHub Repository we make code used in this study available.

