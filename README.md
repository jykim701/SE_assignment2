# SoftEngineering assignment#2
## github addr :

## add
> 파일을 staging area로 옮기는 것<br>
> $ git add<파일> : 새로운 파일을 추가하거나 존재하는 파일의 변경사항을 포함<Br>
> $ git add -A : 커밋에 파일의 변경 사항 한번에 모두 포함

<br>

## branch
> $ git branch : 브랜치 목록<br>
> $ git branch <브랜치 이름> : 새 브랜치 생성<br>
> $ git branch -r : 원격 브랜치 목록 보기<br>
> $ git branch -a : 지역과 원격 포함 모든 브랜치 목록 보기<br>
> $ git branch <새로운 브랜치><브랜치 생성 위치> : 다른 시작 지점에서 브랜치 생성하기
> $ git branch -d <브랜치 이름> : 브랜치 삭제

<br>

## checkout
> 로컬의 변경 사항을 변경 전으로 되돌리는 기능<br>
> $ git checkout <브랜치> : 다른 브랜치 체크아웃하기<br>
> $ git checkout -b <새로운 브랜치> : 현재 브랜치에서 새로운 브랜치 생성하고 체크아웃하기(생성&이동)<br>
> $ git checkout master : master branch로 되돌아 옴

<br>

## clone
> 그대로 복사하는 명령어<br>
> $ git clone <경로> : 해당 경로의 것을 복사

<br>

## commit
> staging area에서 local repository로 최종적으로 저장하는 것<br>
> $ git commit

<br>

## config
> configuration
> $ git config --global user.name "Your name" <br>
> $ git config --global user.email "Your email addr"<br>
> $ git config --list : 저장소별 설정 정보 조회

<br>

## init
> initialize. git을 시작할 때 쓰는 명령어<br>
> $ git

<br>

## log
> commit 내역을 확인하기 위해 사용<br>
> $ git log<br>
> $ git log -p : 변경 사항을 보여주는 패치와 함꼐 로그 표시<br>
> $ git log <시작>...<끝> : 시작 지점이나 끝 지점을 설정하여 두 지점 사이의 커밋 로그 보기

<br>

## merge
> $ git merge <브랜치> : 다른 브랜치를 현재 브랜치로 합치기<br>
> $ git merge --no-commit <브랜치> : 커밋하지 않고 합치기

<br>

## pull
> 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기<br>
> $ git pull

<br>

## push
> 원격 저장소로 저장하는 일<br>
> $ git push origin <브랜치 이름> : 만든 브랜치를 원격 서버에 전송<br>
> $ git push -u remote <브랜치 이름> : 새 브랜치를 원격 저장소로 push

<br>

## rebase
> 하나의 브랜치에서 진행돈 소스와 다른 브랜치에서 진행된 소스를 합치면서 merge와 다르게 히스토리를 일렬로 합칠 때

<br>

## remote
> 원격 저장소의 주소가 제대로 설정되어 있는지 확인하기 위함<br>
> $ git remote -v : 원격 저장소 확인하기<br>
> $ git remote add origin <github repo addr> : 원격 저장소와 등록해주기 위함

<br>

## reset--hard
> commit을 취소하는 상태<br>
> git에서 이력을 되돌리고 이후 모든 내용을 지운다

<br>

## status
> git이 현재 변통된 파일들 중 어떤 파일을 추적하고 있는지 아닌지 확인 (상태 확인)<br>
> $ git status

<br>

## tag
> 소스 코드의 버전 관리를 위해 커멋 중 어떤 특정 커밋을 가리키고 싶을 때 사용