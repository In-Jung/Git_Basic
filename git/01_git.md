# Git 명령어

* `git status` : git으로 관리되고 있는 폴더 상태(==Repository, 저장소)

* `git init` : git 현재 폴더 초기 설정 

* `git add` : git으로 관리할 파일 추가

  * `git add a.txt` : `a.txt` 파일/파일을 INDEX에 등록
  * `git add .` : 현재 폴더의 모든 내부 파일을 등록

* `git commit` : INDEX에 있는 파일을 기록으로 남김

  * `git commit -m '메세지'` : 기록을 남기면서, 메세지를 남김(필수)

* `git log` : 남겨온 commit을 확인

  * `git log --online --graph` : 그래프 + 한줄로 기록을 조회

* `git config` : git 프로그램 설정 담당

  ```git config --global user.emil""```

  * `git config --global --list` : 현재 git 프로그램에 설정된 값들을 확인 

