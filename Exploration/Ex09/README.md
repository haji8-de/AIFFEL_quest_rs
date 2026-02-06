
# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 하지양
- 리뷰어 : 신대웅


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 주어진 프로젝트 제출 루브릭을 모두 충족하였고 한국어 답변을 출력하는 모델 수준까지 구현하였음
    - <img width="852" height="457" alt="image" src="https://github.com/user-attachments/assets/0640bffe-8bff-4600-8763-7f3dc0944b7a" />
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술하였으며, 주석을 보고 코드에 대한 이해가 수월하였음
    - 해당 코드 설계에서는 전처리 과정 후 인코딩, 디코딩, 토크나이징이 핵심이며 모델이 정상적으로 수렴하도록 하였음(모델의 Loss가 학습시 감소하는 추세로 판단하였음)
    - <img width="807" height="792" alt="image" src="https://github.com/user-attachments/assets/b5dcd947-014b-4355-a3d2-fa01a3a2cb93" />

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 특히, 2가지 대답을 반복하고 있는 문제를 해결하기 위한 시도가 가장 뚜렷하게 잘 설명하고 보였음
    - <img width="869" height="838" alt="image" src="https://github.com/user-attachments/assets/225defa6-8ab1-407f-bde3-a88afe4ddfbd" />

- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 및 프로젝트 결과물에 대해 설정 기록과 결과 정리를 충실히 수행하여 리뷰어가 검토하기에 어려움이 없었음
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화 및 모듈화하였음
    - 노드 학습 내용을 잘 숙지하고 높은 이해도로 정형화된 코드를 설계하였음
    - 중<img width="855" height="334" alt="image" src="https://github.com/user-attachments/assets/d48b2e54-faa3-4119-abf9-1f3a535a838b" />



# 회고(참고 링크 및 코드 개선)
```
# Loss와 Accuracy의 그래프를 분석하여 Epochs를 20으로 설정한 점에서 체계적인 실험을 계획하여 배울점이 많았음
# 본 리뷰어와 차이점은 레이어 층수를 2로 설정하고 에폭수 20으로 설정한 점에서 다른 실험 조건의 사례를 잘 보여주었음
# 시간이 더 주어진다면 인코더-디코더 수정을 통하여 더 맥락에 적합한 한국어 트랜스포머 모델을 구현할 수 있을 것으로 기대함
<img width="761" height="306" alt="image" src="https://github.com/user-attachments/assets/abbecee6-1be4-4c28-b39e-7d1926c37916" />

```
