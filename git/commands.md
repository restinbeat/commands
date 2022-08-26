# Git Commands

### 1. 저장소 복제

```bash
$ git clone <https:// URL>
```

### 2. 파일상태 확인

```bash
$ git status
```

### 3. Repository Commit / Push

```bash
$ git pull
$ git add <file name>
or
$ git add .
or
$ git add -A 

$ git commit -m "[commit message]"
$ git push origin master
```

**Get recent commit**

```bash
$ git reset --hard <copy commit ID>
```

**Update commit version**

```bash
$ git fetch
```

### 4. Branch

**Show branch**

``` bash
$ git branch
```

**Create branch**

```bash
$ git branch <branch name>
$ git push origin <branch name>
```

**Change branch name**

```bash
$ git branch -m <default> <change name>
```

**Delete branch**

```bash
$ git branch -d <branch name>
```

**Checkout**

```bash
$ git checkout -b <branch name> // Create branch and Move
$ git checkout <branch name or master>
```

### 5. Log

**Commit Log**

```bash
$ git log
or 
$ git log --oneline
```

### 6. Copy Repository

**Copy all commits and tags.**
<br>
copy repository : https://github.com/restinbeat/flutter-instagram.git
<br>
new repository : https://github.com/restinbeat/flutter-qr.git

```bash
$ git clone --mirror https://github.com/restinbeat/flutter-instagram.git
cd flutter-instagram.git/
$ git remote set-url --push origin https://github.com/restinbeat/flutter-qr.git
$ git push --mirror
```

### 7. Git reset

**Cancel recent commit**

```bash
$ git reset --soft
$ git reset --soft HEAD^
$ git reset --soft HEAD~<number>
or
$ git reset --mixed 
or 
$ git reset --hard
```

### 8. Git histroy

```bash
$ git blame <file path>
```

### 9. Git 

```bash
$ git bisect start 
$ git bisect good [good Commit ID]
$ git bisect bad [bad Commit ID]
```