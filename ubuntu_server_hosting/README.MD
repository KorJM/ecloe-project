<h1> Ubuntu 설치</h1>

<span>UTM 가상머신을 사용하여 Ubuntu를 설치하는 방법을 알려드리겠습니다</span>
<span>공식 홈페이지에서 UTM과 ubuntu ISO 파일을 다운받아주세요</span>
<br><br>

<img width="896" alt="UTM에서 Ubuntu설치" src="https://github.com/KorJM/maphant-app/assets/114234223/a864f014-fcf9-410e-bdc5-9b9b37d22c3a">

<br>

<span>Virtualize 선택</span>

<br><br>

<img width="896" alt="스크린샷 2023-09-09 오전 1 11 07" src="https://github.com/KorJM/maphant-app/assets/114234223/88926025-7c6f-43c1-9d53-cb1a69aeb97b">

<br><br>

<span>Linux 선택</span>
<br>

<img width="896" alt="스크린샷 2023-09-09 오전 1 11 17" src="https://github.com/KorJM/maphant-app/assets/114234223/38b6c3d6-66fc-46d9-8bc7-bd26dd131d18">

<br>

<span>Boot ISO Image에 다운받은 ubuntu ISO 파일을 선택합니다</span>

<br><br>
<span>이후 메모리 설정해주시고 저장소는 20GB 이상 잡아주시는게 좋습니다</span><br>
<span>공유 폴더는 설정하지 않습니다</span>
<br><br>

<img width="896" alt="스크린샷 2023-09-09 오전 1 12 31" src="https://github.com/KorJM/maphant-app/assets/114234223/84e067aa-f2f1-4c50-9cfc-c222708ca37a">

<br>
<span>이름 설정하고 저장해주시면 됩니다</span>

<br><br>

<img width="789" alt="스크린샷 2023-09-09 오전 1 13 39" src="https://github.com/KorJM/maphant-app/assets/114234223/6b7dd6c6-5217-44ac-9d6e-e9ef79b03bd0">

<br>

<span>Install Ubuntu Server에서 Enter쳐주시고요</span>

<br><br>

<img width="1274" alt="스크린샷 2023-09-09 오전 1 14 22" src="https://github.com/KorJM/maphant-app/assets/114234223/52977183-9732-49de-920c-8de57a0d298d">

<br>
<span>English 선택</span>

<br><br>

<img width="1274" alt="스크린샷 2023-09-09 오전 1 14 34" src="https://github.com/KorJM/maphant-app/assets/114234223/7ee6854d-19c1-48f2-a41c-4d81abcf5ed7">

<br>

<span>update 해줍시다</span>
<span>이후에 전부 Done 해주시고</span>

<br><br>

<img width="1276" alt="스크린샷 2023-09-09 오전 1 16 55" src="https://github.com/KorJM/maphant-app/assets/114234223/eeeb1303-d0f8-41cc-9be5-12d89f6184cf">

<br>

<span>DHCP로 IP 자동 할당 해줬습니다</span>
<span>이후에 전부 Done 해주시고</span>

<br><br>

<img width="1274" alt="스크린샷 2023-09-09 오전 1 17 44" src="https://github.com/KorJM/maphant-app/assets/114234223/bbdd4de8-af47-4e25-a5ce-ca3cd07847aa">

<br>
<span>Set up this disk as an LVM group는 여러 물리 디스크를 하나의 가상 디스크로 묶어주는 것인데 체크 풀어주세요</span>
<span>이후엔 계속 넘겨주시고</span>
<br><br>

<img width="1274" alt="스크린샷 2023-09-09 오전 1 18 30" src="https://github.com/KorJM/maphant-app/assets/114234223/39e21809-683c-43ae-8380-2a4fcf488e2b">

<br>

<span>서버이름과 유저 이름 비밀번호 설정해주십다</span>

<br><br>

<img width="1274" alt="스크린샷 2023-09-09 오전 1 18 46" src="https://github.com/KorJM/maphant-app/assets/114234223/574510f2-5725-4fe7-853b-d0dd11f9c6d0">

<br><span>버전 업그레이드인데 유료이니 넘겨줍니다</span>

<br><br>

<img width="1274" alt="스크린샷 2023-09-09 오전 1 19 23" src="https://github.com/KorJM/maphant-app/assets/114234223/877b6a61-fe2a-49ab-b0ad-fc558b4a305f">

<br><span>SSH를 사용해 원격으로 시스템에 접속하는 기능입니다. 체크해줍시다</span>
<span>이후엔 계속 넘겨주세요</span>
<br><br>

<img width="1278" alt="스크린샷 2023-09-09 오전 1 28 55" src="https://github.com/KorJM/maphant-app/assets/114234223/9470b658-4056-4eee-8c07-298983229409">

<br><span>업데이트가 다 되면 Reboot합니다</span>

<br><br>

<img width="1278" alt="스크린샷 2023-09-09 오전 1 30 59" src="https://github.com/KorJM/maphant-app/assets/114234223/5594c7c8-f404-443a-bda4-1bef4064586b">

<br>

<img width="1280" alt="스크린샷 2023-09-09 오전 1 33 04" src="https://github.com/KorJM/maphant-app/assets/114234223/f9e86fe4-0d85-443c-84cb-cfc0ba311495">

<br><span>로그인 하시고 $ sudo apt update && sudo apt upgrade -y 으로 업그레이드 해주시면 설치가 끝났습니다</span>

<br><br>

<h1>cockpit 설치</h1>
<span>cockpit은 리눅스 기반 서버 관리를 위한 웹 기반 관리 도구로 원격으로 서버를 관리할 수 있는 장점이 있습니다</span>

<br><br>

<img width="963" alt="cockpit설치 및 Ubuntu Web VM" src="https://github.com/KorJM/maphant-app/assets/114234223/98099b5a-d803-4d7c-99fc-529265090215">

<br><span>$ sudo apt install cockpit 명령어를 통해 설치해주시고</span>
<span>순서대로 $ sudo systemctl enable cockpit</span>
<span>$ sudo systemctl start cockpit로 실행해줍시다.</span>

<br><br>

<img width="846" alt="스크린샷 2023-09-09 오전 1 45 58" src="https://github.com/KorJM/maphant-app/assets/114234223/f2733069-1094-44c3-bee8-7d3ab687e8f4">

<br>

<span>cockpit이 설치된 서버의 IP주소:9090를 입력하여 Cockpit 웹 인터페이스에 접속합니다.</span>

<br><br>

<img width="846" alt="끝" src="https://github.com/KorJM/maphant-app/assets/114234223/875d4db1-30fd-4cd2-9933-c276e4a761c8">

<br>

<span>로그인 하시고 관리자 자격 증명 해주시면 원격으로 시스템 관리 작업, 모니터링, 서비스 관리 및 다른 관리 작업을 수행할 수 있습니다.</span>

<br><br>

<h1>CloudPanel 설치</h1>
<span>CloudPanel은 웹 호스팅 및 서버 관리를 위한 웹 기반 패널입니다. Ubuntu 22.04에 설치해보겠습니다<span>

<br><br>

<img width="779" alt="스크린샷 2023-09-09 오전 2 28 57" src="https://github.com/KorJM/maphant-app/assets/114234223/901a88c3-40e8-480b-b2b1-e39e3bba2959">

<br>
<span>cloudpanel.io에 접속하여 Installation on Other 들어가줍니다</span>
<br><br>

<img width="779" alt="스크린샷 2023-09-09 오전 2 31 10" src="https://github.com/KorJM/maphant-app/assets/114234223/281a1621-5c58-4e3a-ade7-2a1bf3ff406b">

<br>
<span>사용하려는 Database Engine을 선택하여 코드 복사 후 붙여넣어 줍니다.</span><br><br>

<img width="779" alt="스크린샷 2023-09-09 오전 3 02 30" src="https://github.com/KorJM/maphant-app/assets/114234223/b7a16a56-01e7-4e11-9bb5-96c769f33482">

<br>

<img width="779" alt="스크린샷 2023-09-09 오전 3 03 15" src="https://github.com/KorJM/maphant-app/assets/114234223/a166e075-12aa-4065-93dd-10cd5e33610e">

<br>

<span>8443포트로 들어가서 가입 후 로그인 하시면 끝~~</span><br>

<img width="779" alt="스크린샷 2023-09-09 오전 3 06 27" src="https://github.com/KorJM/maphant-app/assets/114234223/4998f62f-f7b6-4437-8e7c-3fd66dfedf74">

<br>
