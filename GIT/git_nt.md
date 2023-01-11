# GIT



- `git init` : git 시작하기, 이 특정 폴더를 git으로 관리할거야!

- `git status` : git 으로 관리되고 있는 폴더의 현황 조회

- `git add` : git 에게 tracking을 요청
  - staging area 에 올려줘!
    1. `git add [파일이름.확장자]`
    2. `git add [파일이름1.확장자] [파일이름2.확장자]`
       - ​	띄어쓰기가 포함된 파일입니다! -> `'` / `"` 감싸준다.
    3. `git add .` : 전체를 다 올려줘

- `git commit -m [커밋 메시지]` : 
  - staging area에 올린 컨텐츠에 커밋 메시지 남기기
  - 커밋 메시지
    - 명령조로 작성한다.