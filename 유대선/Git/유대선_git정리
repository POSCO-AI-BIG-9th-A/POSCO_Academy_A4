[git init]
-> $git init : 현재 디렉토리에서 작업을 진행하겠다고 git에 알려줌  
-> $ls -al -> .git 이 생긴게 보임 -> 버전관리 시 생성정보들이 저장됨  
  #



$ls -al -> .git 이 생긴게 보임 -> 버전관리 시 생성정보들이 저장됨  
#




[git status] -> $git status -> untracked files : f1.txt 보임 
             -> git이 f1.txt를 무시 (명령전까지 관리하지 않음)
             -> 버전관리에 적용되지 않는 파일  
  #
  
  
  
     
[git config] ->$git config --global user.name 사용자 이름
             ->$git config --global user.email 이메일 
             -> 누가 버전을 수정했는지 명시하는 것  
  #
 
 
 
 

[git add] ->$git add 파일 -> git add f1.txt -> f1.txt를 git이 인식하여 새로운 파일로써 인식함
          -> git이 이 파일을 추적하도록 명령하는 것 
          -> 버전관리에 핵심적인 파일만 관리하기 위해 git에게 명확하게 어떤것을 추적할지 알려주는것  
  #




 

[git commit] ->$git commit -m "메모"
             -> 추적중인 파일을 커밋함
  
git log -> 해당 버전 작성한 사람 날짜 메모 등등 볼 수 있음

git commit 후 git log 보면 수정 내역 나옴  
#







[스스로 해보기]
git commit --help

git commit -al :수정한것 전부 커밋(add 생략가능
git commit -m "메세지" : 커밋 메세지 즉시 작성  
#


[원격 저장소에 연결 및 파일 올리기]
git remote add origin 깃허브주소
-> 현재 로컬저장소를 (git) 원격저장소에 연결시킨다 (remote) 그리고 그 원격저장소의 주소는 origin이라는 별명을 가진 ~주소의 저장소이다 이다

git remote -v 입력하여 연결된 세부 원격저장소 주소 볼 수 있음
git remote add friend(설정가능한 이름임) 주소 -> 해당 로컬저장소에 연결된 원격 저장소 추가도
가능함 -> 즉 여러 원격저장소에 연결 가능
git remove --help
git remote --help 쳐보면 도움말 나옴

git remote remove 원격저장소명 : 해당 저장소 연결 삭제

git push origin master : origin이라는 이름을 가진 원격저장소의 master 브랜치에 내 pc의 로컬저장소에 저장된 파일들을 원격으로 보내겠다  
#


[오류 해결]
-> git push 시 

C:\Users\gitProject>git push origin master
To https://github.com/userId/userProject.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/userId/userProject.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

다음과 같은 오류가 발생 가능

[1차 해결법] -> git pull을 통한 병합 후 git push origin 브런치명 명령어 재실행

[2차 해결법] -> 실패 시 git pull origin 브런치명(master) --allow-unrelated-histories 




