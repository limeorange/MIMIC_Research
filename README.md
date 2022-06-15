# 🔎 DSML 학부 연구생 프로젝트 💡
## 1. Data Science 학회
> Voting ensemble LSTM을 이용한 중환자실 EMR 폐렴 환자 생존예측
> 
<img width="850" alt="스크린샷 2022-06-15 오후 4 05 02" src="https://user-images.githubusercontent.com/78308684/173764028-249a8ea2-df7a-4b9e-afcb-eb5aa159e293.png">


* 2021.06 ~ 
* 추후 국내/해외 논문을 목표로 함.
* MIMIC_III 데이터를 사용하여 mortality prediction 모델을 구축한 후 생존에 영향을 미치는 feature 선별하는 연구 


### 📄 MIMIC_III DATA
[MIMIC-III documentation](https://mimic.mit.edu/docs/iii/) <br>
MIMIC-III (Medical Information Mart for Intensive Care III) is a large, freely-available database comprising deidentified health-related data associated with over forty thousand patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012.
The database includes information such as demographics, vital sign measurements made at the bedside (~1 data point per hour), laboratory test results, procedures, medications, caregiver notes, imaging reports, and mortality (both in and out of hospital).

### 📊 사용 Table

- PATIENTS (SUBJECT_ID, EXPIRE_FLAG)
- ADMISSION (SUBJECT_ID, DISCHTIME)
- D_ICD_DIAGNOSES (SHORT_TITLE, ICD9_CODE) - 폐렴 병명 코드 추출에 사용
- D_ICD_DIAGNOSES (SUBJECT_ID, ICD9_CODE) - 폐렴 환자 추출
- LABEVENTS (SUBJECT_ID, ITEMID, CHARTTIME, FLAG)
- [생성] 폐렴환자lab.csv (7799, 690), 폐렴환자.csv (7807, 8)
- PRESCRIPTIONS( ) - Feature 추가에 사용
- PROCEDUREEVENTS_MV( ) - Feature 추가에 사용
