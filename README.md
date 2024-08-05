## 💡 DS&ML Undergraduate Researcher Project
> Title : Identification of Time-Series Pattern Marker in its Application to
Mortality Analysis of Pneumonia Patients in Intensive Care Unit


| No | Title | Conference | Date |
|:--:|:-----:|:----:|:----------:|
| 1 | [Identification of Time-Series Pattern Marker in Its Application to Mortality Analysis of Pneumonia Patients in Intensive Care Unit](https://www.mdpi.com/2075-4426/14/8/812) | Journal of Personalized Medicine | 2024.07 |
| 2 | [Simulation-Based Time-Series Death Marker Detection for ICU Pneumonia Patients](https://drive.google.com/file/d/1i3AKqFJbLsTTfpYngTa2-lX7DGGjcEW6/view?usp=sharing) | Korean Institute of Information Scientists and Engineers | 2022.06 |
| 3 | [Survival Prediction of ICU Pneumonia Patients Using Voting ensemble LSTM](https://drive.google.com/file/d/1t5TnVJJ1ao9-9NiLE6SR0nmTkkjBuQNj/view?usp=sharing) | USW Data Science Conference | 2021.11 |

### ☁️ MIMIC_III
- [MIMIC-III Documentation](https://mimic.mit.edu/docs/iii/)
- MIMIC-III (Medical Information Mart for Intensive Care III) is a time-series electronic medical record (EMR) dataset tracking and recording medical events during the ICU stays of more than 40,000 patients from 2001 to 2012 at the Beth Israel Deaconess Medical Center. It was anonymized and structured by the MIT Laboratory for Computational Physiology and released in 2015.

### ☁️ Used Tables
| No | Filename | Used Columns |
|:--:|:--------:|:------------:|
| 1 | [PATIENTS.csv](https://mimic.mit.edu/docs/iii/tables/patients/) | `SUBJECT_ID` / `EXPIRE_FLAG` |
| 2 | [D_ICD_DIAGNOSES.csv](https://mimic.mit.edu/docs/iii/tables/d_icd_diagnoses/) | `ICD9_CODE` / `SHORT_TITLE` / `LONG_TITLE` | 
| 3 | [PROCEDUREEVENTS_MV.csv](https://mimic.mit.edu/docs/iii/tables/procedureevents_mv/) | `SUBJECT_ID` / `STARTTIME` / `ENDTIME` / `ITEMID` |
| 4 | [ADMISSIONS.csv](https://mimic.mit.edu/docs/iii/tables/admissions/) | `SUBJECT_ID` / `DISCHTIME` |
| 5 | [PRESCRIPTIONS.csv](https://mimic.mit.edu/docs/iii/tables/prescriptions/) | `SUBJECT_ID` / `STARTDATE` / `ENDDATE` / `NDC` |
| 6 | [LABEVENTS](https://mimic.mit.edu/docs/iii/tables/labevents/) | `SUBJECT_ID` / `ITEMID` / `CHARTTIME` / `FLAG` |
| 7 | [DIAGNOSES_ICD](https://mimic.mit.edu/docs/iii/tables/diagnoses_icd/) | `SUBJECT_ID` / `ICD9_CODE` |
| 8 | [D_ITEMS](https://mimic.mit.edu/docs/iii/tables/d_items/) | `ITEMID` / `LABEL` |
| 9 | [D_LABITEMS](https://mimic.mit.edu/docs/iii/tables/d_labitems/) | `ITEMID` / `LABEL` / `LOINC_CODE` |

