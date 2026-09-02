# SafeDeal Docs

SafeDeal의 **확정 문서** 저장소입니다. 흐르는 논의(회의록·브레인스토밍·일정)는 노션에, 확정된 것은 여기에 둡니다.

## 원본(Source of Truth) 규칙

| 대상 | 원본 위치 |
|---|---|
| DB 스키마 | `safeDeal-Backend`의 Flyway 마이그레이션 (`src/main/resources/db/migration`) |
| API 스펙 | `safeDeal-Backend`의 springdoc 자동 생성 (OpenAPI) |
| 확정 정책·계약·ADR | 이 레포 |
| 회의록·안건·브레인스토밍 | 노션 (Core Station) |

동일 내용이 여러 곳에 있으면 위 표의 원본이 우선합니다. 다른 곳의 사본에는 원본 링크를 답니다.

## 디렉토리

- `policy/` — 도메인별 확정 정책 (이관 범위는 팀 결정 후)
- `contracts/` — 도메인 간 이벤트 계약 (감점·결제·알림)
- `adr/` — 아키텍처 결정 기록 (Architecture Decision Records)
- `process/` — 개발 프로세스 (deferred 규칙, 커밋 컨벤션 등)








