# 學習筆記

## 第零週 | 歡迎光臨 Jupyter 星球。
-  Jupyter 命名中 Ju 指的是 Julia 語言、py 指的是 Python 語言、r 指的是 R 語言。

## 第一週 | 預覽約維安文明的科技樹。
- 黑暗時代：命令列、Markdown 與 Git/GitHub。
- 封建時代：SQL、Python 與 R。
- 城堡時代：進階程式設計能力，包含物件導向程式設計（Object-oriented programming, OOP）、函數型程式設計（Functional programming）、套件以及環境管理。
- 帝王時代：資料分析任務，涵蓋一個或多個資料科學應用場景，包含資料載入、資料處理、資料轉換、資料視覺化、資料模型與資料溝通。

## 第二週 | 初嘗命令列的滋味。
```
pwd                      # print working directory
mkdir folder_name        # make directory
ls                       # list directory and file
cd folder_name           # changing directory (進入資料夾); cd ..(退出);  cd ~從任何目錄直接更換到家目錄，使用cd /從任何目錄直接更換到根目錄
touch file_name          # create file
mv file_name file_name   # move file (重新命檔名, mv 舊檔名 新檔名)
cp file_name file_name   # copy file (cp 舊檔名 新檔名)
rm file_name file_name   # remove file
rm -r folder_name        # remove folder
clear                    # clear command line, Ctrl-L
# up-arrow / down-arrow for history commands
# tab for auto-completion
# Ctrl-C to stop execution
```

## 第三週 | 初嘗 Markdown 的滋味。
- Markdown 是一個輕量的標記式語言（Markup language），約維安能夠使用它撰寫文件，只要在新增txt文字檔之後將副檔名更改為 .md 即可。
- https://www.markdownguide.org/basic-syntax/
- 為文字加上樣式：**粗體文字** *斜體文字* `行內程式碼` ~~刪除線文字~~
```
**粗體文字**
*斜體文字*
`行內程式碼`
~~刪除線文字~~
```

- 為文件設計結構
```
# 標題階層一

## 標題階層二

### 標題階層三

## 清單

- 項目一
- 項目二
- 項目三

## 多行程式碼

```
多行的\
程式碼
```

## 引用

> Life was like a box of chocolates. You never know what you're gonna get.
>
> Forrest Gump

## 換行 

字尾加"\" or 2個空白"  "

##圖片

```
## 第四週 | 初嘗 Git 與 GitHub 的滋味。
- 在自己的電腦中也保有一份與遠端儲存庫相同的專案
```
開啟 Git Bash（Windows）或者終端機（macOS）輸入以下指令將遠端儲存庫複製一份到電腦中，成為一個本地儲存庫，其中遠端儲存庫的網址可以點選右上角的 Code > Copy 圖示複製。\
~$ git clone <YOUR-REPOSITORY-URL>
```
![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
