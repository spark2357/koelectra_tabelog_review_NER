# koelectra_tabelog_review_NER
monologg/koelectra-base-v3-discriminator를 크롤링한 타베로그 리뷰 데이터로 파인튜닝한 모델

🤗 5gidong/kcelectra_review_ner
https://huggingface.co/5gidong/kcelectra_review_ner

## 준비한 데이터셋 중 일부만 라벨링 후 태그 통계
https://github.com/spark2357/koelectra_tabelog_review_NER/blob/main/analyze_dataset.ipynb
<img width="1389" height="989" alt="image" src="https://github.com/user-attachments/assets/34823c79-df0a-4169-941e-4613a9f7dc13" />

## 학습 후 정확도 통계
https://github.com/spark2357/koelectra_tabelog_review_NER/blob/main/analyze_trained_model.ipynb
<img width="798" height="778" alt="image" src="https://github.com/user-attachments/assets/cef56254-dc80-4c22-9557-2a8cd012a5c6" />

- 라벨링한 데이터셋에서 수가 적은 AMB(분위기), PP(인원수) 태그의 정확도가 현저히 낮다.
- 대부분 MENU(메뉴)와 EXP(경험)로 잘못 판정되었다.
