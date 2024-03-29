---
title: 정보처리 산업기사 필기 공부

date: 2023-05-03 19:40:00 +09:00
categories: [License]
tag: [license]

toc: true
toc_sticky: true
future: true
---

# Ⅰ. 프로그래밍 언어 활용

## 《1 - 1. 구조적 프로그래밍 설계》

### ▢ 구조적 프로그래밍 설계 구조 및 절차
    
구조적 프로그래밍은 구조화 프로그래밍으로도 불리며 절차적 프로그래밍  
기반 아래 만들어진 프로그래밍 기법으로 프로그램을 결합하는 순차, 분기,  
반복 구조를 통하여 설계된다.  

#### ▣ 구조적 프로그래밍 설계 구조
1. `순차구조`
2. `선택구조`
3. `반복구조`

#### ▣ 구조적 프로그래밍 언어 개발 절차
1. `요구사항 분석`
2. `구조적 분석`
3. `구조적 설계`
4. `구조적 프로그래밍`

### ▢ 구조적 프로그래밍 설계서 구성요소 및 작성 방법

#### ▣ 구조적 프로그램 구성요소

1. `데이터 흐름도`
2. `자료사전`
3. `상태 전이도 STD`
4. `소단위 명세 Minispec`

#### ▣ DFD 기반 구조적 프로그래밍 설계 요소

#### ▦ DFD 구성요소

㉠`프로세스`  
㉡`데이터 흐름(Data Flow)`  
㉢`데이터 저장소(Data Store)`  
㉣`외부 엔티티`  

## 《1 - 2. 구조적 프로그래밍 언어 활용》

### ▢ 구조적 프로그래밍 언어 개요
구조적 프로그래밍은 구조화된 조직 체계의 모양처럼 하나의 프로그램이 구  
조를 갖도록 만들어 나가는 프로그래밍 방법을 말한다. 기본 제어 구조인  
순차 구조, 선택 구조, 반복 구조를 이용하여 프로그램의 흐름을 구조화시키  
고 간결하게 만드는 방식으로 사용하는 언어이다.  

⑴ `절차식 언어`  
⑵ `명령어 언어 `  
⑶ `함수 중심 언어`  

### ▢ 구조적 프로그래밍 유형

⑴`C언어`  
⑵`파스칼(Pascal)`  
⑶`에이다(Ada)`  

### ▢ 주요 구현 언어 문법

⑴`조건문`  
⑵`반복문`  

## 《2 - 1. 라이브러리 활용》

### ▢ 객체지향 설계 원칙의 이해

#### ▣ 객체지향 속성

⑴ `캡슐화`  
⑵ `추상화`  
⑶ `다형성(오버로딩, 오버라이딩)`  
⑷ `정보 은닉`  
⑸ `상속성`  

#### ▣ 객체지향 설계 원칙

⑴ `단일 책임 원칙`  
⑵ `개방-폐쇄 원칙`  
⑶ `리스코프 치환 원칙`  
⑷ `인터페이스 분리 원칙`  
⑸ `의존 역전 원칙`  

## 《2 - 2. 객체지향 프로그래밍 언어 활용》

### ▢ 객체지향 프로그래밍 언어의 개요
프로그래밍에서 필요한 데이터를 추상화시켜서 상태와 행위를 가진 객체  
를 만들고, 그 객체들 간의 유기적인 메세지를 통해 상호작용 로직을 구성하는  
프로그래밍 방법이다.  

#### ▣ 객체지향 프로그래밍 언어 구성 요소

⑴ `클래스`  
⑵ `객체`  
⑶ `메소드`  
⑷ `속성`  

### ▣ 접근 지정자

⑴ `public`  
⑵ `protected`  
⑶ `private`  
⑷ `dafault`  

### ▢ 객체지향 프로그래밍 언어 기본 문법

⑴ `데이터 타입`  
⑵ `변수와 메소드`  
#### ▣ 변수 유형  
	⑴ 멤버 변수
	⑵ 인스턴스 변수
	⑶ 매게 변수 
	⑷ 지역 변수
	⑸ 클래스 변수

⑶ `메소드`  
⑷ `연산자`   

### ▢ 디자인 패턴
디자인 패턴은 객체지향 프로그래밍 시 발생하는 여러 가지 문제에 대한 설  
계 사례를 분석하여 공통저긍로 발생하는 문제를 해결하기 위한 방법론으로,  
여러 설계들로 분류하고, 각 문제 유형별로 가장 적합한 설계를 일반화 한   
패턴이다.  

#### ▣ 디자인 패턴 구조  

⑴ `콘텍스트`  
⑵ `문제`  
⑶ `해결`  

#### ▣ 디자인 패턴의 종류

✨별로 중요하지 않을 뜻  
⑴ `GoF 디자인 패턴`   
⑵ `GoF 디자인 패턴의 분류`  

## 《3 - 1. 스크립트 언어 설계》

### ▢ 스크립트 언어 개요
스크립트 언어는 응용 소프트웨어를 제어하는 컴퓨터    
프로그래밍 언어이다. 초창기 스크립트 언어는 배치 언어    
또는 작업 제어 언어라고도 불렸다.    

#### ▣  스크립트 언어 특징

⑴ `인터프리터 언어`   
⑵ `단순한 구문`  
⑶ `컴파일 시간 소요(오래)`  
⑷ `신속한 활용`  

### ▢ 기능 설계서와 화면 설계서
✨아래 페이지에서 보기  
P.20  

## 《3 - 2. 스크립트 언어 활용》

### ▢ 스크립트 언어의 유형과 원리

#### ▣ 스크립트 프로그래밍 언어 유형

⑴ `JavaScript`  
⑵ `jQuery`  
⑶ `JSP`  
⑷ `PHP`  
⑸ `ASP`  
⑹ `Python`  
⑺ `VBScript`  

### ▣ 스크립트 프로그래밍 원칙

⑴ `스크립트 코드 작성`  
⑵ `Byte Code 변환`   
⑶ `기계어 변환`    
⑷ `CPU 코드 변환`  

### ▢ JavaScript 언어의 이해  
자바스크립트는 객체지향의 프로그래밍 언어로서 웹 브라우저에서 주로 사  
용된다. 자바스크립트를 이용하여 웹 페이지에서 발생하는 사용자 이벤트에   
대한 처리가 가능하고, 자바 스크립트의 내장 객체를 활용하면 다양한 형태  
의 웹 페이지를 구현할 수 있다.  

### ▣ 자바스크립트 구현 예
✨P.23 ~ P.24 보세요!  

## ✅Ⅰ. 프로그래밍 언어 활용 끝✅

# ✨Ⅱ. 애플리케이션 배포✨

## 《1 - 1. 애플리케이션 배포환경 구성》

### ▢ 소스코드 빌드 과정의 이해  
빌드는 프로그래머가 작성한 소스코드를 실행할 수 있는 상태로 변환하는  
과정을 말하며, 프로그래밍 언어의 유형에 따라 차이가 있다.  

⑴ `컴파일 언어(C, C++ 등)`  
⑵ `Byte Code 언어(Java, C# 등)`  
⑶ `인터프리터 언어(JavaScript, Python, Ruby)`  

### ▢ 애플리케이션 배포 환경

⑴ `웹 서버(Web Server)`  
⑵ `WAS`  

### ▢ 애플리케이션 배포 단위

⑴ `jar`  
⑵ `war`  
⑶ `ear`  

### ▢ 형상관리 시스템

#### ▣ 형상관리 시스템에서 사용하는 용어

⑴ `형상관리`  
⑵ `형상항목`  
⑶ `기준선`  
⑷ `마이그레이션`  
⑸ `리포지터리`  
⑹ `워크플로`  
⑺ `반출(Check Out)`  
⑻ `반입(Check In)`  

## 《2 - 1. 애플리케이션 소스 검증》

### ▢ 소스코드 검증도구

#### ▣ 소스코드 검증도구의 용도

⑴ `정적 테스트 도구 사용 목적`  
⑵ `동적 테스트 도구 사용 목적`  

### ▢ 코드 인스펙션
코드 인스펙션은 정적 테스트의 가장 일반덕인 유형으로, 사전에 정의된 코  
드 작성 규칙 기반으로 소스코드를 점검하여 작성 규칙에 위반되는  
소스코드를 추출하는 분석 도구로 애플리케이션 개발 시 대부분 사용되면   
빌드 도구와 연계하여 빌드•배포 수행 시 자동적으로 점검할 수 있다.  

#### ▣ 코드 인스펙션 Rule 유형

⑴ `성능 개선`  
⑵ `코드 작성 규칙`  
⑶ `에러 발생 가능성`  

#### ▣ 코드 작성 Rule 심각도 구분(예시)

⑴ `필수, Blocker`  
⑵ `권고 상, Critical`  
⑶ `권고 중, Major`  
⑷ `권고 하, Minor`  
⑸ `정보, Info`  

### ▢ 테스트 프레임워크의 구성

#### ▣ 테스트 프레임워크의 구성

⑴ `테스트 코드`  
⑵ `테스트 저장소`  

## 《3 - 1. 애플리케이션 빌드》

### ▢ 지속적인 통합 환경

⑴ `빌드 도구`  
⑵ `테스트 도구`  
⑶ `소스코드 품질 측정도구(코드 인스펙션)`  
⑷ `테스트 커버리지 측정도구`  
⑸ `빌드 스케줄 관리도구`  

### ▢ 테스트 커버리지

#### ▣ 테스트 커버리지 측정 유형

⑴ `라인 커버리지`  
⑵ `분기 커버리지`  
⑶ `조건 커버리지`  

### ▢ 빌드 스케줄 관리도구

#### ▣ 빌드 스케줄 관리도구의 기능

⑴ `빌드 작업 스케줄링`  
⑵ `빌드 작업의 작업 주기, 작업 시간을 설정한다.`  
⑶ `빌드 도구 연계 관리`  
⑷ `빌드 수행 결과 리포팅`  

## 《4 - 1. 애플리케이션 배포》

### ▢ 운영 환경의 특징
기업의 IT 인프라 운영 환경은 안정적인 IT 서비스 운영 관리를 위해서 애  
플리케이션 배포 및 변경 작업에 대한 관리, 통제를 강화하고 있으며, 여러  
가지 제약 사항을 가지고 있다.  

⑴ `네트워크 관점`
⑵ `계정 관리 부분`
⑶ `보안 취약점 부분`

## ✅Ⅱ. 애플리케이션 배포 끝✅

# Ⅲ. 응용 SW 기초 기술 활용

## 《1 - 1. 네트워크 프로토콜 활용》

### ▢ 네트워크 계층 구조

#### ▣ OSI 7 계층  
#### ▣ TCP/IP 프로토콜 스택  

### ▢ 인캡슐레이션과 디캡슐레이션
🍏P.45 ~ P.47쪽 보세요!   

#### ▣ 라우팅 유형

⑴ `정적 라우팅`  
⑵ `동적 라우팅`  

## 《2 - 1. 미들웨어 파악》

### ▢ 미들웨어

#### ▣ 미들웨어 개념
하나의 시스템에서 다양한 목적의 응용소프트웨어가 동시에 수행되거나 복수 시스  
템의 응용소프트웨어가 서로 연계되어 수행되는 경에에도 안정적으로 실행될 수   
있도록 운영체제와 응용소프트웨어 사이에서 다양한 기능을 지원하는 소프트웨어이다.  

#### ▣ 미들웨어 주요기능

⑴ `분산 시스템 SW`  
⑵ `IT 자원 관리`  
⑶ `서비스 플랫폼`  
⑷ `네트워크 보안`  

## 《2 - 2. 미들웨어 운용》
🍋별로 중요해 보이지 않음..  
P.52 ~ 54 훑어보기  

### 《3 - 1. 데이터베이스 특징 식별》
### 《3 - 2. 관계형 데이터베이스 테이블 정의》
### 《3 - 3. 관계형 데이터베이스 테이블 조작》
🍋정리하기 너무 힘들어서 뚩어보기    
P.55 ~ 64 훑어보기  

## ✅Ⅲ. 응용 SW 기초 기술 활용✅

# Ⅳ. 화면 구현

## 《1 - 1. UI설계 내용 확인》

### ▢ UI
사용자가 하드웨어나 시스템에 연결되는 과정에서 사용자의 편리성과 가독  
성을 높여 주기 위한 것이다.  

⑴ `CLI`  
⑵ `GUI`  
⑶ `NUI`  

### ▢ UI 개발 도구 분류

#### ▣ 화면 설계

⑴ `와이어프레임`  
⑵ `스토리 보드`  
⑶ `목업`  

#### ▣ 프로토타입
#### ▣ UI 디자인

## 《1 - 2. UI 메뉴 구조 확인》

▢ `사용성`  

▢ `유용성`  

▢ `정보 구조`  

▢ `내비게이션`  

▢ `유스케이스`  

## 《2 - 1. UI 구현하기》

▢ `W3C`   

▢ `한국형 웹 콘텐츠 접근성 지침`  

▢ `전자정부 웹 표준 준수 지침`  

#### ▣ 웹 표준  
#### ▣ 웹 접근성  
#### ▣ 웹 호환성  

## 《2 - 2. UI 구현》

### ▢ 서버와 클라이언트

#### ▣ 서버
#### ▣ 클라이언트

▢ `웹 사이트와 웹 페이지`

▢ `HTML`

▢ `CSS`

▢ `자바스크립트(JavaScript)`

🍊**정리하기 애매한 내용**   
P.80 ~ P.104쪽 흝어보기!  

## 2 - 3. UI테스트》

### ▢ 사용성 테스트

🍏**이 부분은 너무 정리하기 애매하여 흝어보기**  
P.105쪽  

### ▢ 사용성 테스트 과정(중요!)✨

⑴ `계획 수립`  
⑵ `테스트 설계`  
⑶ `테스트 실행`  
⑷ `결과 보고서 작성`  

▢ `테스트 케이스의 작성`  
▢ `유효성 검사`  

🍊**정리하기 애매한 내용**  
P.106 ~ P.109쪽 흝어보기  

## ✅Ⅳ. 화면 구현 끝✅

# ✨Ⅴ. 애플리케이션 테스트 수행✨

## 《1 - 1. 테스트 수행》

### ▢ 테스트의 개요
테스트는 단위 테스트, 통합 테스트, 시스템 테스트, 인수 테스트의 순으로 진행된다.

#### ▣  프로젝트 수행 단계에 따른 테스트의 분류

⑴ `단위 테스트`  
⑵ `통합 테스트`  
⑶ `시스템 테스트`  
⑷ `인수 테스트`  

#### ▣ 프로젝트 수행에 따른 테스트의 접근 방법
P.114 ~ P.119쪽 흝어보기!

## 《1 - 2. 결함 관리》

### ▢ 결함의 정의

⑴ `결함은 프로그램과 명세서 간의 차이, 업무 내용 불일치이다.`  
⑵ `결함은 기대 결과와 실제 관찰 결과 간의 차이이다.`  
⑶ `시스템이 사용자가 기대하는 타당한 기대치를 만족시키지 못할 때`
`변경이 필요한 모든 것은 결합이다.`

### ▢ 결함관리 프로세스

⑴ `결함관리 계획`  
⑵ `결함 기록`  
⑶ `결함 검토`  
⑷ `결함 수정`  
⑸ `결함 재확인`  
⑹ `결함 상태 추적 및 모니터링 활동`  
⑺ `최종 결함 분석 및 보고서 작성`  

### ▢ 결함의 상태 및 추적

⑴ `결함 등록`  
⑵ `결함 검토`  
⑶ `결함 할당`  
⑷ `결함 수정`  
⑸ `결함 조치 보류`  
⑹ `결함 종료`  
⑺ `결함 해제`  

### ▢ 결함 분류

⑴ `시스템 결함`  
⑵ `기능 결함`  
⑶ `GUI 결함`  
⑷ `문서 결함`  
⑸ `결함 심각도`  

## 《2 - 1. 조치 우선순위 결정》

### ▢ 소프트웨어 테스트 기법

#### ▣ 단위 테스트 기법

⑴ `JUnit을 활용한 테스트 `  
⑵ `Mock 테스트`

#### ▣ 통합 테스트 기법
전체 시스템이 통합 완료될 때까지 단위 시스템 간의 연계성 및 기능 요  
구사항들을 확인하고, 하트웨어와 소프트웨어 구성 요소 간의 상호 작용을 테스트하는   것이 주요 목적이다.  

#### ▣ 시스템 테스트 기법

⑴ `부하 및 성능 테스트`  
⑵ `장애 복구 테스트`  
⑶ `보안 테스트`  
⑷ `인수 테스트 기법`  

### ▢ 결함관리의 이해

#### ▣ 결함 관련 용어

⑴ `에러`  
⑵ `오류`  
⑶ `실패`  
⑷ `결함`  

**P.130 ~ P.131쪽 흝어보기!**  

## 《2 - 2. 결함 조치 관리》

### ▢ 프로그램 코드 검토 기법

#### ▣ 인스펙션 중점 항목

⑴ `자동 코드 인스펙션을 위한 환경 지원, 계획 수립 지원 활동`  
⑵ `체크리스트 정합성 검토 지원 활동`  
⑶ `인스펙션 결과 리뷰 참석`  
⑷ `발견된 결함을 수정하기 위한 개발자 리딩 지원 활동`  

### ▢ 형상 관리 및 구성 요소

#### ▣ 소프트웨어 형상 관리의 정의

⑴ `소프트웨어 프로세스의 모든 출력물 정보`  
⑵ `컴퓨터 프로그램, 컴퓨터 프로그램 설명 문서, 데이터 등`  
⑶ `소프트웨어 프로세스 전반에 걸쳐 소프트웨어 형상의 변경 요인에 대해`  
`소프트웨어 형상을 보호하는 활동`  

#### ▣ 기준선과 소프트웨어 형상 항목

⑴ `기준선`  
⑵ `소프트웨어 형상 항목`  
⑶ `형상 관리의 주요 활동`  
    ▣ `형상 관리 기능`  
    ▣ `형상 식별`  
    ▣ `버전 관리`  
    ▣ `변경 통제에 대한 업무별 활동`  

## ✅Ⅴ. 애플리케이션 테스트 수행✅
 
# Ⅵ. SQL 활용

🍎**이 부분은 전체적으로 봐야 함**   
P.143 ~ P.162쪽  

## ✅Ⅵ. SQL 활용✅

# ✨Ⅶ. UI 테스트✨

## 《1 - 1. 테스트 기법 선정》

▢ `휴리스틱 평가`  
▢ `페이퍼 프로토타입 평가`  
▢ `선호도 평가`  
▢ `성능 평가`  

## 《1 - 2. 테스트 환경 구축》

▢ `사용자 중심 디자인`  
▢ `인터랙션 디자인`  
▢ `프로토타입`  
▢ `와이어프레임`  
▢ `시장현황보고서`  
▢ `기술현황 보고서`  

## 《1 - 3. 사용성 테스트 계획서 작성》

▢ `사용성`     
▢ `사용성 테스트`    
▢ `테스트 계획서`  
▢ `테스트 계획서 항목`  
▢ `인터페이스`  
▢ `그래픽 사용자 인터페이스`  
▢ `UI 디자인`  
▢ `UX 디자인`  
▢ `태스크 설정`  

## 《2 - 1. 사용성 테스트 수행》

▢ `파일럿 테스트`  
▢ `심층 인터뷰`  
▢ `포커스 그룹 인터뷰`  
▢ `맥락적 인터뷰`  

## 《2 - 2. 평가 분석서 작성 및 이슈 도출》

▢ `태스크 성공 매트릭스`  
▢ `에러 매트릭스`  
▢ `효율성 매트릭스`  
▢ `시간 기반 태스크 매트릭스`  
▢ `데이터 이력기록기`  
▢ `옵저베이션`  
▢ `테스트 신뢰성`  
▢ `NEM 기법`  

## 《3 - 1. UI 개선방안 및 수정계획 수립》

▢ `UI 디자인`  
▢ `UI 컨셉션`  
▢ `GUI 컨셉션`  
▢ `UX 컨셉 리뷰`  
▢ `컨셉모델`  
▢ `멘탈모델`  
▢ `카드 소팅`  

## 《3 - 2. UI 개선 결과 보고서 공유》

▢ `사용자 중심 메뉴얼`  
▢ `ISO/IEC 9126`  
▢ `정량적 리서치`  
▢ `정성적 리서치`  

## ✅Ⅶ. UI 테스트 끝✅

# ✨Ⅷ. 개발자 환경 구축✨

## 《1 - 1. 운영체제 식별》

### ▢ 운영체제
	- 컴퓨터 시스템이 제공하는 하드웨어(H/W)와 소프트웨어(S/W) 기능을
	  사용할 수 있도록 해주는 시스템 소프트웨어(S/W)
	- 한정된 시스템 자원을 효율적으로 사용할 수 있도록 관리 및 운영함으로써 
      사용자에게 편리성 제공

#### ▣ 운영체제의 주요 기능
⑴ `처리능력 향상`   
⑵ `응답시간 단축`  
⑶ `신뢰도 향상`  
⑷ `컴퓨터 시스템과 사용자 간 인터페이스 기능 제공`  
⑸ `출력 역활 지원`  
⑹ `각 프로그램과 사용자 간 보호`  
⑺ `주기억 장치 관리`  
⑻ `CPU를 통한 프로그램 실행 관리`  
⑼ `컴퓨터 시스템 낸 파일 관리`  
⑽ `컴퓨터 시스템 명령어 해석/수행`  

#### ▣ 운영체제의 종류
⑴ `윈도즈 OS`   
⑵ `UNIX`  
⑶ `Linux`  
⑷ `iOS`  
⑸ `Android`  

## 1 - 2. 운영체제 기본 명령어 활용》

### ▢ 운영체제 기본 명령어 사용 환경

#### ▣ CLI
#### ▣ GUI

## 《1 - 3. 운영체제 작업 우선순위 설정》

### ▢ 운영체제 프로세서 개요

#### ▣ 운영체제의 프로세스의 개념
#### ▣ 운영체제의 프로세스의 특징
P.197쪽

### ▢ 운영체제 프로세스 종류

#### ▣ 순차 프로세스
#### ▣ 병행 프로세스

### ▢ 프로세스 상태의 개념

#### ▣ 상태
#### ▣ 준비 리스트와 대기 리스트 

## 《2 - 1. 운영체제 설치》

### ▢ 운영체제별 개발환경의 이해
	- 개발환경 구축은 설하는 운영체제에 따라 웹 서버, 데이터베이스, 프
	  프로그래밍 언어가 상이할 수 있음
	- 운영체제별 벤더사에 종속되거나 호환성 확보를 위해서는 별도의 프로
	  그램을 필요에 따라 설치할 수 있음

### ▢ 시스템 설치보고서의 이해
⑴ `시스템 개요`  
⑵ `시스템 설치`  
⑶ `상세 작업내역`  
⑷ `플랫폼 설치 결과`  
⑸ `시스템 설치 결과`  
⑹ `시스템 정기 점검`  

### 《2 - 2. 개발도구 설치》

### ▢ 응용소프트웨어 개발도구 종류 및 용도
P.201 ~ P.202쪽

### 《2 - 3. 개발도구 활용》

### ▢ 개발도구

#### ▣ 통합개발환경(IDE)

P.203 ~ P.204쪽

## ✅Ⅷ. 개발자 환경 구축✅

# Ⅸ. 프로그래밍 언어 응용

## 《1 - 1. 언어별 특성 파악》

### ▢ 프로그래밍 언어의 유형 분류

#### ▣ 개발 편의성 측면에 따른 분류
⑴ `저급언어`  
⑵ `고급언어`  

#### ▣ 실행 및 구현 방식에 따른 분류
⑴ `명령형 언어`  
⑵ `함수형 언어`  
⑶ `논리형 언어`  
⑷ `객체지향언어`  

#### ▣ 빌드 방식에 따른 분류
⑴ `컴파일 언어`  
⑵ `인터프리터 언어`  
⑶ `바이트 코드 언어`  

### ▢ 절차형 언어와 객체지향 언어의 차이
절차지향의 경우 절차(실행 순서)가 중점이 되고, 객체지향의 경우 객체의  
종류와 속성 등에 더 중점을 둔 개발 패러다임을 의미한다.  

### ▣ 객체지향의 구성요소
⑴ `객체`  
⑵ `클래스`  
⑶ `메시지`  

### ▣ 객체지향의 특징
⑴ `캡슐화`  
⑵ `정보 은닉`  
⑶ `추상화`  
⑷ `상속`  
⑸ `다형성`  

## 《1 - 2. 애플리케이션 구현 및 최적화》

### ▢ 코드 인스펙션

#### ▣ 인스펙션 수행 절차
⑴ `계획`  
⑵ `개관`  
⑶ `준비`  
⑷ `검토회의`  
⑸ `재작업`  
⑹ `추적`  

🍏**정리하기 애매**  
P.219 ~ P.236쪽 까지 흝어보기!

## 《2 - 1. 라이브러리 선정》

### ▢ 라이브러리

### ▣ 라이브러리 개념과 목적
라이브러리란 영어로 도서관을 의미하며 코드의 재사용 및 부품화, 기술 유  
출 방지를 위하여 하나 이상의 Subroutine 혹은 Function들의 집합으로 일반적으로  
컴파일되어 실행이 가능한 Object Code 형태로 제공된다.  

### ▢ 라이브러리 유형
#### ▣ 별도 설치 여부에 따른 유형 
⑴ `표준 라이브러리`  
⑵ `외부 라이브러리`  
#### ▣ 코드 결합 방식에 따른 유형
⑴ `정적 라이브러리`  
⑵ `동적 라이브러리`  

🍏**정리하기 애매**
P.238 ~ P.247쪽 흝어보기!

## 《2 - 2. 라이브러리 구성 및 적용》

### ▢ 모듈과 패키지
라이브러리는 모듈과 패키지를 모두 포함하며, 모듈의 경우 갭별 파일을 지  
칭하고 패키지의 경우 여러 개의 파일을 모아놓은 폴더로 생각할 수 있다.  

## ✅Ⅸ. 프로그래밍 언어 응용 끝!✅