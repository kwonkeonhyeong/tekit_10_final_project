# [1주차] 바코드팀 팀플 진행상황

## 팀 구성원, 개인 별 역할

---

🐂권건형 🐳지유빈 🫧김유진 🍀윤유경 🦎김찬우

**공통 진행**

1. 주제 선정
2. 피그마 작성 (프로토타입 + 시나리오 작성)
3. 요구사항 정의서 (API 목록) 작성
4. Git 환경 설정 (SourceTree + Github)

구체적 역할은 개발 진행 시 분배

## 팀 내부 회의 진행 회차 및 일자

---

> 김찬우님 - 2024.07.23 ~ 07.25 → 예비군/병결로 불참
> 

**07.23(화)** 

- 프로젝트 주제 선정 + Figma UI 구성
    
    https://www.figma.com/design/Uns2p3BvztcpnfINOJQ4SO/barcode_team?node-id=0-1&t=LjJYPK9gRk9vK0b5-0
    

**07.24(수)**

- 팀 협업 레파지토리 및 팀원별 브랜치 생성  + Figma UI 완성
    
    [Git 설정](https://www.notion.so/Git-2d0208b29ab44076b3a0148c25d07ed9?pvs=21)
    
    https://github.com/kongkong2233/barcode_project
    
- 그라운드 룰 설정

**07.25(목)**

- API 명세서 작성
    
    https://docs.google.com/spreadsheets/d/1GkmDh9rUg3uV13m2qnLsMFrruzmEkEFF59aYYZHGf2A/edit?gid=0#gid=0
    
- 1주차 팀플 보고서 작성

## 현재까지 개발 과정 요약

---

## 1주차 진행상황

**07.23(화)** 

- 프로젝트 주제 선정
    - 주제 : 반려동물 SNS
    - **어떤 사람**들을 위해 만들어야 하는가? (주 사용자, 이해관계자)
        - 반려동물을 사랑 하는 사람
        - 반려동물을 자랑하고 싶은 사람
        - 반려동물을 키우지는 않지만 대리 만족 하고 싶은 사람
        - 반려동물과 관련된 게시물에만 노출되고 싶은 사람
        - 애완동물 관련 사업 광고 하고 싶은 사람
    - **어떤 기술**들(언어, 프레임워크 등)을 사용할까?
        - java spring boot, spring security, react.js, MySQL, docker, redis, git hub action
    - **어떻게 개발**할까? (방법론, 아키텍처)
        - 방법론: Waterfall, Agile, TDD, DDD
        - 아키텍쳐: 고민중…
        - PoEAA, MVC, MVVM, MVP, MVS, MVA …
    - **예비 후보**
        1. **스터디 어플**
            - 타이머 기능으로 시간을 계산 (열품타)
            - todo기능
            - 커뮤니티 기능
            - 공부를 해서 시간을 남기면 그에 따른 지식 나무가 자라는 설정
            
        2. **지역 별 채팅 (익명)** 
            - 시, 군 별 전체 채팅으로 맘껏 노는 채팅방
        
        1. **분리수거, 재활용**
            - 재활용 커뮤니티 (재활용품 재 사용 tip)
            - 사진 찍어서 어떤 재활용인지 확인
            - 사진은 무조건 앱이어야 함
            - 사진 데이터가 많이 필요함, 사용해야 할 ai도 선택 or 개발 필요함
        
        1. **음악 추천 어플**
            - 특정 지역에 갔을 때에 듣는 음악 추천
                
                (다른 사람들이 많이 들은 음악을 기준으로? 지역의 특징에 맞게 미리 입력 후 추천)
                
        2. **숙박**
            - 내가 원하는 테마, 분위기, 컨셉의 숙소를 찾고 싶은 사용자
- Figma UI 구성 + 시나리오
    
    https://www.figma.com/design/Uns2p3BvztcpnfINOJQ4SO/barcode_team?node-id=0-1&t=LjJYPK9gRk9vK0b5-0
    

**07.24(수)**

- 팀 협업 레파지토리 및 팀원별 브랜치 생성  + Figma UI 완성
    
    [Git 설정](https://www.notion.so/Git-b5001524047148cf993613c0b74c7ee1?pvs=21)
    
    https://github.com/kongkong2233/barcode_project
    
- 그라운드 룰 설정

**07.25(목)**

- API 명세서 작성
    
    https://docs.google.com/spreadsheets/d/1GkmDh9rUg3uV13m2qnLsMFrruzmEkEFF59aYYZHGf2A/edit?gid=0#gid=0
    
- 1주차 팀플 보고서 작성
- 프로젝트 이름 선정
    - FluffyTime
    - **예비 후보**
        - WagWag
        - Animal Love
        - WagZone
        - BarkBark
        - PawPaw

개발이 진행하기 앞서 프로젝트 기획 및 팀 빌딩 중입니다.

개발을 시작하기 전에 기획을 최대한 자세히 하는 것이 중요한데, 백엔드 분야라고 해서 화면 구성을 소홀히 하면 구체적인 로직과 데이터 파악이 어려울 수 있다고 생각합니다.

이 때문에 Figma를 사용해 프로젝트의 화면 구성을 상세히 작성하는 데 많은 시간을 투자했으며, 구체적인 시나리오와 함께 데이터 및 API를 추출하는 과정을 진행하고 있습니다.

## 개발 과정에서 나왔던 질문

---

1. **프로젝트 진행 시 Git 협업에 대한 전체적인 사이클이 궁금합니다.**
    1. 브랜치 구성
    2. pull request, merge 과정
        - 실습으로 팀원들이 각자 브랜치를 생성하고 Pull Request를 통해 Merge를 진행했는데, 이에 대한 실제 현업에서 사용하는 전체적인 흐름 확인 필요
        
2. **API 설계 시 어떤 것을 중점으로 보고 설계해야 하는지 궁금합니다.**
    - 유저 페이지 정보 불러올때 api를 여러번 통신해서 정보들을 불러오는게 맞는지, 
    서비스에서 프로필정보와 유저정보를 조인해서 하나의 api로 통신하는게 맞는지???
    - 페이징 처리와 관련된 파라미터도 api 명세에 추가해야되는지??

## 개발 결과물 공유

---

Github Repository URL:  https://github.com/kongkong2233/barcode_project

https://www.figma.com/design/Uns2p3BvztcpnfINOJQ4SO/barcode_team?node-id=0-1&t=LjJYPK9gRk9vK0b5-0

https://docs.google.com/spreadsheets/d/1GkmDh9rUg3uV13m2qnLsMFrruzmEkEFF59aYYZHGf2A/edit?gid=0#gid=0