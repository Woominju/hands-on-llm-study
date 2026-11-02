# 학습 계획

2026년 2학기 『핸즈온 LLM』 학습 및 과제 진행 순서에 맞춘 개인 학습 계획입니다.

- **기간**: 2026년 11월 3일 ~ 12월 6일 (5주)
- **방향**: 기초 복습(1·2단계)은 첫 주에 핵심 위주로 압축하고, 나머지 4주는 『핸즈온 LLM』 학습과 실습에 집중합니다.
- **범위**: 5주 안에 현실적으로 마칠 수 있는 1단계부터 8단계 7장까지를 목표로 하고, 8장·GraphRAG와 9단계는 여유가 있을 때 진행합니다.

## 주차별 계획

| 주차 | 기간 | 단계 | 학습 내용 | 결과물 |
| --- | --- | --- | --- | --- |
| 1주 | 11/3 ~ 11/9 | 1·2 | Transformer와 LLM 기초 복습: Attention, Transformer 구조, KV-cache, State of GPT를 중심으로 정리. BERT와 ViT 구간 학습 | `01-foundations/notes.md`, `02-bert-vit/notes.md` |
| 2주 | 11/10 ~ 11/16 | 3·4 | 『핸즈온 LLM』 1·2장(2.15절, 2.5절 제외), 3장 대규모 언어 모델 자세히 살펴보기 + Llama 강의 | `03-ch01-02/summary.md`, `04-ch03-llama/summary.md` |
| 3주 | 11/17 ~ 11/23 | 5 | 4장 텍스트 분류 학습과 요약, Colab Pro와 OpenAI API로 4장 과제 실습 | `05-ch04-classification/summary.md`, `assignment.md`, 실습 노트북 |
| 4주 | 11/24 ~ 11/30 | 6·7 | Google Agent Whitepaper 요약. t-SNE, LDA, TF-IDF 예비학습 후 5장 텍스트 클러스터링과 토픽 모델링 학습·실습 | `06-agent-whitepaper/summary.md`, `07-ch05-clustering/` |
| 5주 | 12/1 ~ 12/6 | 8 | 6장 → 7장 학습과 실습 | `08-ch06-08/ch06/`, `ch07/` |

## 여유가 있을 때

- 8장과 GraphRAG
- 9단계: 12장, 이후 10장 → 11장 → 9장

## 진행 보고

매주 일요일에 그 주에 한 것과 다음 주 계획을 [reports](reports/)에 `YYYY-MM-DD.md`로 올립니다. 계획보다 늦어지면 다음 주 보고에서 일정을 조정합니다.

## 실습 환경

4장 과제부터 Colab Pro(10~12월)와 OpenAI API를 사용합니다. API 키는 `.env`에만 두고 저장소에는 올리지 않습니다.
