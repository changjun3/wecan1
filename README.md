## 0. CoDev

손 쉽게 팀원을 매칭해드립니다, CoDev

## 1. 팀원

- 우준석 : 부산대학교 it응용공학과 20학번
- 이창준:  부산대학교 it응용공학과 20학번

## 2. 개발 환경

- FrontEnd: Html, CSS
- BackEnd: Spring Boot
- DB: MySQL

## 3. ERD (DB 설계)

![297330612-11013b68-b80b-4d9c-b2eb-a1a4fc1a15d0](https://github.com/user-attachments/assets/586a90d6-b2d2-4a74-977e-fa1e3b3c6e34)
## 4.  기능 소개

### 홈 화면

![297330645-0507778b-d08c-47d7-9b09-86bca1a7d26f](https://github.com/user-attachments/assets/6f19a12e-abda-45d6-943c-da76d6802dd4)
- 게시물 목록
- 아이디어 공모전 랭킹 Top3
- 로그인, 로그아웃, 회원가입, 마이프로필 버튼
    - 로그인한 사용자인 경우, 로그아웃, 마이프로필 버튼 활성화
    - 로그인을 하지 않은 사용자인 경우,  로그인, 회원가입 버튼 활성화

---

### 로그인 화면

- 회원가입

![297330683-fe59e8cd-a05e-4a9b-ab49-36a44b1eb345](https://github.com/user-attachments/assets/b5b0c81f-304f-47a2-8177-fac873e43988)
- 앱 자체 회원가입을 구현하여 아이디, 비밀번호 그 외 웹 사용을 위해 필요한 학력, 수상내역1, 수상내역2,스택, 깃헙 url, 한줄 소개에 대한 정보를 따로 입력받습니다.
- 로그인

![297330704-31cb1923-62d8-44ef-86b3-5ea470945399](https://github.com/user-attachments/assets/0ccda8bf-b360-46f6-bef3-29e034e316ad)
- 로그인 시, 아이디, 비밀번호를 입력 받아 DB에 있는 경우 로그인이 가능하고 없는 경우 회원가입창으로 이동해 바로 회원가입이 가능합니다.

---

### 게시물 화면

- 게시물 목록 (검색)
    
![297330740-f7510f17-50ef-49a2-b5d5-e1386b59415e](https://github.com/user-attachments/assets/35c43072-0999-405a-be37-d248aaceb52b)
    - 게시물 목록에서 검색어가 작성자, 내용, 제목에 들어간 게시물을 검색이 가능하고 게시물이 최근 순으로 정렬됩니다.
- 게시물 추가
    
![297330794-350b1f47-5628-4779-9e28-57ce00716822](https://github.com/user-attachments/assets/777edf40-d748-464f-9654-7f7f3b9e1f52)
    - 게시물 추가가 가능하여 게시물 제목, 게시물 내용, 프로젝트 제목, 날짜, 프로젝트 설명, 프로젝트 멤버 수에 대한 정보를 입력 받습니다. 프로젝트 팀원을 모집하는 게시물로 댓글로 소통이 가능합니다.
- 댓글 기능
    
![297330869-20e8d915-1bc6-4710-9a34-ad1882160f00](https://github.com/user-attachments/assets/c2bccf96-50d5-4225-9aaf-c394bf726575)
    - 댓글로 다른 사용자가 올린 프로젝트에 참여하고 싶은 경우, 의사를 표시할 있습니다.
    - 게시물을 작성한 작성자의 경우 댓글을 보며 댓글 작성자 프로필을 확인할 수 있습니다. 원하는 팀원을 고른 후, 팀원 매칭 버튼을 누르면 해당 팀원들이 프로젝트에 매칭됩니다.

---

### 아이디어 공모전 화면

- 아이디어 공모전 투표
    
![297330899-6dabe071-bb87-4db8-ae7e-c749b9e77beb](https://github.com/user-attachments/assets/0576dd34-11e1-4ef5-aa33-ba6699ff0d70)
    - 아이디어 목록이 보이고 로그인한 사용자는 하나의 공모전에 대해 한 번 투표할 수 있습니다. 투표 결과는 홈 화면의 Top3에 바로 반영되고 그 외의 결과도 DB에는 반영됩니다.
- 아이디어 추가
    
![297330921-b5f326ac-3cb1-4507-b56f-637915979e41](https://github.com/user-attachments/assets/43c0ee93-a0cc-40e3-aecd-6639583204d3)
    - 아이디어 제목, 아이디어 설명을 적어 아이디어 공모전에 나의 아이디어를 추가할 수 있습니다. 아이디어 추가 시,  아이디어 목록에서 확인할 수 있습니다.

---

### 프로필 화면

- 자기소개
    
![297331039-2a785c5c-47a2-46c3-a982-6e94d2c84859](https://github.com/user-attachments/assets/af191964-bb68-4d1d-af08-12f25a1dc065)
    - 사용자의 학력, 수상내역1, 수상내역2, 스택, 깃헙 url, 한줄 소개, 기여도에 대한 정보를 보여줍니다.
- 참여한 프로젝트
    
![297331109-e27db1e9-fee7-4575-b68d-e5afecf25ffd](https://github.com/user-attachments/assets/369c8834-e4cc-491c-b016-036ea146616b)
    - 사용자가 참여한 프로젝트가 있을 경우, 참여한 프로젝트들을 보여줍니다.
    - 오른쪽 평가 버튼을 누르면 같이 프로젝트를 진행한 팀원들의 기여도를 남길 수 있습니다.
        
![297331160-29ab6f6c-1964-48ae-9369-84d01f6d2f6e](https://github.com/user-attachments/assets/18b8b1f5-e4c7-4668-b013-314ee01c14da)

---

### 스크럼

- 스크럼 목록
    
![297331197-5ecf21bb-136d-4c82-98f6-2f538d41a901](https://github.com/user-attachments/assets/b7527aa5-3903-4804-b2ce-ac66b3f9f3d8)
    - 프로젝트에서 지금까지 진행한 스크럼 목록을 보여줍니다. 3개, 5개, 7개의 스크럼 수를 기준으로 원의 색깔이 변경됩니다.
- 스크럼 추가
    
![297331234-be5e1105-70e8-4b0c-87c6-aadc220fcd4f](https://github.com/user-attachments/assets/858584f3-9d18-4031-8ad3-c13e70b04617)
    - 스크럼 제목, 스크럼 설명, 스크럼 날짜를 입력하여 스크럼을 추가할 수 있습니다.
