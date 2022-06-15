## 💡 DSML 학부 연구생 프로젝트
### ☁️ 교내 Data Science 학회 
> Title : Voting ensemble LSTM을 이용한 중환자실 EMR 폐렴 환자 생존예측 (2021.11)

### ☁️ 국내 논문 - 한국정보과학회
> Title : 중환자실 폐렴 환자에 대한 시뮬레이션 기반 시계열 사망 마커 탐지 (2022.06)

### ☁️ 해외 논문 - Journal of Biomedical Informatics
> Title : Detection of Mortality Medical Markers for ICU Pneumonia Patients by Time-Series Feature Importance of LSTM Model

<br>

### 📄 [MIMIC_III](https://mimic.mit.edu/docs/iii/)
MIMIC-III(Medical Information Mart for Intensive Care III)는 2001년부터 2012년까지 Beth Israel Deaconess Medical Center의 중환자실에 머물렀던 4만 명 이상의 환자에 대해서 중환자실 입원 기간동안 발생한 의료 이벤트를 추적 및 기록한 시계열 전자 의무 기록(EMR : Electronic Medical Record) 데이터이다. MIT Laboratory for Computational Physiology 연구실에서 익명화 및 구조화를 진행하고 2015년에 공개되었다.

### 💧 Used Tables
1) [PATIENTS.csv](https://mimic.mit.edu/docs/iii/tables/patients/) - `SUBJECT_ID` / `EXPIRE_FLAG`
2) [D_ICD_DIAGNOSES.csv](https://mimic.mit.edu/docs/iii/tables/d_icd_diagnoses/) - `ICD9_CODE` / `SHORT_TITLE` / `LONG_TITLE`
3) [PROCEDUREEVENTS_MV.csv](https://mimic.mit.edu/docs/iii/tables/procedureevents_mv/) - `SUBJECT_ID` / `STARTTIME` / `ENDTIME` / `ITEMID`
4) [ADMISSIONS.csv](https://mimic.mit.edu/docs/iii/tables/admissions/) - `SUBJECT_ID` / `DISCHTIME`
5) [PRESCRIPTIONS.csv](https://mimic.mit.edu/docs/iii/tables/prescriptions/) - `SUBJECT_ID` / `STARTDATE` / `ENDDATE` / `NDC`
6) [LABEVENTS](https://mimic.mit.edu/docs/iii/tables/labevents/) - `SUBJECT_ID` / `ITEMID` / `CHARTTIME` / `FLAG`
7) [DIAGNOSES_ICD](https://mimic.mit.edu/docs/iii/tables/diagnoses_icd/) - `SUBJECT_ID` / `ICD9_CODE`
8) [D_ITEMS](https://mimic.mit.edu/docs/iii/tables/d_items/) - `ITEMID` / `LABEL`
9) [D_LABITEMS](https://mimic.mit.edu/docs/iii/tables/d_labitems/) - `ITEMID` / `LABEL` / `LOINC_CODE`
