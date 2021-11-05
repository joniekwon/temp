practice git and github.

관리할 폴더 우클릭 - Git Bash Here 
git init 명령 입력하여 깃 지역 저장소로 지정 (취소: .git 삭제ㅋㅋ rm -rf .git)
git config 명령어를 이용해 깃 지역 저장소에 사용자 등록
git config user.name "username"
git config user.email "useremail@email.com"


.git/config 파일에서 설정파일 확인
repositoryformatversion : 레포지토리 형식 및 버전 식별을 위한 내부 변수
filemode : true or false 파일 변경 감지 여부 설정 (윈도우, 리눅스 동시 작업할경우 변경 안해도 변경됐다고 표시될 수 있음)
bare : 코드 변경 작업 용도가 아닌 복사, 저장 용이면 true로 설정
logallrefupdates : 깃 명령어 수행 로그 기록 활성화 git reflog 명령어로 기록된 작업 내역 확인
ignorecase : 대소문자 구분여부 설정 true- 구분하지 않음
precomposeunicode : 맥OS에서 한글파일명 인식문제 true로 설정하면 해결됨


git add를 이용하여 커밋에 포함될 파일 등록
git add README.md

git commit 명령어로 새로운 커밋 생성
git commit -m "저장소 설명"
-m : 커밋 메시지를 작성하는 기능

git log를 이용해서 커밋 확인


리모트 저장소 등록
git remote add origin 리모트저장소주소
*origin은 리모트저장소 이름 정한것

로컬 저장소에서 생성한 커밋을 리모트저장소에 등록
git push origin main 
*main은 리모트저장소의 브랜치 이름 정한것

