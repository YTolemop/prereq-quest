# YTolemop

<!-- Public fork: use only your GitHub username. Do not add a student ID,
Discord name, legal name, email address, or other private identifier. -->

## Environment

OS: Windows

Editor / IDE: VS Code, Code::Blocks

Shell: Git Bash, PowerShell, CMD

Languages I have used: C++, Python

## Things I have done before

- [x] SSH into another machine
- [ ] Resolve a Git merge conflict
- [x] Build a Docker image
- [x] Read a stack trace
- [x] Compile software from source
- [x] Use a debugger
- [ ] Use Linux as a primary development environment
- [ ] `sudo rm -rf /` a server ???!
- [x] 辦理校內 CTF 競賽、辦理校內 Vibe Coding 營隊、辦理校內暑期APCS與選手培訓營隊

## Something I built

- 參與飲仕 insir 飲料店 LINE Bot 集點系統開發，主要擔任後端工程師，負責集點功能、前後端 API 串接與資安審查；系統規劃採用 Django 開發後端、PostgreSQL 儲存會員與點數資料，並搭配 LINE LIFF 與網頁管理介面。
- 參與程式煉鋒吧 - Forge In Coding 開發，主要負責撰寫自動解題外掛，呼叫 Azure 上部署的語言模型 API，進行題目擷取、解答生成、程式提交與判題結果分析，用以維護題庫。

## Something I want to understand better

想學更多有關 Linux 的東西，還有有關物件導向的知識。（如果教怎麼攻擊學校伺服器也不錯？）

## Mission 01 — Linux

### Task A — find the file

Path: missions/01-linux/files/.config/nested/.deep/.treasure

Command I used: grep -rFn 'THE_PENGUIN_WAS_HERE' missions/01-linux/files/

### Task B — count the errors

Count: 8

Command I used: grep -c 'ERROR' missions/01-linux/server.log

## Mission 03 — SSH

SSH token: FLAG{fe322c8dc745}

Command I used: ssh -i "$HOME/.ssh/knock knock" flag@217.142.229.247

## Mission 04 — Debug

What was wrong: 應該輸出 42 但輸出 41

What I changed: 把 (+ (base-value) 1) 改成 (+ (base-value) 2)

## Mission 05 — Docker

What was wrong:

What I changed:

## Mission 06 — Improve something

What I changed:

Why:
