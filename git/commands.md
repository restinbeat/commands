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
$ git add
or
$ git add -A 

$ git commit -m "[commit message]"
$ git push origin master
```

### 4. Branch
**'Show branch'
``` bash
$ git branch
```

**'Create branch'
```bash
$ git branch <branch name>
$ git push origin <branch name>
```

**'Delete branch'
```bash
$ git branch -d <branch name>
```

**'Checkout'
```bash
$ git checkout -b <branch name> // Create branch and Move
$ git checkout <branch name or master>
```

### 5. Log
**'Commit Log'
```bash
$ git log
or 
$ git log --oneline
```