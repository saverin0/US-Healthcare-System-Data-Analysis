# A Two-Way ANOVA Analysis of Variations in U.S. Health Insurance Coinsurance Across Age Groups and Plan Types

## 📊 Project Overview
This project investigates the variations in U.S. health insurance coinsurance rates across **age groups** and **plan types** using **Two-Way ANOVA**. The study aims to uncover how these factors influence cost-sharing mechanisms and provide insights for designing equitable and affordable health insurance policies.

---

## ✨ Abstract
The U.S. healthcare system relies heavily on private insurance and cost-sharing mechanisms, often placing financial burdens on patients. This study uses **Two-Way ANOVA** to analyze the effects of **age groups** and **insurance plan types** on coinsurance rates. The results reveal that:
- **Plan type** significantly affects coinsurance rates (p < 0.05).
- **Age group** does not significantly affect coinsurance rates (p > 0.05).
- There is no significant interaction effect between age groups and plan types.

These findings emphasize the importance of plan type in cost-sharing mechanisms and provide actionable insights for policymakers and insurers.

---

## 🛠️ Methodology
### Data Collection
The data was sourced from the **U.S. Health Insurance Marketplace** (via Kaggle) and included three datasets:
1. **BenefitsCostSharing.csv**: Coinsurance details.
2. **Rate.csv**: Age groupings and rates.
3. **PlanAttributes.csv**: Insurance plan types (PPO, POS, HMO, EPO, Indemnity).

### Data Cleaning
- Standardized coinsurance descriptions into numeric values.
- Removed missing values and merged datasets.
- Binned ages into six groups: 0-20, 21-25, 26-40, 41-60, 61-64, 65+.

### Statistical Analysis
- **Two-Way ANOVA** was used to test the effects of age groups and plan types on coinsurance rates.
- Assumptions tested:
  - **Normality**: Verified using Q-Q plots and histograms.
  - **Homogeneity of Variance**: Tested using Levene's Test.

---

## 📈 Results
### Key Findings
1. **Plan Type**: Statistically significant effect on coinsurance rates (p < 0.05).
2. **Age Group**: No significant effect on coinsurance rates (p > 0.05).
3. **Interaction Effect**: No significant interaction between age groups and plan types (p > 0.05).

### Visualizations
- **Q-Q Plot**: Showed normal distribution of coinsurance rates.
- **Histogram**: Depicted bell-shaped distribution for some subgroups.

---

## 🏁 Conclusion
The study concludes that **plan type** significantly affects coinsurance rates, while **age group** does not. There is no interaction effect between age groups and plan types. These findings highlight the importance of plan type in cost-sharing mechanisms and provide insights for designing equitable and affordable health insurance policies.

Future work will explore **multiple regression models** to investigate the relationship between additional variables and coinsurance rates.

---

## 📚 References
1. Fundamentals of Statistics, John Wiley & Sons.  
2. "Understanding Two-Way ANOVA," YouTube.  
3. "Co-insurance," Healthcare.gov.  
4. "Understanding HMO, PPO, EPO, POS," UnitedHealthcare.  
5. R. D. Peng and E. Matsui, *The Art of Data Science*.  
6. CareerFoundry Blog: *The Data Analysis Process*.  
7. Statology: "Two-Way ANOVA in Excel."  
8. Scribbr: "Two-Way ANOVA."  

---

## 🔗 Additional Resources
- **Video Presentation**: [Watch here](https://drive.google.com/file/d/1EpJnIGnh_tcMwjZvERKL8j3Op2BXzzrm/view?usp=sharing)  
- **PowerPoint Presentation**: [View here](https://docs.google.com/presentation/d/18NPzqp9rfj6uuJFAQ3W3KdrVXGsIk5z6/edit?usp=sharing&ouid=102373423325166728202&rtpof=true&sd=true)  
- **Dataset**: [Access on Kaggle](https://www.kaggle.com/datasets/hhs/health-insurance-marketplace)  

---

## 👩‍💻 Authors
- **Abhishek Singh**  
  Data Science (M.Sc.), University of Europe for Applied Sciences, Potsdam, Germany  
  ✉️ Email: abhishek.singh@ue-germany.de  

- **Daniela Oliveira Rocha**  
  Data Science (M.Sc.), University of Europe for Applied Sciences, Potsdam, Germany  
  ✉️ Email: daniela.rocha@ue-germany.de  

- **Sarawut Boonyarat**  
  Data Science (M.Sc.), University of Europe for Applied Sciences, Potsdam, Germany  
  ✉️ Email: sarawut.boonyarat@ue-germany.de  

- **Mati Nakphon**  
  Data Science (M.Sc.), University of Europe for Applied Sciences, Potsdam, Germany  
  ✉️ Email: mati.nakphon@ue-germany.de  

- **Muthamizhan Alagu**  
  Data Science (M.Sc.), University of Europe for Applied Sciences, Potsdam, Germany  
  ✉️ Email: muthamizhan.alagu@ue-germany.de  

---

> *"Data is the new oil, and analysis is the refinery."*  
> — Group 6, University of Europe for Applied Sciences 🌟
