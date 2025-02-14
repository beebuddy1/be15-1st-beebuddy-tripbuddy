
![image](https://github.com/user-attachments/assets/7c64846b-fc61-4581-85c9-c28bae363c5e)

## 🐝 beebuddy! 팀원 소개  
<table style="width: 100%; text-align: center;">
  <tr>
    <td align="center"> <a href="https://github.com/mijuckboon">곽진웅</a></td>
    <td align="center"> <a href="https://github.com/wishbornDev">김소원</a></td>
    <td align="center"> <a href="https://github.com/oyk0510">오유경</a></td>
    <td align="center"> <a href="https://github.com/hnjee">이현지</a></td>
    <td align="center"> <a href="https://github.com/Cho-Hyun-Seung">조현승</a></td>
    <td align="center"> <a href="https://github.com/dxmlk">한성경</a></td>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/c5ea1f98-b4c1-4d4a-a221-602fae97db86" width="150px" height="130px"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/82943f25-208e-4ab7-9245-6ffe9662cea2" width="150px" height="130px"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/cb0ba9a4-c19b-4ce7-ac6e-8f8df777d121" width="150px" height="130px"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/a7aa5b88-7ff7-4bbf-9b3f-2d8667a18dcc" width="150px" height="130px"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/c36e4e7f-da00-469d-b76d-a1e7163ac76c" width="150px" height="130px"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/a16628c4-0cc1-4348-aed4-8f8ba9d611a0" width="150px" height="130px"/></td>
  </tr>
</table>
  <br>


## 🧳 트립버디 개요

<a href="#1">1. 프로젝트 기획</a>
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-1">1-1. 주제</a>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-2">1-2. 배경 및 필요성</a>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-3">1-3. 주요 기능</a>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-4">1-4. WBS(Work Breakdown Structure)</a>
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-5">1-5. 요구사항 명세서 </a>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#1-6">1-6. UML(Usecase Diagram)</a>

<a href="#2">2. DB 모델링</a>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#2-1">2-1. 논리 모델링</a>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#2-2">2-2. 물리 모델링</a>

<a href="#3">3. 서버 구축 </a>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#3-1">3-1. 리플리케이션(Replication) </a>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#3-2">3-2. DDL </a>

<a href="#4">4. 테스트케이스 </a>

<a href="#5">5. 기술 스택 </a>

<a href="#6">6. 트러블슈팅 </a>

<a href="#7">7. 팀원 회고 </a>

<br>


## <p id="1">1. 프로젝트 기획</p>


### <p id="1-1">1-1. 주제</p>
트립버디는 실시간 공동 작업 및 투표 기능을 활용한 **협업 기반 여행 계획 서비스**입니다. 
<br><br>
사용자는 그룹을 생성하여 친구를 초대하고, 그룹에서 여행 일정과 가고 싶은 장소를 토의하며 날짜·장소·예산 등을 투표를 통해 결정할 수 있습니다. 또한, 비용 정산 기능과 사진 공유 앨범을 활용하여 여행 계획을 체계적으로 관리할 수 있으며, 캘린더를 통해 모든 여행 일정을 한눈에 확인하고 기록할 수 있는 편리한 기능을 제공합니다.
<br><br>
### <p id="1-2">1-2. 배경 및 필요성</p>
#### [ 국내 관광 시장 규모의 성장 ]
<img src="https://github.com/user-attachments/assets/269e3016-154c-44a1-b4c4-95a7e7520968" width="600px"/> <br>
코로나19 팬데믹이 종식되고 억눌렸던 여행 수요가 폭발적으로 증가하면서 관광업, 항공업, 숙박업 등 다양한 분야에서 활발한 성장이 이루어지고 있습니다. 2022년에는 국내 관광 시장 규모는 14조 900억 원으로, 2019년 대비 97% 수준으로 회복되었습니다. 더 나아가 2027년에는 19조 6,900억 원 시장 규모를 형성할 것으로 전망됩니다. 

#### [ 국내 여행 플랫폼 시장 규모의 성장 ]  
<img src="https://github.com/user-attachments/assets/c864aca5-6e03-4bba-b31d-2527b376af7f" width="400px"/> 
<img src="https://github.com/user-attachments/assets/d6cb9a56-cade-4c85-868e-8b30c20a3f33" width="420px"/> <br>
여행 수요 증가와 함께 모바일과 웹을 활용한 여행 상품 판매 방식이 강화되고 있으며, 여행 플랫폼 앱의 시장성이 급속도로 확대되고 있습니다.
위의 자료는 주요 여행 플랫폼 앱을 대상으로 조사한 결과, 사용자와 월간 결제 추정 금액이 코로나19 이전 대비 약 2배 증가한 것을 보여줍니다. <br><br>

이처럼 엔데믹 이후 여행 시장은 급격하게 성장하고 있으며, 특히 모바일과 웹을 활용한 여행 서비스가 새로운 트렌드로 자리 잡고 있습니다. 자연스럽게 여행 일정 수립과 관련된 디지털 플랫폼의 수요도 증가하고 있음을 확인할 수 있습니다. 

#### [ 기존 여행 계획 플랫폼의 한계 ]
|  | **트리플** | **마이리얼트립** | **노션** |
| --- | --- | --- | --- |
| **서비스 성격** | 개인 맞춤형 여행 일정 & 가이드 제공 | 여행 상품 및 가이드 연결 플랫폼 | 업무 및 프로젝트 관리를 위한 다목적 협업 툴 |
| **핵심기능**  | AI 기반 일정 추천, 여행 후기, 지도, 맛집·명소 정보 제공 | 항공권/숙소/투어 예약, 여행 가이드 연결, 맞춤형 여행 플랜 제공 | 문서 및 위키 관리, 작업 관리,  일정관리, 협업/공유 기능 특화   |
| **주 이용자** | 자유여행을 직접 계획하는 사람 | 가이드 투어나 맞춤 | 프로젝트나 개인 작업을 정리하고 싶은 사람  |

- 여행 계획 서비스 - 트리플, 마이리얼트립
: 기존의 여행 계획 서비스는 주로 개인의 일정 계획을 돕거나, 여행 관련 정보를 제공하는 데 중점을 두고 있습니다. 하지만, 이들 서비스는 여행을 함께 계획하는 사용자들이 실시간으로 소통하고 조율할 수 있는 <b>협업 기능이 부족합니다. </b>
- 다목적 협업툴 - 노션
: Notion과 같은 협업툴은 실시간 공동 작업 기능을 제공하지만, 일반적인 업무 및 프로젝트 관리에 초점이 맞춰져 있어 <b>여행 일정 기획에 특화되어 있지 않습니다.</b>

#### [ 트립버디의 차별성: 여행일정 + 협업 ] 
<img src="https://github.com/user-attachments/assets/06a2a36a-5d2e-45cb-a85a-61e4d2428b74" width="400px"/> <br>
기존의 여행 계획 수립 플랫폼들은 여행 일정 기획에 특화되어 있지 않거나, 협업 기능이 부족합니다. 트립버디는 이러한 시장의 빈틈을 보완하여, **여행 일정이라는 특정 주제를 중심으로 + 실시간 공동 작업이 가능한 플랫폼을 제공**합니다. 여행을 함께 계획하는 과정에서 발생하는 불편함을 최소화하고, 사용자들이 더욱 원활하게 협업할 수 있도록 지원합니다. 이를 통해, 개인 중심의 여행 계획 서비스를 넘어, **여행을 함께 준비하는 사람들을 위한 최적의 협업 도구로 자리 잡는 것**을 목표로 합니다.
<br><br>
### <p id="1-3">1-3. 주요 기능</p>
#### 📝 그룹 여행방 일정 보드
- 여행 날짜, 여행지, 숙소, 교통 수단, 식당 등의 일정 리스트를 팀원들과 동시에 편집 가능
- 등록된 일정 수정 및 삭제 가능
- 여행 하루 전 일정 알림 기능 제공
#### 📅 그룹 캘린더 기능
- 그룹원들의 개별 일정을 반영한 최적의 여행 날짜 조율
#### 🗳️ 투표 기능
- 일정, 숙소 등 주요 결정을 손쉽게 투표로 결정
- 완료된 투표 결과를 여행 일정에 반영
#### 💰 예산 관리 및 정산 기능
- 여행 전 항목 별 예산 설정 가능
- 여행 중 발생한 비용을 금액, 날짜, 카테고리 등과 함께 기록
- 비용 기록 히스토리 조회 가능 
#### 📸 사진 공유 및 여행 기록 기능
- 여행 후 사진을 공유하고 기록을 보관하여 활용
- 여행 종료 시 자동 사진 공유 요청 알림 제공
#### 🔔 회원 관리 및 알림 시스템
- 회원 가입 및 개인 정보 관리 
- 그룹 초대, 투표 생성, 갤러리 공유 등 실시간 알림 제공 및 개별 설정 가능
#### 👥 그룹 및 여행방 관리 
- 그룹 생성 및 초대
- 그룹 내 여러 개의 여행 방 생성 가능 
<br><br>

### <p id="1-4">1-4. WBS(Work Breakdown Structure)</p>
<a href="https://docs.google.com/spreadsheets/d/1g5JGdYRIqlfTwxo8pWvn_RjXfj637lqHXj-BadZo7cY/edit?gid=661890835#gid=661890835">WBS</a>
<img width="1001" alt="image" src="https://github.com/user-attachments/assets/3b57cf77-31ea-4801-9f1a-fc4dcafe2e5c" />
<br><br>

### <p id="1-5">1-5. 요구사항 명세서</p>
<a href="https://docs.google.com/spreadsheets/d/1g5JGdYRIqlfTwxo8pWvn_RjXfj637lqHXj-BadZo7cY/edit?gid=1875085029#gid=1875085029">요구사항 명세서</a>
![요구사항 명세서](https://github.com/user-attachments/assets/26c892a0-9ac2-4d60-bce0-e6bcd6eaf763)

### <p id="1-6">1-6. UML</p>
<details>
<summary>UML</summary>
<div markdown="1">
  <img src="https://github.com/user-attachments/assets/20d39e15-95e3-4734-9d13-e92b41ec5810"/>
</div>
</details>
<br><br>


## <p id="2">2. DB모델링</p>


### <p id="2-1">2-1. 논리 모델링</p>
![논리 모델](https://github.com/user-attachments/assets/ec1d504a-648d-44dc-a92a-577e6598d8ef)


### <p id="2-2">2-2. 물리 모델링</p>
![물리 모델](https://github.com/user-attachments/assets/680993b9-5395-4080-9988-1883ee5269c3)

<br><br>
## <p id="3">3. 서버 구축</p>
### <p id="3-1">3-1. MariaDB 리플리케이션</p>
![레플리케이션](https://github.com/user-attachments/assets/a25a4ee2-7125-4b71-b017-ce93bad93e30)
- DB 서버의 부하를 분산시키고 데이터를 백업하기 위해 Master-Slave 구조로 DB서버 구축 진행
- MariaDB에서 제공하는 리플리케이션(DB 복제) 기능을 사용 
- 2대의 리눅스 VM 내에 설치한 mariaDB를 master(1번)와 slave(2번)로 나누어 비동기 복제 방식으로 데이터를 복제하도록 함
- Master-Slave 구조
  - master 서버: 데이터의 변경에 대한 처리를 담당하며 변경 발생시 binary log에 기록한다. 
  - slave 서버: master 서버에 접근하여 binary log를 전달받고 이를 slave DB에 반영하고 조회의 부담을 담당한다.
  - 단, slave 서버는 master의 데이터를 전달받아 백업하는 용도이므로 readonly 설정을 하여 데이터 변경이 불가능하도록 한다. 
<br>

### <p id="3-2">3-2. DDL</p>
[DDL](https://github.com/beebuddy1/be15-1st-beebuddy-tripbuddy/blob/a1ba4df29c8ee8648c906ceb246ab0a3a9b5330f/src/ddl/ddl.sql)

<br><br>
## <p id="4">4. 테스트케이스 </p>
[테스트케이스](https://docs.google.com/spreadsheets/d/1g5JGdYRIqlfTwxo8pWvn_RjXfj637lqHXj-BadZo7cY/edit?gid=2127407408#gid=2127407408)  

![beebuddy 테스트 케이스_1](https://github.com/user-attachments/assets/3be5a832-6ebc-435e-a2f5-ec61ec8f4dad)
![beebuddy 테스트 케이스_2](https://github.com/user-attachments/assets/55f2fcda-e293-48a3-93bc-841672c053e4)


<br><br>
## <p id="5">5. 기술 스택 </p>
<div dir="auto">
<img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/vscode-000000?style=for-the-badge&logo=vsco&logoColor=white">
<img src="https://img.shields.io/badge/Sourcetree-0052CC?style=for-the-badge&logo=sourcetree&logoColor=white">
<img src="https://img.shields.io/badge/HeidiSQL-25D366?style=for-the-badge&logoColor=white">
</div>
<div dir="auto">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/ERD CLOUD-339AF0?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/StarUML-3D03A7?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
</div>

<br><br>

## <p id="6">6. 트러블슈팅</p>

### 6-1. PK 지정 전 AUTO_INCREMENT Error
#### 1️⃣ 에러 발생 코드
``` sql
 CREATE TABLE `tbl_member` (
  `member_id`  INT NOT NULL AUTO_INCREMENT, -- ⚠️ 에러 발생
  `email`  CHAR(30)  NOT NULL  COMMENT '로그인 ID'
);

ALTER TABLE `tbl_member` ADD CONSTRAINT `PK_TBL_MEMBER` PRIMARY KEY (
  `member_id`
);
```
 #### 2️⃣ SQL 에러 코드
 > SQL 오류 (1075): **Incorrect table definition**; 
    there can be only one auto column and it must be defined as a key 

#### 3️⃣ 발생 원인 
-  <span style="background-color:fff5b1;">one auto column and it must be defined as a key </span>
- `AUTO_INCREMENT` 를 적용할 컬럼은 KEY로 지정된 상태여야 한다.

#### 4️⃣ 해결 방법 
##### 1. PK를 인라인 방식으로 통일한다.
``` sql
CREATE TABLE `tbl_member` (
`member_id`   INT NOT NULL AUTO_INCREMENT PRIMARY KEY, -- 인라인 방식으로 해결
`email`   CHAR(30)   NOT NULL   COMMENT '로그인 ID',
);
```
##### 2. ALTER 문으로 통일한다. 
``` sql
CREATE TABLE `tbl_member` (
`member_id`   INT NOT NULL AUTO_INCREMENT PRIMARY KEY, -- 인라인 방식으로 해결
`email`   CHAR(30)   NOT NULL   COMMENT '로그인 ID',
);

# ALTER문으로 AUTO_INCREMENT, PRIMARY KEY 지정
ALTER TABLE `tbl_member` MODIFY member_id INT NOT NULL AUTO_INCREMENT PRIMARY KEY;
```

<br>

### 6-2. ALTER로 ON UPDATE CASCADE ON DELETE CASCADE 지정 Error
#### 1️⃣ 에러 발생 코드
``` sql
ALTER TABLE `tbl_group_member` ADD CONSTRAINT `FK_tbl_group_TO_tbl_group_member_1` 
FOREIGN KEY (
   `group_id`
)
REFERENCES `tbl_group` (
   `group_id` ON UPDATE CASCADE ON DELETE CASCADE
) ;
```
 #### 2️⃣ SQL 에러 코드
 > SQL 오류 (1064): **You have an error in your SQL syntax**; 
check the menual that corresponds to your MariaDB server version for the right syntax
to use near 'ON UPDATE CASCADE ON DELETE CASCADE)' 

#### 3️⃣ 발생 원인 
- <span style="background-color:fff5b1;">check the menual that corresponds to your MariaDB server version for the right syntax
to use near 'ON UPDATE CASCADE ON DELETE CASCADE)’ </span>
- `ALTER`로 `ON UPDATE CASCADE ON DELETE CASCADE`  와 같은 CSCADE 옵션 지정 시 참조 컬럼의 괄호 밖에 명시해주어야 한다. 

#### 4️⃣ 해결 방법 
##### 1. CASCADE 옵션을 참조 컬럼 괄호 밖에 명시한다.
``` sql
ALTER TABLE `tbl_group_member` ADD CONSTRAINT `FK_tbl_group_TO_tbl_group_member_1` 
FOREIGN KEY (
   `group_id`
)
REFERENCES `tbl_group` (
   `group_id`   
) ON UPDATE CASCADE ON DELETE CASCADE ;
```

<br>

### 6-3. TRIGGER AFTER DELETE 옵션 NEW 사용 불가
#### 1️⃣ 에러 발생 코드
``` sql
DELIMITER ;
-- 비용 삭제 트리거
CREATE OR REPLACE TRIGGER after_delete_cost
   AFTER DELETE
   ON tbl_cost
   FOR EACH ROW
BEGIN
   INSERT INTO
      tbl_cost_history
   (
      history_type
      , updated_at
      , cost_amount
      , cost_id
   )
   VALUES
   (
      'DELETED'
      , NEW.created_at -- ⚠️ ON DELETE 옵션에서 NEW 사용하여 문제 발생
      , NEW.cost_amount
      , NULL -- cost_id null로 바꿔줌!
   );   
END //

DELIMITER ;
```
 #### 2️⃣ SQL 에러 코드
 > SQL 오류 (1363): There is no NEW row in on DELETE trigger' 

#### 3️⃣ 발생 원인 
-  `TRIGGER` ~ `[AFTER/BEFORE] DELETE` 옵션에서 `NEW` 사용
- `DELETE` 옵션은 추가 데이터가 없어 `NEW` 사용 불가

#### 4️⃣ 해결 방법 
##### 1.  `NEW`를 제외하 작성한다.
``` sql
DELIMITER ;
-- 비용 삭제 트리거
CREATE OR REPLACE TRIGGER after_delete_cost
   AFTER DELETE
   ON tbl_cost
   FOR EACH ROW
BEGIN
   INSERT INTO
      tbl_cost_history
   (
      history_type
      , updated_at
      , cost_amount
      , cost_id
   )
   VALUES
   (
      'DELETED'
      , created_at
      , cost_amount
      , NULL -- cost_id null로 바꿔줌!
   );
END //

DELIMITER ;
```

<br>

### 6-4. Organization Repository에 push시 Permission 에러
#### 1️⃣ 에러 발생 상황
- ##### Organization Repository를 Local에 `clone` 한 후 `branch` 생성
- ##### 생성한 `branch`에서 파일을 수정하여 `commit` 하고 원격에 `push`

#### 2️⃣ 에러 코드
 > $ git push origin feat/vote   
→ **Permission** to beebuddy1/be15-1st-beebuddy-tripbuddy.git **denied** to hnjee.
fatal: unable to access 'https://github.com/beebuddy1/be15-1st-beebuddy-tripbuddy.git/': The requested URL returned error: 403

#### 3️⃣ 발생 원인
- ##### 케이스1: GitHub Repository에 권한이 문제
  ##### repository 권한 부재 또는 `Branch protection rules`에 `Require pull request before merging` 옵션 설정
- ##### 케이스2: GitHub 계정 오류
- ##### 케이스3: 현재 로컬에 연결된 GitHub 인증 정보 오류 -> 당시 에러 발생 원인 
  ##### ✔️ GitHub 계정 인증 정보가 갱신되지 않아서 이전의 권한 정보만 유효함  

#### 4️⃣ 해결 방법 
##### 1. 기존에 저장된 GitHub 자격증명을 삭제
##### ✔️ 로컬 컴퓨터 윈도우-사용자계정-자격증명 관리자에서  기존의 깃허브와 관련된 자격증명 모두 삭제
![permission_error](https://github.com/user-attachments/assets/03200652-9cdd-4904-b218-2b752c02e6be)
##### 2. PUSH 할 때 다시 로컬과 GitHub 연결 
<br>

### 6-5. 레플리카 서버 구축 시 테이블 생성 오류
#### 1️⃣ 에러 발생 상황
``` sql
 CREATE TABLE `tbl_member` (
  `member_id`  INT  NOT  NULL  AUTO_INCREMENT, 
  `email`   CHAR(30)   NOT  NULL   COMMENT  '로그인 ID'
);
```

#### 2️⃣ SQL 에러 코드
 > 프로젝트 테이블 생성을 위한 DDL 스크립트를 읽혔으나 테이블이 정상적으로 생성되지 않아doesn't exist 에러 발생 
![replica_error](https://github.com/user-attachments/assets/89782cdb-a491-414a-828b-8ffca925d4b2)


#### 3️⃣ 발생 원인 
- ##### 리눅스 환경에서 위의 SQL 코드의 Tab 처리를 인식하지 못하여 공백이 없는 채로 명령어를 읽음 (예시: CHAR(30)NOT NULL)

#### 4️⃣ 해결 방법 
##### 1. `TAB` 을 `space_bar`로 공백 설정하여 스크립트를 수정한다. 
``` sql
 CREATE TABLE `tbl_member` (
  `member_id`  INT NOT NULL AUTO_INCREMENT, -- ⚠️ 에러 발생
  `email`  CHAR(30)  NOT NULL  COMMENT '로그인 ID'
);

ALTER TABLE `tbl_member` ADD CONSTRAINT `PK_TBL_MEMBER` PRIMARY KEY (
  `member_id`
);
```
![replica_success](https://github.com/user-attachments/assets/298c01d4-878c-45d4-9803-51eb4aa5dce2)

<br>

### 6-6. MariaDB doesn’t support variable for offset
#### 1️⃣ 에러 발생 상황
``` sql
SET @room_id = 10;
set @page = 1;
SET @offset = (@page - 1) * 12;
SELECT
    gal.file_id,
    gal.file_name,
    gal.file_path,
    gal.created_at,
    gal.is_deleted,
    gal.room_id
FROM
    tbl_gallery gal
WHERE
    gal.room_id = @room_id
    AND gal.is_deleted = 'N'
ORDER BY
    gal.created_at DESC
LIMIT 12 OFFSET @offset;
```

 #### 2️⃣ SQL 에러 코드
``` sql
Error: (conn:57, no: 1064, SQLState: 42000) You have an error in your SQL syntax;
check the manual that corresponds to your MariaDB server version for the right syntax 
to use near '@offset' at line 15 sql: SELECT gal.file_id, gal.file_name, gal.file_path,
gal.created_at, gal.is_deleted, gal.room_id FROM tbl_gallery gal WHERE gal.room_id =
@room_id AND gal.is_deleted = 'N' ORDER BY gal.created_at DESC L... - parameters:[]   
```

#### 3️⃣ 발생 원인 
- ##### 갤러리의 한 페이지당 12개의 사진을 보여주기 위해서 @page를 입력 받고 @offset을 계산하여 OFFSET에 추가함.
- ##### ❗ mariaDB에서는 OFFSET에 변수를 허용하지 않음.

#### 4️⃣ 해결 방법 
##### 1. PREPARE 문을 사용한다.
``` sql
SET @room_id = 10;
SET @page = 1;
SET @offset = (@page - 1) * 12;
-- @sql_query라는 변수에 실행시키고자 했던 SQL 문을 문자열 형태로 저장
SET @sql_query = CONCAT(
    'SELECT file_id, file_name, file_path, created_at, is_deleted, room_id ',
    'FROM tbl_gallery ',
    'WHERE room_id = ', @room_id,
    ' AND is_deleted = ''N'' ',
    'ORDER BY created_at DESC ',
    'LIMIT 12 OFFSET ', @offset
);
-- PREPARE 문으로 @sql_query를 불러오고, EXCUTE로 실행.
PREPARE stmt FROM @sql_query;
EXECUTE stmt;
-- DEALLOCATE PREPARE로 사용이 끝난 SQL을 삭제하여 메모리 정리.
DEALLOCATE PREPARE stmt;
```

<br><br>



## <p id="7">7. 회고록</p>


