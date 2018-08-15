=========================================================
原本的readme
=========================================================
本範本是由元智大學碩博士論文latex範本改編而來
目前主要是修改了以下幾個東西
1.浮水印
2.封面格式
3.加入教授推薦書頁面
4.刪除無用的頁面
5.更改檔案結構

在進行論文寫作時
只需改變所有檔名為my_XXXXXXX.XXX之文件

本tex之主結構檔為my_ntust_thesis.tex
其中需要修改的東西為在frontpages及backpages之文件
論文主結構及內容請分類放置於sections目錄中
references的bibtex檔請放置於目錄第一層之my_bib.bib

為了生產出正確的檔案，請務必編輯四次
否則目錄及參考資料會亂掉

pdflatex + bibtex + pdflatex + pdflatex
=========================================================



=========================================================
上面那段是拿到這份檔案就有了, 後來經過實驗室大神的修改
然後再根據自己的喜好去調整一些細微的東西, 就多了下面這些東東

想參考學校格式, 可以看NCTU_files裡面的pdf檔

add by wufish
=========================================================
1. 修改個人資料
frontpages/my_names.tex

2. 致謝, 中英文摘要的路徑
frontpages/my_ackn.tex		//致謝
frontpages/my_cabstract.tex	//中文摘要
frontpages/my_eabstract.tex	//英文摘要

3. 內文 (可以依照自己的喜好去擴充, 我當時是一個章節一個tex檔)
sections/introduction.tex
sections/method.tex
sections/conclusion.tex

4. 參考文獻
my_bib.bib

如果是研討會論文, 出處通常都會加in Proc.在前面
ex: in Proc. IEEE Int'l Conference on Distributed Computing Systems (ICDCS)

如果是期刊論文, 就不用加這個了 XD


[編譯方式]
xelatex -> bibtex -> xelatex -> xelatex

ps1. 我也不知道為啥要跑兩次xelatex
ps2. 跑完之後就會出現pdf, 我習慣事後再去開檔案
ps3. 沒有買, 現在值得入手PS3嗎
ps4. 現在好像很多PS4遊戲了