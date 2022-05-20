# BERT fine-tuning method for downstream tasks

파인 튜닝은 BERT를 처음부터 학습시키지 않는다는 것을 의마한다. 그 대신 사전 학습된 BERT를 기반으로 태스크에 맞게 가중치를 업데이트 하게된다.
이로써 Kaggle, Dacon과 같은 NLP_competition에서 가장 중요한 작업이라고 할 수 있을 것이다. (최근 몇년 NLP계열 S.O.T.A는 BERT가 싹쓸이하기 때문)

총 4가지의 다운스트림 태스크를 다룰 예정이다.

1. 텍스트 분류
2. 자연어 추론
3. 개체명 인식
4. 질문 - 응답
