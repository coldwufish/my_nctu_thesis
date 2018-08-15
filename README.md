# my_nctu_thesis
latex template for NCTU thesis

來源不知道是哪裡了 (NTUST!?) \
後來經過實驗室大神的修改, 然後再根據自己的喜好去調整一些細微的東西, 就多了這些東東 \
想參考學校格式, 可以看NCTU_files裡面的pdf檔

by wufish@gmail

======================================================================
1. 修改個人資料 \
frontpages/my_names.tex

2. 致謝, 中英文摘要的路徑 \
frontpages/my_ackn.tex		//致謝 \
frontpages/my_cabstract.tex	//中文摘要 \
frontpages/my_eabstract.tex	//英文摘要

3. 內文 (可以依照自己的喜好去擴充, 我當時是一個章節一個tex檔) \
sections/introduction.tex \
sections/method.tex \
sections/conclusion.tex

4. 參考文獻 \
my_bib.bib

如果是研討會論文, 出處通常都會加in Proc.在前面 \
ex: in Proc. IEEE Int'l Conference on Distributed Computing Systems (ICDCS)

如果是期刊論文, 就不用加這個了 XD


[編譯方式] \
打開 my_nctu_thesis.tex, 然後編譯 \
xelatex -> bibtex -> xelatex -> xelatex

ps1. 我也不知道為啥要跑兩次xelatex \
ps2. 跑完之後就會出現pdf, 我習慣事後再去開檔案 \
ps3. 沒有買, 現在值得入手PS3嗎 \
ps4. 現在好像很多PS4遊戲了, 可是我已經買switch了 \
