# Toosin Patch Notes - Version 0002

전투 시스템의 체감 품질을 높이고, 메타 성장 시스템 도입 및 유저 피드백을 바탕으로 UI 및 편의성을 대폭 개선한 0002 업데이트 내역입니다.

---

## 1. 전투 및 조작 시스템 (Combat & Controls)

### 👊 초근접 피격 신뢰성 및 사거리 판정 개선

- **원인**: 무기마다 사거리가 다르고 공격 판정이 무기 끝부분에 집중되어 있어, 적과 너무 밀착할 경우 무기가 적의 충돌 영역을 지나쳐버리는 '관통 현상'이 확인되었습니다.
- **해결 방법**: 공격 시작 시 **구체형(Sphere) 보조 감지 로직(120cm)**을 도입했습니다. 이제 적과 완전히 밀착한 상태에서도 무기의 궤적에 상관없이 안정적으로 타격을 입힐 수 있습니다.

### 🛡️ 가드 메커니즘 개선 및 보상 정상화

- **가드 우선권 부여**: 공격 중 가드 입력 시 진행 중인 공격 동작을 즉시 취소하고 방어 태세로 전환하도록 개선되었습니다.
- **가드 경험치 버그 수정**: 아레나에서 가드 성공 시 경험치 보너스가 정상적으로 카운트되지 않던 고질적인 버그를 수정했습니다. 이제 적의 공격을 방어할 때마다 정당한 경험치 보상을 획득합니다.

### 🎥 카메라 락온 및 조작감 조정

- **개선 내용**: 카메라 고정(Lock-on) 시스템의 보간 수치를 조정하여 락온 상태에서도 카메라 무빙이 더 부드럽고 자유롭게 느껴지도록 최적화했습니다.

---

## 2. 메타 성장 시스템 (Meta-Progression)

### 🌟 계정 레벨 및 영구 스탯 보너스 도입

- **계정 레벨링**: 매 판 정산 시 획득한 인게임 경험치의 **10%가 계정 경험치(Account EXP)로 누적**됩니다.
- **영구 성장 요소**: 계정 레벨이 오를 때마다 다음 보상을 영구적으로 획득합니다 (사망 시에도 유지):
  - **영구 특성 포인트(PTP)**: 허브에서 사용 가능한 특성 포인트 1 획득.
  - **영구 능력치 보너스**: 계정 레벨당 **HP +10, SP +6, ATK +2, DEF +1**이 기본 능력치에 영구 가산됩니다.

### 📜 경험치 획득량 증가 시스템

- **특전 반영**: '경험치 획득량 증가' 특전(Perk) 또는 특성을 보유한 경우, 라운드 정산 결과에 해당 배율이 정상 적용되도록 로직을 보강했습니다. 이제 더 빠른 성장이 가능합니다.

---

## 3. 유저 인터페이스 및 비주얼 (UI & Visuals)

### 📊 경험치 결과창(Exp Summary) 전면 개편

- **수치 가독성 개선**: 라운드 종료 후 가드/패링 성공 횟수 및 그로 인한 추가 보너스 경험치를 실시간 애니메이션으로 확인할 수 있습니다.
- **레벨업 결과 요약**: 레벨업 시 상승한 스탯과 함께, 현재 계정 레벨로 인해 적용받고 있는 **영구 보너스 수치를 하단에 요약 표기**하도록 개선했습니다.

### ✨ 특성 트리 요구치 시각화

- **해결 방법**: 특정 티어 특성 해금에 필요한 최소 요구 포인트와 선행 조건을 각 노드에 명확히 표기하여 성장 계획 수립을 돕습니다.

### 🩸 비주얼 및 연출 보정

- **화면 효과**: 피격 시 블러드 스크린 효과의 앵커 설정을 수정하여 모든 해상도에서 자연스럽게 출력되도록 보정했습니다.
- **패링 연출**: 플레이어가 패링당했을 때의 리액션 애니메이션 속도를 조정하여 시각적인 인지력을 높였습니다.

---

## 4. 최적화 및 안정성 (Optimization)

### ⚙️ 그래픽 옵션 최적화

- **성능 개선**: 테스트 빌드에서 최대치로 고정되어 있던 그래픽 설정을 사양에 맞게 조정 가능하도록 최적화하고, 기본 엔진 설정을 보완하여 프레임 안정성을 확보했습니다.

---




## 결과 이미지

- Main

<img width="1904" height="861" alt="image" src="https://github.com/user-attachments/assets/10dcf699-27f7-43ed-8b81-279d7e3f9492" />

- Hub

<img width="1901" height="866" alt="image" src="https://github.com/user-attachments/assets/97e0e98c-1aec-46d8-b25e-579f3db0d0b5" />

- weapon select

<img width="1835" height="812" alt="image" src="https://github.com/user-attachments/assets/cfc7659c-c080-40f6-b2d9-9547c7f48db0" />

- Trait

<img width="1791" height="840" alt="image" src="https://github.com/user-attachments/assets/25368513-6d29-4d91-87a4-5b5eeae2f8b3" />

- Perk

<img width="1892" height="870" alt="image" src="https://github.com/user-attachments/assets/3035604e-9ade-4c5c-9438-aa7b826c7e09" />

- Stat

<img width="1893" height="866" alt="image" src="https://github.com/user-attachments/assets/9fca4b7c-f78c-428d-a1c9-fcdddf0b84bd" />

- Perk Select

<img width="1316" height="607" alt="image" src="https://github.com/user-attachments/assets/1dac5024-fe85-4fda-a6f6-8179910ca7ff" />

- Round Summary

<img width="1849" height="867" alt="image" src="https://github.com/user-attachments/assets/6efd1fad-f0af-451a-af09-7937242a8962" />


---
앞으로도 여러분의 소중한 피드백을 바탕으로 발전하는 투신이 되겠습니다. 감사합니다!  
*투신 개발팀*
