

## 🎓 About LG Aimers
LG Aimers는 최고의 교수진이 함께 하는 AI교육과 LG의 실제 데이터를 다루는 AI해커톤에 참여할 수 있는 경험의 기회를 제공하는 LG그룹의 청년 교육 프로그램이다. LG AI연구원에서 진행하며 1개월의 온라인 교육과 1개월의 해커톤으로 구성된다. 해커톤에서는 LG의 여러 계열사가 보유한 다양한 산업의 현장 Data를 직접 다루고, 문제를 해결하는 실무 경험을 쌓을 수 있다.

LG Aimers 5기
주제: 제품 이상 여부 판별 AI 온라인 해커톤
기간: 2024.08.10~2024.08.30
결과: Public 0th, Private 0th

​최근 기계학습 모델의 발전과 함께 제품의 생산 단계에서 이상 여부를 미리 판단하려는 시도가 증가하고 있습니다.
이번 경진대회에서는 공정 과정의 여러 가지 데이터를 이용해 이상 여부를 판별하는 모델을 구현하고 그 성능을 비교하고자 합니다.


Model
LightGBM classifier & Lidge classifier [model.py]

Conclusion
Public score와 Private score의 큰 차이의 원인은 리더보드용 평가 데이터에 대한 overfitting으로 cross-validation을 하지않아 그런 것으로 사료됨.
