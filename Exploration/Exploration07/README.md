# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 이창훈
- 리뷰어 : 신대웅


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 Loss의 시각화와 Extractive 및 Abstractive 방식 비교 등을 충실히 이행하였음
    - Loss를 시각화하는 부분에서 이론에 적합하도록 Loss를 줄였다는 측면에서 모델의 오류가 없었음을 확인하였음
    - <img width="830" height="600" alt="image" src="https://github.com/user-attachments/assets/e33e558b-2941-45be-be58-2cb2b437e85f" />

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 주석을 통하여 기술하여 코드에 대한 이해가 수월하였음
    - 디코더와 인코더 입력 정의가 이 코드 설계의 핵심이라고 판단되며 토크나이저 정의 등 오류 없이 수행하였음
    - <img width="847" height="111" alt="image" src="https://github.com/user-attachments/assets/813db094-c1b1-4f02-80b9-99b1830ead8a" />

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정이 코드 실행 플로우를 통해 잘 드러나있고 평가 기준에 부합하도록 실험을 수행하였음
    - 새로운 시도나 추가 실험을 수행하지 않았으나 모델의 오류가 없음을 보여줌
    - 에러 부분을 지우지 않고 문제를 해결하고자 시도한 기록들이 보여짐
    - <img width="826" height="227" alt="image" src="https://github.com/user-attachments/assets/5b11ba73-95a1-4a6b-9f4f-ca63ae762582" />

- [ ]  **4. 회고를 잘 작성했나요?**
    - 필요한 부분을 시각화하여 이해를 시키는 것에 도움을 주었음
    - <img width="688" height="580" alt="image" src="https://github.com/user-attachments/assets/dadce733-9b43-4980-839e-7dd6657d25bd" />
    - 주어진 문제를 해결하는 완성된 코드또는 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등을 기록한 회고가 추가되었으면 더 질 높은 프로젝트 결과물이 될 것으로 기대함

- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화 및 모듈화하고자 스텝별로 코드의 실행 순서를 분류하였음
    - <img width="831" height="352" alt="image" src="https://github.com/user-attachments/assets/c9377709-eec2-4a47-b0e8-8c43259817b9" />



# 회고(참고 링크 및 코드 개선)
```
# 노드 학습의 플로우에 맞춰 코드 설계가 코드의 형식이 정형화되어 학습하기에 좋았음
# 특히, Step별로 코드의 실행 순서를 분류하여 리뷰어가 검토하기에 어려움이 없도록 쉽게 설계하였다는 점에서 배울 점이 많았음
```
