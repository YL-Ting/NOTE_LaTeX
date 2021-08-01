# NOTE_LaTeX
## 第一次學 LaTeX，想說做點紀錄方便以後回來看，然後學一下 git 的使用方式
## 參考教學
- [LaTex Tutorial for Beginners Full Course (主要是這個)](https://www.youtube.com/watch?v=fCzF5gDy60g)
- [LaTeX Tutorials (featuring Texmaker)（這個講得比較細我比較沒看）](https://www.youtube.com/watch?v=0ivLZh9xK1Q&list=PL1D4EAB31D3EBC449)

## 日誌
- Day1：學習一些基本的符號及字體大小，vscode 設定 git 失敗 Day2 再來試試
- Day2：學了表格跟跟陣列（矩陣）的寫法，然後 vscode 上 git push 還是失敗（應該是我用錯 QQ），在我搞定之前應該會都用終端機上傳
- Day3：今天是學一些寫微積分時會用的符號，諸如微分符號，積分符號，向量等，到在學的時候遇到了

    ```
    LaTeX Error: File `esvect.sty' not found
    ```
    缺套件的問題，上網查了一下解決方法

    ![解決方法](./Day3/PackageNotFound.png)
    
    我自己是裝 textlive-base（想說沒有要學很深結果馬上就踩坑ww）雖然 3 GB的確挺多的，不過之後應該不太會再遇到缺套件的問題了
- Day4：數學符號與定義，~~越學越佩服那些數學家怎麼記得住XD~~
- Day5：今天學的東西比較多是在設定檔案的環境以及如何進行客製化，所以註解寫的比程式碼還多XD
- Day6：今天的部份大多是一些比較零碎的知識點，其中比較重要的大概就是檔案目錄、章節參考跟超連結的寫法了吧
- Day7：這次內容可以說是用 LaTeX 來做 PPT 也不為過，雖然 Beamer 的功能與預設模板沒那麼多不過我認為各有各的優勢
- Day8：今天學習 TikZ 套件，也是這個 LATEX 教學的最後一個章節，TikZ是非常強大的套件，裡面有很多用來畫圖的工具（也因此這次的檔案花了兩三天才寫完，但為了學習的完整性我還是都歸在第八天）第八天

## 完結心得：學 LaTeX，我覺得就像在學寫網頁一樣，一樣的程式碼出來的結果跟教學上看到的不一定會一樣（大部分是因為編譯器不同），而且跟網頁一樣對於排版有非常多的指令可以使用 ~~（雖然我都沒在排）~~，整個學下來還蠻有趣的，以後如果要寫論文或是其他比較要求格式的檔案應該會用 LaTeX 寫，但一般小文檔應該不會，因為 LaTeX 在檔案的架構上考慮很多，對寫一些輕鬆小品的人來說我覺得有點多餘。