# 팀 개발용 Git · GitHub 협업 문서 레포

![](images/nano_banana.png)

[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/)

코드보다 **협업 프로세스**랑 **문서 합의**를 연습하는 샌드박스

## 이 레포가 해결하려는 문제
- 이 기능 범위 어디까지? → 문서로 합의
- PR이 왜 이렇게 커짐 → 작업 단위 쪼개기 + 템플릿으로 강제
- 나중에 왜 이렇게 했지 → ADR로 결정 이유 남기기

## 문서 바로가기
- 스코프/기능 맵: `docs/features.md`
- 샘플 데이터: `docs/data/tshirt-list.md`
- Spec
    - 디테일 페이지: `docs/spec/detail-page.md`
    - 반응(좋아요/싫어요): `docs/spec/reactions.md`
    - 댓글: `docs/spec/comments.md`
    - 장바구니: `docs/spec/cart.md`
    - Spec 템플릿: `docs/spec/template.md`
- ADR
    - `docs/adr/0001-doc-first.md`

## 협업 룰 (최소)
- `main`은 항상 **Deployable** 유지
- 작업은 브랜치에서 하고 PR로 합치기
- PR은 작게, 설명은 `무엇/왜/리스크/롤백` 남기기
- 커밋은 Conventional Commits(`feat:`, `fix:`, `docs:`, `chore:`) 필수

## 개발자
- 택
- 택2
