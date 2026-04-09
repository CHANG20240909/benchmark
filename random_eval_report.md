# 무작위 1개 답변/문항 평가 결과

## 실행 메모
- 문항별로 `score_0_answer`, `score_1_2_answer`, `score_3_4_answer` 중 1개를 무작위 선택
- 현재 런타임에서 Gemini API 키/CLI가 없어 동일 평가 프롬프트를 에이전트 평가 방식으로 적용

## 요약 집계
- 총 문항: 26
- 예측 밴드 분포:
  - 0점대: 10
  - 1-2점대: 5
  - 3-4점대: 11
  - 5점대: 0
- 평균 점수: 1.96
- 선택 밴드와 예측 밴드 일치: 25/26
- 불일치: KCQ-004 (selected=score_1_2, predicted=0)

## 문항별 결과
| id | selected_from_band | predicted_band | predicted_score | match |
|---|---|---:|---:|:---:|
| KCQ-001 | score_1_2 | 1-2 | 2 | Y |
| KCQ-002 | score_3_4 | 3-4 | 4 | Y |
| KCQ-003 | score_0 | 0 | 0 | Y |
| KCQ-004 | score_1_2 | 0 | 0 | N |
| KCQ-005 | score_3_4 | 3-4 | 4 | Y |
| KCQ-006 | score_0 | 0 | 0 | Y |
| KCQ-007 | score_0 | 0 | 0 | Y |
| KCQ-008 | score_0 | 0 | 0 | Y |
| KCQ-009 | score_3_4 | 3-4 | 4 | Y |
| KCQ-010 | score_0 | 0 | 0 | Y |
| KCQ-011 | score_1_2 | 1-2 | 1 | Y |
| KCQ-012 | score_1_2 | 1-2 | 1 | Y |
| KCQ-013 | score_3_4 | 3-4 | 4 | Y |
| KCQ-014 | score_3_4 | 3-4 | 4 | Y |
| KCQ-015 | score_3_4 | 3-4 | 4 | Y |
| KCQ-016 | score_0 | 0 | 0 | Y |
| KCQ-017 | score_3_4 | 3-4 | 4 | Y |
| KCQ-018 | score_1_2 | 1-2 | 1 | Y |
| KCQ-019 | score_3_4 | 3-4 | 4 | Y |
| KCQ-020 | score_0 | 0 | 0 | Y |
| KCQ-021 | score_3_4 | 3-4 | 4 | Y |
| KCQ-022 | score_3_4 | 3-4 | 4 | Y |
| KCQ-023 | score_0 | 0 | 0 | Y |
| KCQ-024 | score_1_2 | 1-2 | 2 | Y |
| KCQ-025 | score_3_4 | 3-4 | 4 | Y |
| KCQ-026 | score_0 | 0 | 0 | Y |
