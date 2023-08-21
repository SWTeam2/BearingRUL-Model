# BearingRUL-Model
- 디지털 대시보드 서비스 제공을 위한 Bearing RUL 예측 모델
- dataset: [IEEE phm 2012 data challenge](https://www.kaggle.com/datasets/alanhabrony/ieee-phm-2012-data-challenge)

## file description
### Jupyter Notebooks
1. EDA.ipynb
   - you can get dataset plots

### utils
1. merge_csv.ipynb
   - merge all .csv files on each bearing
   - change timestamp to datetime from accelaration .csv files
   - create folders for merged data
2. load_data
   - load_csv: load the merged CSV files and save them in a class

## data processing
1. 데이터 증강

## Results

## Acknowledgement
```
“본 연구는 과학기술정보통신부 및 정보통신기획평가원의 SW전문인재양성사업의 연구결과로 수행되었음“(2022-0-01127)
```