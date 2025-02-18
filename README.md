# Lab9
- git checkout -b develop
- git checkout -b feature/fetch-users
- git add script.js index.html
- git add index.html
- git commit -m "โหลดรายชื่อผู้ใช้"
- git checkout develop
- git merge feature/fetch-users
- git branch -d feature/fetch-users
- git checkout -b feature/user-detail
- git add user-detail.js 
- git add user-detail.html
- git commit -m "รายละเอียดผู้ใช้"
- git checkout develop
- git merge feature/user-detail
- git branch -d feature/user-detail
- git checkout -b feature/user-post
- git add user-post.js
- git add user-post.html
- git commit -m "โพสต์ของผู้ใช้"
- git checkout develop
- git merge feature/user-post
- git branch -d feature/user-post
- git caheckout -b feature/ui-update
- git add style.css
- git commit -m "ตกแต่ง UI"
- git checkout develop
- git merge feature/ui-update
- git branch -d feature/ui-update
- git checkout main
- git merge develop
- git add user-detail.js user-detail.html
- git commit -m "แก้ไขโพสต์ของผู้ใช้"
- git add README.md
- git commit -m "Git Commands"
- git push -u origin main
- git push origin develop