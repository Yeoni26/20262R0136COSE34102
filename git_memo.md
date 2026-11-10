# git 기본 명령어 정리

## 1. Repository
- GitHub Repository를 로컬로 복사  
`git clone [repository URL]`

- 현재 폴더의 Git 상태 확인  
`git status`

## 2. Commit
- 변경된 파일 추가  
`git add .`

- 특정 파일만 추가  
`git add [filename]`

- 변경사항 기록  
`git commit -m "commit message"`

## 3. Push & Pull
- GitHub 에 업로드  
`git push`

- GitHub 변경사항 가져오기  
`git pull`

- 처음 push 할 때 원격 브랜치 연결  
`git push -u origin main`

## 4. Branch
- 브랜치 확인  
`git branch`

- 새 브랜치 생성  
`git branch branch-name`

- 브랜치 이동  
`git switch branch-name`

- 브랜치 생성 및 이동  
`git switch -c branch-name`


## 5. Log
- 로그 확인  
`git log`

- 현재 변경사항 확인  
`git diff`

