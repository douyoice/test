# 手冊
## unix 基本操作

### 進入工作資料夾
```
cd <資料夾>
```
e.g. 切換到 D:/test/folder 作為工作資料夾
```
cd /D/test/folder
```

e.g. 切換到目前資料夾的子資料夾 folder 作為工作資料夾
```
cd AnotherFolder
# 如果延續上一個範例的話，當前資料夾會變成/D/test/folder/AnotherFolder
```
### 列出目前資料夾下的檔案
* 僅列出檔案以及資料夾名稱
```
ls
```
* 列出詳細資料
```
ls -al
```

### 回到上一層資料夾
```
cd ..
```

### 顯示當前工作資料夾
```
pwd
```

### 創建資料夾
```
mkdir <資料夾>
```
e.g.

```
mkdir test
```

### 刪除資料夾以及檔案(不可逆)
```
rm -Rf <資料夾>
```
e.g.

```
rm -Rf test
```

### 複製資料夾以及檔案
```
cp -Rf <來源資料夾> <目標資料夾>
```
e.g.
```
cp -Rf test test2
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
e.g.
```
git clone https://github.com/douyoice/test
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
