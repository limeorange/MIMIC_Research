## 💡 DSML 학부 연구생 프로젝트
| No | Title | Conference | Date | Blog |
|:--:|:-----:|:----:|:----------:|:----:|
| 1 | Voting ensemble LSTM을 이용한 중환자실 EMR 폐렴 환자 생존예측 | 교내 Data Science 학회 | 2021.11 ||
| 2 | [중환자실 폐렴 환자에 대한 시뮬레이션 기반 시계열 사망 마커 탐지](https://github.com/limeorange/MIMIC_Research/tree/main/%EA%B5%AD%EB%82%B4_%ED%95%9C%EA%B5%AD%EC%A0%95%EB%B3%B4%EA%B3%BC%ED%95%99%ED%9A%8C) | 한국정보과학회 | 2022.06 ||
| 3 | Detection of Mortality Medical Markers for ICU Pneumonia Patients by Time-Series Feature Importance of LSTM Model | Journal of Biomedical Informatics | 2022.7 ||





<!-- 
## 💡 DSML 학부 연구생 프로젝트
### ☁️ 교내 Data Science 학회 
> Title : Voting ensemble LSTM을 이용한 중환자실 EMR 폐렴 환자 생존예측 (2021.11) -->
<!-- <img width="600" alt="스크린샷 2022-06-15 오후 5 05 26" src="https://user-images.githubusercontent.com/78308684/173775713-6bda8188-f53b-44d3-99ad-553140b716c2.png"> -->


<!-- ### ☁️ 국내 논문 - 한국정보과학회
> Title : 중환자실 폐렴 환자에 대한 시뮬레이션 기반 시계열 사망 마커 탐지 (2022.06) -->
<!-- <img width="600" alt="스크린샷 2022-06-15 오후 5 12 32" src="https://user-images.githubusercontent.com/78308684/173777118-7ac17aff-fdb1-4733-9ae7-b36e30ffae3d.png"> -->
<!-- <img width="600" alt="스크린샷 2022-06-15 오후 5 13 56" src="https://user-images.githubusercontent.com/78308684/173777394-598060f2-af6f-4c4d-8d17-8c539b9416c3.png"> -->
<!-- <img width="600" alt="스크린샷 2022-06-15 오후 5 13 25" src="https://user-images.githubusercontent.com/78308684/173777292-212bf67e-f092-48ab-a227-5bdeb6526b2a.png"> -->
<!-- ## 사진을 넣는다면 아래.. -->
<!-- <img width="600" alt="스크린샷 2022-06-15 오후 5 15 59" src="https://user-images.githubusercontent.com/78308684/173777863-0a614048-80e0-4133-8276-ee59c8cc029d.png"> -->


<!-- ### ☁️ 해외 논문 - Journal of Biomedical Informatics
> Title : Detection of Mortality Medical Markers for ICU Pneumonia Patients by Time-Series Feature Importance of LSTM Model -->

### ☁️ MIMIC_III
- [MIMIC-III Documentation](https://mimic.mit.edu/docs/iii/)
- MIMIC-III(Medical Information Mart for Intensive Care III)는 2001년부터 2012년까지 Beth Israel Deaconess Medical Center의 중환자실에 머물렀던 4만 명 이상의 환자에 대해서 중환자실 입원 기간동안 발생한 의료 이벤트를 추적 및 기록한 시계열 전자 의무 기록(EMR : Electronic Medical Record) 데이터이다. MIT Laboratory for Computational Physiology 연구실에서 익명화 및 구조화를 진행하고 2015년에 공개되었다.

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

