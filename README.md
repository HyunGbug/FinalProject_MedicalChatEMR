# FinalProject_MedicalChatEMR
#[매디컬 챗 EMR]

2. 데이터 수집
API, 그림 데이터, 텍스트 데이터

3. REST API를 통한 HTTP 요청을 통해 통신해 레코드 생성 읽기 ,업데이트 및 삭제(CRUD) 등의 DB 수행 방식 사용, 
Spring MVC구조 사용, MyBatis 사용하여 데이터베이스 연동

4. 역할 분담
박홍석 : 조장, 발표, DB관련, Api 연동
임준혁 : DB관련, Api 연동, 
정민석 : 전체 디자인 수정, DB관련, 디자인
정현지 : 메인페이지 디자인, DB관련, Api 연동 
현지수 : 채팅 알림, 


5. 개발일정 계획(~8/23)
총 5주의 프로젝트

1주차 : 
 - 구체적인 방향성 잡기
 - 역할 분담 및 필요한 부분 공부, 협업 공간 마련(노션, 깃)
 - 데이터 수집 및 서비스의 구체적인 타겟과 메인 기능을 하나만 선정 
 - 기본 디자인 선택 ( 대표색상 )
 - 채팅, 웹소켓 : 연결 지향, 한번 연결 맺은 뒤 유지, 양방향 통신
 - 각 맡은 파트에 대해 구체적인 계획과 변수이름 등 공유 후 데이터베이스 수립
 - 페이지 초안(그림으로 버튼 위치 등 서로 상호작용해야 하는 부분의 레이아웃 정리)

2주차 : (7/27~ 8/2)
 - 월 : 메인화면 UI 설정
 - 화 : UI 세부적 역할분담, 깃 공부
 - 수 : 간호사의 할 일, 의사의 할 일 필요한 것 정보수집 및 정리, 
        툴 및 필요 기술스택 설정( 스프링부트(STS4, IDEA), REST형 API 호출 )
 - 목 : 개인 파트 공부 스타트, 깃 포크 및 풀 리퀘스트 완료, 의사 UI 초안 완성
 - 금 : 개인 파트 공부,  뷰어기능 DB저장 진행중, 메인화면 UI 디자인 완성

박홍석 : 스프링부트 공부, api연동 공부, 레스트공부, 수간호사 ui 구현 중
임준혁 : 스프링부트 공부, STS4 사용해서 dcm파일을 데이터베이스에 파일과 여러 정보를 저장 후 이미지 파일을 화면에 불러오는 테스트 성공
정민석 : 스프링부트 공부, 메인화면, 환자 클릭 때의 화면 구현
정현지 : 스프링부트 공부, 전체적인 ui 목업 및 직업 기능 구축, 필요한 데이터베이스 컬럼 정리
현지수 : 스프링부트 공부, 의사 ui 코드화, 의사, 관리자 기능 구축

3주차 : (8/3 ~ 8/9)예정
박홍석 : 스프링부트 공부, api연동 공부, 레스트공부, 수간호사 ui완성
임준혁 : 스프링부트 공부,  spring boot로 이미지 불러오는거 해결 후 뷰어 기능 구현 할 예정
정민석 : 스프링부트 공부, 처방전(의약품 api) 따오기 => REST방식 사용, 공공데이터 포럼 사용
정현지 : 스프링 부트 공부, DB 일반 간호사 페이지 환자 정보 수정 기능 추가
현지수 : 스프링 부트 공부, 웹소캣 공부(메신저 기능), 관리자 ui































        
//알림 서비스
//: 
//Spring AOP를 통해 기능 분리, 유지보수성, 확정성을 위해 Spring Annotation을 활용
//Notify와 관련된 controller,dto,entity,repository,service 클래스를  정의

//2주차 : 각자 맡은 부분 공부 하면서, 개발 스타트
//3주차 : 

의료영상을 보고 추후 변동 가능성 있음




Cornerstone_api를 이용한 Viewer 구현중
