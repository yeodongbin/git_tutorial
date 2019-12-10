# git_tutorial<br>
git config --global user.name "이름"<br>
git config --global user.email "깃허브 메일주소" // 매번 물어보는 귀찮음을 피하기 위해 설정.<br>
<br>
mkdir ~/MyProject   // 로컬 디렉토리 만들고<br>
cd ~/myproject      // 디렉토리로 들어가서<br>
git init            // 깃 명령어를 사용할 수 있는 디렉토리로 만든다.<br>
git status          // 현재 상태를 훑어보고<br>
git add 화일명.확장자  // 깃 주목 리스트에 화일을 추가하고 or<br>
git add .           // 이 명령은 현재 디렉토리의 모든 화일을 추가할 수 있다.<br>
git commit -m “현재형으로 설명” // 커밋해서 스냅샷을 찍는다.<br>
<br>
git remote add origin https://github.com/username/myproject.git // 로컬과 원격 저장소를 연결한다.<br>
git remote -v // 연결상태를 확인한다.<br>
git push origin master // 깃허브로 푸시한다.<br>
