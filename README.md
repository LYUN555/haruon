# 📝 개요
  - 프로젝트 명 : 프랜차이즈 본사 그룹웨어 HARUON<br>
  - 프로젝트 기간 : 2025.01.06 ~ 2024.02.14<br>
  - (K-Digital Training) 클라우드 활용 자바 개발자 양성과정 86기 파이널 팀 프로젝트<br>

# 📑 서비스 초기 설계 개요
 - <a href="https://drive.google.com/file/d/165VDJQDqiuiWo3ycASGSIZJyNAXy-zLX/view?usp=sharing">스토리보드</a>
 - <a href="https://docs.google.com/spreadsheets/d/1_2jt6uWHEDrZeYYrJ9j3cnmxJiIQ8ytv/edit?usp=sharing&ouid=106995358265152035103&rtpof=true&sd=true">요구사항 정의</a>
 - <a href="https://drive.google.com/file/d/1tqYL68vizimMNjUDtYVkYri1X2adKIGt/view?usp=sharing">테이블 정의서</a>
 - <a href="https://drive.google.com/file/d/1ECC0TI89oR5kalXibpfRy_HdT9egl8Ff/view?usp=sharing">ERD 다이어그램</a>

# 🧰 개발 환경 및 기술 스택
#### LANGUAGE & SKILL
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
#### Framework
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring%20Boot&logoColor=white)
#### DATABASE
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
#### LIBLARY
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JSTL](https://img.shields.io/badge/jstl-E4F7BA?style=for-the-badge)
![Lombok](https://img.shields.io/badge/Lombok-FFA7A7?style=for-the-badge)
![MyBatis](https://img.shields.io/badge/MyBatis-47C83E?style=for-the-badge)
#### WAS Apache
![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat%2010-23F8DC75.svg?style=for-the-badge&logo=apache%20tomcat%2010&logoColor=black)
#### TOOL
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Heidi](https://img.shields.io/badge/Heidi%20SQL-6B9900?style=for-the-badge)
![Spring Tool Suite 4](https://img.shields.io/badge/Spring%20Tool%20Suite%204-8A2BE2?style=for-the-badge)
![Google Spread Sheet](https://img.shields.io/badge/Google%20Spread%20Sheet-4285F4?style=for-the-badge&logo=google&logoColor=white)

# 🗂️ 주요 기능
그룹웨어 사이트를 전자결재, 일정관리, 메일, SNS, 사내 커뮤니티 및 피드형 게시판 등 필수적인 기능을 기획/제작한 웹 사이트입니다.

<details>
<summary><b>각 기능 상세보기</b></summary>
<div markdown="1">
	
|기능|설명|
|---|---|
| 조직도 | 1. 조직도로 부서장 정보, 부서별 직원 조회 <br> 2. 전체 사원 조회, 검색, 사원 등록 <br> 3. 회사/부서 정보 조회, 수정, 상태변경 기능 |
| 전자결재 | 1. 양식별 결재 작성 및 기안 <br> 2. 중간/최종 결재 처리 <br> 3. 결재 상태별 문서 확인 |
| 근태관리 | 1. 전날 출장, 연차 등을 고려하여 근태 기록 자동 업데이트 <br> 2. 권한에 따른 근태유형 변경 및 근태 승인 <br> 3. 부서별, 개인별 출장 및 연차 신청 기록 조회 4. 권한에 따른 연차 조정 기능 |
| 일정관리 | 1. 내 일정 등록, 수정, 삭제 기능 <br> 2. 권한에 따른 부서일정 등록, 수정, 삭제 기능 <br> 3. 출장,연차 결재완료 시 일정 자동 등록 <br> 4. 회의실 예약 시 일정 자동 등록  |
| 가맹점관리 | 1. 가맹점 목록 조회, 수정, 가맹점별 매출 통계 <br> 2. 가맹점 대상 교육 목록 조회, 등록 <br> 3. 가맹점 문의사항 조회, 답변 등록 |
| 커뮤니티 | 1. 권한에 따른 부서 공지사항 조회, 등록, 수정, 삭제 기능 <br> 2. 카테고리별 피드형 게시판(댓글, 좋아요, 조회수, 파일 첨부)|
| 메일함 | 1. 메일 전송(파일 첨부) <br> 2.수신/답장 기능 <br> 3.임시 저장, 삭제 기능 |
| 메신저 | 1. 웹 소켓을 이용한 채팅 기능 <br> 2. 사원을 검색하여 초대 <br> 3. 접속상태 조회 및 변경 |
</div>
</details>



# 🧑‍🤝‍🧑 Collaborators
| 팀원 | 역할 | 담당업무 |
|---|---|---|
| <a href="https://github.com/LYUN555">이동윤</a>|팀장|전자결재 아키텍처 설계&구현, 사원등록|
| <a href="https://github.com/ES-Im">김은서</a>| 팀원 |근태관리, 실시간 채팅 |
| <a href="https://github.com/najungwoo">나정우</a>|팀원|회의실예약, 일정관리|
| <a href="https://github.com/alim0o0">오아림</a>|팀원|조직도, 커뮤니티|
| <a href="https://github.com/gd2872">장우림</a>|팀원|메일, 가맹점관리|

# 📌 담당 업무

### 📝 결재 문서
- 기본, 매출보고서, 휴가신청서, 출장신청서 총 4개의 기안서 작성 폼 구현
- 기안 작성 시, 모달 창을 통해 중간결재자/최종결재자/수신참조자 선택 가능
- 기안 제출 후 결재대기 상태에서 수정 및 삭제 가능
- 결재문서 수정·삭제 시, 서비스 레이어에서 유효성 검증을 수행하여 본인이 아닐 경우 로그인 페이지로 리다이렉트 처리
- 결재문서에서 기안자가 설정한 결재라인 및 참조자만 열람 가능하도록 권한 검증 메서드 구현
- 결재자가 서명 미등록 시, 알림(alert) 창을 띄우고 마이페이지에서 전자결재 이미지 등록하도록 처리
- 결재 완료 후 PDF 파일로 다운로드 가능
- 결재 완료 시, 일정(Calendar)에 자동 등록하여 업무 일정과 연동
- 결재 목록 및 참조 리스트 관리를 효율적으로 하기 위해 Datatables 라이브러리와 AJAX를 활용하여 리스트 페이지 구현
- 페이징, 검색 기능 추가로 사용자 편의성 향상

### 🏢 신규 사원 등록
- 사원 초대 시 `JavaMailSender`를 활용하여 이메일 발송 구현
- `Spring Security(CustomUserDetailsService)`로 권한·인증 처리 시 프로필 사진까지 세션에 로드하여 사용자별 접근 제어와 UX를 개선
- 데이터베이스에 새로운 사원 등록 시 중복 여부 확인 및 유효성 검증 로직 구현

### 🔒 마이페이지
- `MultipartFile`로 프로필 이미지 업로드 및 서버에 저장, 기존 파일 삭제 처리 구현
- 사원은 본인의 기본 정보를 실시간으로 수정 가능
- 결재 시스템에서 사용되는 디지털 서명 이미지를 추가하거나 수정 가능

### 📅 일정 관리
- `FullCalendar.js`와 REST API를 활용해 달력에 일정 표시
- 일정 페이지에서 AJAX 통신을 통해 서버에서 실시간으로 불러와 달력에 표시
- 사용자가 새 일정을 추가할 수 있는 기능 제공
- 일정 상세보기 페이지에서 수정, 삭제 기능

# 구현 과정에서 겪은 문제해결 및 개선사례

<details>
<summary>
<h3> 1. [결재문서 상세보기] 역할별 접근 제어 & 보안 설계 </h3>
</summary>

**[문제 상황 및 요구 사항]**  
결재문서 상세보기 페이지에서 결재 라인, 참조자, 그리고 해당 팀의 부서장만 문서를 열람할 수 있도록 구현해야 했습니다.

단순히 본인만 볼 수 있는 결재문서는 Spring Security에서 세션 정보를 이용해 확인할 수 있었지만  
부서장, 중간/최종 결재자, 참조자 등 다양한 역할에 따라 접근 권한을 부여해야 하는 상황에서는  
URL을 직접 입력해 접근하려는 권한 없는 사용자를 효과적으로 차단하는 방법에 대해 고민했습니다.

**[원인 분석 및 고려 사항]**
- **보안 취약점:** URL 직접 입력 시 인증되지 않은 사용자가 접근할 가능성이 존재합니다.
- **역할별 특성:** 결재 시스템 내에서 각 역할이 갖는 권한과 접근 범위가 상이하여 단순한 본인 확인 이상의 상세한 조건이 필요했습니다.
- **성능 측면:** 매 요청마다 사용자의 권한 및 문서 접근 권한을 실시간으로 비교해야 하므로, 이 로직이 최적화되어야 합니다.

**[구현 방법 및 선택 이유]**

- **Spring Security의 SecurityContextHolder 활용**
  - **구현:** 사용자가 로그인할 때 SecurityContextHolder에 저장된 인증 정보를 활용하여 현재 사용자와 그 Role을 가져왔습니다.
  - **장점:** 별도의 DB 조회 없이 세션 내 정보를 활용하여 빠른 인증 확인이 가능합니다.
  - **고려 사항:** 세션 만료나 인증 정보의 최신성 유지에 주의가 필요합니다.

- **Access 메서드 구현**
  - **구현:** 결재 문서에 대해 DB에서 접근 허용 정보를 조회한 후  
    SecurityContextHolder에서 가져온 현재 로그인 사용자의 역할 및 식별자와 비교하여 접근 권한을 판별하는 로직을 구현했습니다.
  - **장점:** 역할별로 접근 권한을 세분화할 수 있어 본인 확인보다 더 정밀한 보안 적용이 가능합니다.
  - **고려 사항:** 역할 변경이나 문서의 접근 권한이 수정될 경우 해당 데이터의 업데이트가 즉시 반영되어야 합니다.

**관련 코드 보기:**  
- [DraftService.java(접근 로직)](https://github.com/LYUN555/haruon/blob/ldy/src/main/java/com/haruon/groupware/draft/service/DraftService.java#L36)  
- [ApprovalActionService.java(결재 로직)](https://github.com/LYUN555/haruon/blob/ldy/src/main/java/com/haruon/groupware/approval/service/ApprovalActionService.java#L41)

**[개선 효과]**
- **보안성 향상:** 무단 접근 시도를 100% 차단.
- **유지보수성:** 역할 추가나 변경 시 Access 메서드 내에서 단일 포인트로 관리가 가능하여 코드 중복이 크게 줄어듦.
- **성능 최적화:** SecurityContextHolder 활용으로 인증 정보 조회 시간이 단축되고, Access 로직이 간결해져 전체 응답 시간이 개선됨.

**[장점 및 대안]**
현재 구현한 방식은 서비스 계층에서 유효성 검증을 수행하고, 컨트롤러에서는 그 결과에 따라 접근 여부를 결정하는 방법입니다.
- **명시적 검증:** 서비스 메서드 내에서 구체적인 접근 권한 검증 로직이 명확히 드러나므로, 어떤 조건에서 접근이 허용되는지 쉽게 파악할 수 있습니다.
- **유지보수성:** 접근 제어 로직이 서비스 단에 집중되어 있어, 권한 로직 변경 시 한 곳만 수정하면 됩니다.
- **디버깅 용이:** 로그를 통해 어느 시점에서 접근이 실패했는지 쉽게 확인할 수 있습니다.

팀원들과 코드 리뷰를 진행한 후 나온 대안점:
- **AOP 기반 보안 필터 또는 인터셉터 사용:** 공통된 보안 로직을 인터셉터나 AOP로 분리하면, 코드 중복을 줄이고 보안 정책 변경 시 보다 유연하게 대응할 수 있습니다.

**[배운 점 및 향후 개선 방향]**
- **배운 점:** 단순 인증 정보 확인을 넘어서, 비즈니스 로직 내에서 역할 기반의 세밀한 권한 검증이 얼마나 중요한지 알았습니다.
- **개선 점:** AOP를 활용하여 접근 제어 로직과 사용자 행동 로그를 관리함으로써, 보안 모니터링을 강화하고 문제 발생 시 원인 분석 및 디버깅을 보다 용이하게 할 수 있을 것 같습니다.

</details>

<details>
<summary>
<h3> 2. [결재 승인 쿼리 로직] 단계별 서명 최적화</h3>
</summary>

**[문제 상황 및 요구 사항]**  
중간 결재자 또는 최종 결재자가 승인해야만 서명 이미지가 표시되도록 해야 했습니다.  
결재 상태(A01: 결재대기, A02: 결재중, A03: 결재완료, A04: 반려)에 따라 서명 이미지를 동적으로 처리해야 했으나,  
단순 DB 조회 시 승인되지 않은 서명도 노출되는 문제가 있었습니다.

**[고민했던 대안]**

- **서버에서 서명 노출 제어:**  
  DB에서 모든 데이터를 받아온 뒤 결재 상태를 확인해 필요한 서명만 보여주는 방식  
  → 실제로 사용하지 않는 데이터도 한꺼번에 서버로 전송되고, 서버에서 필터링하는 로직이 복잡해지며 데이터가 많아질수록 전송 비용 및 서버 자원 소모가 크게 증가합니다.

- **클라이언트에서 서명 노출 제어:**  
  서버가 서명 정보를 전부 전달하고, 브라우저에서 표시 여부를 결정하는 방식  
  → 간단한 정보 조작을 통해 승인되지 않은 서명이 노출될 위험이 있으므로 보안이 취약합니다.

- **DB에서 CASE문 분기 처리 (최종 선택):**  
  쿼리 단계에서 결재 상태별로 서명 이미지를 조건부로 반환하는 방식  
  → 한 번의 SELECT로 처리 가능해, 서비스·프론트 로직이 단순해지고 보안도 강화됩니다.

**[해결 및 개선]**  
CASE문을 통해 결재중 상태일 때만 중간결재자 서명을,  
결재완료 상태일 때 최종결재자 서명까지 표시하도록 설계했습니다.  
이로써 승인되지 않은 서명 노출 문제를 해소했고, 각 승인 단계별 서명 흐름을 명확히 분리할 수 있었습니다.

**관련 코드 보기:**  
- [DraftMapper.xml (결재 상세보기 & 페이징/검색 쿼리 포함)](https://github.com/LYUN555/haruon/blob/ldy/src/main/java/com/haruon/groupware/draft/mapper/DraftMapper.xml#L22)

**[개선 효과]**
- **정교한 승인 흐름:**  
  쿼리 단계에서 한 번에 로직 분기가 이루어져, 승인 단계와 서명 이미지 표시 여부를 한눈에 파악할 수 있습니다.
- **보안성 및 유지보수성:**  
  서버와 프론트엔드에서 민감한 정보를 별도로 다루지 않아 보안이 강화되었으며, 로직 중복이 크게 줄어들었습니다.
- **간결한 코드:**  
  CASE문을 활용하여 결재 상태에 따른 분기 처리를 일괄적으로 관리함으로써 코드가 간결해졌습니다.

**[배운 점 및 향후 개선 방향]**
- **배운 점:** 결재 승인 쿼리 최적화를 통해 DB에서 조건부 데이터 반환의 중요성과, 쿼리 성능이 보안 및 유지보수에 미치는 영향을 이해했습니다.
- **개선 점:** 향후 쿼리 튜닝 관련 기술을 학습한 후 EXPLAIN 실행 계획을 조회하여 인덱스 활용도, 비용 분석 후 병목 구간을 파악한 뒤 인덱스 조정이나 쿼리 재작성으로 성능 튜닝을 할 계획입니다.

</details>

<details>
<summary>
<h3> 3. [결재 문서 목록] 대량 데이터 페이징 & 검색 성능 개선 </h3>
</summary>

**[문제 상황 및 요구 사항]**  
프로젝트 초기에 결재 문서 누적에 대비하고자, 테스트 환경에서 약 100,000건 이상의 더미 데이터를 생성해 로딩 속도를 확인했습니다.  
초기에는 DataTables 라이브러리를 기본 설정인 클라이언트 사이드 렌더링(CSR)을 사용했는데, 모든 데이터를 한 번에 로딩해야 해서 성능이 급격히 떨어졌습니다.

**[해결 및 개선]**  
이 문제를 해결하기 위해 DataTables 라이브러리의 AJAX 기능을 사용해 커스텀 페이징 및 검색을 처리하도록 변경했습니다.  
Mapper에서 페이징 처리와 검색 기능 쿼리를 추가한 후 서버에서 필요한 데이터만 가져오도록 개선한 결과,  
**평균 3초 이상 걸리던 로딩 시간이 1초 이하**로 단축되었으며, 데이터가 늘어나도 안정적으로 처리할 수 있게 되었습니다.

**관련 코드 보기:**  
- [DraftMapper.xml (페이징/검색 & 결재 상세보기 쿼리 포함)](https://github.com/LYUN555/haruon/blob/ldy/src/main/java/com/haruon/groupware/draft/mapper/DraftMapper.xml#L394)

**[개선 효과]**
- **페이징 속도 향상:**  
  클라이언트에서 전체 데이터를 렌더링하는 부담이 제거되어, 로딩 시간이 2~3초에서 1초 이하로 단축되었습니다.
- **클라이언트 성능 최적화:**  
  서버에서 데이터를 정제해 전송하여 브라우저는 적은 리소스로도 원활하게 작동할 수 있습니다.
- **확장성 증가:**  
  데이터량 증가에도 서버에서 직접 페이징 및 검색을 처리하므로, 성능 저하 없이 안정적인 처리가 가능합니다.

**[배운 점 및 향후 개선 방향]**
- **배운 점:** 클라이언트와 서버 간 데이터 전송 및 렌더링 부담을 줄이는 것이 성능 최적화에 매우 중요하다는 것을 깨달았습니다.
- **개선 점:**  
  - 기존의 '%LIKE%' 검색 방식이 인덱스를 제대로 활용하지 못해 성능 저하가 발생한다는 점을 발견했습니다.  
    이를 개선하기 위해 '검색어%' 형태로 검색 패턴을 변경하면 인덱스를 효과적으로 사용할 수 있음을 확인하여 적용했습니다.
  - 여러 컬럼을 대상으로 OR 조건 검색 시 MySQL 옵티마이저가 복합 인덱스를 효율적으로 선택하지 못하는 문제도 EXPLAIN을 통해 파악했습니다.  
  - UNION ALL, FULLTEXT INDEX 등을 도입해 검색 성능을 높일 수도 있음을 확인했고, 향후 실제 프로젝트에 적용하여 최적화할 계획입니다.
  - MySQL 옵티마이저의 인덱스 선택 기준과 실행 계획 분석의 중요성을 깊이 이해하게 되었습니다.

</details>

<details>
<summary>
<h3> 4. [URL 매핑 구조] 중복 매핑 리팩토링으로 유지보수성 향상 </h3>
</summary>

**[문제 상황 및 요구 사항]**  
결재 문서 리스트를 구현할 때, 처음에는 각 결재 문서 유형별로 URL을 다르게 설정하고  
이를 각각 `@GetMapping`으로 매핑하여 상세보기 페이지로 이동하도록 구현했습니다.

이 방식은 다음과 같은 문제점을 가지고 있었습니다:
- **문제 1:** 새로운 결재 유형이 추가될 때마다 컨트롤러에 별도의 매핑을 추가해야 하므로 유지보수가 어려웠습니다.
- **문제 2:** 각 유형별 메서드에서 결재 첨부파일을 불러오는 코드가 반복되어 코드의 가독성과 유지보수성이 떨어졌습니다.

**[해결 및 개선]**  
URL을 `@PathVariable`을 활용하는 방식으로 리팩토링했습니다.  
결재 문서의 유형과 해당 문서의 PK 번호를 URL에 포함시켜, 단일 `@GetMapping`에서 모든 유형을 처리할 수 있도록 변경했습니다.  
이를 통해 각 문서 유형을 별도로 매핑할 필요 없이 URL 자체로 문서 유형을 식별하면서도 유지보수가 쉬워졌습니다.

**관련 코드 보기:**  
- [DraftController.java(매핑 리팩토링) 코드](https://github.com/LYUN555/haruon/blob/ldy/src/main/java/com/haruon/groupware/draft/controller/DraftController.java#L28)

**[개선 효과]**
- URL 매핑 구조를 통일함으로써 코드 중복이 크게 줄어들어 유지보수성이 향상되었습니다.
- 단일 URL 패턴을 통해 모든 유형의 문서를 처리할 수 있어 확장성이 증가하였습니다.

**[배운 점 및 향후 개선 방향]**
- **배운 점:** URL 매핑을 단순화하면 코드 중복을 줄이고 확장성과 유지보수성이 크게 향상된다는 것을 확인했습니다.
- **개선 점:**  
  - 현재는 공통 코드(ex: C01, C02)를 URL에 사용하고 있는데, 프로젝트를 처음 접하는 사람도 쉽게 이해할 수 있도록 직관적인 URL 구조를 고민해야 합니다.  
  - API 문서를 체계적으로 작성하여 전체 시스템 이해도를 높일 계획입니다.

</details>

<details>
<summary>
<h3> 5. [결재문서 작성 폼] 유형별 공통화와 최적화 방식 결정 </h3>
</summary>

**[문제 상황 및 요구 사항]**  
결재 문서를 작성할 때, 각 유형별로 개별 페이지를 만들어야 할지,  
혹은 한 페이지에서 유형을 선택하면 필요한 항목만 동적으로 표시하도록 구현해야 할지 고민이 있었습니다.

**[해결 및 개선]**  
유형별 공통 항목이 많다는 점을 고려하여, 한 페이지에서 유형을 선택하면 필요한 값만 표시하고 나머지는 숨기는 방식을 선택했습니다.  
숨겨진 부분의 내용은 초기화하여 불필요한 데이터가 전달되지 않도록 처리했으며, 최종적으로 각 유형별로 입력된 데이터를 분리하여 DB에 저장되도록 설계했습니다.

**관련 코드 보기:**  
- [approval.jsp (JavaScript 동적 폼 처리)](https://github.com/LYUN555/haruon/blob/ldy/src/main/webapp/WEB-INF/view/approval/approval.jsp#L446)

**[개선 효과]**
- **유형별 폼 통합:** 한 페이지에서 모든 유형의 폼을 관리함으로써 페이지 이동 없이 직관적으로 작성할 수 있게 되었습니다.
- **데이터 최적화:** 공통 필드와 개별 필드의 검증을 서비스 레이어에서 분리하여, 불필요한 데이터 전송이나 저장을 방지했습니다.  
  - [ApprovalService.java (유효성 검증 로직)](https://github.com/LYUN555/haruon/blob/ldy/src/main/java/com/haruon/groupware/approval/service/ApprovalService.java#L65)
- **유지보수성 향상:** 중복된 코드와 검증 로직을 통합함으로써, 새로운 유형 추가 시 코드 변경 부담이 크게 줄었습니다.

**[배운 점 및 향후 개선 방향]**
- **배운 점:** 폼의 공통화와 동적 렌더링을 통해 UI/UX 개선과 유지보수성을 크게 향상시킬 수 있음을 확인했습니다.
- **개선 점:**  
  - 현재 한 페이지에서 유형별 폼을 통합하여 관리하는 방식은 초기에는 간단하지만, 향후 유형이 크게 증가하면 검증 로직이 복잡해질 수 있습니다.  
  - 필요 시 페이지 이동을 통한 분리 방안이나, 검증 로직을 모듈화하는 방법, Bean Validation 등을 도입하여 더 견고한 검증 체계를 마련할 예정입니다.

</details>

<details>
<summary>
<h3> 6. [마이페이지 프로필] 실시간 반영을 위한 Security Context 업데이트 </h3>
</summary>

**[문제 상황 및 요구 사항]**  
로그인 후 모든 페이지에 표시되는 프로필 이미지를 매번 DB에 요청하는 방식은 비효율적이라고 판단하여,  
Security Context에 프로필 정보를 저장하는 방법을 도입했습니다.  
하지만 프로필 변경 시, 컨텍스트 홀더에 저장된 정보가 갱신되지 않는 문제가 발생했습니다.

**[고민했던 대안]**
- **AJAX를 통한 새로고침 방식:**  
  프로필 변경 후 클라이언트에서 AJAX를 사용해 최신 이미지를 비동기적으로 로드  
  → 항상 최신 정보를 가져올 수 있으나 페이지 이동 시마다 DB 호출이 필요해 서버 부하가 증가할 수 있습니다.
- **SecurityContextHolder 업데이트 방식 (최종 선택):**  
  프로필 변경 시 보안 컨텍스트에 저장된 사용자 정보를 즉시 갱신  
  → 페이지 이동마다 DB를 호출하지 않아도 되어 서버 리소스를 절약할 수 있습니다.

**[해결 및 개선]**  
매 페이지마다 DB에 요청하는 방식이 비효율적이라 생각하여 SecurityContextHolder 업데이트 방식을 선택했습니다.

**관련 코드 보기:**  
- [EmpProfileService.java (Security Context Update) 코드](https://github.com/LYUN555/haruon/blob/ldy/src/main/java/com/haruon/groupware/user/service/EmpProfileService.java#L55)

- **시큐리티 컨텍스트 동기화:** 프로필 정보 업데이트 시 SecurityContextHolder에서 현재 사용자의 인증 객체를 재생성해 최신 정보를 즉시 반영  
- **DB와 세션 데이터 일관성 강화:** DB에 반영된 최신 프로필 정보를 조회한 후 인증 객체에 갱신된 데이터를 설정해 세션과 DB 간 데이터 불일치 문제를 방지  
- **리소스 절약:** AJAX 방식이나 매 페이지 DB 호출 대신 보안 컨텍스트를 활용해 불필요한 DB 호출을 줄이고 서버 리소스 소모를 최소화

**[장점]**
- **즉각적인 UI 반영:** 프로필 변경 사항이 새로고침 없이 모든 페이지에 즉시 반영됩니다.
- **보안성 유지:** 세션 기반 데이터 동기화 방식으로 안전성을 확보합니다.
- **경량화 솔루션:** 추가 라이브러리 없이 Spring Security만으로 구현해 시스템 복잡도를 낮춥니다.

**[배운 점 및 향후 개선 방향]**
- **배운 점:** 보안 컨텍스트를 활용한 프로필 정보 관리가 서버 부하를 줄이고, 즉각적인 UI 반영 및 보안성을 확보할 수 있음을 확인했습니다.
- **개선 점:**  
  - AJAX 방식과 SecurityContextHolder 업데이트 방식을 시나리오에 맞춰 선택하는 전략이 필요합니다.  
  - 캐시 최적화 및 세션 갱신 범위를 세분화하여 더 효율적인 시스템을 구축할 수 있습니다.

</details>

