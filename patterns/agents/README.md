# 효과적인 에이전트 구축 쿡북

Erik Schluntz와 Barry Zhang의 [Building Effective Agents](https://anthropic.com/research/building-effective-agents) 참조 구현입니다.

이 레포지토리는 블로그에서 다룬 일반적인 에이전트 워크플로우의 최소 구현 예제를 포함합니다:

- 기본 구성 요소
  - 프롬프트 체이닝
  - 라우팅
  - 다중 LLM 병렬화
- 고급 워크플로우
  - 오케스트레이터-서브에이전트
  - 평가자-최적화기

## 시작하기
자세한 예제는 Jupyter 노트북을 참조하세요:

- [기본 워크플로우](basic_workflows.ipynb)
- [평가자-최적화기 워크플로우](evaluator_optimizer.ipynb)
- [오케스트레이터-워커 워크플로우](orchestrator_workers.ipynb)