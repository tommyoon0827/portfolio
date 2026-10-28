# 김윤지 포트폴리오

AI 엔지니어를 목표로 하고 있습니다.
모델을 학습하고 평가하는 일부터, 그 모델이 쓸 데이터 파이프라인과 결과를 보여 줄 화면·서버까지 직접 만들어 운영에 올려 봤습니다.
학교에서는 LangChain과 GPT-4o-mini로 소아과 문진 에이전트와 RAG 육아 상담 챗봇을 만들었습니다.
인턴으로 일하면서는 CCTV 관제 시스템의 화면과 서버를 새로 만들고, 그 위에서 도는 비전 모델과 모델에 들어갈 학습 데이터 수집 플랫폼을 만들었습니다.
학습 때 점수가 좋던 모델이 운영 카메라 앞에서 전혀 다르게 동작하는 일을 몇 번 겪고 나서, 모델을 바꾸기 전에 데이터와 평가부터 다시 보는 편입니다.
모델과 데이터는 Python으로, 서비스는 TypeScript와 Go로 만듭니다.

회사 프로젝트는 코드 대신 화면과 결과로 정리했습니다.

## 회사 (인턴, 2026)

### [CCTV 관제 시스템 재작성](cctv-control-system/)
`Vue 3` `TypeScript` `Go` `PostgreSQL` · 2026.07–08  
기존 PHP 관제 시스템 대체용. 화면 41개, API 115개 1인 개발.

### [학습 데이터 수집 기능](training-dataset-collection/)
`Nuxt 4` `TypeScript` `Prisma` `MariaDB` `ClamAV` · 2026.08–09  
모델 배포 플랫폼에 수집·자동 검사·검수·릴리스 추가. YARA 규칙 작동률 0.2% → 93.9%.

### [CCTV 걷기·서기 판정](walk-stand-classification/)
`YOLO` `Python` · 2026.07  
전용 모델 제거 후 이동량 판정. 균형 정확도 75.5%, 추가 연산 0.

### [CCTV 화분·야구방망이 탐지](potbat-detection/)
`YOLO12n` `Python` · 2026.07  
2클래스 경량 모델, 1일 완료. 방망이 미탐률 44% → 14%.

### [CCTV 라벨링 도구](cctv-labeling-tool/)
`Python` `Tkinter` `OpenCV` `YOLO12` · 2026.07–08  
영상 → YOLO 데이터셋 자동·수동 라벨링, 검수 모드. 위 두 모델의 데이터를 이 도구로 제작.

## 학교 (2025)

### [소아과 사전 문진 AI 에이전트](pediatric-previsit-agent/)
`LangChain` `GPT-4o-mini` `ChromaDB` `Streamlit` · 2025.10–11  
나이별 문진, 답변별 LLM 안내, 의료진용 요약, RAG 육아 상담. 학부 연구생.

### [쓰레기 분류·재활용 가이드 앱](waste-classification-app/)
`Python` `PyTorch` `ChromaDB` · 2025.03–06  
4인 팀 중 데이터 담당. 15종 분류 데이터 구축, 캡스톤 디자인 경진대회 동상.
