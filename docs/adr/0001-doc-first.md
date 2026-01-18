# ADR
- Architecture Decision Record (아키텍처 의사결정 기록)

# ADR-0001: Doc-first로 굴린다


## Context
본 레포는 코드보다 **협업 프로세스/문서 합의**가 목적

## Decision
- 기능을 건드리기 전에 `docs/`에 스코프/규칙/수용 기준(Acceptance Criteria)을 먼저 적는다.

## Consequences
- PR이랑 코드 리뷰가 쉬워지고, `왜 이렇게 했지`가 덜 터진다.
