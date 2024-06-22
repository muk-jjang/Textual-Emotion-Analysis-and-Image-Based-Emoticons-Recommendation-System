# Textual-Emotion-Analysis-and-Image-Based-Emoticons-Recommendation-System
## 접근 방법
- 감정에 맞게 이모티콘을 추천해주는 것이므로 다중 분류모델로 학습
- 추분한 대화 데이터셋 확보가 어려워 사전 훈련이 된 모델(koBERT) 사용
---
## Datasets
✔ 1. 한국어 감정 정보가 포함된 단발성 대화 데이터셋
- (https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100)

✔ 2. 한국어 감정 정보가 포함된 연속적 대화 데이터셋
- (https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100)

✔ 3. 감성대화 말뭉치
- (https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100)

✔ 4. 온라인 구어체 말뭉치 데이터
- (https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=625)
---
## 당시 Trouble Shooting
- 충분한 데이터셋 확보가 어려워 GPT API를 활용한 감정라벨링
- 기존의 데이터셋 일부를 label로 프롬프트를 준 후 다른 데이터셋을 해당 형식에 맞게 라벨링
---
## OUTPUT
![image](https://github.com/muk-jjang/Textual-Emotion-Analysis-and-Image-Based-Emoticons-Recommendation-System/assets/122384236/1bc4d554-e663-41a2-a260-7dc16a9bd86f)

