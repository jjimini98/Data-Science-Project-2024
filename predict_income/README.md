# 소득 예측 AI 해커톤

목표

1. 다양한 개인적 특성을 바탕으로 한 데이터를 활용하여 소득 수준을 예측하는 것
2. 다양한 개인적 특성 데이터를 분석하고 이해하는 능력을 키우며, 이를 통해 AI 역량과 경험을 한 단계 더 발전


평가 
- 평가산식 : RMSE
- Public Score: 전체 테스트 데이터 중 30%
- Private Score: 전체 테스트 데이터 중 70%


데이터 정보

train.csv [파일]

한 사람에 관련된 다양한 사회적, 경제적 정보

- ID : 학습 데이터 고유 ID
- Age
- Gender
- Education_Status
- Employment_Status
- Working_Week (Yearly)
- Industry_Status
- Occupation_Status
- Race
- Hispanic_Origin
- Martial_Status
- Household_Status
- Household_summary
- Citizenship
- Birth_Country
- Birth_Country (Father)
- Birth_Country (Mother)
- Tax_Status
- Gains
- Losses
- Divdends
- Incom_Status
- Income : 예측 목표, 1시간 단위의 소득을 예측


test.csv [파일]
한 사람에 관련된 다양한 사회적, 경제적 정보
- ID : 테스트 데이터 고유 ID
- Income이 존재하지 않음


sample_submission.csv [파일] - 제출 양식
- ID : 테스트 데이터 고유 ID
- Income : ID에 해당되는 Income을 예측하여 제출