# Claude Code 커스텀 에이전트 모음

[CSM (Claude Session Manager)](https://github.com/dev-woodwood/CSM)에서 설치 가능한 커스텀 에이전트 모음입니다.

## 설치 방법

### CSM에서 설치
1. CSM 앱 실행
2. Agents 탭 → 마켓 → 원하는 에이전트 설치

### 수동 설치
`.md` 파일을 `~/.claude/agents/`에 복사하면 됩니다.

## 에이전트 목록

| 이름 | 설명 |
|------|------|
| anti-ai-ui-reviewer | AI스러운 UI 디자인 방지 |
| code-reviewer | 코드 품질/일관성 리뷰 |
| cross-project-sync | 프로젝트 간 코드 동기화 |
| deploy-validator | 배포 설정 검증 |
| dev-master-teacher | 프로그래밍 학습 멘토 |
| lts-planner | 기술 설계/아키텍처 계획 |
| ruthless-qa-tester | 엄격한 QA 테스트 |
| security-auditor | 보안 감사 |

## 기여
PR로 에이전트를 추가할 수 있습니다. `agents/` 폴더에 `.md` 파일을 넣고 `index.json`을 업데이트해주세요.
