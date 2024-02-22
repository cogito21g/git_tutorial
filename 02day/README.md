# Day02> Git 버전관리

### 상태 관리(이전으로 돌리기)

1. 커밋 이후 변경 이력 및 파일 모두 삭제
```bash
git reset --hard <commit hash>
```

1. 커밋 변경 이력은 삭제하지만 파일은 남겨둠.
- working directory 상태
```bash
git reset --mixed <commit hash>
```

1. 변경 이력은 삭제하지만 변경 내용은 남겨둠.
- staging area에 있는 상태
```bash
git reset --soft <commit hash>
```

1. 해당 커밋만 삭제하고 삭제 내역을 추가 기록
```bash
git revert <commit hash>
```

### 브랜치 나누어 관리
- [버전관리 전략](https://hudi.blog/git-branch-strategy/)

1. 브랜치 생성 및 삭제
```bash
git branch <branch_name>
git branch -D <branch_name>
```

2. 현재 브랜치 확인 및 브랜치 목록
```bash
git branch
```

3. 브랜치 변경
```bash
git checkout <branch>
git switch <branch_name>
```

4. 브랜치 병합
- 현재 브랜치로 다른 브랜치를 가져옴.
```bash
git checkout <병합 기준 branch>
git merge <병합될 branch>
```