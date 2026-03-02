# TOOSIN 📝 패치노트

---

<details>
<summary><b>[📝Patch_Ver_0002] 상세 패치 내역 보기 (클릭)</b></summary>

전투 시스템의 체감 품질을 높이고, 메타 성장 시스템 도입 및 유저 피드백을 바탕으로 UI 및 편의성을 대폭 개선한 0002 업데이트 내역입니다.

[📸 결과 이미지 바로가기](#v0002-결과-이미지)

---

### 1. 전투 및 조작 시스템 (Combat & Controls)

#### 👊 초근접 피격 신뢰성 및 사거리 판정 개선

- **원인**: 무기마다 사거리가 다르고 공격 판정이 무기 끝부분에 집중되어 있어 밀착 시 '관통 현상' 발생.
- **해결 방법**: 공격 시작 시 **구체형(Sphere) 보조 감지 로직(120cm)**을 도입했습니다.

#### 🛡️ 가드 메커니즘 개선 및 보상 정상화

- **가드 우선권 부여**: 공격 중 가드 입력 시 즉시 방어 태세로 전환됩니다.
- **가드 경험치 버그 수정**: 아레나에서 가드 성공 시 경험치 보너스가 정상적으로 카운트됩니다.

#### 🎥 카메라 락온 및 조작감 조정

- **개선 내용**: 락온 상태에서도 카메라 무빙이 더 부드럽고 자유롭게 느껴지도록 보간 수치를 조정했습니다.

---

### 2. 메타 성장 시스템 (Meta-Progression)

#### 🌟 계정 레벨 및 영구 스탯 보너스 도입

- **계정 레벨링**: 매 판 획득한 인게임 EXP의 **10%가 계정 경험치(Account EXP)로 누적**됩니다.
- **영구 성장 요소**: 계정 레벨당 **HP +10, SP +6, ATK +2, DEF +1** 및 **영구 특성 포인트(PTP)**를 획득합니다.

#### 📜 경험치 획득량 증가 시스템

- **특전 반영**: '경험치 획득량 증가' 특전/특성 보유 시 배율이 정상 적용됩니다.

---

### 3. 유저 인터페이스 및 비주얼 (UI & Visuals)

#### 📊 경험치 결과창(Exp Summary) 전면 개편

- **수치 가독성 개선**: 실시간 애니메이션으로 보너스 경험치를 확인하고 하단에서 **영구 보너스 요약**을 볼 수 있습니다.

#### ✨ 특성 트리 요구치 시각화

- **해결 방법**: 특정 티어 특성 해금에 필요한 최소 요구 포인트와 선행 조건을 명확히 표기합니다.

#### 🩸 비주얼 및 연출 보정

- **화면 효과**: 블러드 스크린 앵커 수정 및 패링 리액션 애니메이션 속도 최적화.

---

### 4. 최적화 및 안정성 (Optimization)

- **그래픽 옵션 최적화**: 테스트 빌드 설정 보완 및 프레임 안정성 확보.

---

<h3 id="v0002-결과-이미지">🖼️ V0002 결과 이미지</h3>

#### [Main Menu]

![Main](https://github.com/user-attachments/assets/10dcf699-27f7-43ed-8b81-279d7e3f9492)

#### [Hub Level]

![Hub](https://github.com/user-attachments/assets/97e0e98c-1aec-46d8-b25e-579f3db0d0b5)

#### [Weapon Select]

![weapon select](https://github.com/user-attachments/assets/cfc7659c-c080-40f6-b2d9-9547c7f48db0)

#### [Trait Tree]

![Trait](https://github.com/user-attachments/assets/25368513-6d29-4d91-87a4-5b5eeae2f8b3)

#### [Perk System]

![Perk](https://github.com/user-attachments/assets/3035604e-9ade-4c5c-9438-aa7b826c7e09)

#### [Stat Panel]

![Stat](https://github.com/user-attachments/assets/9fca4b7c-f78c-428d-a1c9-fcdddf0b84bd)

#### [Perk Selection Card]

![Perk Select](https://github.com/user-attachments/assets/1dac5024-fe85-4fda-a6f6-8179910ca7ff)

#### [Round Summary UI]

![Round Summary](https://github.com/user-attachments/assets/6efd1fad-f0af-451a-af09-7937242a8962)

</details>

<details>
<summary><b>[📝Patch_Ver_0003] 상세 패치 내역 보기 (클릭)</b></summary>

*업데이트 예정...*

</details>

---

# TOOSIN 📝 개발자노트

---

<details>
<summary><b>[📝Dev_Ver_0003] 패치 예정 내역 보기 (클릭)</b></summary>

## 📋 상세 작업 내용 (Task List)
### 💰 1. 경제 및 상점 시스템 (Economy & Shop)
- [ ] **재화(Money) 기능 도입**
  - 매 판 전투 승리 시 일정량의 재화를 획득하는 로직 추가
  - 획득 및 소모한 재화의 세이브 및 로드 연동 (`CurrentSaveGame` 활용)
- [ ] **허브 상점 UI 구축**
  - 상점에서 콤보 애니메이션 시퀀스 아이템 전시 및 구매 기능 구현
  - 
### ⚔️ 2. 콤보 커스터마이징 세팅 (Combo Modification)
- [ ] **콤보 슬롯 UI (`WBP_ComboEditor`) 구현**
  - 우측 패널: 플레이어의 현재 스탯 정보 시각화
  - 좌측 패널: 소지 중인 무기의 콤보 애니메이션 시퀀스 리스트업 (경공격 1~3타 / 강공격 1타)
  - 선택한 모션의 콤보 구성 시각화 제공 (영상/프리뷰 연동 기능)
  - 무기 타입별 가용 콤보 제한 및 전용 슬롯 UI 분리 
- [ ] **동적 애니메이션 몽타주 조립 로직 구현**
  - 상점에서 구매해 소지 중인 애니메이션 시퀀스를 무기의 COMBO 1, 2, 3 슬롯에 드래그 앤 드롭으로 장착하는 UI 로직 구현
  - 런타임에 커스텀 슬롯 설정대로 하나의 몽타주가 연계 및 조합되어 실제 공격 모션으로 발동되도록 구현


</details>

---
앞으로도 여러분의 소중한 피드백을 바탕으로 발전하는 투신이 되겠습니다. 감사합니다!  

*투신 개발팀*  
