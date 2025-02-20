# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 양건우
- 리뷰어 : 리뷰어의 이름을 작성하세요.

## 정보구조도 (보다 자세한 설명은 와이어 프레임 상에 표시해 두었음)

![스크린샷 2025-02-03 오후 6 08 35](https://github.com/user-attachments/assets/d4b25f0f-d07f-4837-b94d-570c3864edcf)

## 와이어프레임

![스크린샷 2025-02-03 오후 6 09 21](https://github.com/user-attachments/assets/704712f0-562f-4b05-a0ba-c4995a7c9ee3)

## 프로토타이핑

![프로토타이핑](https://github.com/user-attachments/assets/c44b0057-b303-4ca0-8344-8d38ca98eb3f)

## 프로토타이핑 시연

![프로토타이핑 시연](https://github.com/user-attachments/assets/c8c20449-4ab5-4b78-98ee-6a5b324d38e1)

## 플러터 : 다트파일 첨부 (Project.Run.dart)

구현한 3가지 주요 기능
1) 일반인, 선수용 테스트 각각 창 구성
2) VO2max 테스트 진행 및 결과표
3) '러닝 시작' 화면에서 5가지 러닝 타입 선택

## 플러터 구동


![플러터 구동](https://github.com/user-attachments/assets/8fabd810-435a-41cf-86f7-f99e13003ad2)


## 회고

상상만했던 앱을 직접 구상하고 구현해내는 경험은 좋았다.
머리로만 상상하던 것을 와이어프레임을 짜고 프로토 타이핑을 하므로서 제법 콘티다운 콘티를 만들 수 있었다.
그러나, 플러터에서 직접 코드를 짤때 좌절할 수밖에 없었다.
챗GPT의 도움을 받기 위해 요구사항을 얘기했을떄 누락된 부분이 상당부분 있었고 보충을 요구할때마다 기존 코드를 삭제하는 상황이 자주 발생했다.
그래도 배운 내용을 바탕으로 짜준 코드를 하나하나 점검하고 수정해나갈 수 있었다.
아직 생각한 모든 부분을 구현해내지는 못했지만 나름 생각했던 화면을 코드로 짜고 구동을 시켜볼 수 있어서 좋았다.

- 오늘 학습한 내용 중 가장 유용했던 점: 와이어프레임과 프로토타이핑으로 콘티에 대한 가독성이 높아졌다.
- 어려웠던 부분과 해결 방법: 콘티를 앱으로 정확히 구현하기 위해서는 플러터 코딩 공부가 더 많이 필요할 거 같다.
- 앞으로 더 학습이 필요한 부분: 플러터 코딩
- 학습한 내용을 실제 프로젝트에 어떻게 적용할 수 있을지: 콘티 내용을 점차 추가해 나가야겠다.

# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
