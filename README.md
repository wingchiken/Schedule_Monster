# 12조 팀 프로젝트
**기획동기**
- 일정 관리하는 것을 싫어하는 이들에게어린시절 포켓몬 스티커를 수집하던 것처럼 포켓몬을 수집하며 일정 관리의 흥미를 느끼도록 하자
**서비스 목표**
- 꾸준하게 사용하는 서비스
- 내가 좋아서 사용하는 서비스

**서비스 이용대상**
- 일정 관리를 좋아하고 캐릭터 수집을 좋아하는 사람
- 일정 관리를 하지 않지만 캐릭터 수집을 좋아하는 사람

**향후 기술 목표**
- 데스크톱 앱, 스마트폰 앱으로 서비스 확대
- 동호회, 모임 커뮤니티로 서비스 확대

<hr />

# 캐릭터 육성 시스템 차용한 일정관리 웹 프로젝트 (Schedule Monster)



## 서비스 구성 안내

## 1. 서비스 소개
일정을 관리하면서 포켓몬을 수집하세요
벌써12월이네요. 
계획만 세우고 실천을 하지 못하는 당신.

내년에는 일정관리를 하면서 
나만의 포켓몬에게 애정을 주세요

계획을 실천하는 습관도 들이고, 
포켓몬이 수집되어가는 모습을 보면 
동기부여가 될 거에요

## 2. 서비스 주요 기능 설명
**서비스**
- 일정을 관리하며 수집의 즐거움을 느껴보세요
- 캘린더, To-Do list를 작성하며 포켓몬을 수집합니다.

**기능 소개**
- 캘린더 일정관리 기능
- 사용자 캐릭터 육성 기능 
- 캐릭터/아이템 관리 기능(관리자)



## 3. 서비스 구성도

- 서비스 구조도 그림 (사용한 기술 스택)
<img src = "/uploads/97d91de19ecaa1ef1495aa0c1af8d644/image.png" width="80%" height="80%">

- 와이어프레임 : [와이어프레임 바로가기](https://mirage-cardboard-868.notion.site/DB-d011b31d832a45258fd8343f303a8a85)

- API 명세서 : [API 명세서 바로가기](https://mirage-cardboard-868.notion.site/API-6605e3921b154407a3179673937b2b1d)

- DB 모델링 : [DB 스키마 바로가기](https://mirage-cardboard-868.notion.site/DB-d011b31d832a45258fd8343f303a8a85)
<img src = "/uploads/ef4c718f6b119fcac310887e499151e3/image.png" width="80%" height="80%">

## 4. 프로젝트 팀원 역할 분담

|  이름  |           담당 업무           |  이름  |           담당 업무           |
| :----: | :---------------------------: | :----: | :---------------------------: |
| 유상우 | 팀장 / 백엔드 / 캘린더, 유저  | 김민경 |   프론트엔드 / 캐릭터 관리    |
| 채유진 | 백엔드 / 캐릭터, 아이템, 상점 | 김현율 |   프론트엔드 / 일정(캘린더)   |
|        |                               | 박지찬 |      프론트엔드 / 관리자      |
|        |                               | 신연주 | 프론트엔드 / 메인화면, 로그인 |
|        |                               |        |                               |

**멤버별 responsibility**

1. 유상우 : 팀장/백엔드 담당

- 기획 단계: 구체적인 설계와 지표에 따른 프로젝트 제안서 작성
- 개발 단계: 팀원간의 일정 등 조율 + 백엔드 개발
- 수정 단계: 기획, 스크럼 진행, 코치님 피드백 반영해서 수정, 발표 준비
- 담당업무 : 
로그인/ 사용자 관리 서비스, 스케줄 관리 서비스, 캘린더 관리 서비스, 캘린더 공유 서비스, 서버 구축(nginx, pm2, gcp 등)

2. 채유진: 백엔드 담당

- 기획 단계: DB 스키마 설계, API 명세서 초안 작성
- 개발 단계: 백엔드 Issue 정리, 캐릭터, 아이템 관련 API 개발
- 수정 단계: 피드백 반영해서 백엔드 설계 수정
- 담당업무 :
캐릭터/아이템 관련 서비스, 사용자 캐릭터 수집 서비스, 사용자 아이템 수집 서비스, 서버 구축(nginx, pm2, gcp 등)

3.  김민경 : 프론트엔드 담당

- 기획 단계: 캐릭터 관련 와이어프레임 작성
- 개발 단계: 팀원간의 일정 등 조율 + 프론트 개발
- 수정 단계: 스크럼 진행, 코치님 피드백 반영해서 수정
- 담당업무 :
아이템 구매 페이지, 상점 페이지, 보유 아이템 사용 페이지, 캐릭터 프로필  페이지, 전체 도감 페이지

4. 김현율 : 프론트엔드 담당
- 기획 단계: 일정 캘린더 관련 와이어프레임 작성
- 개발 단계: 팀원간의 일정 등 조율 + 프론트 개발
- 수정 단계: 기획, 스크럼 진행, 코치님 피드백 반영해서 수정
- 캘린더 제작
- 담당 업무: 캘린더 페이지, 일정/할 일 관련 UI

5. 박지찬 : 프론트엔드 담당
- 기획 단계: 관리자 페이지 관련 와이어프레임 작성
- 개발 단계: 관리자 페이지 관련 프론트 개발
- 수정 단계: 기획, 스크럼 진행, 코치님 피드백 반영해서 수정
- 담당업무 :
관리자 페이지, 
아이템/도감/카테고리 정보 페이지, 유저 조회 및 삭제 페이지

6. 신연주 : 프론트엔드 담당
- 기획 단계: 메인화면, 로그인 관련 와이어 프레임 개발
- 개발 단계: 메인화면, 로그인 페이지 프론트 개발
- 수정 단계: 기획, 스크럼 진행, 코치님 피드백 반영해서 수정
- 담당업무 : 
로그인/회원가입 페이지, 사용자 정보 수정 페이지, 서비스(마이페이지) 페이지, 메인화면 페이지, 캘린더 공유 서비스 페이지


## 5. 실행 방법
#### 백엔드 : 실행 방법
```bash
0. cd app
1. yarn install     ## node package 설치
2. yarn start    ## 실행
2-2.yarn build    ## 빌드
```

#### 백엔드 : 실행 방법
```bash
0. cd server
1. yarn install     ## node package 설치
2. yarn dev    ## 실행

```

## 6. env 설정파일
#### 프론트 .env 파일 설정 예시
```bash
REACT_APP_API_KEY='{구글캘린더 연동을 위한 키}'
REACT_APP_CLOUD_DB='http://kdt-sw3-team12.elicecoding.com'
GENERATE_SOURCEMAP = false
```

#### 백엔드 .env 파일 설정 예시
```bash
MONGODB_URI = 'mongodb://localhost:27017/scheduleMonster'
PORT = 5000
JWT_SECRET_KEY='SceduleMonster'
REACT_APP_API_KEY='{구글캘린더 연동을 위한 키}'
SMTPID='{이메일 인증을 위한 SMTPID}'
SMTPPW='{이메일 인증을 위한 Password}'
```

### 6. 데모 영상

<details><summary>메인 페이지</summary>
<img src = 'https://kdt-gitlab.elice.io/sw_track/class_03/web_project_2/team12/schedule_monster/uploads/811237270c57ad560b0d117848b0eb25/1.gif' width ="640px" />
</details>

<details><summary>사용자 마이페이지</summary>
<img src = '/uploads/d25c8242424231e56ed07ee55ac5a42e/2.gif' width ="640px" />
</details>

<details><summary>캘린더 페이지</summary>
<img src = '/uploads/f78d4447e808a8b1ef2d7058dbb5dea2/ezgif.com-gif-maker__2_.gif' width ="640px" />
</details>

<details><summary>캘린더 다른 사용자와 공유하는 기능</summary>
<img src = '/uploads/93b49903bc6b218b728beaf818b1179b/5.gif' width ="640px" />
</details>

<details><summary>캘린더 추가</summary>
<img src = '/uploads/4878030e32a99a83f4ef0e880a537c3d/3.gif' width ="640px" />
</details>

<details><summary>캐릭터 페이지</summary>
<img src = 'https://im3.ezgif.com/tmp/ezgif-3-6e66a0f807.gif' width ="640px" />
</details>

<details><summary>상점 페이지</summary>
<img src = 'https://im3.ezgif.com/tmp/ezgif-3-e0e7774147.gif' width ="640px" />
</details>

<details><summary>관리자 페이지</summary>
<img src = '/uploads/5ed7e69f56f17789a61c572a80bc7fe6/8.gif' width ="640px" />

</details>

<br />


## 7. 버전

- 프로젝트의 버전 (1.0.0)

## 8. FAQ

- 자주 받는 질문 정리
- 예시) 이 서비스는 어떻게 실행하면 되나요?
  - git clone을 하신 후 아래 커맨드를 입력하시면 됩니다. ~~~
