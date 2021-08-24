## 프로젝트

### Main Project 목록

- 1) 증강현실을 활용한 스마트 홈의 제어

  - 기간: 19.09 ~ 19.12

  - 기술스택 및 사용 툴: C#, Unity(Vuforia 라이브러리, Ardunity 라이브러리), IoT(Arduino leonardo 및 센서들, 실모형 제작까지), 3D modelling(Sketchup)

  - 내용:  

    유니티 기반으로 스마트홈을 제어하고, 사용자가 편리하게 사용할 수 있는 UI를 만들었음.
    더 나아가 슬립테크를 스마트홈에 접목시키면서 동시에 증강현실을 이용해 제어를 할 수 있게 구현함. 

    사용한 기술은 AR, IoT, 3D modeling이고, AR은 Vuforia라이브러리를 활용, IoT는 아두이노를 활용, 3D modelling은 스케치업을 활용하였고, 각 요소를 유니티 환경으로 통합하고 안드로이드 빌드를해주어 앱에서 제어가 가능하도록 설계하고 개발함.

   - 모델링 - 평면도 구상 후 Sketchup 툴을 이용하여 직접 사용할 3D모델링을 제작

   - 실모형 제작 - 우드락, 폼보드 및 센서를 이용한 실 모형 제작

   - 어플리케이션 제작 - 

    1. 유니티를 통해 UI제작, 3D 모델링 제어, 아두이노 센서 제어 등을 구현함.
    2. Sketchup을 이용해 만든 3D 모델링을 유니티로 가져오고 실제 모형에 부착되어 있는 아두이노 센서들을 제어하기 위해 ‘아두니티’ 툴을 사용

   - 인터페이스 제작  - 

    1. 홈 화면에서 모드 변경을 통해 재택모드와 외출모드로 변경
    2. 스캔을 눌러 카메라로 화면을 전환(AR 스캔)
    3. 모델을 누르면 오른쪽에 보이는 UI와 같이 3D 모델링 제어

   - 스마트 홈 제어 -

    1. 조도센서와 서보모터를 활용하여 창문 제어, 수동 및 빛의 인식을 통한 자동 조절 가능
    2. 초음파 센서를 활용하여 재택모드, 외출 모드를 구별하고 움직임이 감지되면 알림창 뜨게 함.
    3. 침대에 온습도센서, 서보모터, LED 부착 - 침대 스캔시 온습도, 조명 밝기 제어 기능 제공 및 침대 윗 부분의 기울기 조정과 알람 설정을 통해 특정 시간에 기울어지게 하는 기능 제공.

  - 역할:

    팀장, 기획, AR 초기 담당, 아두이노 활용하여 실모형 제작, 문서작성 및  발표  

```
ppt 자료: https://drive.google.com/file/d/1KGMfiT-OQpeEE4wwmUJg4TsGUAtyDQ32/view?usp=sharing

- 교내 SW공모전 금상 (주관 : IITP정보통신기술진흥센터)
- 캡스톤 경진대회 본선 진출
- 산학협력단과 함께 특허출원 (스마트홈 환경에서 AR기술을 활용한 슬립테크 제어 방법)
- 논문 (Method of Sleeptech control using AR ln Smart home environment) [http://koreascience.or.kr/article/CFKO202024664104598.page]
- 학술발표대회 (2020 한국정보처리학회, 온라인 춘계학술발표대회(5/29 ~ 30)  발표자)
```

- 2) 증강현실을 활용한 스마트 빌딩 관리 

  - 기간: 20.03 ~ 20.06

  - 기술스택 및 사용 툴: C#, Unity(Vuforia 라이브러리, Ardunity 라이브러리), IoT(Arduino leonardo 및 센서들, 실모형 제작까지), 3D modelling(Sketchup), OpenCV, Maria DB

  - 내용: 

    위 프로젝트의 피드백으로 얻은 내용을 기반으로 빌딩 관리 제어 앱 개발.     

    제공기능: 사용자 인증, 3D 모델링, AR, 방범모드

    OpenCV를 활용하여 관리자 인증을 구현.
    모델링을 터치하여 건물 제어가능 하도록 구현.
    사무실을 들어가지 않더라도 문 앞에서 QR코드 스캔을 통해 사무실 안의 정보를 AR형태의 그래픽으로 출력해주어 확인이 가능하도록 구현. (제어도 가능)
    일반 모드, 방범 모드로 나누어 방범 모드일 때에는 특정 구역에 움직임이 느껴지면 알림이 오도록 구현.  

   - 모델링 - 평면도 구상 후 Sketchup 툴을 이용하여 직접 사용할 3D모델링을 제작  

   - 실모형 제작 - 우드락, 폼보드 및 센서를 이용한 실 모형 제작  

   - 어플리케이션 제작 -   

    1. 유니티를 통해 UI제작, 3D 모델링 제어, 아두이노 센서 제어 등을 구현함.  
    2. Sketchup을 이용해 만든 3D 모델링을 유니티로 가져오고 실제 모형에 부착되어 있는 아두이노 센서들을 제어하기 위해 ‘아두니티’ 툴을 사용

   - 인터페이스 제작  -   

    1. 홈 화면에서 모드 변경을 통해 일반모드와 외출모드로 변경  
    2. 스캔을 눌러 카메라로 화면을 전환(AR 스캔)  
    3. 모델을 누르면 오른쪽에 보이는 UI와 같이 3D 모델링 제어 

  - 역할:
    팀장, 기획, AR 초기 담당, 아두이노 활용하여 실모형 제작, 문서작성 및 발표

```
발표영상: https://drive.google.com/file/d/11yecyuLX10u1akSJ7C5PHtpIWtbXZ-zo/view?usp=sharing

보고서: https://drive.google.com/file/d/1fHwCgp7mo6uHcnrw-VbgyLEkU_9uztnx/view?usp=sharing

- 위의 증강현실을 이용한 스마트 홈의 제어의 피드백 내용을 토대로 블루투스 연결의 보안취약점을 OpenCV를 활용하여 해결
  
```

- 3) 삼성청년소프트웨어아카데미(SSAFY) 1학기 최종 관통 프로젝트 영화 커뮤니티 제작

  - 기간: 21.05.20 ~ 21.05.28 (학습 기간 21.03 ~ 21.05)

  - 기술스택 및 사용 툴: Vue.js(node.js를 통한 CLI), Django, Django REST API, Bootstrap, Sqlite, TmDB api, Youtube API, Vscode, Chrome Browser, Vanilla JS, Node.js

  - 내용:
    삼성청년SW아카데미 1학기 최종 관통 프로젝트로서 1학기 동안  배운 내용을  토대로 영화 커뮤니티 웹사이트 제작 진행함.      

    외부 영화 API를 활용하여 DB를 구축하고, node.js를 통해 활용한 Vue.js(CLI)를 통해 프론트단을, Django를 통해 Restful하게 백단을 구성하고 css과 Bootstrap을 이용하여 디자인을 꾸몄음.

  - 기본 요구 사항:
   - 관리자 뷰 (Django내에서 admin.py에 만든 기능들 연결 후 superuser 계정을 생성하여 완료)
     
     :white_check_mark: 관리자 권한의 유저만 영화 등록/ 수정 / 삭제 권한 가짐.
     
     :white_check_mark: 관리자 권한의 유저만 유저 관리 권한을 가짐.
     
     :white_check_mark: 장고에서 기본적으로 제공하는 admin 기능 이용하여 구현
   - 영화 정보(Tmdb API를 통해 영화정보를 가져오고 이를 구조에 맞게 수정 후 DB구축)
     
     :white_check_mark: 영화 정보는 최소 50개 이상의 데이터가 존재하도록 구성
     
     :white_check_mark: 모든 로그인 된 유저는 영화에 대한 평점 등록 / 수정 / 삭제 등이 가능해야함.
   - 추천 알고리즘(콜드 스타트에 대비하여 다양한 장르들의 대표작들을 선택할 수 있도록 제공하고, 사용자의 선택에 따라 영화 추천)
     
     :white_check_mark: 평점을 등록한 유저는 해당 정보를 기반으로 영화를 추천 받을 수 있어야 함.
     
     :white_check_mark: 추천 알고리즘의 지정된 형식은 없으나, 사용자는 반드시 최소 1개 이상의 방식으로 영화를 추천 받을 수 있어야 함.
     
     :white_check_mark: 추천 방식은 각 팀별로 자유롭게 선택할 수 있으며 어떠한 방식으로 추천 시 스템을 구성 했는지 설명할 수 있어야 함.
   - 커뮤니티
     
     :white_check_mark: 영화 정보와 관련된 대화를 할 수 있는 커뮤니티 기능을 구현해야 함.
     
     :white_check_mark: 로그인한 사용자만 글을 조회 / 생성 할 수 있으며 작성자 본인만 글을 수정 / 삭제 할 수 있음
     
     :white_check_mark: 사용자는 작성된 게시글에 댓글을 작성할 수 있어야 하며 작성자 본인만 댓 글을 삭제 할 수 있음
     
     :white_check_mark: 각 게시글 및 댓글은 생성 및 수정 시각 정보가 포함되어야 함
   - 기타
     
     :white_check_mark: 최소한 5개 이상의 URL 및 페이지를 구성해야 합니다.
     
     :white_check_mark: HTTP Method와 상태 코드는 상황에 맞게 적절하게 반환되어야 하며, 필요에 따라 메시지 프레임워크 등을 사용하여 에러 페이지를 구성해야 합니다
     
     :white_check_mark: 필요한 경우 Ajax를 활용한 비동기 요청을 통해 사용자 경험을 적절하게 향 상 시켜야 합니다
  - 추가 구현 기능(자율적으로 수행):
    
    :white_check_mark: 인피니트 스크롤, 캐로셀 등의 디자인 적인 요소 추가
    
    :white_check_mark: 사용자의 경험을 위한 비동기식(ajax) 코드 추가 구현(사진 불러올 때 등)
    
    :white_check_mark: 유튜브 api를 활용하여 리뷰 페이지에서 영화의 트레일러 영상 제공
    
    :white_check_mark: 커뮤니티 페이지에서 게시글들 검색 기능 추가
    
    :white_check_mark: 회원 가입 시 비밀번호 일치 여부 제공, 로그인 시 자동 저장 기능 추가.

  - 역할:
    팀장, 아이디어 구상 및 모델 및 컴포넌트 구조 구성, 초기 BE 담당, 추가 기능 구현
    사용자 경험을 우선으로 한 디자인 작업, 예외 처리, 발표 자료 준비 및 발표

```
레포 주소: https://github.com/CHASEONGMIN/Projects/tree/main/MainProjects/SSAFY_5TH_firstsemester_final_pjt

시연 이전 부분까지의 내용 ppt: https://github.com/CHASEONGMIN/Projects/blob/main/MainProjects/SSAFY_5TH_firstsemester_final_pjt/210528_5%EA%B8%B0_%EB%8C%80%EC%A0%84_2%EB%B0%98_%EA%B4%80%ED%86%B5PJT_%EC%A1%B0%EC%9B%85%ED%98%84_%EC%B0%A8%EC%84%B1%EB%AF%BC.pptx
 
```

- 4) 삼성청년소프트웨어아카데미(SSAFY) 2학기 공통 프로젝트 웹IoT 트랙   (우수 프로젝트 선정)

  - 기간: 21.07.05 ~ 21.08.20

  - 기술스택 및 사용 툴: React, Node.js, Django, DB(웹: Mysql, 라즈베리파이: Maria DB), 라즈베리파이, Whimsical, Python, Vanilla JS, vsCode, Chrome Browser, LED, 부저센서, 체계적인 프로젝트를 위해 Jira, Notion, GitLab등의 협업툴을 활용(Git flow 활용 포함).

  - 내용:     
   1. 서비스명 : 냉장고를부탁해
   2. 서비스 설명/ 주요기능 : 
     - 서비스 설명: 점점 늘어가는 2030 1인가구를 위한 냉장고 매니저이고, 특히 요리에 관심있는 2030 1인가구들의 입장에서 냉장고를 보다 효율적으로 활용할 수 있게 서비스를 제공하는 서비스
     - 주요 기능:  개인별 맞춤형 서비스 제공, 레시피 활용 서비스, 재료 관리 서비스
     
        :white_check_mark:  사용자별 재료 및 좋아하는 레시피 등록 가능
      
        :white_check_mark:  등록한 내용토대로 2가지 방식으로 추천 레시피 제공 및 레시피 검색 가능
      
        :white_check_mark:  레시피 재료 중 없는 것 표시 및 유통기한 지난 재료 있을 시 알림
      
   3. 주요기술스택: React, Node.js, Django, DB(웹: Mysql, 라즈베리파이: Maria DB), 라즈베리파이, Whimsical, Python, Vanilla JS, vsCode, Chrome Browser, LED, 부저센서   
   4. 차별화된 기술:
    
      :white_check_mark:  유저 개인별 맞춤형 추천 서비스 제공          
    
      :white_check_mark:  데이터 전처리 후, 더 나아가 연관성 검색 기능을 구현하여 오타있어도 제대로된 결과 도출
    
      :white_check_mark:  시중에 없는 다양한 부가기능 제공(없는 재료 파악, 타이머 등)
      
      :white_check_mark:  IoT센서를 활용한 기능 탑재
      
  - 역할:
    팀장(Jira 스프린트 및 이슈 관리, Git flow 관리 및 머지 확인, 진행현황 매일 확인하며 팀장회의 참석, 간트차트 활용하여 팀 일정관리),
    기획(Whimsical을 통한 와이어프레임 제작, 화면정의서 제작), 프런트엔드(React) 및 디자인(Material-Ui) 개발, 발표

```
UCC: https://drive.google.com/file/d/1IWZLK2Kx22yCSVlsHReYPQaXrGsl-NgR/view?usp=sharing

최종 ppt: https://docs.google.com/presentation/d/1shVhlIhsxN9V1Hzay55PwE47-LzFTyj5/edit?usp=sharing&ouid=104755432594470438671&rtpof=true&sd=true
 
```

    
### 2인 이하 서브 프로젝트

- 레포 주소: https://github.com/CHASEONGMIN/Projects/tree/main/SubProjects

  그래픽스 프로젝트 보고서 및 PPT
  매트랩 프로젝트 보고서


