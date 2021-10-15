# helloGit
Git study project

## git config
```
### git config global 조회
cat ~/.gitconfig

### git config 조회
git config --list
cat .git/config

### 사용자 등록
--global 추가 시 전체
git config user.name <github-name>

### 사용자 이메일 등록
--global 추가 시 전체
git config user.email <email>

alias ll='ls -al'
```

## git 초기 설정
```
### local repository 생성
git init

### 파일 추가 
git add --all           # 파일 전체 추가
git add .               # 파일 전체 추가
git add <file-name>     # 특정 파일 추가

### local repository 수정 및 업로드 시
git commit -am <commit-message>

### remote repository 정리
git remote add origin <git-remote-url>

git push -u origin <branch-name>
git push -fu origin <branch-name>

### 로그 확인
git log

### staging 상태 확인
git status 

### 서버의 최신 소스를 다운받기
git pull

### 서버와 연결된 repo 해지
git remote rm origin

```

## git cmd
```
## git log 확인
git log --graph --oneline

## 해당 시점으로 돌아감, 그 사이 로그 삭제
- 기본은 소스는 변경되지 않음
- 최대한 쓰지 말 것
git reset --hard
git reset --soft
git reset --mixed

## 해당 시점으로 돌아감, 그 사이 로그 존재
git resert

1111111111111111111111111111

22222222222222222222222222222

3333333333333333333333333333
```