# Day01> Git 원격 저장소 생성 및 동기화

1. Local에 Directory 생성
```bash
mkdir my_folder
```

2. 생성된 Directory로 이동
```bash
cd my_folder
```

3. git repository로 초기화(.git 생성)
```bash
git init
```

4. GitHub(Remote) Repository 주소 등록
```bash
git remote add origin <github url>
```

5. README.md 생성
```bash
echo "# My Folder" >> README.md
```

6. Working Directory에서 Staging Area로 등록
- 되돌리기: git rm -r --cached <file>
```bash
git add README.md
```

7. 파일 상태 확인하기
- Untracked, Unmodified, Modified, Staged
```bash
git status
```

8. Staging Area에서 Local Repository로 등록
- -m 옵션: 한줄 등록
```bash
git commit -m "first commit"
```

9. commit 상태 확인하기
```bash
git log
```

10. Remote Repository에 업로드
```bash
git push origin main
```