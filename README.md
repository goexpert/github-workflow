# github-workflow

포크 브랜치 저장소를 원본 저장소와 싱크 및 pull request 가능 상태로 만들기<br>

원본 master는 배포 가능 상태로 유지<br>
원본 development 브랜치 생성<br>
원본 development 브랜치를 fork<br>

fork된 자신의 원격 저장소에서 로컬 저장소로 클론<br>
remote 에 upstream(원본 development 등록)<br>
원격 저장소 추가 명령어 : git remote add upstream 주소 - 소스트리 왼쪽 트리메뉴 remote에 추가<br>
원격 저장소 확인 명령어 : git remote -v<br>

원본 원격 저장소의 데이터를 정기적으로 받아서 충돌이 너무 많지 않게 유지.<br>
pull request 를 해야 하거나 나의 원격 저장소를 upstream 과 동기화 하고 싶을 때 사용<br>
원격 저장소 받아오기 : git pull upstream development - 소스트리 왼쪽 트리메뉴 remote에 pull 이용<br>

merge 작업 진행 후 커밋<br>

git push origin master(fork해서 기본 브랜치인 경우 master)<br>

pull request 가 필요하다면 작성<br>
