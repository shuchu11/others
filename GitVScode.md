ref : https://youtu.be/FKXRiAiQFiY?si=cfopXxS0cGPyzhx4 

下載 git ( http://git-scm.com/downloads ) 

打開PowerShell 在Terminal輸入
```
git --version
```
如果跑出git編號代表成功，EX : 
```
git version 2.50.0.windows.1
```

**pre-required** 
```
git config --global user.name "shuchu11" # 輸入名稱
git config --global user.email "2018310ruin@gmail.com"  # 輸入email
```

# Example :
## EX1 如何在 vscode 操作 Github ?  
ref : https://youtu.be/FKXRiAiQFiY?si=cfopXxS0cGPyzhx4     [ 從 12 : 39 開始觀看]\
抓取自己想編輯的 github repository

![alt text](<螢幕擷取畫面 2025-06-25 122856.png>)

在`{目標 repository 的 git }`貼上複製連結取代，並在Vscode 的 Terminal中執行以下
```
 git clone {目標 repository 的 git } 
```
進入拽取下來的資料夾
```
cd {reponstory 名稱}
```
## EX2 如何編輯並儲存檔案 ?
edit file > `Ctrl + S`儲存 > `git add .` > `git commit -m "建立還原點"`

## 如何一邊寫Markdown筆記一邊預覽筆記
右上角的「📘 書本圖示」
圖示名稱是：Open Preview to the Side

**general command**
查看檔案狀態
```
git status
```

追蹤檔案 (成功追蹤的檔案檔名旁邊會顯示 `A`) 
```
git add {File name 1} {File name 2}
```
or
```
git add *.md  #將所有.md檔皆追蹤
```
查看log日誌(提交紀錄)
```
git log
```
enter `q` to exit



隨意點選一檔案進行編輯 :\
edit file > `Ctrl + S`儲存 > `git add .` > `git commit -m "test"`

上傳
```
git push
```

p.s 隨時可用 `git pull` 再拉下來編輯
