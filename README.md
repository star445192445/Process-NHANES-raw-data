This project shows the process of NHANES variable preprocessing.
### File structure
Process-NHANES-raw-data <br>
├─0708NHANES<br>
│  ├─alcohol<br>
│  ├─Blood Pressure <br>
│  ├─Body Measure <br>
│  ├─Cholesterol <br>
│  ├─CRP <br>
│  ├─Demograph <br>
│  ├─Diabetes <br>
│  ├─Diet <br>
│  ├─HbA1c <br>
│  ├─Medical Conditions <br>
│  ├─Mental <br>
│  ├─Mortality <br>
│  ├─Physical <br>
│  ├─Sleep <br>
│  └─Smoking <br>
├─0910NHANES <br>
│  ├─Alcohol <br>
│  ├─Blood Pressure <br>
│  ├─Body Measure <br>
│  ├─Cholesterol <br>
│  ├─CRP <br>
│  ├─Demograph <br>
│  ├─Diabetes <br>
│  ├─Diet <br>
│  ├─HbA1c <br>
│  ├─Medical Conditions <br>
│  ├─Mental <br>
│  ├─Mortality <br>
│  ├─Physical <br>
│  ├─Sleep <br>
│  └─Smoking <br>
| 07080910 MERGE.ipynb <br>

1. Each folder of 0708NHANES and 0910NHANES represents the extraction and preprocessing of the corresponding category features.
2. After running the above files in sequence, run 07080910 merge.ipynb to MERGE two years of data.
3. The address in the file can be changed to your own file path.
