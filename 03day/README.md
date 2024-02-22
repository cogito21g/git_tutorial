# Day03> 저장소 업로드 및 가져오기

### 저장소 업로드

1. Staging Area 등록
```bash
git add <file>
```

2. 파일 상태 확임
```bash
git status
```

3. Local Repository 등록
- git commit message에 따라 메시지 등록하기
```bash
git commit
vi 편집기로 메시지 편집
```

4. commit 상태 확인하기
```bash
git log
```

5. Remote Repository 업로드
- -u 옵션: 처음 업로드시 사용(= --set-upstream과 동일)
```bash
git push origin main
git push --set-upstream <branch> <remote branch>
```

### 저장소 가져오기

#### Clone
1. Remote Repository에서 가져오면서 새로운 directory 생성
- local history 유지하지 않음.
```bash
git clone <github url> <dir_name>
```

#### Pull
1. Remote Repository에서 가져오면서 기존 history 유지
```bash
git pull <remote branch> <local branch>
```

#### Fetch
1. Remote Repository에서 변경 사항 가져오기
```bash
git fetch <remote branch>
```

2. 브랜치 병합하기
```bash
git checkout <branch>
git merge <branch>
```