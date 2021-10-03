# DataScience
Python 데이터 분석 실무

## 00.Information
-------------------------------------------------

주요 목적 및 필요 사전 지식, 전체 구성에 대한 설명을 제공

강의의 목적을 이해하고 구조를 사전에 이해하는 것이 목적

목차 
- 목적
- Target Audience (사전 필요지식)
- 목차
-------------------------------------------------
### 00-1 목적

#### 분석 실무 역량 제고
  * 분석 실무에서 접하는 다양한 문제를 이해하고 직접 해결해보는 경험을 통해 실무 역량을 제고
    * 분석 환경/배경의 이해
    * 데이터 분석 실무 이해
    * 개인별 프로젝트 진행
   * 실제 실무에서 쓰이는 데이터 -> 정제되지 않은 데이터. 따라서 데이터의 이해나 비즈니스 맥락등 복합적인 요소 동시 고려 필요함

#### 프로세스 이해
  * 전처리와 데이터 이해/탐색에 대부분의 시간 사용
  * 복잡한 모델링이나 최적화된 파라메터 튜닝, 시각화 작업 업무는 극히 일부분
  * 프로세스 과정
    * 문제 정의 및 가설 수립
    * 데이터 설계/수립/처리/검수
    * 데이터 추출 및 전처리
    * 데이터 탐색 및 모델링 (평가, 모델 개선)
    * 보고서 작성 및 커뮤니케이션

#### 소프트 스킬의 중요성 이해
  * 소프트 스킬을 제고하여 분석 결과의 전달력과 효과성을 높이는 것 중요함
    * 데이터 분석가로서 마인드셋/태도/원칙
    * 커뮤니케이션 방식 / 보고서 작성법
    * 비즈니스 문제 정의/해결 방안 고민
    * 비즈니스 본질 및 주요 고객에 대한 이해


-------------------------------------------------
### 002- Target Audience

#### 필요한 사전 지식

실무에 실제 쓰이는 프로그래밍 코드와 실용적인 통계/머신러닝 방법론을 중심으로 구성

* Python(for문, if문, lambda함수, list comprehension, slicing 등)을 통해 원하는 형태의 데이터셋 가공
* Numpy, Pandas, Scipy, Statsmodel, Scikit-learn, Matplotlib 등의 라이브러리 기본 사용법 숙지
* 통계 및 머신러닝에 대한 기초 지식 보유
  * ANOVA, T-test 등 통계적 가설 검정 방법 및 해석 방법, 개념 등에 대해 이해함
  * Ridge/LASSO Regression, Logistic Regression, RandomForest, SVM, ANN 등 머신러닝 모델을 이해함
  * Confusion Matrix, AUC, R-sqaured, RMSE 등 모델 평가 방법을 알고 있음
  * Grid Search 및 K-fold CV 등을 통해 모델의 파라메터 튜닝 방법을 알고 있음
  * 표준화, 로그 transformation, Polynomial/Interaction항 등 주요 Feature Engineering 방법 숙지
* SQL 코드를 작성하여 db에서 원하는 테이블을 추출/조인할 수 있음
---------------------------------------------------------------------
### 003- 목차

강의 커리 큘럼 총 8회: 5회의 강의(실습 포함), 3회의 개인 프로젝트 실습

#### 1회차 Part1: 분석 실무에 대한 이해

분석 실무 전반에 대한 개념과 프로세스를 이해 및 주요 활용 툴과 환경, 분석가의 소프트 역량에 대한 부분 중점적으로 학습

* 분석 주제 예시
* 분석 프로세스
* 팀구성 및 역할
* 분석툴 및 환경 소개
* 소프트 스킬/역량

#### 1회차 Part2: 데이터 수집 및 처리 시스템 소개

분석 환경에 대한 내용을 중점적으로 학습 하고 실습 진행
로그 데이터를 파싱하는 것과 SQL을 활용해 간단한 전처리를 하는 방법 다룸

* Apache Spark & Modules 소개
* 클라이언트 로그 설계 사례
* (실습)Json 및 Text 형태의 로그 데이터 Parsing
* (실습)SQL 및 Pandas를 통한 전처리


#### 2회차: 유저 Funnel 분석을 통해 이탈 구간 개선
Funnel Analysis를 통해 이탈이 발생하는 구간 파알 및 개선안을 도출하는 프로젝트

* 문제 정의 및 가설 정립
* 분석 Frame 구성 / MECE 및 로직트리
* 데이터 로딩 및 전처리
* 탐색적 데이터 분석 / K-means를 활용한 클러스터링
* 시각화 및 리포팅

#### 3회차: 결제 예측 모델을 통한 결제율 제고
결제 확률이 높은 유저들을 분류하는 모델 구축 및 성능을 측정하는 과정을 진행

* 문제 정의 및 가설
* 분석 Frame 구성
* 데이터 전처리
* 데이터 분석 및 변환
* 모델 학습 및 Cross Validation
* 모델 평가 및 성과 개선

#### 4회차: 신규 비즈니스 지표 개발
비즈니스 지표 개발 및 대시 보드를 이용해 시각화하는 과정 진행

* 배경 및 목적
* 분석 프레임 구축
* 판정 기준 선택 및 패턴 이해를 위한 데이터 탐색
* 주요 변수 선정 및 가중치 도출을 위한 데이터 탐색
* 스코어 산출 및 대시보드 구축

#### 5회차: 랭킹 및 추천 로직 설계
랭킹 및 추천을 위한 로직을 설계하고 검증하는 과정 진행.

#### 6~8회차: 개별 프로젝트

* 개별 프로젝트 진행 및 피드백
* 프로젝트 결과 발표


## 01.분석 실무에 대한 이해 Part1
-------------------------------------------------
### 목적

* 분석 실무의 예시와 주요 개념, 프로세스 전반과 세부 업무별 중요 사항에 대해 이해
* 분석가의 업무 환경와 팀구조를 이해하고, 협업의 중요성을 인지하기
* 문제 정의 및 커뮤니케이션 등 소프트 역량/스킬의 역량을 높이기

### 목차

* 분석 주제 예시
* 분석 프로세스
* 팀구성 및 역할
* 분석툴 및 환경 소개
* 소프트 역량
* 마치며

----------------------------------
### 01-1 분석 주제 예시

#### 데이터 분석이 제공할 수 있는 가치

데이터 분석은 데이터를 통해서만 만들어 낼 수 있는 가치 혹은 서비스를 제공하기 위한 과정에 불과

1) 비즈니스 영역
2) 개발 영역

![image](https://user-images.githubusercontent.com/62330533/134807650-dd638664-04df-4d68-8733-9293f85aa1d2.png)

#### 기획/UX 영역

가장 중요한 것: 유저에게 매끈한 경험을 제공 --> Conversion Rate(전환율)이 높은 것을 의미

Conversion Rate --> Funnel 분석을 통해 파악(이탈이 많이 일어나는 구간(Bottleneck)을 파악해 AB Test등을 통해 개선함으로써 UX 향상

기획 영역에서는 UX개선을 위한 목적뿐 아니라, 데이터 기반에 새로운 서비스를 기획하는 것도 가능

EX)
* 추천/랭킹 서비스 (영화, 매장, 뉴스/블로그 컨텐츠, 아이템, 지인 등)
* 이미지, 텍스트, 오디오 데이터 처리를 통한 자동분류 서비스 (병 진단, 번역, 주문 처리 등)
* 이상치 탐지
* 클러스터링 등을 통한 유저 세분화

#### 마케팅 영역

ROI(Return on Investment)에 민감 --> KPI로 고려

* 집행량(expense) 대비 노출(impression)
* 노출 대비 클릭 (Click Thorugh Rate)
* 클릭 대비 구매 (Purchase Rate)
* 구매 대비 재구매 (Repurchase Rate)

![image](https://user-images.githubusercontent.com/62330533/134807882-93e498b4-2ba1-4faa-9509-fe9afda97263.png)

EX) 높은 ROI를 보이는 세그먼트를 집중적으로 공략 ==> 전체 ROI를 높이는 마케팅 전략 고려

STP(Segment, Targeting, Positioning) 전략 수립을 위해 데이터 분석이 활용 되기도 함
ex) 
1) K-menas 등의 클러스터링을 통해 전체 고객 분류
2) 특정기준(충성도, 재구매율)으로 세그먼트 정렬
3) 우선순위에 따라 맞춤형 컨텐츠/커뮤니케이션을 제공(Association-Rules)

==> 마케팅 활동의 효율성/효과성 높임

#### 영업/CS/개발 영역

영업, 신규 고객 창출과 기존 고객의 유지가 주요 관심사

데이터를 통해 
1) 신규 고객을 창출할 수 있는 기회/영역 탐색
2) 고객의 이탈을 사전 예측 --> 이탈 예방

CS영역
1) 자동화 응대나 이슈 대응을 하기위해 데이터 활용

개발 영역
1) 제품의 안정화 및 버그 관리 등을 위해 데이터 활용
-------------------------------------------------------------
### 01-2 분석 프로세스

#### 분석 프로세스

![image](https://user-images.githubusercontent.com/62330533/134808022-c74890bd-eb63-4f32-8e7a-d15e057f4b2e.png)

* 문제 정의
* 데이터 수집
* 데이터 처리
* 데이터 분석
* 리포팅/피드백 Loop

#### 문제 정의

* 업무의 큰 방향성과 전반적인 Frame을 설정하는 '문제 정의'단계
* 유관자와 업무의 목적, 이유, 비즈니스에 미치는 영향, 구체적인 설계와 지표, 일정과 예상 Output 등에 협의
* 요청자의 모호한 비즈니스적 요구사항을 해석하고 구체화하여, 데이터 엔지니어와 협업을 통해 분석을 준비

필요한 역량
* 모호한 언어를 개발적인 언어로 해석할 수 있는 능력이 요구
* 요청자의 니즈를 파악하여 문제 정의 과정을 리딩할 필요가 종종 발생
* 구체와 과정에서 약간의 수학적 지식고 지표의 타당성을 고려할 필요 있음
* 비즈니스 연결성ㅇ르 고려하여 전반적인 Frame을 잘 설정할 필요 있음

![image](https://user-images.githubusercontent.com/62330533/134808096-01a5d61a-3131-4d0f-8a9c-4a01725bf869.png)

#### 데이터 수집


* 로그 설계 단계
** 로그 항목 및 Format 정의
** Key, Value, Params 정의
* 모듈화 단계
** 모듈화 개발
** 모듈 적용/테스트
* 로그 검증
** 데이터 퀄리티 검증/관리
** 수집 과정 모니터링

분석가 ==> 로그 설계와 검증 부분을 담당
분석 목적에 맞춰 무수한 로그를 선별하고 항목을 정의하며, 실제 데이터가 정의한 대로 잘 쌓이고 있는지 확인하고 수정하는 작업에 관여

#### 데이터 엔지니어

엔지니어 ==> 주로 실시간 혹은 시간대별 배치 작업을 통해 테이블을 업데이트 하거나 동기화 하는 업무
분석가 ==> 원하는 데이터를 추출하여 분석전 전처리 작업을 진행할 수 있음

분석가의 입장에서 전처리 작업은 아래와 같은 활동을 의미
* 데이터 추출, 필터링, 그룹핑, 조인 등 (SQL)
* 이상치 제거, 분포 변환, 표준화, 카테고리화, 차원 축소 등(Python/R)

첫번째 항목
* 주로 SQL을 활용, 다양한 소스(DB, Hadoop 등)으로부터 데이터 분석을 위한 기본적인 테이블을 만드는 단계
* 테이블과 칼럼의 명칭, 처리/집계 기준, 조인시 데이터 증식 방지 등, 데이터 엔지니어로부터 도움이 필요한 경우 많음

두번째 항목
* 데이터 분석가 주도적으로 R이나 Python으로 진행하는 경우가 많음
* 의미있는 분석 결과나 성능 좋은 모델을 만들기 위해 가장 중요한 단계
* 대부분의 분석가는 이 과정에서 많은 시간을 소요
* 모델 개선이나 재분석 진행시 이 과정으로 다시 돌아와서 개선

#### 데이터 분석
* 분석 영역은 사실 매우 큰 영역을 아우르는 범위
* 도메인과 여러 상황에 따라 다양한 분석을 진행함

간략한 영역 구분

* 지표 정의 및 트래킹
 * 비즈니스와 관련한 주요 지표를 개발/산출하고 대시보드 및 리포트를 통해 트래킹
 * DAU, MAU, WAU, NRU, Retention, Conversion(Purchase) Rate, ARPPU, LTV 등
 * AARRR
* 탐색적 데이터 분석
 * 그룹별 평균, 합 등 현황 확인
 * 분포 확인
* 통계 분석
 * 가설 검정, 모수 추정
 * 변수간 관계 파악 및 변수간 영향력 파악
 * 통계 모형 구축
 * 차원 축소(요인분석, 군집분석)
* 머신 러닝
 * 분류 및 회귀 문제 해결 (지도학습)
 * 추천 및 이상치 탐지, 클러스터링 등 (비지도 학습)

#### 리포팅 및 피드백 반영

분석 결과 및 인사이트를 설득력 있게 정리/전달하는 과정은 매우 중요

* 내용의 초점은 분석가 아닌 상대방
* 간결하고 명확한 메시지로 전달
* 적절한 시각화 방법 활용
* 투명하고 공정한 피드백
---------------------------------------------------------------
### 01-3. 팀 구성 및 환경

#### 팀구성
데이터 사이언스팀 
* 엔지니어링과 분석 파트로 구분 ==> 서로 협업을 통해 프로젝트 진행
* 엔지니어와 분석가는 보유 역량 및 지식의 영역이 다르기 때문에 원활한 커뮤니케이션과 협업, 목적의 공유가 특히 더 강조

#### 데이터 엔지니어

* 소프트웨어 개발 및 인프라, 데이터 수집 및 처리에 대한 경험과 전문성 보유
* 시스템 환경(Spark, Hadoop) 설치 및 관리, 테이블 동기화/자동화 작업 등의 업무를 주로 맡음
* 주로 Scalar, Java, Python 등의 언어를 사용하며, 경우에 따라 웹/앱/서버 개발을 진행하기도 함

#### 데이터 분석가

* 로그 설계 및 지표 정의, 데이터 탐색 분석/모델링 업무를 맡음
* 통계/수학이나 산업공학을 전공한 경우가 많으며, 경영/마케팅, 사회/심리, 물리 등 다양한 전공자들이 데이터 분석 업무를 수행함
* 한 분야의 전문성과 지식으로 복잡한 현상을 분석하고 해석하기엔 한계가 있으므로 여러 관점을 통해 다각적이고 풍부하게 해석하고자 하는 의지가 반영된 결과
* 주로 SQL 기반의 언어(Presto, Hive)을 통해 데이터를 추출하여 로컬 머신에서 R/Python/사용튤을 사용해 분석하거나, 데이터 사이즈가 큰 경우 분산 처리 환경(Spark가 제공하는 API(R/Python/SQL)에서 분석
* Adhoc이 아닌 트래킹이 필요한 경우 태블로 등을 이용해 대시보드를 구축하기도 함

![image](https://user-images.githubusercontent.com/62330533/134808539-8ec5718e-61ee-443d-8f1c-ecfb9acd68b4.png)

#### 분석 툴 및 환경

분석 환경 및 시스템의 실제적인 구축과 관리 --> 엔지니어의 역할

##### 분석 환경/시스템

* Spark (오픈 소스)
 * Java로만 다룰 수 있는 Hadoop을 보다 분석 친화적으로 개선 (Scalar, Python, R API 제공)
 * RDD, DataFrame, Dataset 등 다양하고 처리가 빠른 데이터셋 제공
 * 데이터 I/O 작업을 디스크가 아닌 RAM 이용 가능
 * Lazy execution으로 보다 효율적인 작업이 가능
 * 다양한 분석 라이브러리 사용 가능(MLlibrary 등)
* Zeppelin (오픈 소스)
 * Rstudio, Jupyter Notebook과 유사한 역할
 * 코드를 저장하고 데이터를 시각화
 * 간단한 시각화/대시보드 제공
* 상용 툴
 * 엑셀, 태블로, 스팟파이어, 스플렁크, Re:dash
 * 구글 애널리틱스, 파이어베이스
 * SPSS, SAS, Matlab
* 분석 환경 예시
![image](https://user-images.githubusercontent.com/62330533/134808609-48cd0412-c8f2-42ee-b5f4-3740156cc05b.png)

----------------------------------------------------------------------------
### 01-4 소프트 역량

#### 문제 정의 역량

분석 프로세스의 첫 단계는 문제 정의
문제 정의를 잘하기 위해서는 특정 지식이나 스킬 보다, 도메인 및 분석 경험이 더 중요하게 요구 됨

문제를 정의할 때 고려할 것 

* 충분한 시간을 투자해 유관자와 논의/협의
* 변경사항 여부에 대해 지속적인 공유
* 많은 질문/대답을 통해 요구사항 명확화
* 문서화를 통한 기록
* 비즈니스에 미치는 영향력 고려하여 우선수위 산정
* 지표의 타당성과 신뢰성 확보

현실적인 시간 제한을 고려하여, 적당한 깊이에서 분석을 중단하고 공유하는 것이 현명
항시 목적성 상기화

#### 프레임 설정 역량

(내용이 비어 있는) 틀(프레임)을 짜고 추후에 데이터 분석을 통해 내용을 채워 넣는 방식으로 진행하는 거싱 효율적

프레임을 설정할 때 고려할 원칙

* 문제 해결에 도달하기 위한 세부적인 주제/질문 선정
* 세부 주제별 필요 데이터 및 분석 방법론 정리
* 예상 Output 및 일정 산출
* 유관자 혹은 유관팀 정리

#### 태도 및 커뮤니케이션 역량

데이터 분석 프로젝트(분석가+엔지니어+유관자, 협업)
누군가를 설득하고 이해시키는 작업은 분석가의 중요한 업무 중 하나

* 분석가의 태도

** 데이터를 끈기 있고 집요하게 파고 들며, 분석하고 이해하고 원인을 추론하며 대안을 생각해내는 태도
** 결과를 누구나 이해하기 쉽게 전달하고 때로는 스토리 텔링 등을 통해 설득하고자 하는 노력 필요

* 분석가의 태도와 커뮤니케이션 방식
 * 경청하고 문제를 이해하고 해결하고자 하는 높은 의지
 * 객관적이고 사실에 근거한 결과 도출 (도덕성과 정직성)
 * 끊임없이 새로운 것을 학습하고 즐겁게 배우는 태도
 * 논리적 사고 및 프로페셔널리즘
 * 적극적이고 빠른 피드백/응대
 * 명확하고 직관적인 결과/메시지 전달 (두괄식 문장, 간결하게)
 * 호기심

----------------------------------------------------------------------

### 마치며

이 장에서는 분석 실무에서의 주요 주제/프로세스/팀 구성/분석 환경/소프트 역량에 대해 간력히 살펴봄

겸손/경청하고 새로 배우며 나무 보다는 숲을 넓게 볼 수 있는 분석가가 되는 것이 중요

* 간단한 토의 과정 (면접 준비용으로 좋을 듯)
 * 당신은 왜 분석가가 되려고 하는 것인가? 혹은 왜 분석을 하려고 하는 것인가?
 * 당신이 데이터를 통해 제공할 수 있는 가치는 무엇일까?
 * 분석가에게 정직성과 신뢰성은 중요한가?
 * 분석 과정에서 시간과 결과 간의 trade-off는 어떻게 다루어야 하는가?
 * 기본적인 분석 방법론 보다 고급 분석 방법론이 더 좋은 것인가?
 * 올바른 질문과 사고를 하려면 어떠한 노력을 해야하는가?
 * 예상하지 못한 결과가 나온다면 어떻게 대처해야하는가?
 * 상대의 이해력이 매우 부족하다면 어떻게 해야하는가?
 * 분석가에게 요구되는 가장 중요한 자질은 무엇인가?
 * 분석가에게 상상력이 중요한가?

---------------------------------------------------
## 02 분석 실무에 대한 이해 Part2

### 02-1 Spark & 주요 Modules 소개

#### 데이터 분석 환경

분석가가 좋은 성과를 내기 위해서 분석 환경을 잘 이해/ 활용하고 떄로는 (분석 관점에 맞게) 개선점을 엔지니어에게 전달 하는등의 역할이 필요
따라서 환경/시스템적 요소에 대한 이해와 지속적인 관여 역시 분석가의 역할

#### 스파크 소개

최근 비정형 데이터의 생성과 매우 큰 사이즈 등의 이슈 ==> 하둡/스파크를 도입하는 추세

비록 RDBS 만큼 즉각적 생성/수정/변경 등은 어렵지만, 
Spark나 하둡을 이용할 경우 분산 저장 및 처리를 통해 빠른 분석 진행이 가능

최근에는 하둡보다 분석 친화적인 스파크 주로 사용
(스파크가 Pyspark/ SparkR과 같은 분석 API 제공) 
(하둡은 Java, Spark는 스칼라 기반)
![image](https://user-images.githubusercontent.com/62330533/135750601-9d824a71-a9d6-4d89-a427-4ae207e43d6c.png)

#### 스파크 RDD, DataFrame, Lazy execution

스파크에서 주로 다루는 주요 데이터 타입 ==> RDD(Resilient Distributed Datasets)와 DataFrame
Lazy Execution ==> 함수를 Transform, Action으로 구분해 Action 일 경우에만 실제 실행이 발생하는 것을 의미
매번 결과를 갖고 오지 않고, 필요한 경우에만 RAM을 통해 데이터 I/O가 발생하므로 분석 작업 속도가 매우 높음


##### RDD
* Distribute collection of JVM Objects
* Funtional Operators (map, filter, reduceByKey, ect)
![image](https://user-images.githubusercontent.com/62330533/135750783-6874b6cf-0cd3-42f1-8b3e-ec08c060b9fe.png)


##### DataFrame
* Distribute collection of Row objects
* Expression-based operations and UDFs
* Logical plans and optimizer
* Fast/efficient internal reprenstations

![image](https://user-images.githubusercontent.com/62330533/135750786-d860fc3c-2538-4e6c-952f-a347360c8089.png)

##### Lazy Execution
![image](https://user-images.githubusercontent.com/62330533/135750802-e938b047-4f6d-4c5c-9a1b-85d7dcc5b714.png)


#### 스파크 Modules & 머신러닝

Spark Streaming
SparkSQL
MLlib
GraphX
--------------------------------------------------
### 02-2. AWS 소개 및 로그 정의/파싱

#### AWS 소개
데이터를 수집하고 저장, 처리 및 분석하는 일련의 과정을 직접 구현하기에 많은 인력과 자원/시간이 소모
--> 이를 쉽게 가능하도록 클라우드 플랫폼 솔루션을 제공하는 것이 AWS

EMR --> Spark, Hadoop, Presto, HBase 등 분석에 유용한 분산 프레임 워크를 제공
Amazon S3 및 Amazon DynamoDB와 같은 저장소와 호환

#### 로그 정의/설계

##### 로그 데이터

* 장점
** 최근 사용자의 사용성 및 행동 패턴을 확인하거나 유저 클러스터링, 모델링 등 다양한 목적으로 사요되는 행동 기반 데이터
** RDB의 결과론적 데이터와 달리 특정 결과에 이르는 과정과 흐름을 상세히 파악 가능 ==> 서비스 개선에 유용
* 단점
** 데이터 용량이 크기 때문에 스토리지 관련 비용/리소스 발생
** JSON, CSV, TSV와 같은 비정형 텍스트 형태이므로 기존 RDB와는 다른 수집/처리 시스템과 전문 인력이 요구됨

##### 로그 정의 및 설계 

* 분석가는 산재된 로그를 분석 목적에 맞게 포멧을 정리하고 로깅할 항목을 우선 순위에 맞게 정하는 역할
* 로그 발생시 수집할 필드명과 값의 이름을 정의하고 설계하는 업무
* 실제 데이터 수집/처리시 정의한 대로 로그가 쌓이므로 이 단계는 매우 중요한 단계
* 쌓인 로그의 데이터 퀄리티를 확인하고 관리하는 역할 역시 분석가의 몫


##### 로그 정의 예시

* 최근 로그의 형태 ==> JSON(JavaScript Object Notation)
* Pandas의 Dictionary와 거의 유사하게 Key, Value로 구성되어 있으며, Hierchial 구조 가질 수 있음
* 분석가는 Json의 Key와 Value에 들어갈 값을 정함.

--------------------------------------------------------
### 02-3. SQL 데이터 추출

#### 데이터 추출

* 이미 수집/처리된 테이블에서 데이터를 불러오고 간단히 전처리하는 방법
* SQL 언어는 데이터를 추출하고 간단하게 전처리, 탐색을 할 때 매우 유용한 언어

** 실습 예제 진행하기
