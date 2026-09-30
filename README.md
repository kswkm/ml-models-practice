# Machine Learning Models Practice

머신러닝 알고리즘을 학습하는 프로젝트입니다.

## 설치
Python 3.9 ~ 3.11이 필요합니다.
```bash
pip install -r requirements.txt
```

## 사용
저장소 루트에서 Jupyter를 실행한 뒤 notebooks 폴더의 노트북을 여세요.
```bash
jupyter lab
```
노트북은 저장소의 `data/` 폴더에서 데이터를 읽으므로 파일을 따로 업로드할 필요가 없습니다.
각 노트북 상단의 Colab 배지로 열면 저장소를 자동으로 복제해 같은 경로를 사용합니다.

## 데이터
```
data/
├── raw/   # 학습용 데이터
│   ├── diabetes.csv         (Diabetes)
│   └── penguins_size.csv    (KNN)
└── new/   # 학습된 모델로 예측해 볼 새 데이터
    ├── new_diabetes.csv     (Diabetes)
    └── penguin_new.csv      (KNN)
```

Decision Tree 노트북이 쓰는 호텔 만족도 데이터는 저장소에 포함되어 있지 않습니다.
Kaggle에서 **Europe Hotel Booking Satisfaction Score** 데이터셋을 내려받아
`data/raw/Europe Hotel Booking Satisfaction Score.csv`로 저장한 뒤 실행하세요.

## 모델
- Decision Tree (호텔 만족도 분류)
- KNN (펭귄 성별 분류)
- Diabetes Prediction (로지스틱 회귀, SMOTE)
- CNN (MNIST 손글씨 숫자 분류)
