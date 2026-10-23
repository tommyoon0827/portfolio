# 김윤지 포트폴리오

AI를 실제 현장에서 제대로 돌아가게 만드는 일에 관심이 있습니다.
학습 때는 점수가 좋았던 모델이 운영 카메라 앞에서는 전혀 다르게 동작하는 일을 몇 번 겪고 나서,
모델 자체보다 데이터를 어떻게 모으고 결과를 어떻게 믿을 수 있게 재는지에 더 시간을 쓰게 됐습니다.
학교에서는 LLM 에이전트와 RAG를 만들었고, 인턴으로 일하면서는 CCTV 관제 시스템의 화면부터 서버까지,
그 위에서 도는 비전 모델, 그리고 그 모델에 필요한 데이터 도구를 만들었습니다.

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
