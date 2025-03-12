# ☕CafeSync
![modern-browser-mockup](https://github.com/user-attachments/assets/fceef9ef-d8b3-4f7a-8c75-182f4b3b9dba)

프로젝트 기간 25.02.17 ~ 25.03.14

## 🔗 빠른 이동
- [프로젝트 소개](#프로젝트-소개)
- [프로젝트 일정](#프로젝트-일정)
- [아키텍처](#아키텍처)
- [기술 스택](#기술-스택)
- [기능 설명](#기능-설명)
- [논리 & 물리 데이터 모델링](#논리--물리-데이터-모델링)

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

## 프로젝트 일정 
여기에 프로젝트 일정

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
    <td><b>프레임워크 & 라이브러리</b></td>
    <td>HTML5, CSS3, JavaScript, React</td>
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
<table border="1">
  <tr>
    <th>구분</th>
    <th>기술 스택</th>
  </tr>
  <tr>
    <td><b>프레임워크</b></td>
    <td>Java, Spring Boot</td>
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
    <td>Railway, Nginx, Fly.io</td>
  </tr>
  <tr>
    <td><b>로그 관리</b></td>
    <td>Logback, ELK Stack (Elasticsearch, Logstash, Kibana)</td>
  </tr>
</table>

<h2>🚀 트래픽 테스트 & 모니터링</h2>
<table border="1">
  <tr>
    <th>구분</th>
    <th>도구</th>
    <th>역할</th>
  </tr>
  <tr>
    <td><b>부하 테스트</b></td>
    <td>JMeter</td>
    <td>다중 사용자 트래픽 시뮬레이션, 성능 테스트 수행</td>
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

<h2>☁️ 파일 저장 & 데이터 백업</h2>
<table border="1">
  <tr>
    <th>구분</th>
    <th>기술</th>
  </tr>
  <tr>
    <td><b>파일 저장소</b></td>
    <td>Firebase Storage (이미지 및 파일 관리)</td>
  </tr>
  <tr>
    <td><b>DB 백업 & 복제</b></td>
    <td>MySQL Replication (Master-Slave 복제)</td>
  </tr>
</table>

## 기능 설명
여기에 기능 설명

## 논리 & 물리 데이터 모델링
여기에 데이터 모델링 설명
