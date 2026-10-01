# TOOSIN : 투신

[English](README_EN.md) · [문서 목록](README.md)

TOOSIN은 Unreal Engine 5.5로 개발한 1인용 아레나 로그라이크 액션 게임입니다. 플레이어의 공격 선택, 가드 타이밍, 회피와 거리 조절을 기록하고 적 AI의 다음 판단에 반영합니다. 전사·검사·격투가 세 직업에 무기, 콤보, 특성, 특전과 특수능력을 조합해 전투를 진행합니다.

[![TOOSIN 1.0 트레일러](assets/toosin-1.0/hero.png)](https://youtu.be/TrSGI-_k3KQ?si=Ldi4LljXUcPoyivW)

[Steam](https://store.steampowered.com/app/4635530/TOOSIN/) · [STOVE](https://store.onstove.com/ko/games/104376) · [데모](https://store.steampowered.com/app/4786560/TOOSIN___Demo/)

## 현재 상태

2026년 10월 1일 기준입니다. 2026년 8월 13일 정식 출시했으며 이 저장소에는 Version 1.3.1까지의 공개 업데이트 기록을 정리했습니다.

**Version 1.4를 준비하고 있습니다.** Codex와 Claude를 활용해 구현과 디버깅, 문서 작업을 진행하며 허브와 메뉴, 외형·직업 선택, 전투 동작, AI, 저장과 현지화를 점검하고 있습니다. 개발 빌드와 자동화 검사, 일부 실화면 검수 결과가 있지만 패키지 빌드와 남은 플레이 검수는 진행 중입니다. 출시 일정과 최종 적용 범위는 확정 후 안내하겠습니다.

[1.4 준비 현황과 검수 범위](DEVELOPMENT_UPDATE_2026-10-01_KR.md) · [로드맵](ROADMAP.md)

## 전투와 성장

- 경공격·강공격·차지 공격과 직업·무기별 콤보
- 가드, 패링, 회피, 가드 브레이크와 넉백
- 무기·콤보·특성·특전·숙련·특수능력을 조합하는 성장
- 무기, 콤보, 외형과 특수능력의 영구 해금
- TAB 또는 게임패드 Y를 누르는 동안 확인하는 AI 학습 상태

적 AI는 게임 안에서 수집한 행동 통계와 규칙 기반 의사결정을 사용합니다. 생성형 AI 도구는 개발 과정에서 활용하며 게임의 전투 AI와 구분합니다.

<p align="center">
  <img src="assets/toosin-1.0/combat-parry.png" width="49%" alt="TOOSIN 패링 전투" />
  <img src="assets/toosin-1.0/combat-close.png" width="49%" alt="TOOSIN 근접 전투" />
</p>

## 게임 모드

| 모드 | 내용 |
|---|---|
| 스테이지 | 전투와 보상, 무작위 사건을 거쳐 성장하는 기본 진행 |
| 무한 | 현재 체력과 스태미나를 유지하며 이어지는 라운드와 전용 기록 |
| 등급전 시즌 2 | 플레이어 1명·아군 AI 4명 대 적 AI 5명의 5대5 전투, 시즌 점수와 영토 영향력 |
| 트레이닝 | 조작과 전투 동작을 연습하는 환경 |

등급전 시즌 2는 1인용 AI 팀 전투입니다. 시즌 기록과 영토 영향력은 플랫폼 기록을 통해 집계합니다.

## 공개 업데이트 기록

| 버전 | 주요 내용 | 문서 |
|---|---|---|
| 1.3.1 | 신규 특전 20종, 기존 특전 수정, 검기 개선 | [상세 기록](V1.3.1_UPDATE_KR.md) |
| 1.3 | 고급 특성 100종, 순위 보너스, 전투·투기장 개선 | [상세 기록](V1.3_UPDATE_KR.md) |
| 1.2 | 시즌 2 5대5 영토전, 전투와 성장 개편 | [상세 기록](V1.2_UPDATE_KR.md) |
| 1.1 | AI 학습, 피의 계약, 튜토리얼과 UI | [상세 기록](V1.1_UPDATE_KR.md) |

각 문서는 해당 버전의 변경 기록입니다. 준비 중인 1.4의 내용은 별도 개발 현황에서 확인해 주세요.

## 게임 정보

| 항목 | 내용 |
|---|---|
| 개발·배급 | TEAM NIRIZ |
| 엔진 | Unreal Engine 5.5 |
| 플랫폼 | Windows PC, Steam, STOVE |
| 장르 | 액션 로그라이크, 액션 RPG, 1인용 |
| 지원 언어 | 한국어, 영어, 일본어, 중국어 간체·번체, 러시아어 |

## 시스템 요구 사항

| 항목 | 최소 | 권장 |
|---|---|---|
| 운영 체제 | Windows 10/11 64-bit | Windows 10/11 64-bit |
| 프로세서 | Intel Core i5-8400 / AMD Ryzen 5 2600 | Intel Core i7-9700K / AMD Ryzen 7 3700X |
| 메모리 | 8 GB RAM | 16 GB RAM |
| 그래픽 | NVIDIA GeForce RTX 2060 | NVIDIA GeForce RTX 3060 |
| DirectX | Version 12 | Version 12 |
| 저장 공간 | 8 GB | 10 GB |

위 표는 [Steam 상점에 공개된 요구 사항](https://store.steampowered.com/app/4635530/TOOSIN/)입니다. 설치된 빌드와 플랫폼별 공지도 함께 확인해 주세요.

## 문서와 문의

[변경 기록](CHANGELOG.md) · [패치 노트](PATCHNOTE.md) · [지원·버그 제보](SUPPORT.md) · [공식 사이트](https://teamniriz.com/) · [Discord](https://discord.gg/EHMwJSjWpA) · [지원 메일](mailto:support@teamniriz.com)

이 저장소는 게임 소개와 공개 변경 기록을 보관합니다. 게임 소스는 별도로 관리합니다.

© 2026 TEAM NIRIZ.
