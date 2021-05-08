# SoftEngineering assignment#2
## github addr : https://github.com/jykim701/SE_assignment2

## 실습 내용
1. config를 통해 내가 사용자임을 알려준다
2. git을 시작하고 기존에 로컬 영역에 있던 내용들을 add 해주며 이를 status로 확인한다. commit과 push를 통해 내용을 github에 올려준다.
3. git status를 이용하여 이를 확인한다.
4. 파일에 수정을 조금 하고 commit을 다시 해본다.
5. remote와 push도 commit과 함께 동반된다.
6. git log를 통해 내 기록을 살핀다.
7. 해당 레포지토리에 있는 데이터를 수정하였고, 이를 github에 반영한다.
8. 해당 commit에 대한 reset을 명령한다. commit을 취소하고자 한다.
9. log를 통해 올바르게 작업되고 있는지 한번 더 확인한다.
10. test1이라는 브랜치를 생성했고 만든 이후 이 브랜치 체크아웃을 진행하였다. 동일하게 merge도 진행되었으나 이미 합치지 않아도 되는 상태이다.
11. remote -v를 활용하여 원격 저장소를 찾아보았고, 옳은 위치에 있음을 확인하였다.
12. git clone을 활용하여 해당 깃을 복제해보았고, 그로 인해 해당 디렉토리가 더 생기게 되었다. 
13. git pull을 해보았으나 수정 사항이나 pull을 할 데이터가 없어 no tracking information for the current branch라는 문구가 뜬다.
14. log를 사용하여 tag를 확인하고 tag 명령어를 사용해보기도 했다.
15. rebase를 위해 reb.txt를 vi 에디터로 생성해주고 각 브랜치에 대한 rebase를 진행해주었으나이미 각 브랜치가 해당 작업이 완료된 상태임을 알 수 있다.


## add
![image](https://user-images.githubusercontent.com/58364280/117539611-70b45d80-b046-11eb-9afd-3afe30588c3e.png)
> 파일을 staging area로 옮기는 것<br>
> $ git add<파일> : 새로운 파일을 추가하거나 존재하는 파일의 변경사항을 포함<Br>
> $ git add -A : 커밋에 파일의 변경 사항 한번에 모두 포함

<br>

## branch
![image](https://user-images.githubusercontent.com/58364280/117539695-be30ca80-b046-11eb-8e7f-29689323c179.png)
![image](https://user-images.githubusercontent.com/58364280/117539726-e8828800-b046-11eb-96ce-733a9ec641a8.png)
> $ git branch : 브랜치 목록<br>
> $ git branch <브랜치 이름> : 새 브랜치 생성<br>
> $ git branch -r : 원격 브랜치 목록 보기<br>
> $ git branch -a : 지역과 원격 포함 모든 브랜치 목록 보기<br>
> $ git branch <새로운 브랜치><브랜치 생성 위치> : 다른 시작 지점에서 브랜치 생성하기
> $ git branch -d <브랜치 이름> : 브랜치 삭제

<br>

## checkout
![image](https://user-images.githubusercontent.com/58364280/117539703-c5f06f00-b046-11eb-994b-d1652bfd8b8f.png)
> 로컬의 변경 사항을 변경 전으로 되돌리는 기능<br>
> $ git checkout <브랜치> : 다른 브랜치 체크아웃하기<br>
> $ git checkout -b <새로운 브랜치> : 현재 브랜치에서 새로운 브랜치 생성하고 체크아웃하기(생성&이동)<br>
> $ git checkout master : master branch로 되돌아 옴

<br>

## clone
![image](https://user-images.githubusercontent.com/58364280/117539747-fd5f1b80-b046-11eb-947c-7e1c2b2227f1.png)
> 그대로 복사하는 명령어<br>
> $ git clone <경로> : 해당 경로의 것을 복사

<br>

## commit
![image](https://user-images.githubusercontent.com/58364280/117539647-8d509580-b046-11eb-8ff9-95a806a54320.png)
> staging area에서 local repository로 최종적으로 저장하는 것<br>
> $ git commit

<br>

## config
![image](https://user-images.githubusercontent.com/58364280/117539587-50849e80-b046-11eb-8b85-6b8462eb58a5.png)
> configuration
> $ git config --global user.name "Your name" <br>
> $ git config --global user.email "Your email addr"<br>
> $ git config --list : 저장소별 설정 정보 조회

<br>

## init
![image](https://user-images.githubusercontent.com/58364280/117539605-61cdab00-b046-11eb-892c-f6da81a6d3d3.png)
> initialize. git을 시작할 때 쓰는 명령어<br>
> $ git

<br>

## log
![image](https://user-images.githubusercontent.com/58364280/117539682-af4a1800-b046-11eb-9a15-3a97d8657df8.png)
> commit 내역을 확인하기 위해 사용<br>
> $ git log<br>
> $ git log -p : 변경 사항을 보여주는 패치와 함꼐 로그 표시<br>
> $ git log <시작>...<끝> : 시작 지점이나 끝 지점을 설정하여 두 지점 사이의 커밋 로그 보기

<br>

## merge
![image](https://user-images.githubusercontent.com/58364280/117539710-cf79d700-b046-11eb-9815-afa03bbcc84a.png)
> $ git merge <브랜치> : 다른 브랜치를 현재 브랜치로 합치기<br>
> $ git merge --no-commit <브랜치> : 커밋하지 않고 합치기

<br>

## pull
![image](https://user-images.githubusercontent.com/58364280/117539798-313a4100-b047-11eb-8198-e7bb25eb8236.png)
> 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기<br>
> $ git pull

<br>

## push
![image](https://user-images.githubusercontent.com/58364280/117539667-a2c5bf80-b046-11eb-9797-62866593ecbe.png)
> 원격 저장소로 저장하는 일<br>
> $ git push origin <브랜치 이름> : 만든 브랜치를 원격 서버에 전송<br>
> $ git push -u remote <브랜치 이름> : 새 브랜치를 원격 저장소로 push

<br>

## rebase
![image](https://user-images.githubusercontent.com/58364280/117539788-1bc51700-b047-11eb-9c52-5b92b088a616.png)
> 하나의 브랜치에서 진행돈 소스와 다른 브랜치에서 진행된 소스를 합치면서 merge와 다르게 히스토리를 일렬로 합칠 때

<br>

## remote
![image](https://user-images.githubusercontent.com/58364280/117539657-98a3c100-b046-11eb-8b95-63809822efed.png)
> 원격 저장소의 주소가 제대로 설정되어 있는지 확인하기 위함<br>
> $ git remote -v : 원격 저장소 확인하기<br>
> $ git remote add origin <github repo addr> : 원격 저장소와 등록해주기 위함

<br>

## reset--hard
![image](https://user-images.githubusercontent.com/58364280/117539845-621a7600-b047-11eb-8ac5-8497a8d5e30c.png)
> commit을 취소하는 상태<br>
> git에서 이력을 되돌리고 이후 모든 내용을 지운다

<br>

## status
![image](https://user-images.githubusercontent.com/58364280/117539637-80cc3d00-b046-11eb-8df6-b4e3b4ea87a3.png)
> git이 현재 변통된 파일들 중 어떤 파일을 추적하고 있는지 아닌지 확인 (상태 확인)<br>
> $ git status

<br>

## tag
![image](https://user-images.githubusercontent.com/58364280/117539760-0b14a100-b047-11eb-814a-b67955a14f75.png)
> 소스 코드의 버전 관리를 위해 커멋 중 어떤 특정 커밋을 가리키고 싶을 때 사용
