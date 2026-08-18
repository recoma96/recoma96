<div align="center">
  <img src="profile.png" alt="profile" height="100px" />
</div>


# 👋Introduction
* Python 기반의 백엔드 개발을 주로 해왔으나. 다른 분야에 대한 학습도 좋아합니다.<br>
* 어떤 것이든 좋지만, 취미와 관심있는 것들을 위주로 개발하는걸 좋아합니다<br>

# 📓Carear
* ScalarData | Python Backend Developer | 2022.09.19 ~ 2026.04.30 | 3 years 7 months
* Archisketch | Python Developer (Intern) | 2020.09.01 ~ 2020.12.31 | 4 months


# 🚧Projects
## 📈MyStocks Data Collector
투자 데이터 수집·적재 배치 인프라

✅ 운영 중 (유지보수·개선 진행 중)
> 토스증권 계좌의 보유 종목·수익률·매수/매도 내역을 주기적으로 수집해 S3에 적재하는 개인 프로젝트 MyStocks의 데이터 수집·배치 인프라
* 토스증권 OpenAPI를 async로 병렬 호출해 보유 종목, 수익률, 비교군(VOO/QQQ) 시세, 체결 내역 수집
* S3 + Parquet 데이터 인프라 구축, DuckDB로 SQL 가공 후 view JSON 생성
* CloudFront + WAF IP Set으로 개인 투자 정보 접근 통제
* Lightsail + crontab 기반 정기 배치, 월 약 $7 수준으로 운영
* **Tech:** Python · uv · DuckDB · AWS(S3, CloudFront, WAF, Lightsail)

### Repository
- [📊 Data Collector](https://github.com/recoma96/mystocks-data-collector)
- [🌐 Web Dashboard](https://github.com/recoma96/mystocks)


## 📍PinLog
현장 위치 데이터 수집 서비스 

🟢 진행 중
> 개발 예정인 Trailine(등산,트레킹 가이드) 서비스에서 사용할 위치 데이터를 수집하기 위한 Android 기반 어플리케이션
* GPS 기반 위치 데이터 및 현장 정보 수집
* 메모, 사진, 영상 등록 및 웹 다운로드 지원
* 기존 서비스(램블러, 트랭글)의 용량 한계를 보완한 데이터 수집 특화
* **Tech:** NestJS · TypeScript · PostgreSQL · React Native · Docker

### Repository
* Private (초기 개발 진행중)

# 🛠Tech Stacks
* **Core**: **Python**, Django, MySQL, Redis, Celery, AWS(EC2, RDB, Lambda, etc...), Docker
* **Expanding**: **FastAPI**, **Typescript**, NestJS, PostgreSQL, React(Web, Native)

# 🎯Interests
* GIS (PostGIS, GPS, etc...)
* ML (Machine Learning)
* Computer Vision
