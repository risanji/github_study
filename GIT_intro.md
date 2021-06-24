## GIT 초기 설정 (컴퓨터를 바꿀 때 마다 설정)

커밋 작성자 설정

```bash
# 명령을 시키고자 하는 주체
# git아, 전역 설정 중, 유저의 email을 설정 할거야. 
$ git config --global user.email wlfltks6037@gmail.com
# git아, 전역 설정 중, 유저의 name을 설정 할거야.
$ git config --global user.name risanji
```



- 커밋을 작성하는 사람이 누구인지 알아야하기 때문에 설정



지정된 설정 확인

```bash
# git아 현재 전역에 설정된 설정 목록 보여줘
$ git config --global -l
# $ git config --global --list 도 가능
```



# Git Basic

## 로컬 저장소 설정(폴더를 바꿀 때 마다 설정)

```bash
$ git init 
```

- 폴더에 git 저장소를 초기화하면,
  - .git이라는 숨김 폴더가 생기고 
  - bash에는 (master)라는 표기가 생성된다.

- 주의사항
  - .git 폴더를 직접적으로 수정하는 일은 없을 것이다.
  - 이미 git으로 관리하고 있는 (bash 창에 master가 표기 되어 있는 폴더 내에서는 절대 git init 하지 말 것!!)



## status

```bash
# git아 너가 관리 중인 폴더의 상태 보여줘
# git status 
```





## add

```bash
$ git add 파일명(하나하나 적기)
$ git add . # 현재 디렉토리(현재 폴더에 있는 모든 변동사항 저장 가능)
$ git add a.txt # 특정 파일
$ git add directory_name/ # 특정 폴더가 가진 모든 파일 
```

- working directory 상태의 파일을 staging area 상태로 변경
- 커밋을 위한 파일 및 폴더들을 추가하는 명령어





## commit

```bash
# git아, commit 할건데 -메세지는 "이걸로 해줘"
$ git commit -m "commit message"
# git commit -m "210624created CLI.md"
```

- 지금 파일이 저장된 걸 사진을 찍어둬서 정보를 저장할건데 어떤 수정 사항들 어떤 행위들을 했는지 메세지를 같이 저장해줘 

- 커밋을 통해 하나의 버전으로 기록 됌
- 커밋 메세지는 현재 변경사항들을 잘 나타낼 수 있도록 작성하는 것을 권장합니다 

- 커밋 목록은 git log를 통해서 확인 할 수 있음

```bash
$ git log --oneline
```





- ctrl+c는 모든 작업을 취소하는 것

