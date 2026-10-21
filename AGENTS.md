# sooptalk

## 프로젝트
sooptalk — SootokTalk 플랫폼의 소스 코드입니다.

## 폴더 구조
- `apps/` — admin, mobile, server, web (4개 앱)
- `packages/` — shared (공유 패키지)
- `specs/` — sprint별 스프린트 문서 (sprint-05 ~ sprint-24 등)
- `docs/` — 기획·디자인 결정 기준 폴더 (아직 존재하지 않거나, 앞으로 만들 예정)
- 루트 — package.json, pnpm-lock.yaml, turbo.json, prd.txt, status.md 등

## 기획·디자인 결정
기획·디자인 관련 결정은 `docs/` 폴더를 기준으로 합니다.

## Git 규칙
- **main 브랜치에 직접 push하지 않는다.**
- 작업마다 `agent/<짧은-설명>` 브랜치를 만들어 push한다.
- push 전에 반드시 테스트를 돌린다.
