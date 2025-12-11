# IoT 119

![Java](https://img.shields.io/badge/Java-11+-red?logo=oracle&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-Framework-brightgreen?logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-ORM-brightgreen)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-DB-336791?logo=postgresql&logoColor=white)
![Apache POI](https://img.shields.io/badge/Apache%20POI-Excel%2FWord-orange)
![Vue.js](https://img.shields.io/badge/Vue.js-3-4FC08D?logo=vue.js&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-HTTP-blue)
![Vuex](https://img.shields.io/badge/Vuex-State%20Management-35495E)
![Chart.js](https://img.shields.io/badge/Chart.js-Data%20Viz-FF6384)


> KT에서 IoT 회선을 컨설팅할때 요금재를 추천해주는 PoC 서비스




## 1. 프로젝트 개요
**IoT119**는 KT에서 IoT 회선 컨설팅을 진행할때 회선 요금제를 추천해주는 PoC 서비스입니다. 본 프로젝트는 KT AICT Future TF 1차 프로젝트에서 개발하였습니다.

**처리 흐름:**
- **DB 적재:** 고객정보를 입력 받은 후 DB에 저장하기
- **DB 조회 및 분석:** 고객정보 DB에서 불러와 요금제 분석 및 표출하기
- **UI 표출:** 추천한 요금제 이력 저장 및 표출하기




## 2. 기술 스택
> Vue.js(WEB) + JAVA Spring(WAS) + PostgreSQL(WEB) 기반 Full Stack 웹 서비스입니다.

| Layer | Tech |
| ----- | ---- |
| DB    | PostgreSQL |
| WAS   | Java Spring |
| Web   | Vue.js |




## 3. 실행 방법
> 3개의 서버를 각각 실행하여 확인 가능합니다. 

### 3.1 Backend 실행

```sh
uv run uvicorn src.main:app --host 0.0.0.0 --port 8001
```

### 3.2 Frontend 실행

```sh
uv run uvicorn src.main:app --host 0.0.0.0 --port 8001
```

### 3.3 Database 실행

```sh
uv run uvicorn src.main:app --host 0.0.0.0 --port 8001
```





## 4. 주요 모듈 구성 및 기능

```
iot-119/
├── README.md                       # 서비스 개요
├── IoT119_DB.sql                   # DB SQL문
├── IoT119_PPT.pptx                 # 발표자료
├── Backend/                        # 백엔드 소스코드
├── Dataset/                        # 데이터셋 소스코드
└── Frontend/                       # 프론트엔드 소스코드
    ├── aicc_dataset.csv
    └── company_article.csv
```
