# 手冊
## unix 基本操作

### 進入目錄
```
cd <目錄>
```

### 列出目前目錄
```
ls
ls -al
```

### 回到上一層目錄
```
cd ..
```

### 顯示當前路徑
```
pwd
```

### 創建目錄
```
mkdir <目錄>
```

### 刪除目錄以及檔案(不可逆)
```
rm -Rf <目錄>
```

### 複製目錄以及檔案
```
cp -Rf <來源目錄> <目標目錄>
```
### 取消當前指令
```
ctrl + c
```

## Git 手冊
###  Git 改變使用者
```
git config --global user.email "xxx@xxx.com"
git config --global user.name "xxx.xxx"
```

### 下載
```
git clone <PATH>
```

### 新增修訂版本
```
git add .
git commit
```

### 上傳
```
git fetch
git rebase -i
git push
```

### 跟遠端同步
```
git pull
```

### 回到當前版本初始狀態
```
git reset --hard
```
### 觀看修訂版本記錄
```
git log
```

### git commit 前想要反悔修改
```
git reset
```

### 觀看目前的修改狀況差異
```
git diff
```

### 把某個檔案或資料夾回復到當前版本
```
git checkout <File Name>
```

### 抓取某個版本分支
```
git checkout <Hash Code>
```
