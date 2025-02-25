# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 오창원
- 리뷰어 : 손병진진


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 테스트 데이터셋 평가 정확도가 0.84로 기준인 80%보다 높은 성능을 보임.
        ![alt text](screenshot\image_1.png)
    - vocab_size와 토크나이저 학습 방식을 바꿔가며 실험해봄.
        ![alt text](screenshot\image_2.png)

    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 구현한 코드마다 테스트를 통해 해당 코드의 목적과 작동이 잘되는지 확인이 가능함.
        ![alt text](screenshot\image_3.png)
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나 새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 정상적인 학습이 진행이 안된 부분에 대한 설명과 상황이 잘 정리되어 있음.
        ![alt text](screenshot\image_4.png)
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 실험 결과와 생각을 정리해서 작성함.
        ![alt text](screenshot\image_5.png)
        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 모델 학습 시각화를 통해 이해하기 쉬움
        ![alt text](screenshot\image_6.png)


# 회고(참고 링크 및 코드 개선)
- 데이터 정제에서 단계별로 진행되어 보기가 편안했고 실수를 줄이는데 도움이 될거 같아 인상깊었습니다.
- SentencePiece 토크나이저 학습 방식을 BPE, N-gram 방식을 학습하여 비교한점이 미처생각하지못한 부분이라 흥미롭게 살펴볼 수 있었습니다.
- 실험부터 결론까지 깔끔하게 정리되어 있어 코드 리뷰하는데 편했습니다.
