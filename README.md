<!--타이틀 부분-->

<div align="center">
<!--   <img src="https://github.com/oka1313/oka1313/assets/101691440/92118a53-c5b6-40bc-b130-bf8c398d7b51" /> -->
  <img src="https://capsule-render.vercel.app/api?type=Waving&color=auto&height=300&section=header&text=JuYeong's%20Github&fontSize=90" />
</div>



<!--내용 부분-->
<h1 align="center">✨ 경력기술서 ✨</h1>

      ❗️ 프로젝트명 또는 프로젝트명 하단에 링크를 누르시면 해당 레파지토리로 이동됩니다
<div>
  <h3><a href="https://github.com/devdaram/Msa-Service.git">🗓️ KT Cloud NMS 차세대 아키텍처 개발 (2024.03 ~ 현재)</a></h3>
  <div>
    
    [Cisco 장비 연동 서비스 개발]
    - 장비에 요청을 보내고, 장비의 응답을 받아서 다른 서비스에 전달하는 서비스를 개발. 
    - SDN : Custom Round Robin 방식을 구현하고자 Temporal workflow를 사용하여 장비 연동 및 자동화 서비스를 개발 중.
    - NSO : 장비로 내려가는 연동 API 개발
    
    [Gateway 서비스 개발]
    - MSA 구조에서 들어오는 요청의 헤더를 보고 인증서버로 보낸 뒤 인증여부에 따라 내부 서비스로의 라우팅 기능을 구현.
       
  </div>
</div>
<br><br>

<div>
  <h3>🗓️ 삼성전자 Private 5G NMS(PNMS) 개발 (2023.03 ~ 2023.12)</h3>
  <h5><a href="https://github.com/devdaram/web-backend/tree/main#-2-%EC%82%BC%EC%84%B1%EC%A0%84%EC%9E%90-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8">⍟ web-backend repository</a></h5>
  <h5><a href="https://github.com/devdaram/Web-Front/tree/main#-2-%EC%82%BC%EC%84%B1%EC%A0%84%EC%9E%90-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8.git">⍟ web-front repository</a></h5>
  <div>
    
    [전체적인 NMS Web 개발]
    - Web Backend : 사용자관리, 로그인, 메뉴관리, 권한관리, Tenant관리, IP 권한관리, 세션관리, 세션 히스토리관리, 3rd party 관리, 장비 Group 관리 등 RestAPI 개발하였음.
    - Web Front : 위의 기능이 동작하는 화면개발 및 공통 컴포넌트 개발
    
    [다국어 처리]
    - Web Backend, Front에서 Exception 처리 및 log 등 다국어처리가 될 수 있도록 locale을 받아 해당 언어로 응답 될 수있도록 개발
    
    [권한 및 세션관리]
    - 사용자의 로그인기능(password 일치여부, lock처리, IP대역체크 등)과 사용자 권한(Tenant, 운용자 권한 등)에 따른 로직처리, 만료된 세션을 체크 경험이 있음.
    
    [파일처리]
    - 파일이나 이미지를 서버에 저장, DB에 저장 후 이를 다시 불러오는 RestAPI를 개발
     
  </div>
</div>
<br><br>

<div>
  <h3>🗓️ SKT HOLA 유지보수 / 고도화 개발 (2021.08 ~ 2022.11) </h3>
    <h5><a href="https://github.com/devdaram/web-backend/tree/main#-1-skt-프로젝트-">⍟ web-backend repository</a></h5>
  <h5><a href="https://github.com/devdaram/Web-Front/tree/main#-1-skt-프로젝트-.git">⍟ web-front repository</a></h5>
  <div>
    
    [장비 토폴로지 등록]
    - Web Backend : 장비 토폴로지(Ring)등록 작업 RestAPI 개발
    - Web Front : 장비 토폴로지(Ring)등록 작업을 화면에 추가
    
    [Package donwload]
    - Web Front : Package download 시 필요한 Web Woker 개발
    (Package가 대부분 용량이 크기 때문에 시간이 오래걸리는 작업으로, 별개의 Thread로 동작할 수 있도록 개발하였음.)


  </div>
</div>
<br><br>

<div>
  <h3><a href="https://github.com/devdaram/Spring-Integration-Syslog.git">🗓️ 한전 Access SDN BMT 개발(2022.02 ~ 2022.04)</a></h3>
  <div>
  
    [Syslog 수집 모듈 개발]
    - Spring Integration 과 Spring Batch를 활용하여 장비의 Log message를 수집하여 DB에 저장할 수 있는 모듈개발
    - 수집된 로그를 화면에서도 볼 수 있도록 Web Front 개발
    
  </div>
</div>
<br><br>

<div>
  <h3><a href="https://github.com/devdaram/Operation-Community-Board.git">🗓️ SKB 국가융합망 (2021.08 ~ 2021.09)</a></h3>
  <div>
    
    [운영자를 위한 게시판 개발]
    - Web Backend : 운영자를 위한 커뮤니티 게시판에 필요한 RestAPI 개발
    - Web Front : 게시판 화면 개발 
    
  </div>
</div>
<br><br>

<div>
  <h3><a href="https://github.com/devdaram/Korail-Web.git">🗓️ 철도공사 전원관리시스템 NMS 개발 (2021.04 ~ 2021.09)</a></h3>
  <div>
    
    [NMS 웹 개발]
    - Web Backend : 전원설비, 무선설비 등 관리하는 화면에 필요한 RestAPI 개발
    - Web Front : 전원설비, 무선설비 등 관리하는 화면 개발 
    
  </div>
</div>
<br>
<br>

<h1 align="center">✨ 활동 목록 ✨</h1>

     ❗️ 제목을 누르시면 해당 레파지토리로 이동됩니다

<div>
  <h3 ><a href="https://github.com/devdaram/Git-convetion-share.git"> 🦋 Git PR , Convention 문화 만들기 </a></h3>

    저는 팀 내 Git 활용도를 높이기 위해 Git PR 및 코드 컨벤션 규칙 관련 문서를 작성하여 교육을 진행했습니다. 
    그 결과, 팀 내에 Git 기반의 개발 문화가 정착되어 이전보다 소통과 협업이 원활해졌습니다.
</div>
<br>

<div>
  <h3><a href="https://github.com/devdaram/OJT-Process.git"> 🦋 신입사원 OJT 진행</a> </h3>

    회사의 OJT 문화가 없었지만, 
    신입사원 시절 상급자분이 따로 OJT를 진행해주셨던 경험이 저에게 큰 도움이 되었습니다.
    이를 바탕으로, 이후 신입사원들을 위해 직접 OJT를 준비하여 진행한 경험이 있습니다.
</div>
<br>

<div>
  <h3><a href="https://github.com/devdaram/keyclock-auth-service.git"> 🦋 Keycloak 사용 </a></h3>

    프로젝트 투입 전에 Keycloak을 활용하면 개발 효율이 높아질 것 같아, 사용자 권한 관련 기능을 Keycloak으로 직접 개발해본 경험이 있습니다. 
    이를 통해 새로운 기술을 빠르게 습득하고, 실제 프로젝트에 적용할 수 있는 가능성을 검증하며 팀에 실질적인 도움을 줄 수 있었습니다.
    
</div>
<br>

<div>
  <h3><a href="https://github.com/devdaram/Notion-Activity.git"> 🦋 Notion으로 업무활동 기록 </a></h3>
    
    사내에서 적극적인 개발 문화를 조성하기 위해 Notion을 활용하여 일정 및 진행 상황을 공유할 수 있는 스페이스를 만들고 사용한 경험이 있습니다.
    이를 통해 기존의 대단위 기능 단위로만 이루어졌던 분업에서 벗어나, 웹 포지션 개발자들과 더 세부적으로 업무를 분담할 수 있었고, 
    그 결과 업무 효율성이 크게 향상되었습니다.
</div>

<!--   <img src="https://img.shields.io/badge/react-20232a.svg?style=for-the-badge&logo=react&logoColor=61DAFB" />&nbsp
  <img src="https://img.shields.io/badge/javascript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=20232a" />&nbsp
  <img src="https://img.shields.io/badge/html5-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />&nbsp -->


