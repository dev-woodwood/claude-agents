# Claude Code 커스텀 에이전트 모음

[CSM (Claude Session Manager)](https://github.com/dev-woodwood/CSM)에서 설치 가능한 커스텀 에이전트 세트입니다.

## 세트 목록

### KDW 개발 에이전트 세트
코드 리뷰, UI 검증, QA 테스트, 보안 감사, 기술 설계를 위한 에이전트 모음

| 에이전트 | 설명 |
|---------|------|
| anti-ai-ui-reviewer | AI스러운 UI 디자인 방지 |
| code-reviewer | 코드 품질/일관성 리뷰 |
| lts-planner | 기술 설계/아키텍처 계획 |
| ruthless-qa-tester | 엄격한 QA 테스트 |
| security-auditor | 보안 감사 |

### KDW 인프라/교육 에이전트 세트
배포 검증, 프로젝트 동기화, 프로그래밍 학습 멘토 에이전트 모음

| 에이전트 | 설명 |
|---------|------|
| deploy-validator | 배포 설정 검증 |
| cross-project-sync | 프로젝트 간 코드 동기화 |
| dev-master-teacher | 프로그래밍 학습 멘토 |

## 설치 방법

### CSM에서 설치
1. CSM 앱 → Agents 탭 → 마켓
2. 세트 선택 → 개별 or 전체 설치
3. 글로벌/프로젝트별 선택

### 수동 설치
`.md` 파일을 `~/.claude/agents/` (글로벌) 또는 `프로젝트/.claude/agents/` (로컬)에 복사

## 기여
PR로 새 에이전트 세트를 추가할 수 있습니다.
