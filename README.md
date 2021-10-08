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
git add --all        # 파일 전체 추가
git add .            # 파일 전체 추가
git add <file명>     # 특정 파일 추가

### local repository 저장
git commit -am "first commit message"



7. git remote add origin <git-remote-url>
8. git push -u origin master
git push -fu origin master
9. git log
10. git status # staging 상태 확인
```