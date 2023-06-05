# VS code에서 GitHub 연동 및 명령어 순서
1. git init
2. git remote add origin {내 Repositories 의 HTTPS 복사}
3. git remote -v
4. git pull origin main
5. git pull origin main --allow-unrelated-histories
6. git branch -M main
7. git add .

**여기는 VS code에서 commit 하는 방법대로 해도 된다**
1. git commit - 왼쪽 상단에 commit message 입력
2. message 입력이 끝났으면 ESC 입력 후 왼쪽 하단에 :wq 입력 후 ENTER
3. git push -u origin main