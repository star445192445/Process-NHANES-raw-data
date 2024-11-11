This project shows the process of NHANES variable preprocessing.
### File structure
Process-NHANES-raw-data
├─0708NHANES
│  ├─alcohol
│  ├─Blood Pressure
│  ├─Body Measure
│  ├─Cholesterol
│  ├─CRP
│  ├─Demograph
│  ├─Diabetes
│  ├─Diet
│  ├─HbA1c
│  ├─Medical Conditions
│  ├─Mental
│  ├─Mortality
│  ├─Physical
│  ├─Sleep
│  └─Smoking
├─0910NHANES
│  ├─Alcohol
│  ├─Blood Pressure
│  ├─Body Measure
│  ├─Cholesterol
│  ├─CRP
│  ├─Demograph
│  ├─Diabetes
│  ├─Diet
│  ├─HbA1c
│  ├─Medical Conditions
│  ├─Mental
│  ├─Mortality
│  ├─Physical
│  ├─Sleep
│  └─Smoking
| 07080910 MERGE.ipynb

1. Each folder of 0708NHANES and 0910NHANES represents the extraction and preprocessing of the corresponding category features.
2. After running the above files in sequence, run 07080910 merge.ipynb to MERGE two years of data.
3. The address in the file can be changed to your own file path.
