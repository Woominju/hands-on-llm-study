# hands-on-llm-study

Transformer 기초 복습부터 『핸즈온 LLM』 장별 실습까지, 한 학기 LLM 학습 과정을 단계별로 정리한 저장소입니다.

학습 계획과 주기적인 진행 보고는 [00-plan](00-plan/)에 있습니다.

## 학습 단계

| 단계 | 폴더 | 내용 | 상태 |
| --- | --- | --- | --- |
| 0 | [00-plan](00-plan/) | 학습 계획서, 진행 보고 | 진행 중 |
| 1 | [01-foundations](01-foundations/) | Transformer와 LLM 기초 복습 (Word2Vec, ELMo, Seq2Seq, Attention, KV-cache, State of GPT 등) | 예정 |
| 2 | [02-bert-vit](02-bert-vit/) | BERT와 ViT 정리 | 예정 |
| 3 | [03-ch01-02](03-ch01-02/) | 『핸즈온 LLM』 1·2장 | 예정 |
| 4 | [04-ch03-llama](04-ch03-llama/) | 3장 대규모 언어 모델 자세히 살펴보기 + Llama | 예정 |
| 5 | [05-ch04-classification](05-ch04-classification/) | 4장 텍스트 분류 (요약, 과제) | 예정 |
| 6 | [06-agent-whitepaper](06-agent-whitepaper/) | Google Agent Whitepaper 요약 | 예정 |
| 7 | [07-ch05-clustering](07-ch05-clustering/) | 5장 텍스트 클러스터링과 토픽 모델링 (+ t-SNE, LDA, TF-IDF 예비학습) | 예정 |
| 8 | [08-ch06-08](08-ch06-08/) | 6장 → 7장 → 8장 (+ GraphRAG) | 예정 |
| 9 | [09-semester-end](09-semester-end/) | 12장, 여유가 있으면 10장 → 11장 → 9장 | 예정 |

## 실행 환경

4장 과제부터 Colab Pro와 OpenAI API를 사용합니다. 로컬에서 실행할 때는 다음과 같이 준비합니다.

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
nbstripout --install            # 노트북 출력은 지우고 커밋
cp .env.example .env && chmod 600 .env   # .env에 OpenAI API 키 입력
```

## 출처

실습 코드는 공식 저장소 [HandsOnLLM/Hands-On-Large-Language-Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models)(Apache-2.0)를 참고했으며, 가져온 코드는 각 노트북 첫 셀에 출처를 적습니다. 교재 본문과 그림, 강의 자료는 포함하지 않습니다.
