# kakaopc_clone
1.git사용방법

- git 세팅

- 유저 이름 / 이메일 세팅
git config --global user.name "닉네임"
git config --global user.email "이메일"

- 유저 이름 / 이메일 정상적으로 세팅 확인
git config --list

- 현재 작업중인 폴더에 git 세팅
git init (*한 번만 입력해주시면 된다)

- 현재 root폴더와 git hub repository를 연결
git remote add origin https://github.com/내 주소

- 현재 root폴더와 git hub repository 정상연결 확인
git remote -v
> fetch / push

현재 root폴더안에 있는 데이터 중에서 아직 git이라는 임시저장공간에 담아놓지 않은 데이터를 확인
git status

- root폴더 임시저장 폴더 (*.git)에 전송할 데이터 담기
git add *

- git hub에 데이터를 보낼 때, 어떠한 메세지로 기록해서 보낼 것인지 결정
git commit -m "firstcommit"

- git hub에 최종적으로 데이터를 전송하는 방법
git push origin master
