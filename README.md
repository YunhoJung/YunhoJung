# 정윤호(Yunho Jung)
* 📧 E-mail: saijdu2198@gmail.com
* 🏠 Study Blog:  [@youknowwhat](https://velog.io/@youknowwhat)



## About Me
Java & Spring / Python, ML / DL, On-premise Kubernetes 기반의 3년차 백엔드 개발자입니다. 소모적이고 반복적인 ML 모델 개발 작업을 자동화하는 플랫폼을 개발해왔으며, AI 기반의 백엔드 애플리케이션을 구현하는 데에 관심이 많습니다. 기존 레거시 시스템의 아키텍처를 개선하여 서비스의 안정성과 개발 생산성을 향상시키는 데에 기여하였습니다. 현재는 대규모 시스템 설계, 성능 개선, ML/DL Model Serving에 관심이 많습니다.



## Work Experiences
### TmaxData, ML Platform Backend Engineer (2020.11 ~ )
*데이터 수집, 저장, 분석, 시각화, AI 기능을 하나의 제품에서 제공하는 분석 플랫폼인 HyperData에서 비전문가도 쉽게 AI 관련 기능을 사용할 수 있게 해주는 기능인 ML Platform 개발 및 유지 보수 업무 담당*
* MSA 전환 과정에서 Hexagonal Architecture 기반의 모듈 설계를 통한 레거시 시스템 아키텍처 개선 경험
* RESTful API 설계 및 개발 경험
* 데이터 모델링 및 SQL 튜닝 경험
* Kubernetes Custom Resource을 활용한 기능 개발 경험
* Unit Test, Integration Test 작성 경험
* ML Platform AutoML Feature Engineering 연구 및 개발

### Playphone, Intern (2019.10 ~ 2020.08)
*모바일 게임 플랫폼 회사인 Playphone에서 데이터 분석 업무 담당*
* User, Game, Marketing, Ads 등 다양한 종류의 데이터 전처리 및 시각화
* Data Dashboard 개발을 위한 KPI 정의 및 쿼리문 작성 업무를 수행
* 데이터 분석 결과 보고서 자동화



## Extra Curricular Activities
### Google Developers Machine Learning Bootcamp (2020.11 ~ 2021.01)
* Andrew Ng 교수의 Deep Learning Specialization 코스 수료
* Tensorflow Developer Certificate 취득
* https://developers-kr.googleblog.com/2020/09/mlbootcamp_11.html



## Projects
### RNN-LM과 SeqGAN을 이용한 노래 가사 생성 프로젝트, 팀장 (2019.05 ~ 2019.07)
*SeqGAN을 이용하여 Verse 부분의 노래 가사를 자동 생성해주고 RNN-LM을 이용하여 Hook 부분의 노래 가사를 자동 생성해주는 사연 기반 인공지능 모델 개발*
* word-to-index dictionary와 index-to-word dictionary를 만들어 학습중에 word와 word vector 간의 상호 참조가 가능하도록 전처리를 하고, 토큰들을 bi-gram 단위로 전처리하여 학습 데이터를 구축
* 문장 길이를 정해놓고 일정 길이보다 작은 문장의 경우 <pad>를 추가하여 데이터 전처리 작업 수행
* https://github.com/YunhoJung/GANsong-text-generation

### Tacotron을 이용한 아이유 음성 합성 프로젝트, 팀원 (2018.11 ~ 2019.01)
*Tacotron을 이용하여 텍스트를 입력하면 아이유 목소리로 음성을 합성시키는 인공지능 모델 개발*
* Pytube를 이용해 유튜브에서 아이유 음성과 관련된 데이터를 추출하고, MoviePy를 이용하여 동영상 파일을 음성 파일로 변환하였으며, Pydub을 이용하여 음성이 없는 구간을 기준으로 Segmentation 작업을 수행
* 모델의 성능을 높이기 위해 KSS 데이터로 Pretrained된 모델을 이용하여 Transfer Learning 진행
* https://github.com/YunhoJung/tobigs-rhapsody-speech-synthesis

### 2018 빅콘테스트 NCSOFT 게임 이탈자 예측 공모전, 팀원 (2021.03 ~ 04)
*NCSOFT로부터 제공된 4GB 가량의 유저 로그 데이터를 이용해 유저들의 게임 이탈을 예측하는 인공지능 모델 개발*
* 블레이드 앤 소울 게임 도메인 지식과 Python, Pandas를 이용해 데이터 전처리 및 Feature Engineering 역할을 수행
* F1 score 0.74 성과
* https://github.com/YunhoJung/2018-bigcontest-bladesoul-analysis



## Skills
[Programming Languages] Java 11, Python 3.7

[Backend] Spring Boot 2.7.0, Junit5, Mockito, JPA, Gradle, JMeter, Elastic APM, Linux, Vim

[Database] MySQL 8.0, Tibero 6, H2

[DevOps] Kubernetes 1.19, Docker, Helm, Nginx, Tomcat

[ML/DL] Kserve 0.7, Pandas, Scikit-learn, Tensorflow 2



## Education
* 서강대학교 철학, 융합 소프트웨어, PEP 전공 (2013.03 ~ 2021.02)
