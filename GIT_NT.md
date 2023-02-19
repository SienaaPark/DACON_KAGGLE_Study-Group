`git init`: 레포를 만들고 워킹 디렉토리랑 연결시켜줄 때 최초 1회

-> 여러분들이 레포를 만들 때마다 계속 해줘야 한다.



`git status`: 워킹 디렉토리에 어떤 변화가 있는지 알아보는 명령어

- 워킹 디렉토리 단계와 스테이징 에리아 단계의 변화

`git add`+`.`: 전체 다 staging area로 올리기

`git add`+`파일명.확장자`: 이것만 올려

`git add 파일1 파일2 파일3`: 여러 파일 올려

`git add 폴더명` : 폴더로 올려

`git commit`+`-m` `"commit message"`

- 되도록 명령어로 작성
  - 동사형으로 시작하기
  - 영어로 적기



`git log --oneline`: -(하이픈) 두 개 

​	`commit`된 상황에서 어떤 메시지로 언제 뭐가 올라갔는지 알기 위한 명령어



`git config --global user.name 'user_name'`

`git config --global user.email 'user_email'`



`git remote add origin <git 주소>`: 내 워킹 디렉토리

​	-`git remote -v` : 리모트가 잘 들어갔는지 확인



`git push`+`origin main`:

`**git remote set-url origin <새로운GITURL>**`



command 창을 켜서 git을 실행시킬 때, 버릇처럼 git pull origin main해 주기.

-> 원격 레포랑 로컬 레포랑 상태가 다르면 에러가 뜨기 때문에 git pull origin main을 통해 동기화를 해 주는 것.



`git rm -rf 삭제하고 싶은 폴더나 파일 `  그리고 꼭 git push -u origin main 해주어야 함



`git branch`: 브랜치의 종류, 어느 브랜치인지 확인하기

`git branch <브랜치>`: 브랜치 생성

- `git branch haley`

`git checkout <브랜치명>`: 브랜치 이동

- 없는 브랜치 명을 작성했을 땐 에러 발생