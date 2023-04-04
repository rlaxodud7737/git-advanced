# 깃 고급 특강

## 브랜치

### 정의
- 영어사전: 가지
- git에서의 정의 : A branch in Git is simply a lightweight movble pointer to one of these commits.
- 실무에서 : 새로운 작업(기냉 개발, 버그 수정 등)을 시작할때 만든다.

### 명령어
1. 브랜치 생성 : 'git branch 브랜치이름'
2. 생성되어있는 브랜치보기
  -'git branch' or 'git branch -r'
3. 다른 브랜치로 전환하기
  -'git checkout 브랜치명'
  -'git switch 브랜치명'
4. 브랜치 만들고, 전환까지 동시에 하기
  -'git checkout -b 브랜치명'


  ## 로컬 저장소와 원격 저장소 동기화하기

  ### PUSH
   - git push 명령어를 사용하면 로컬 저장소의 브랜치에 있는 커밋들을 원격 저장소에 특정 브랜치로 push해서 동기화 할 수 있다.