# Database

## Database 란?

데이터베이스(영어: database, DB)는 여러 사람이 공유하여 사용할 목적으로 체계화해 통합, 관리하는 데이터의 집합이다. 작성된 목록으로써 여러 응용 시스템들의 통합된 정보들을 저장하여 운영할 수 있는 공용 데이터들의 묶음이다.

## Database 개념

여러 사람이 공유하고 사용할 목적으로 통합 관리되는 정보의 집합이다. 논리적으로 연관된 하나 이상의 자료의 모음으로 그 내용을 고도로 구조화함으로써 검색과 갱신의 효율화를 꾀한 것이다. 즉, 몇 개의 자료 파일을 조직적으로 통합하여 자료 항목의 중복을 없애고 자료를 구조화하여 기억시켜 놓은 자료의 집합체라고 할 수 있다.

공동 자료로서 각 사용자는 같은 데이터라 할지라도 각자의 응용 목적에 따라 다르게 사용할 수 있다.

#### 데이터베이스의 특징

- 실시간 접근성
- 지속적인 변화
- 동시 공유
- 내용에 대한 참조
- 데이터 논리적 독립성


### 데이터베이스의 장단점

#### 데이터베이스 장점

- 데이터 중복 최소화
- 데이터 공유
- 일관성, 무결성, 보안성 유지
- 최신의 데이터 유지
- 데이터의 표준화 가능
- 데이터의 논리적, 물리적 독립성
- 용이한 데이터 접근
- 데이터 저장 공간 절약


#### 데이터베이스 단점

- 데이터베이스 전문가 필요
- 많은 비용 부담
- 데이터 백업과 복구가 어려움
- 시스템의 복잡함
- 대용량 디스크로 엑세스가 집중되면 과부하 발생

## Database 모델

### 관계 데이터 모델


관계 데이터모델 (relational datamodel)은 데이터 모델 중에서 가장 개념이 간단한 모델이다. IBM 연구소에서 근무하던 코드(E.F.Codd)가 1970년에 제안했다. 이 모델은 상대 수학적인 이론을 기반으로 한다. 코드가 수학자였기 때문에 수학 분야, 특히 집합론과 논리분야의 개념을 사용했다. 데이터 모델을 개발하기 위해서 테이블 관계로 묘사하는 이론적 모델 과정이 발생하는데 이를 개체관계모델(영어:entity relational model)이라고 한다. 이 관계 데이터베이스를 위한 설계과정은 이론적으로 관계수학에 기초한 실지 구현이라 보면 된다. 현실 세계는 객체관계 그림(다이어그램)으로 표현되며, 개체와 그 관계는 각기 사각과 선으로 그려진다.

### SQL


개체 관계형 데이터베이스를 지원하기 위해 1974년 IBM 연구소에서 만든 SQL(Structured Query Language)(원어(SEQUEL):Structured English Query Language)가 창안되었으며, 이 언어는 수학적 관계 대수와 관계 논리(relational calculus)에 기반을 두고 있다. 데이터 모델은 데이터를 조작하기 위한 연산집합을 가져야 한다. 왜냐하면 그것은 데이터베이스 구조와 제약 조건을 정의하기 때문이다. 다시 말해, 관계 데이터모델 연산집합(a set of operations)은 관계대수로 표현되고, 그 연산은 사용자에게 여러 질의를 가능하게 한다.

## Database 관리 시스템 선택

데이터베이스 설계 후 데이터베이스 관리 시스템을 사용해야 한다. 여러가지 데이터베이스 관리 시스템 선택 사항(DBMS)이 존재한다.

데이터베이스 관리 시스템으로 현재에는 많이 사용하지 않으나 IBM 메인프레임 환경 하에서 운영되는 'IMS'가 있다. IMS는 정보 관리 시스템(Information Management System)의 약자로 DBMS와 DC 기능을 수행한다. IMS가 관리하는 DB 종류에는 'DEDB'와 'MSDB'가 있다. DEDB는 Data Entry DB로 전통적인 계층형 DB이며 MSDB는 주기억 DB로 시스템 가동시 주 메모리에 상주하는 DB로 빠른 접근이 필요한 업무에 사용된다. 다만, 접근 속도가 매우 빠른 반면 메모리에 상주하기 때문에 용량 및 구조에 제한이 많다.

출처 : https://ko.wikipedia.org/wiki/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4
