# 📘 개발 가이드 (Development Guide)

이 문서는 **TOOSIN : 투신** 프로젝트의 **TEAM NIRIZ 개발팀** 협업 워크플로우와 **GitHub Desktop** 사용 규칙을 정의합니다.
5월 11일 게임 클라이언트 개발자 합류에 따라 체계적인 협업 절차를 따릅니다.

---

## 🖥️ 깃허브 데스크탑 워크플로우 (GitHub Desktop Workflow)

복잡한 명령어 대신, **GitHub Desktop**의 GUI 기능을 적극 활용하여 개발합니다.

### 1. 브랜치 전략 (Branch Strategy)
* **`main`**: **"언제든 실행 가능한 완성본"**. 각 MVP 단계가 완전히 끝났을 때만 합칩니다.
* **`dev`**: **"개발 작업대"**. 기능 구현이 끝나면 이리로 모읍니다.
* **`Patch_VerXXXX`**: **"실제 작업 브랜치"**. `dev`에서 따와서 작업하고, 완료되면 다시 `dev`로 합칩니다.
  * **반드시 버전 형식으로 작성합니다.** (예: `Patch_Ver0082`, `Patch_Ver0090`)
  * 문서 작업 등 특수 목적의 경우 `Document` 브랜치를 사용합니다.

### 2. 작업 순서 (Step-by-Step)

#### 1단계: 작업 시작 전 (Sync)
1. **GitHub Desktop**을 켭니다. **Current Branch**를 `dev`로 맞추고 **Pull origin** 하여 최신화합니다.

#### 2단계: 이슈 작성 (Project Planning)
1. 작업 시작 전, **`C:\Toosin\.github\ISSUE_TEMPLATE`**의 양식을 참고하여 이슈를 생성합니다.
2. 작업의 목적, 세부 항목, 완료 조건을 명확히 합니다.

#### 3단계: 브랜치 생성 (New Branch)
1. 상단 메뉴의 **Branch** -> **New Branch** 클릭.
2. 이름 입력: **`Patch_VerXXXX`** (예: `Patch_Ver0082`).

#### 4단계: 개발 및 커밋 (Code & Commit)
1. **Summary**: 작업 내용을 명확히 적고 **Commit** 합니다.

#### 5단계: PR 작성 (Code Review)
1. 작업 완료 후 PR 생성 시 `Pull Request document form.md` 템플릿을 사용합니다.
2. 제목은 `[MVP-X] 작업명` 형식으로 작성하고, `Closes #이슈번호`를 포함합니다.

#### 6단계: 상호 리뷰 및 병합 (Code Review)
1. 팀원의 **승인(Approve)** 후 `dev`에 병합합니다.
2. Desktop으로 돌아와서 `dev` 브랜치를 **Pull origin** 하여 최신화합니다.
3. 다 쓴 `Patch_VerXXXX` 브랜치는 **Delete**로 삭제하여 정리합니다.

---

## 📝 커밋 메시지 규칙 (Commit Convention)

| 태그 | 설명 | 예시 |
| :--- | :--- | :--- |
| **feat** | 새로운 기능 추가 | `feat: 3타 콤보 공격 추가` |
| **fix** | 버그 수정 | `fix: 공격 중 이동되는 버그 수정` |
| **docs** | 문서 수정 | `docs: 로드맵 업데이트` |
| **style** | 코드 포맷/정리 | `style: 들여쓰기 정리` |
| **refactor**| 구조 개선 (기능 변화 X) | `refactor: 스탯 관리 로직 최적화` |
| **chore** | 기타 설정 | `chore: 언리얼 프로젝트 설정 변경` |
