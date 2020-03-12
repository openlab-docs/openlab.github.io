---
layout: documentation
title: log-analytics
category: Solutions
order: 2
---



# 솔루션 개요

  * Log Analytics는 Data Lake 에 저장된 각종 데이터로부터 특정 키워드를 검색하거나 통계 및 고급분석을 할 수 있는 분석 인프라를 제공합니다. 사용자는 이상징후 탐지, 데이터 패턴 분석, 상관관계 분석 등을 Log Analytics를 통해 쉽고 빠르게 분석이 가능합니다.

# 솔루션 주요특징

##  쉬운 데이터 검색 및 직관적인 인사이트 제공

  * 검색 키워드를 통해 누구나 쉽게 검색이 가능하며 SQL 문법 지원과 Full Text 검색 지원이 가능하여 사용자가 원하는 방식으로 데이터를 탐색할 수 있습니다.

![iris analyzer](\images\documents\products\b-iris-data-browser.png){:some-css-class width="800"}

---

##  분석가가 직접 데이터 샘플링이 가능한 프로세스

  * 개발자의 도움 없이 분석가가 직접 분석에 필요한 데이터를 UI를 통해 가공할 수 있는 기능을 제공합니다.

![iris analyzer](\images\documents\solutions\iris-analyzer-data-sampling.png){:some-css-class width="800"}

---

##  이벤트 통계 정보 및 상관분석

  * 데이터 검색 후 통계 및 차트를 통해 비정상 상황을 직관적으로 분석할 수 있습니다.

![iris analyzer](\images\documents\solutions\iris-analyzer-outlier.png){:some-css-class width="800"}

---

##  고급분석 기술로 내장된 이상징후 탐지


  * 이상징후 탐지 (Anomaly Detection) 기반 고급분석 엔진이 내장되어 쉽고 빠른 분석이 가능합니다.

![iris analyzer](\images\documents\solutions\iris-analyzer-ade.png){:some-css-class width="800"}

---



##  직관적인 피벗차트 지원


  * 누구나 쉽게 사용가능한 UI 옵션 기능으로 피벗분석이 가능한 UX환경을 제공합니다.

![iris analyzer](\images\documents\solutions\log-analytics-pivot.png){:some-css-class width="600"}

---

##  용도에 따른 다양한 시각화 차트 지원

  * 고급시각화 분석 결과를 쉽게 이해하고 빠른 의사 결정을 할 수 있는 인사이트를 제공합니다.


![iris analyzer](\images\documents\solutions\iris-analyzer-advanced-chart-a.png){:some-css-class width="600"}

![iris analyzer](\images\documents\solutions\iris-analyzer-advanced-chart-b.png){:some-css-class width="600"}



---

  * 위치 정보를 기반으로 한 데이터를 다양한 지도형태의 시각화 유형으로 제공합니다.

![iris analyzer](\images\documents\solutions\iris-analyzer-mapview.png){:some-css-class width="800"}

---



## 분석가 선호에 따른 다양한 분석툴과 연동 가능

  * 오픈소스 툴과 연동하여 분석 후 전수 데이터에 적용하는 프로세스 절차를 간소화하여 분석과정의 절차를 단축시켰습니다.

![iris analyzer](\images\documents\solutions\iris-analyzer-opensource-1.png){:some-css-class width="800"}

---



# 솔루션 응용사례


## 1. 이동통신망 장비의 이상원인 분석 사례

### 비지니스 이슈


#### 안정적인 이동통신 서비스를 제공하기 위해 수많은 장비들에 대한 고장 감시 시스템을 운영중


  * 1차적인 주요 알람, 이벤트, KPI 들에 대한 감시는 적용되어 운영

  * 장애의 조기 탐지 및 대응 및 신속하고 정확한 장애 원인 분석 필요

  * 심각한 서비스 장애를 유발할 수 있는 잠재적 위험 요소를 탐지하여 사전 예방하기 위한 선제적 대응 방안 필요



#### 분석 과정


  * 적재 : 분석 대상인 LTE 장비 3식에서 4일 동안 발생한 Alarm, Fault, Status 메시지 약 350만 건을 IRIS DB에 적재

  * 전처리 : 적재된 원시 데이터 350만 건을 분석을 위한 구조로 변환

  * 탐색적 분석 : 장비별 이상 탐지, 시각화를 통한 특성 도출

  * 고급 분석 : 중점 분석 대상 장비에 대한 시계열 분석, 비정형 텍스트 분석


#### 분석 환경

  * 적재 : IRIS ETL

  * 전처리 : IRIS 데이터브라우저 (검색, 피벗)

  * 탐색적 분석 : IRIS 데이터브라우저 (검색, 피벗, 시각화)

  * 고급 분석 : IRIS 대화형 분석 (R-Studio)



#### 분석 단계



  * 목적 : 개별 시스템의 작은 변화가 전체 시스템에 영향을 주는지 분석

  * Step 1 : 개별 시스템별 고정 임계치 기준으로감시되지 않는 이상상황의 존재 유무 판단

  * Step 2 : 이상상황의 탐지 & 의심 장비 및 시점 식별

  * Step 3 : 이상상황의 원인이 무엇인지 분석

![iris analyzer](\images\documents\solutions\ade-usecase.png){:some-css-class width="600"}



---



## 2. 사용량 패턴 분석을 통한 모바일앱 분류 사례



#### 비즈니스 이슈

  * 이동통신사에서는 비정상적인 모바일 App 서비스의 트래픽으로 인한 이동 통신망 과부하 발생에 선제적으로 대응하기 위해 모바일 App 단위 사용량을 분석/감시

  * App 서비스는 다수의 서버에서 제공되며 서버의 IP는 자주 변경(추가/삭제)

  * 수작업으로 서버스 IP로 접속하여 App을 식별중이나 정확한 관리의 한계가 있음

  * 미식별 App(IP)에 대하여 자동으로 App 서비스를 식별할 수 있는 방법을 연구



#### 분석 과정

  * 적재 : 1일 동안의 모바일 App 사용 이력 로그 1분 통계 약 250 만 건을 IRIS DB에 적재

  * 전처리 : 적재된 원시 데이터 250 만 건을 분석을 위한 구조로 변환

  * 탐색적 분석 : App 사용 패턴 분류, 시각화를 통한 특성 도출

  * 고급 분석 : 식별 App과 미식별 App의 상관 계수 도출 및 통계적 검증(K-S test)


#### 분석 환경

  * 적재 : IRIS ETL

  * 전처리 : IRIS 데이터브라우저 (검색, 피벗)

  * 탐색적 분석 : IRIS 데이터브라우저 (검색, 피벗, 시각화)

  * 고급 분석 : IRIS 대화형 분석 (R-Studio)

![iris analyzer](\images\documents\solutions\mobile-usecase.png){:some-css-class width="600"}



---







