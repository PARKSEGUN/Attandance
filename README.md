# 📄지식 복습

- 2024.01.22 - 상속에서의 오버라이딩은 부모보다 좁은 범위로 설정될 수 없다, java에서의 String의 크기는 불변하다
- 2024.01.25 - 재귀 알고리즘은 분할정복의 한종류의 해결법, 변수의 중복으로인한 복잡성을 해결할 수 있다 진행상태의 정보를 저장하기때문
- 2024.01.26 - 다이나믹프로그래밍은 분할정복의 종류로 중복되는 계산을 찾고 이전에 계산한값을 미리 저장해서 사용, 점화식을 이용해서 해결
- 2024.01.30 - Java에서의 우선순위큐는 가장 작은 값이나 가장 큰값을 반환해주는 것은 보장해주지만, 정렬된 데이터를 보장해주진않는다.
- 2024.02.02 - 트리는 각 노드에서 루트까지의 경로가 한가지이다. 연결정보를 저장해줄때에는 한방향으로만 저장해주면된다.
- 2024.02.10 - RDBMS와 NOSQL의 차이는 정해진 스키마가 있냐 없냐 차이이다.
- 2024.02.11 - delete는 데이터 삭제, turncate는 테이블내 모든 데이터 삭제(복구불가), drop 인덱스나, 테이브 제거(복구불가)
- 2024.02.12 - DB에서 인덱스를 활용해서 데이터에 빠르게 접근할 수 있지만 하나의 데이터에 접근하는 속도보다 4 ~ 5배정도 느리기때문에 인덱스의 사용이 많아지게된다면 오히려 속도가 느려질 수 있다
- 2024.03.07 - 웹페이지를 구성하는 3가지 요소는 html, css, js 가 있다 html은 뼈대, css 는 스타일, js 는 동작을 담당한다.
- 2024.03.10 - 트랜잭션의 격리성 수준에는 uncommited read(커밋안되도 조회), commited read(커밋된것만 조회), repeatable read(트랜잭션이 시작되기 이전의 상태만 조회가능), serializable read(현재 트랜잭션이 사용하는 테이블 이용불가)가 있다.
- 2024.03.11 - HTML을 꾸며주는 CSS를 사용하는 방식의 효율성을 높여주기위해서 **부트스트랩**이 만들어졌다. 클래스의 이름에 해당 엘리먼트가 가질 수 있는 성질을 정의해준다.
- 2024.03.14 - 인덱스는 Clustered Index와 None Clustered Index가 있다. Clustered Index는 실제 데이 데이터를 지정된 컬럼을 기준으로 정렬시킨다. Index  Page에는 키값과 실제 정렬된 데이터 페이지를 연결할 수 있는 페이지 번호가 저장되어있다. (테이블당 하나)
  None Clustered Index는 별도의 장소에 인덱스 페이지를 생성한 후 만들어진 인덱스 페이지를 통해 실제 데이터에 접근한다. (테이블당 여러개 가능)
- 2024.03.18 - DB 드라이버로 Connection을 생성하고, Connection으로 PrepareStatement를 생성하고, PrepareStatement로 ResultSet을 생성하는 순서가 자바 언어로 DB에 연결하고 쿼리를 실행할 수 있도록 하는 API
- 2024.03.24 - 하나의 쿼리로 하나의 객체를 조회할때에 조회한 객체가 또 다른 객체와 연결되어있다면 이 객체를 조회해야하는 하나의 쿼리가 또 필요하게된다. 만약 그 객체가 N개의 객체를 포함하고 있다면 처음 조회를 시작할 1개의 쿼리와 그 안의 N개의 객체를 조회하기위한 N개의 쿼리가 필요하게된다. 이러한 문제점을 N+1 문제 라고한다.
- 2024.04.12 - DBMS란 데이터베이스 관리 시스템으로 사용자가 DB에 저장된 데이터를 원활하게 사용할 수 있게 해주는 응용프로그램입니다. RDBMS는 테이블에 저장된 데이터를 관계형 데이터 모델링을 기반으로 사용하고 SQL을 사용해서 데이터에 쉽게 접근할 수 있습니다.
