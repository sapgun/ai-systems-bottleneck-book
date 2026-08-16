# Contributing / 피드백 가이드

이 저장소는 코드 프로젝트라기보다 **실전형 시스템 사고 훈련서의 배포·피드백 저장소**입니다.

Pull Request보다 먼저 Issue를 이용해 주세요. 특히 다음 피드백을 환영합니다.

## 가장 도움이 되는 피드백

- 오타, 글자 깨짐, 잘못된 캡션
- 기술적으로 부정확하거나 오해의 여지가 있는 설명
- Windows / macOS / Linux에서 재현되지 않는 실습
- GPU가 없는 CPU-only 환경에서 막히는 구간
- 같은 현상을 더 직관적으로 설명할 수 있는 비유
- SYSTEM-7로 진단했을 때 다른 결론이 나오는 반례

## Issue 작성 시

가능하면 아래 정보를 포함해 주세요.

```text
Edition / Version:
Page or section:
Environment (optional):
What I expected:
What I observed:
Suggested correction (optional):
```

기술적 오류라면 재현 가능한 로그, 명령어, profiler 결과 또는 공식 레퍼런스를 함께 남겨주면 확인에 도움이 됩니다.

## 범위

이 책의 핵심 범위는 다음과 같습니다.

- 컴퓨터 자원 감각과 시스템 구조
- CPU / Memory / I/O / Network / GPU
- Local LLM과 AI runtime
- Profiling과 bottleneck diagnosis
- SYSTEM-7 기반 문제 해결

분산 시스템, 데이터베이스 내부 구현, 커널 개발 등은 관련이 있더라도 현재 에디션의 주 범위 밖일 수 있습니다.

감사합니다. 실제 학습 과정에서 나온 피드백이 가장 가치 있습니다.
