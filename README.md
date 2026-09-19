<div align="center">

<!-- 헤더 -->
<a href="https://github.com/devxb/gitanimals">
<img src="https://render.gitanimals.org/lines/protofu?pet-id=1" width="1000" height="120"/>
</a>

<br/>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fprotofu&count_bg=%233D6BC8&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

</div>

## 👋 About

AI Engineer · 영상·문서·설비 시계열 데이터를 다루는 AI 모델을 개발하고 운영 환경에 배포하고 있습니다.
외부 반출이 불가능한 데이터를 다루며, 모델을 내부 서버 한 대에 올릴 수 있도록 경량화하고 어디까지 자동으로 맡길지 범위를 나누는 일을 주로 합니다.

## 🛠 Work Projects

> 업무 프로젝트라 코드는 비공개입니다.

**설비 시계열 이상탐지** · 2026.08 ~ 현재 · 단독
- 센서 데이터 수집·5분 단위 정렬·결측 처리·품질 지표 산출 파이프라인, InfluxDB + Grafana 대시보드
- 고장 라벨이 없어 정상 구간에 고장을 합성 주입하는 평가 체계 설계, 유형별 검출률 분리 측정
- 기존 모델이 직전값을 추종해 완만한 고장을 놓치는 문제를 규명 → 물리 제약 규칙 + CUSUM 기반 탐지로 보완

**문서 정보 추출** · 2026.03 ~ 08 · 단독
- OCR 3종 결과를 합친 1차 추출 + Qwen2.5-VL-32B를 NVFP4 4비트로 양자화해 vLLM으로 올린 검증 단계
- 자동 확정 / 사람 검수 범위 분리 → 검수 항목 약 76% 감소
- 양자화로 단일 GPU 처리량 약 1.7배, 건당 처리시간 약 45% 단축
- 외부 클라우드 OCR 제거, 전 구간 내부 처리로 전환

**영상 판정·감지** · 2026.01 ~ 07
- 두 이미지가 같은 위치·같은 대상인지 판정하는 시스템 단독 개발, 오탐·오판 0건 (SuperPoint+LightGlue, MAGSAC++, DINOv2 활용)
- CCTV 화재·침입 감지 (4인 팀, 감지 모듈·API 담당): YOLOv8 학습, 타일 분할 추론, 1차 자체 모델 → 모호한 장면만 2차 질의하는 2단 구조

<div align="center">

## Skill :four_leaf_clover:

<!-- AI / ML -->
<div>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=YOLO&logoColor=white" alt="YOLOv8">
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge&logoColor=white" alt="vLLM">
<img src="https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logoColor=white" alt="XGBoost">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn">
</div>

<!-- Serving / Data -->
<div>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white" alt="InfluxDB">
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white" alt="Grafana">
</div>

<!-- Web (SSAFY) -->
<div>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white" alt="Spring Boot">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" alt="MySQL">
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white" alt="Jenkins">
</div>

<br/>

## 🏆 SSAFY 9기 프로젝트 (4회 모두 수상)

| 프로젝트 | 내용 | 역할 | 결과 |
|---|---|---|---|
| [Seiren](https://github.com/protofu/Seiren) | AI 음성 모델 학습·거래 서비스 (VITS) | 팀장 · 프론트엔드 | 특화 우수상 1위 |
| [BeNurse](https://github.com/protofu/BeNurse) | 3교대 간호사 업무 보조 서비스 | 백엔드 · CI/CD | 자율 우수상 2위 |
| [냠냠프렌즈](https://github.com/protofu/YumYumFriends) | AI·WebRTC 유아 식사 독려 게임 | 프론트엔드 | 공통 우수상 1위 |

<br/>

## :pencil2: Study log

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=protofu&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=protofu&show_icons=true&theme=radical)

## Problem Solving :muscle:

[![Solved.ac Profile](http://mazassumnida.wtf/api/generate_badge?boj=sungjae0512)](https://solved.ac/sungjae0512)

</div>
