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

✅ 운영 중
> 토스증권 계좌의 보유 종목·수익률·매수/매도 내역을 주기적으로 수집해 S3에 적재하는 개인 프로젝트 MyStocks의 데이터 수집·배치 인프라
* 토스증권 OpenAPI를 async로 병렬 호출해 보유 종목, 수익률, 비교군(VOO/QQQ) 시세, 체결 내역 수집
* S3 + Parquet 데이터 인프라 구축, DuckDB로 SQL 가공 후 view JSON 생성
* CloudFront + WAF IP Set으로 개인 투자 정보 접근 통제
* Lightsail + crontab 기반 정기 배치, 월 약 $7 수준으로 운영
* **Tech:** Python · uv · DuckDB · AWS(S3, CloudFront, WAF, Lightsail)

### Repository
- [📊 Data Collector](https://github.com/recoma96/mystocks-data-collector)
- [🌐 Web Dashboard](https://github.com/recoma96/mystocks)

## 🥾 [WalkRoadMap](https://github.com/walkroadmap)
위치·도보 코스 데이터 수집 및 관리 플랫폼

🚧 개발 중
> 여행 명소와 등산·트레킹 등 도보 코스 데이터를 수집하고, 향후 다양한 서비스와 자동화에 활용하기 위한 위치 데이터 플랫폼

* 위치 및 도보 코스 데이터를 수집·관리하기 위한 Internal Product 개발
* 데이터 수집 API를 중심으로 Backend부터 개발 진행
* 사용 빈도가 높지 않은 내부 API 특성을 고려해 EC2 대신 AWS Lambda 기반 Serverless 구조 적용
* 향후 수집 데이터를 기반으로 코스 탐색 및 데이터 자동화 및 기반 서비스 개발 예정
* **Tech:** Python · AWS Lambda

# 🛠Tech Stacks
* **Core**: **Python**, Django, MySQL, Redis, Celery, AWS(EC2, RDB, Lambda, etc...), Docker
* **Expanding**: **FastAPI**, **Typescript**, NestJS, PostgreSQL, React(Web, Native)
