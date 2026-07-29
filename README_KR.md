<div align="right">
  <strong>🇰🇷 한국어</strong> · <a href="README_EN.md">🇺🇸 English</a>
</div>

<div align="center">

# TOOSIN : 투신

### 나를 학습한 AI를 넘어라

[![Steam](https://img.shields.io/badge/Steam-앞서_해보기-1b2838?style=for-the-badge&logo=steam)](https://store.steampowered.com/app/4635530/TOOSIN/)
[![1.0](https://img.shields.io/badge/Version_1.0-2026년_8월_말-c69b57?style=for-the-badge)](ROADMAP.md)
[![UE 5.5](https://img.shields.io/badge/Unreal_Engine-5.5-0e1128?style=for-the-badge&logo=unrealengine)](https://www.unrealengine.com/)

**TOOSIN : 투신**은 플레이어의 공격·가드·회피 습관을 분석해 다음 전투의 대응 가중치를 바꾸는  
적응형 AI와 맞서는 **1대1 아레나 로그라이크 액션 게임**입니다.

[Steam](https://store.steampowered.com/app/4635530/TOOSIN/) ·
[최신 개발자 노트](https://store.steampowered.com/news/app/4635530/view/1839041357025737) ·
[STOVE](https://store.onstove.com/ko/games/104376) ·
[공식 사이트](https://teamniriz.com/) ·
[Discord](https://discord.gg/EHMwJSjWpA) ·
[지원 메일](mailto:support@teamniriz.com)

</div>

<p align="center">
  <a href="https://youtu.be/nkfCGh1Q-rE">
    <img src="https://github.com/user-attachments/assets/a64041f1-75fa-4496-8f03-d41b7e126852" width="100%" alt="TOOSIN 공식 트레일러" />
  </a>
  <br/>
  <sub>이미지를 클릭하면 공식 트레일러로 이동합니다.</sub>
</p>

---

## 출시 현황

| 구분 | 일정 | 상태 |
|---|---:|---|
| STOVE 앞서 해보기 | 2026.04.17 | 출시 완료 |
| Steam 앞서 해보기 | 2026.05.06 | 출시 완료 |
| Version 1.0 Beta | 2026년 8월 초~중순 | 준비 중 |
| Version 1.0 정식 출시 · 앞서 해보기 종료 | **2026년 8월 말** | 베타 검증 후 출시 |

다음 주요 배포는 Version 1.0 정식 출시 빌드입니다. 최신 일정과 세부 범위는 [개발 로드맵](ROADMAP.md)에서 확인할 수 있습니다.

---

## 핵심 전투

### 적응형 전투 AI

적은 단순히 정해진 패턴을 반복하지 않습니다. 플레이어가 자주 사용하는 콤보, 가드 시점, 회피 방향과 이동 경로를 기록하고 Behavior Tree와 DDA 가중치에 반영해 공격·방어·거리 조절 방식을 변화시킵니다.

### 반응형 근접 액션

- 경공격·강공격·차지 공격과 클래스별 콤보
- 가드, 패링, 저스트 회피, 가드 브레이크
- 거리와 타격 방향을 반영한 넉백 및 Hit Reaction
- 무기·맨손 공격에 맞춘 타격 VFX, 카메라 피드백, 게임패드 진동

### 로그라이크 빌드와 영구 성장

- 100개 이상의 특성과 20종 이상의 특전
- 액티브·패시브 특수능력과 무기·콤보 조합
- 계정 경험치와 Play Point 기반의 영구 성장
- 끝자리가 3·7인 스테이지의 보상 1개와 0인 마일스톤 스테이지의 보상 2개
- 사망 후 특성은 초기화되지만 투자한 Play Point는 환급되어 자유롭게 다시 설계 가능

---

## Version 1.0 예정 주요 변화

- **영구 스테이지 보상**: 콤보, 특수능력, 클래스, 외형, 무기를 획득하고 환생 후에도 유지
- **Play Point 시스템**: 사망해도 보존되는 성장 재화와 특성 재설계
- **무기 강화**: 기본 무기를 최대 +30까지 강화
- **클래스 전직**: 캐릭터 외형과 전투 클래스·무기·콤보의 선택 폭 확대
- **AI 및 이동 개편**: 전 방향 이동, 거리 판단, 공격 예고, 대응 패턴과 반복 행동 개선
- **전투력 시스템**: 전투 전 상대의 예상 전투력을 확인
- **타격 시각 피드백**: 적 유형별 붉은색·녹색 Blood VFX, 맨손 타격 효과와 피격·저체력 화면 피드백 개선
- **전투·UI·게임패드 개편**: 패링·저스트 회피 성공 표시, 등급전 VS 연출, 체력·경험치 게이지와 전반 UI를 정비하고 Xbox 계열 패드의 키 아이콘·포커스·입력 안내 개선
- **등급전 Season 1**: Version 1.0과 함께 새로운 시즌 시작
- **튜토리얼 개편**: 실제 아레나에서 무한 체력·스태미나로 패턴 분석 과정을 직접 체험
- **안정화**: 장시간 플레이, 맵 전환, 저장, GPU 사용량과 전투 물리 오류 개선

> Version 1.0 Beta부터 저장 구조가 변경되어 이전 앞서 해보기 세이브와 호환되지 않습니다. 보존 대상과 백업 방법은 Beta 배포 공지에서 다시 안내합니다.

---

## 게임 정보

| 항목 | 내용 |
|---|---|
| 개발·배급 | TEAM NIRIZ |
| 엔진 | Unreal Engine 5.5 |
| 플랫폼 | Windows PC · Steam · STOVE |
| 장르 | 액션 로그라이크 · 액션 RPG · 1인용 |
| 지원 언어 | 한국어 · 영어 · 일본어 · 중국어 간체 · 중국어 번체 |
| Steam 기능 | 도전 과제 30개 · Cloud · 통계 · 리더보드 · 가족 공유 |

## 시스템 요구 사항

| | 최소 | 권장 |
|---|---|---|
| 운영 체제 | Windows 10/11 64-bit | Windows 10/11 64-bit |
| 프로세서 | Intel Core i5-8400 / AMD Ryzen 5 2600 | Intel Core i7-9700K / AMD Ryzen 7 3700X |
| 메모리 | 8 GB RAM | 16 GB RAM |
| 그래픽 | NVIDIA GeForce RTX 2060 | NVIDIA GeForce RTX 3060 |
| DirectX | Version 12 | Version 12 |
| 저장 공간 | 8 GB | 10 GB |

---

## 문서

- [개발 로드맵](ROADMAP.md)
- [변경 기록](CHANGELOG.md)
- [상세 패치 노트](PATCHNOTE.md)
- [지원 및 버그 제보](SUPPORT.md)

## 문의

- 공식 사이트: [teamniriz.com](https://teamniriz.com/)
- 커뮤니티: [Discord 서버](https://discord.gg/EHMwJSjWpA)
- 기술 지원: [support@teamniriz.com](mailto:support@teamniriz.com)

<div align="center">

© 2026 TEAM NIRIZ. All rights reserved.

</div>
