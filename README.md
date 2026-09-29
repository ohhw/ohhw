# ohhw

작은 문제를 오래 들여다보고, 쓸 수 있는 형태로 만듭니다.

웹 서비스와 데이터·AI 도구를 다룹니다.
빠르게 보이는 결과보다, 이해한 만큼 단단하게 만드는 과정을 좋아합니다.

## selected work

- **[forest](https://github.com/ohhw/forest)** — CUDA, PyTorch, YOLO 환경과 반복 작업을 정리한 컴퓨터 비전 도구
- **[dotnet_env](https://github.com/ohhw/dotnet_env)** — ASP.NET Core와 Razor Pages로 만든 웹 애플리케이션

## private work

로컬 언어 모델, 검색 기반 응답, 학습용 웹 서비스를 만들고 기록하고 있습니다.

`Python` · `TypeScript` · `.NET` · `Machine Learning` · `Automation`

일부 작업은 개인정보와 운영 환경을 포함해 비공개로 관리합니다.

## Commit Message 가이드라인

- **형식:** `타입(스코프): 제목`으로 시작합니다.
- **스코프:** 변경 영역을 밝힐 때만 붙입니다.
- **본문:** 제목 아래 한 줄을 비우고 변경 내용을 `-` 목록으로 적습니다.
- **제목:** 50자 이내로 쓰고 끝에 마침표를 붙이지 않습니다.
- **원칙:** 영문 제목은 명령조로 쓰고, 커밋 하나에는 목적 하나만 담습니다.
- **관련 이슈:** 본문 아래 한 줄을 비우고 `Refs: #번호`를 적습니다.

### feat · 기능 추가

```text
feat(ui): 다크 모드 추가

- 화면 테마 전환 버튼 추가
- 선택한 테마 저장
```

### fix · 버그 수정

```text
fix(search): 검색 결과 누락 수정

- 빈 검색어를 처리하는 조건 수정
- 결과가 없을 때 안내 메시지 표시
```

### docs · 문서 변경

```text
docs(readme): 설치 방법 보완

- 설치 전 요구 사항 명시
- 실행 명령 예시 추가
```

### style · 표현·포맷 변경

```text
style(button): 버튼 간격 정리

- 버튼 사이 여백 통일
- 동작 변경 없이 화면 표현 조정
```

### refactor · 코드 구조 개선

```text
refactor(api): 응답 처리 함수 분리

- 중복된 응답 처리 로직 통합
- 기존 동작 유지
```

### chore · 설정·관리 작업

```text
chore(deps): 의존성 버전 갱신

- 패키지 버전 업데이트
- 잠금 파일 동기화
```
