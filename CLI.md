# CLI(command line interface) bash 쓰는법

## ls(list의 약자)

- '-' 은 앞에 목록 형태를 나타 낼 수 있다. 하이폰
- ls명령어는 현재 작업중인 위치에 존재하는 파일 혹은 폴더 목록을 보여준다
- `백틱 3개는 코드 블락을 생성 할 수 있다. 밑에께 코드블락임↓

```bash
user@DESKTOP-9V8KBU1 MINGW64 ~/Desktop/github_study
$ ls
test_folder/  text.txt
```





## cd(change directory)

- 현재 작업중인 디렉토리(a.k.a.폴더)를 변경하겠다

  ```bash
  user@DESKTOP-9V8KBU1 MINGW64 ~/Desktop/github_study
  $ cd {directory name저장공간 이름}/
  $ cd ..(보통 경로를 나타낼 때 상위폴더는 ..) # 내 상위 폴더로 이동
  ```

  

  

## pwd(print working directory)





## mkdir (make directory)

- 디렉토리/폴더를 생성한다.

  ```bash
  user@DESKTOP-9V8KBU1 MINGW64 ~/desktop/github_study
  $ mkdir {directory name}
  ```



## touch

- 파일을 생성한다.

  ```bash
  user@DESKTOP-9V8KBU1 MINGW64 ~/desktop/github_study
  $ touch {file name}.{확장자}
  ```

  

- cli 커맨드들 cli명령어들을 검색하면 더 나옴 
- 작업하는 위치가 중요한 터미널 창이기 때문에 자기가 작업하고 있는 공간을 잘 확인해야 함