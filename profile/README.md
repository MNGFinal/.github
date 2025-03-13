# ☕CafeSync
![modern-browser-mockup](https://github.com/user-attachments/assets/fceef9ef-d8b3-4f7a-8c75-182f4b3b9dba)

프로젝트 기간 25.02.17 ~ 25.03.14 <br/>

---

[🤝Discussions](https://github.com/orgs/MNGFinal/discussions) | [👍Front-PR](https://github.com/MNGFinal/CafeSync-Front/pulls?q=is%3Apr+is%3Aclosed) | [👍Back-PR](https://github.com/MNGFinal/CafeSync-Back/pulls?q=is%3Apr+is%3Aclosed) | [🖥️Front-Issues](https://github.com/MNGFinal/CafeSync-Front/issues?q=is%3Aissue%20state%3Aclosed) | [🔙Back-Issues](https://github.com/MNGFinal/CafeSync-Back/issues?q=is%3Aissue%20state%3Aclosed) | [👨‍💻Front-Project](https://github.com/MNGFinal/CafeSync-Front/projects?query=is%3Aopen) | [👩‍💻Back-Project](https://github.com/MNGFinal/CafeSync-Back/projects?query=is%3Aopen)

---

## 🔗 빠른 이동
- [프로젝트 소개](#프로젝트-소개)
- [프로젝트 일정](#프로젝트-일정)
- [아키텍처](#아키텍처)
- [기술 스택](#기술-스택)
- [기능 설명](#기능-설명)
- [논리 & 물리 데이터 모델링](#논리--물리-데이터-모델링)
- [Wiki](#Wiki)

## 프로젝트 소개
### 📌 프로젝트 개요
CafeSync는 대형 프랜차이즈 카페의 운영을 본사와 가맹점과의
<br/>
통합 및 재고관리를 최적화하여 데이터 기반 의사결정을 지원하는 ERP 프로젝트 입니다.
<br/><br/>
가맹점이 보다 효율적으로
<br/>
재고 관리, 매출 분석, 직원 배치, 메뉴 구성 등을 할 수 있도록 돕는 스마트 카페 운영 솔루션을 제공합니다
<br/><br/>
### 🔥 CafeSync의 핵심 기능
✅ 1. 효율적인 재고 관리
- 각 지점별 실시간 재고 현황을 한눈에 확인
- 부족한 재고를 자동으로 감지하고 신속하게 발주
- 수요 예측 기능을 통해 매출 손실 최소화

✅ 2. 데이터 기반 의사결정 지원
- 운영 데이터를 분석하여 전략적인 의사결정 지원
- 매출 분석 대시보드 제공 → 인기 메뉴/시간대 분석
- 비용 절감 및 수익 증가를 위한 인사이트 제공

✅ 3. 운영 최적화
- 직원 스케줄링 및 배치 최적화
- 마케팅 및 프로모션 전략 분석 지원
- 지점별 운영 효율성 비교 및 개선점 도출

[🟨팀 노션](https://www.notion.so/ohgiraffers/60cc7536288b4df6abe34fc9425a9947)  [🌈Figma](https://www.figma.com/design/fCWU0YWRTSobSMnrvXK6bA/MNG?node-id=43-4627&t=nBIeEnq1qjnJXkSb-1)

## 프로젝트 일정 
![일정 관리](https://github.com/user-attachments/assets/941bc5dc-f9ac-456a-992d-f602302732cf)

## 아키텍처
여기에 아키텍처 설명

## 기술 스택
### **🖥️Frontend**
<table>
  <tr>
    <th>구분</th>
    <th>기술 스택</th>
  </tr>
  <tr>
    <td><b>프레임워크</b>　　　　　　　</td>
    <td>React</td>
  </tr>
  <tr>
    <td><b>기본 웹 기술</b></td>
    <td>HTML5, CSS3, JavaScript</td>
  </tr>
  <tr>
    <td><b>상태 관리</b></td>
    <td>Redux Toolkit, React-Redux, Redux-Thunk, Redux-Actions</td>
  </tr>
  <tr>
    <td><b>UI 라이브러리</b></td>
    <td>React-Icons, Recharts, Chart.js, React-Chartjs-2</td>
  </tr>
  <tr>
    <td><b>일정 & 캘린더</b></td>
    <td>FullCalendar (@fullcalendar/core, @fullcalendar/react, @fullcalendar/daygrid, @fullcalendar/interaction)</td>
  </tr>
  <tr>
    <td><b>라우팅</b></td>
    <td>React-Router-Dom</td>
  </tr>
  <tr>
    <td><b>HTTP 요청</b></td>
    <td>Axios</td>
  </tr>
  <tr>
    <td><b>실시간 기능</b></td>
    <td>Stomp.js (@stomp/stompjs), SockJS-Client</td>
  </tr>
  <tr>
    <td><b>애니메이션</b></td>
    <td>Lottie-React, @lottiefiles/react-lottie-player</td>
  </tr>
  <tr>
    <td><b>PDF & 문서 처리</b></td>
    <td>JSPDF, JSPDF-AutoTable, PDF-Lib</td>
  </tr>
  <tr>
    <td><b>날짜 & 시간 관리</b></td>
    <td>Moment.js, Date-Fns</td>
  </tr>
  <tr>
    <td><b>기타 유틸리티</b></td>
    <td>UUID, Web-Vitals</td>
  </tr>
</table>


<h3>🔙 Backend</h3>
<table>
  <tr>
    <th>구분</th>
    <th>기술 스택</th>
  </tr>
  <tr>
    <td><b>프레임워크 및 언어　　　　　　</b></td>
    <td>Java, Spring Boot　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　</td>
  </tr>
  <tr>
    <td><b>보안 & 인증</b></td>
    <td>Spring Security, JWT (io.jsonwebtoken:jjwt)</td>
  </tr>
  <tr>
    <td><b>ORM & DB</b></td>
    <td>Spring Data JPA, MyBatis, MySQL</td>
  </tr>
  <tr>
    <td><b>MySQL Replication</b></td>
    <td>Master-Slave 구조 활용 (고가용성 및 백업)</td>
  </tr>
  <tr>
    <td><b>Redis</b></td>
    <td>Spring Data Redis (세션 관리 및 캐싱)</td>
  </tr>
  <tr>
    <td><b>웹 서비스</b></td>
    <td>Spring Boot Web (Spring MVC)</td>
  </tr>
  <tr>
    <td><b>API 문서화</b></td>
    <td>SpringDoc OpenAPI (Swagger)</td>
  </tr>
  <tr>
    <td><b>WebSocket</b></td>
    <td>Spring Boot WebSocket (STOMP)</td>
  </tr>
  <tr>
    <td><b>이메일 전송</b></td>
    <td>JavaMailSender (Spring Boot Mail)</td>
  </tr>
  <tr>
    <td><b>모델 변환</b></td>
    <td>ModelMapper</td>
  </tr>
  <tr>
    <td><b>테스트</b></td>
    <td>JUnit, Spring Security Test, MyBatis Test</td>
  </tr>
  <tr>
    <td><b>배포 환경</b></td>
    <td>Railway</td>
  </tr>
  <tr>
    <td><b>로그 관리</b></td>
    <td>Spring AOP</td>
  </tr>
</table>

### **🚀 트래픽 테스트 & 모니터링**
<table>
  <tr>
    <th>구분</th>
    <th>도구</th>
    <th>역할</th>
  </tr>
  <tr>
    <td><b>부하 테스트　　　　</b></td>
    <td>JMeter　　　　</td>
    <td>다중 사용자 트래픽 시뮬레이션, 성능 테스트 수행　　　　　　　　　　　　　　　　　　　　　　</td>
  </tr>
  <tr>
    <td><b>메트릭 수집</b></td>
    <td>Prometheus</td>
    <td>애플리케이션 및 서버 메트릭 수집, 성능 모니터링</td>
  </tr>
  <tr>
    <td><b>데이터 시각화</b></td>
    <td>Grafana</td>
    <td>Prometheus 데이터를 기반으로 성능 대시보드 시각화</td>
  </tr>
</table>

### **☁️ 파일 저장 & 데이터 백업**
<table>
  <tr>
    <th>구분　　</th>
    <th>기술　　</th>
  </tr>
  <tr>
    <td><b>파일 저장소　　　　　　</b></td>
    <td>Firebase Storage (이미지 및 파일 관리)　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　</td>
  </tr>
  <tr>
    <td><b>DB 백업 & 복제　　　　</b></td>
    <td>MySQL Replication (Master-Slave 복제)</td>
  </tr>
</table>

## 기능 설명
### 📌로그인
![1  로그인](https://github.com/user-attachments/assets/cc0a5fa3-ebd5-4ecd-a20d-8a40fdb9ff14)
- 본사에서 부여받은 아이디와 비밀번호로 로그인이 가능합니다.
- 로그인과 동시에 AccessToken(15분), RefreshToken(7일)이 발급됩니다.
- AccessToken은 세션에 저장하였고, RefreshToken은 Redis에 저장하였습니다

### 📌아이디 찾기
![2  아이디 찾기](https://github.com/user-attachments/assets/77e0a5bc-d4c3-4a77-8d20-28ad1d948e70)
- 가맹점과 본사를 선택적으로 아이디 찾기를 할 수 있습니다.

### 📌비밀번호 찾기
![3  비밀번호 찾기](https://github.com/user-attachments/assets/1a53abd5-fe91-4d66-b3fa-524d72e45173)
- DB와 일치한 정보는 해당 이메일로 인증번호가 발송됩니다.
- 인증번호는 Redis 에 5분간 저장이 되며 5분 후에는 만료되어 사용할 수 없습니다.
- 일치할 시 비밀번호 변경 페이지로 이동합니다.

### 📌메인화면(가맹점)
![4  메인화면](https://github.com/user-attachments/assets/948a0199-adb8-4ac3-a891-91c66faeca7a)
- 로그인 정보의 따라서 가맹점 및 본사 페이지로 이동할 수 있도록 하였습니다.
- 가맹점 메인화면은 전사 공지사항, 스케줄, 재고부족품목, 매출현황 그래프를 확인할 수 있습니다.

### 📌메인화면(본사)
![21  본사 메인화면](https://github.com/user-attachments/assets/81ff3441-64c2-4606-9ad3-22956ba38fc9)
- 본사 메인화면의 경우 각 가맹점의 매출현황 그래프 및 전사 공지사항, 이벤트 일정을 한 눈에 확인할 수 있습니다.

### 📌 AccessToken 갱신 및 자동 로그아웃
![4-1  토큰 만료 시 자동 로그아웃](https://github.com/user-attachments/assets/41533aa0-d973-41cb-8644-b274f48af565)
- 상단에 로그아웃 버튼 및 AccessToken 만료 시간을 확인할 수 있으며 만료 시 자동 로그아웃이 됩니다.

### 📌토큰 갱신 가능
![4-2  토큰 갱신](https://github.com/user-attachments/assets/16e3c5e3-a2a1-4d3d-9717-c9b8e46d6452)
- 연장 버튼을 누른다면 Redis 에 저장된 RefreshToken 기반으로 AccessToken을 갱신할 수 있도록 하였습니다.

## 📌재고관리(가맹점)
![5  재고관리(가맹점)](https://github.com/user-attachments/assets/37dbcfaf-a282-49b8-8491-5a3898b6e494)
- 로그인한 가맹점의 재고 현황을 확인할 수 있습니다.
- 재고목록을 체크하여 PDF 파일로 추출할 수 있습니다.
- 유통기한 임박 및 재고부족 필터링이 가능합니다.

## 📌입출고 관리
![5-1  입출고 신청](https://github.com/user-attachments/assets/5ca7bcd0-d7fc-4242-b276-5a8b520d7c87)
- 부족한 재고는 타 매장에서 요청 시 출고하는 매장에서 출고 등록할 수 있도록 하였습니다.
- 입고 매장은 승인 또는 취소 처리를 할 수 있습니다.

## 📌가맹점별 재고현황
![17  가맹점별 재고 현황](https://github.com/user-attachments/assets/51b5e201-ba6d-43db-afdf-c123376ac985)
- 타 매장의 보유하고 있는 재고를 확인할 수 있습니다.

## 📌발주신청
![18  발주신청](https://github.com/user-attachments/assets/e27c8d8c-6568-4e17-b0c5-e8b318849c9e)
- 부족한 재고는 발주 신청을 할 수 있습니다.
- 본사는 각 가맹점의 발주 신청 내역을 확인할 수 있으며 승인 또는 반려 처리를 할 수 있습니다

## 📌공급업체 관리
![19  공급업체 관리](https://github.com/user-attachments/assets/9a1a6495-9b3e-43d5-a77c-ef55068b281d)
- 본사는 계약되어 있는 거래처를 확인할 수 있으며 신규 등록 및 수정, 계약해지를 할 수 있습니다.
- 업체 이미지는 Firebase 에 업로드 되도록 하였습니다.
- 업체 등록 시 주소는 다음 주소API 를 활용하였습니다.

## 📌메뉴관리(가맹점)
![6  메뉴관리(가맹점)](https://github.com/user-attachments/assets/60b8a0a3-28e3-47f0-a5a5-7acf669fef7f)
- 현재 판매되고 있는 메뉴들을 확인할 수 있습니다.
- 메뉴 사진들은 Firebase 를 사용하여 클라우스 서버에 저장하였습니다.

## 📌일정관리(본사)
![20  본사 일정관리](https://github.com/user-attachments/assets/2c8baf06-b9d2-4e72-b73a-10cbfaf13aa0)
- 행사 일정을 등록하여 본사 내부적으로 공유할 수 있게끔 하였습니다.

## 📌전표처리
![7  전표처리](https://github.com/user-attachments/assets/25bd9a7a-e80d-48ee-94d5-c2544af562b8)
- 가맹점 및 본사는 전표처리를 할 수 있습니다
- 행 추가 버튼을 누를 시 목록을 추가할 수 있습니다
- 체크 후 세금계산서 or 손익계산서가 발행됩니다.
- 초기 데이터값은 시스템 날짜 기준으로 한 달치를 조회합니다.

## 📌세금 계산서 발행
![8  세금 계산서 발행](https://github.com/user-attachments/assets/a04bed2b-1538-4b54-a2df-7f68d6feedf5)
- 전표처리에서 선택한 행의 데이터 기반으로 세금 계산서를 발행할 수 있으며 PDF 파일로도 추출 가능하도록 하였습니다.

## 📌손익 계산서 발행
![9  손익 계산서 발행](https://github.com/user-attachments/assets/f0b77071-178e-4896-8887-6991ee0150b4)
- 전표처리에서 선택한 행의 데이터 기반으로 손익 계산서를 발행할 수 있으며 PDF 파일로도 추출 가능하도록 하였습니다.

## 📌컴플레인
![10  컴플레인](https://github.com/user-attachments/assets/bc8f38cb-6ffc-46f7-824d-3fdc7140d6c8)
- 컴플레인을 등록할 수 있습니다.
- 시간 선택은 현재 시간보다 이 후인 시간을 선택할 수 없도록 하였습니다.

## 📌직원목록
![11  직원 목록](https://github.com/user-attachments/assets/1c5b1f8f-9166-46db-8e28-e6a1ec70eabb)
- 각 가맹점마다 근무하는 직원 및 퇴사자를 확인할 수 있습니다.
- 점장 직급만 직원의 정보를 수정하거나 등록을 할 수 있도록 하였습니다.
- 직원 등록 시 다음 주소 API 를 사용하여 정확한 주소지를 선택할 수 있도록 하였습니다.
- 프로필 사진은 Firebase 클라우드 서버에 업로드가 되도록 하였습니다.

## 📌스케줄 등록
![12  스케줄 등록](https://github.com/user-attachments/assets/2766195d-ed5e-4c32-9b14-8d23c229151e)
- 점장 직급만 스케줄 등록 및 수정할 수 있도록 하였습니다.
- 로그인된 가맹점의 데이터 기반으로 직원 정보 가져와서 오픈 미들 마감을 등록할 수 있습니다.

## 📌공지사항
![13  공지사항](https://github.com/user-attachments/assets/35b35cbe-7fe6-4159-bf8e-f6f6797bf40a)
- 공지사항은 본사에서 각 가맹점에 전달할 사항들을 작성하는 공간입니다.
- 본사에서만 작성이 가능하며 첨부파일은 Firebase 에 저장 및 다운로드를 받을 수 있도록 하였습니다.


## 📌실시간 채팅
![14  실시간채팅](https://github.com/user-attachments/assets/c2186172-0a0a-4805-ab98-63e73929d233)
![14-1  그룹채팅](https://github.com/user-attachments/assets/6e9331b2-25f9-4bf1-b0fd-a3b823640fac)
- WebSocket + STOMP + Redis 를 활용하여 1:1, 그룹채팅이 가능합니다.
- 채팅방 개설 및 채팅방 이름도 변경할 수 있습니다.
- 채팅 내역은 DB 부하 방지를 위해 MySQL 에 즉시 저장되지 않으며 Redis 에 보관한 뒤 30초마다 배치 처리를 통해 MySQL 에 저장됩니다.


## 📌바리스타 노트
![15  바리스타 노트](https://github.com/user-attachments/assets/447d0f71-7b8d-4241-8fd9-9d319b1327a6)
- 바리스타 노트는 본사 + 각 가맹점 별로 소통을 할 수 있는 커뮤니티 게시판 입니다.
- 파일첨부 시 Firebase 에 업로드 및 다운로드를 할 수 있도록 하였습니다.

## 📌통계
![16  통계](https://github.com/user-attachments/assets/fdbc8da6-d917-4320-8337-a79536a631f5)
- 가맹점 및 본사는 판매현황 통계를 확인할 수 있습니다.
- 대시보드의 경우 Chart.js 라이브러리를 사용하였습니다.



## 논리 & 물리 데이터 모델링(총 32개 테이블 - 수정중)
### 🖼️논리 데이터 모델링
![image](https://github.com/user-attachments/assets/c83c72d3-2a89-4fe7-a1b5-a0985bddf276)

## Wiki
### 🛠️기능 개발중 개선했던 항목 정리
- [🛡️로그인 - JWT + Redis 활용](https://github.com/MNGFinal/CafeSync-Back/wiki/%EB%A1%9C%EA%B7%B8%EC%9D%B8-Spring-Security---JWT---Redis-%ED%99%9C%EC%9A%A9)
- [💬실시간 채팅(1:1, 그룹채팅) - WebSocket + STOMP + Redis](https://github.com/MNGFinal/CafeSync-Back/wiki/%EC%8B%A4%EC%8B%9C%EA%B0%84-%EC%B1%84%ED%8C%85(1:1,-%EA%B7%B8%EB%A3%B9%EC%B1%84%ED%8C%85)-%E2%80%90-WebSocket---STOMP---Redis)
- [🎨이미지 및 파일 업로드, 다운로드 - Firebase + Google Cloud CDN 방식 적용](https://github.com/MNGFinal/CafeSync-Front/wiki/Firebase-%EC%9D%B4%EB%AF%B8%EC%A7%80,-%ED%8C%8C%EC%9D%BC-%EC%A0%80%EC%9E%A5-%EB%B0%8F-%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C--URL-%EB%B0%98%ED%99%98)
- [🚀트래픽 테스트 - JMeter + Prometheus + Grafana](https://github.com/MNGFinal/CafeSync-Back/wiki/%ED%8A%B8%EB%9E%98%ED%94%BD-%ED%85%8C%EC%8A%A4%ED%8A%B8(JMeter---Prometheus---Grafana))
- [🔥DB 백업 및 부하분산 - MySQL Replication 도입](https://github.com/MNGFinal/CafeSync-Back/wiki/MySQL-Replication(AOP-%ED%99%9C%EC%9A%A9%ED%95%9C-Master,-Slave-%EB%B6%80%ED%95%98-%EB%B6%84%EC%82%B0-%EC%B2%98%EB%A6%AC))
