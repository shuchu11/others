**pre-required**
```
git config --global user.name "shuchu11" # 輸入名稱
git config --global user.email "2018310ruin@gmail.com"  # 輸入email
```
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
**Example :**
**EX1 :** edit file > `Ctrl + S`儲存 > `git add .` > "git commit -m "建立還原點""

查看log日誌(提交紀錄)
```
git log
```
enter `q` to exit
