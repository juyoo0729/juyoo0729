# 유정욱 | AI · 데이터 엔지니어를 준비합니다

고객서비스 현장에서 쌓은 문제 파악과 소통 경험을 바탕으로, 데이터를 정리하고 모델의 결과를 근거로 설명하는 일을 하고 싶습니다.
AIFFEL에서 Python·PyTorch 기반 모델 실험을 경험했으며, 공공데이터 활용과 LLM·RAG의 검색·평가를 중심으로 프로젝트를 이어가고 있습니다.

[기술 블로그](https://juyoo0729.tistory.com/) · [프로젝트와 문제 해결 기록](https://juyoo0729.tistory.com/notice/38)

## 대표 프로젝트와 담당 역할

### ClaFact · 공식 통계의 조건을 맞추는 근거 탐색

뉴스 속 수치와 KOSIS 통계를 연결하는 팀 프로젝트에서 **통계표 탐색과 근거 매핑**을 담당했습니다.
지표명뿐 아니라 항목·시점·단위를 확인하고, 목록을 사전에 수집·색인하는 방향을 제안했습니다.
팀의 350개 통계표 카탈로그 확보에 기여했으며, 확보한 표 수와 검색 정확도를 구분해 기록합니다.

[코드와 시스템 설명](https://github.com/juyoo0729/clafact-auto) · [팀 프로젝트 이후의 개인 실험 기록](https://juyoo0729.tistory.com/32)

### 제주 지니 · 서비스에 사용할 수 있는 공공데이터 확인

제주 관광 RAG 팀 프로젝트에서 **공공데이터 조사·확보와 활용 방식 분류**를 맡았습니다.
후보 417개를 조사해 REST와 LINK, 정형·비정형 자료를 구분하고 팀 공유 목록을 작성했습니다.
417개는 조사한 후보 수이며, 실제 연동 완료 API 수와 구분합니다.

[팀 프로젝트 저장소](https://github.com/juyoo0729/jeju-genie) · [개인 역할과 데이터 확보 회고](https://juyoo0729.tistory.com/31)

### Project Han · 야간 영상의 작은 클래스 인식 개선

야간 주행 영상 분석 팀 프로젝트에서 **클래스 불균형 분석, 가중 손실 비교와 후처리**를 수행했습니다.
차선처럼 작은 클래스의 IoU를 따로 확인하고 예측 결과를 비교했습니다.
위험 점수는 장면 분석을 위한 실험값이며 실제 사고 확률로 해석하지 않습니다.

[문제·접근·결과·평가 범위](https://juyoo0729.tistory.com/29)

## 실습과 실험 기록

| 기록 | 확인할 내용 |
| --- | --- |
| [AIFFEL 학습 기록](https://github.com/juyoo0729/AIFFEL_quest_eng) | Python·CV·NLP·RAG·MLOps 실습과 주요 결과 문서 |
| [RAG 평가 실습](https://github.com/juyoo0729/rag-eval-practice) | 10개 질문·3개 설정의 저장 결과, 평가 데이터와 검색 문서 분리 과제 |
| [MLOps CI/CD 실습](https://github.com/juyoo0729/mlops-quicklab-cicd) | 원본 교육 자료를 바탕으로 한 학습·검사·컨테이너·클라우드 작업 흐름 |
| [MLflow 실험 기록](https://github.com/juyoo0729/AIFFEL_quest_eng/blob/main/MLOps/MLOps06/results_summary.md) | 강의 실습 재현, 설정별 실행 기록과 모델 등록 과정 |

팀 프로젝트의 전체 구현과 교육용 원본은 개인 단독 성과로 표시하지 않으며, 담당 업무와 후속 실험을 구분합니다.

## 활용한 기술

- **데이터 처리:** Python, pandas, NumPy, 공공데이터 OpenAPI, 데이터 정제·유형 분류
- **모델 실험:** PyTorch, U-Net, OpenCV, 클래스별 IoU 비교
- **검색·평가:** RAG, KOSIS 근거 매핑, RAGAS 평가 실습
- **개발·운영 학습:** Git/GitHub, Docker, GitHub Actions, MLflow, Airflow, Vertex AI

## 작업할 때 중요하게 보는 것

1. 데이터의 출처·분포·누락부터 확인합니다.
2. 변경한 조건과 결과를 함께 기록합니다.
3. 실패 사례와 평가 한계를 남겨 다음 개선으로 연결합니다.

**교육:** AIFFEL · AI 기반 지능형 서비스 개발 과정 · 2026.03–2026.09
