# 20230307
<!-- md 문서 작성 -->
<!-- # : 제목을 작성해주고 -->
## 20230307
### 20230307
#### 20230307

<!-- - : 리스트 형태 작성 -->
# git 프로젝트

- git은 뭐냐?
1. 형상 관리 도구 중 하나
형산관리 도구 : 버전 관지 시스템
작업하면서 작업의 리스트를 관리 할수 있다.

- git의 장점
- 협업하는 단계에서 소스 코드를 파일로 주고 받을 필요가 없이
같은 파일을 팀원과 병렬로 작업이 가능하다.

- 눈으로 보고 찾는것보다 효율이 좋고 작업이 편하다.

- 코드의 다른 부분을 바로 찾을 수 있다.


- git 설치

- git 사용자 설정

- git config --global user.name "byungjoo0806"
- git config --global user.email "andybyungjoopark@gmail.com

-설정 정보 조회
- git config --global --list

- 경로 지정
- cd .. : 한 폴더 뒤로 이동
- ls -a : 경로의 파일을 전부 보고싶으면
- cd 폴더명 : 해당 폴더로 경로 이동
- cd 앞부분 폴더명 쓰고 기억이 안나면 tab 버트 눌러서 비슷한 폴더명 확인 가능

- git 저장소 초기화 저장소를 생성하는 명령어
- 해당 프로젝트 경로에서
- git init

- 저장소와 파일의 내용이 다를떄 컬러로 표현 해준다
- git 저장소 파일 스테이징
- 업로드 전 준비 업로드할 파일들

- git add 해당 파일 이름
- git add . : 모든 파일 스테이징

- 커밋 메시지 작성
- git commit -m "메세지 내용"

- 파일들을 업로드할 준비가 끝났다.
- git remote add origin "연결할 원격 저장소 주소"

- 원격저장소에 업로드
- git push

- git을 관리하면서 자리 이동 했을때 커밋을 올렸는데 사용자명이 다를 경우:
- 제어판 -> 사용자 계정 -> 자격증명관리자 -> 

- 협업을 할때는 git push 부터 날리면 안되고
- pull/push : 먼저 작업물을 병합하고 작업물을 올리자.

- A와 B가 있으면 A가 먼저 push, B가 계속 작업을 하다가
- A의 작업물을 병합하지 않고 push를 하게되면 A의 작업물이 다 날아간다

- .git 파일을 잘못 만들었을때
- rm -rf : 폴더 삭제( (ex) rm - rf .git/ )

- 새로운 환경에서 git 저장소 연결을 할때 따라하세요
- git init
- git remote add origin "저장소의 주소"
- 저장소의 주소는 해당 깃허브의 저장소에 접속해서 code(초록색버튼)을 누르면 볼수있다.

- git pull origin master : 원격저장소에서 파일을 받아온다.
