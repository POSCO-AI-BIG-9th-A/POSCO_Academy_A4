[완전 초보를 위한 깃허브]

깃이란 프로젝트의 어떤 부분도 겹쳐쓰지 않게 프로젝트의 변경을 관리하는 버전관리 소프트웨어이다.
깃은 서로 다른 동료가 같은 페이지를 각각 수정하고, 변경사항들을 병합할 수 있다. 

기본 용어
command line : 깃 명령어를 입력할 때 사용하는 컴퓨터 프로그램
repository : 프로젝트가 거주할 수 있는 디렉토리나 저장 공간
version control : 깃이 서비스되도록 고안된 목적. 깃을 사용하면 프로젝트 히스토리의 모든 시점의 ‘스냅샷’을 유지하므로, 잃어버리거나 겹쳐쓰지 않을 수 있다.
Commit : 깃에게 파워를 주는 명령. commit하면 체크 포인트를 가지게 된다.
Branch : 여러 명이 하나의 프로젝트에서 작업할 때 메인을 branch off하여 자신의 버전을 만들어 변경한 후, 작업 종료후에 다시 병합한다.

주요 명령어
git init : 깃 저장소 초기화
git config : 처음 깃을 설정할때 유용
git help : 특정 깃 명령어를 사용하고 설정하는 범 알려줌
git status : 저장소 상태 체크
*git add : 깃이 새 화일들을 지켜봄. 화일 추가시, 깃의 저장소 ‘스냅샷’에 포함
git commit : 변경사항을 만든 후, 저장소의 ‘스냅샷’을 찍기 위해 명령어 입력
git branch : 자신만의 변경사항과 화일 추가 등의 커밋 타임라인을 만든다.
Git checkout : 현재 위치하고 있지 않은 저장소를 체크아웃한다.
Git merge : 브랜치에서 작업을 끝내고 모든 협업자가 볼 수 있도록 병합한다.
Git push : 로컬 컴퓨터에서 작업하고, 나의 커밋을 깃허브에서 온라인으로도 볼 수 있게 한다.
Git pull : 로컬 컴퓨터에서 작업할 때, 작업하고 있는 저장소의 최신 버전을 원하면 변경사항을 다운로드한다.



