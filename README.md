<img width="763" alt="front" src="https://github.com/SWTeam2/Data_preprocessing/assets/139730231/5920ef27-f4a4-49b6-af37-ac67fd3efa73">

# Data preprocessing
시계열 데이터 증강기법들에 대한 코드들입니다. 

노이즈를 추가하거나, 슬라이딩 윈도우를 이용해 비슷하지만 다른 데이터를 만들어 모델의 정확도를 높이는데 사용됩니다.

## Data report
- 디지털 대시보드 서비스 제공을 위한 Bearing RUL 예측 모델
- dataset: [IEEE phm 2012 data challenge](https://www.kaggle.com/datasets/alanhabrony/ieee-phm-2012-data-challenge)

## file description
### Augmentation
1. [CNN_LSTM_DataSet_Preparation.ipynb](augmentation/CNN_LSTM_DataSet_Preparation.ipynb)
   
2. [Delete_noisy.ipynb](augmentation/Delete_noisy.ipynb)
   
3. [G_Noisy.ipynb](augmentation/G_Noisy.ipynb)
   
4. [Noisy_data_pkz.ipynb](augmentation/Noisy_data_pkz.ipynb)
   
5. [sliding.ipynb](augmentation/sliding.ipynb)
   
### EDA
[EDA.ipynb](EDA.ipynb)

진동 시계열 데이터 시각화 코드입니다.

<div>
	<h3>📚 Tech Stack 📚</h3>
	<p>✨ Platforms & Languages ✨</p>
   <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
</div>


## Process
- data augmentation
   1. noise addition method
   2. window sliding method 
- EDA

## Example of EDA result
- example of training data
![example of training data](image-1.png)
-  example of test data
![example of test data](image-2.png)

## Acknowledgement
```
“본 연구는 과학기술정보통신부 및 정보통신기획평가원의 SW전문인재양성사업의 연구결과로 수행되었음“(2022-0-01127)
```
