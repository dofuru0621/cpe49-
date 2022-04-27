# cpe49-1星題 

![未命名](https://user-images.githubusercontent.com/74231280/165333778-370dd38e-1ce5-4afe-8ebf-48b5e99beb30.png)

## 10041 Vito’s family

### 中文翻譯
> 題目述說的是要幫助黑道家族找到一個位置讓他去找他所有的親戚最短的位置。
> 這題題目其實就是要找到一個點到每個位置的最短距離和，然後輸出就可以了！
### 解法
```
基本上就是找到輸入數字的中位數
接著，計算每一個點到中位數的距離

記得要做絕對值喔!!(abs)

然後加總起來就可以啦~
```

## 10222 Decode the Mad man

### 中文翻譯
> BUET大學有一位老教授就發瘋了。他開始說一些奇怪的話。沒有人能夠聽得懂他的上課內容。
最終，BUET大學陷入了難題。無法讓這位老教授繼續在大學教書。
突然有一位學生(肯定是UVA ACM章節的註冊作者，並且在online judge排名很高)創造了一個可以將教授說的話解碼的程式。
在此之後，老教授又繼續正常的教書，每個人都感到很開心。
因此，如果你有機會參訪BUET大學，並且看到一位老師正在用裝有語音辨識麥克風講話，你可別嚇到。
因為現在你的工作就是寫相同的程式來解碼瘋狂老教授的語言。

### 解法
```
他想要把鍵盤按鍵都往左移，當我們想要印出Ｈ的話，我們不能直接打Ｈ而是要打Ｋ這個按鍵。

解題步驟：
首先先把鍵盤的順序輸入到陣列中（c++可以用把它視為string來存）
讀取資料
資料跟鍵盤做比對
輸出
```

## 10407 Hashmat the brave warrior

### 中文翻譯
> Hashmat是一個勇敢的將領，他帶著年輕的士兵從這個城市移動到另一個城市與敵人對抗。在打仗之前他會計算己方與敵方士兵的數目差距，來決定是要開打或不開打。Hashmat的士兵數絕不會比敵人的士兵數大。

### 解法
```
絕對值計算兩隊兵力差
因為"The input numbers are not greater than 2^32，所以要用long才不會溢位
```

## 10420 listOfConquests

### 中文翻譯
> 簡單講一下，就是有一個大情聖，要記錄他的魚池攻略本，原本是用時間順序紀錄，現在為了方便要照國籍與姓名重新排序

### 解法
```
輸入國家和人名，輸出國名與人數
需要注意的有：
第一行輸入整數 n 代表人數 (最多 2000)
接下來的 n 行輸入每個人的國籍與名字 (最多 75 個字元)
國籍是一個單字
按照國籍的英文字母排序，輸出國籍與該國人數
隱藏要點：
國籍只有一個單字，但名字不會

用 map 來實作，因為每個元素都唯一且排序，直接 key 放國名，value 放次數

```

## 10783 Odd sum

### 中文翻譯
> 給你一個範圍 a 到 b ，請你找出 a 與 b 之間所有奇數的和。

### 解法
```
用迴圈+a到b的每個基數
```

## 10929 You can say 11

### 中文翻譯
> 輸入數字，判斷是否為11的倍數，數字長度最大為1000位數。

### 解法
```
不能用INT會爆掉，要用String
```


## 272 TeX Quotes

### 中文翻譯
> TeX 是一種由 Donald Knuth 所發展出的一套文書排版軟體。這套軟體可以將原始文件檔加上一些像字型等型態後，轉成一份很漂亮的文件。而一份漂亮的文件是需要用 `` 和 " 來把別人說的話給「引」出來，而不是用大部份鍵盤上有的 " 。雖然鍵盤裡通常不會有這種有方向的雙引號鍵，不過上面有左單引號 ` （有人叫 backquote ），和右單引號 ' （有人叫 apostrophe 或 quote ）。你可以在你的鍵盤上找一下，不過要小心不要將 ` 與 \ （ backslash 鍵）搞混了。而在 TeX 裡，使用者可以輸入兩個左單引號 `` 來構成一個左雙引號 `` ，或者是兩個右單引號 '' 來構造一個右單引號 '' ，不過呢，通常大家打字時都很習慣用普通的雙引號 " 來引述別人的話。

### 解法
```
輸入是若干列的文字，其中有偶數個雙引號（ " ），以 end-of-file 做結束。輸出的文字必須和輸入的一模一樣，除了：
* 每一組雙引號的第一個 " 必須用兩個 ` 字元（就是 `` ）來代替
* 每一組雙引號的第二個 " 必須用兩個 ' 字元（ 就是 ''）來代替。
```

## 11461 Square Number

### 中文翻譯
> 完全平方數就是平方根為整數的整數。例如 1, 4, 81 就是完全平方數。給你兩個整數 a 和 b，請你求出 a 與 b 之間 (含) 有幾個完全平方數。

### 解法
```
計算 a 及 b 之平方數，並相減算出其個數
```

## 10071 Back to High School Physics

### 中文翻譯
> 某一個粒子有一初速度和等加速度。假設在 t 秒後此粒子的速度為 v ，請問這個粒子在 2t 秒後所經過的位移是多少。

### 解法
```
位移=2*v*t
```

## 11417 GCD

### 中文翻譯
> 單純累加 0~N 之間 數字的GCD值

### 解法
```
比較要注意的是我有多加一個判斷是當 a ==0 時也回傳0
```

## 100 The 3n+1 Problem

### 中文翻譯
> 輸入兩個數字，並找到兩個數字間經過這神奇的計算的最大值（比其他數字計算後都大）

### 解法
```
知道要怎麼算出神奇算式
讓他從範圍裡面一個一個做計算，然後比大小。
```

## 10101 Bangla Numbers

### 中文翻譯
> 輸入給一個正整數，依據要求將其轉換成不同的單位做輸出

### 解法
```
測資數字範圍大，用long long

2. 遞迴

3. 這題輸出指定格式很麻煩，核對超多次　

　用uDebug提供的測資對比就懂了！

　https://www.udebug.com/UVa/10101
```

## 10019 - Funny Encryption Method

### 中文翻譯
> 一位來自墨西哥蒙特瑞技術研究學院(ITESM Campus Monterrey)的學生想發表一種新的數值加密演算法。
演算法步驟如下：

1. 讀入一個整數N，N為欲加密的數字：N = 265
2. 將N當作十進位的數值：X1 = 265(decimal)
3. 把X1由十進制轉為二進制：X1 = 100001001(binary)
4. 計算二進制的X1有幾個1：b1 = 3
5. 把N當作十六進位數值：X2 = 265(hexadecimal)
6. 把X2由十六進制轉為二進制：X2 = 1001100101(binary)
7. 計算二進制的X2有幾個1：b2 = 5
8. 最後的編碼為N xor (b1*b2)：265 xor (3*5) = 262

這位學生並未通過這次的計算機組識考試，所以他請求校方在ACM的試題上出一題計算共有幾個位元1的題目，好讓他能順利發表他的數值加密演算法。
你必須寫一個程式能讀入一個整數，然後輸出該整數的b1, b2值。

### 解法
```
依計概所教的方法去求出2進位，並計算有多少個1。
```

## 11321 — Sort! Sort!! and Sort!!!

### 中文翻譯
> 給你兩個整數 N (0<N<=10000), M (0<M<=10000)，你要依照某些規則排序N個整數。先利用每個數字除以M的餘數由小到大排，若排序中比較的兩數為一奇一偶且兩數除以M 的餘數相等，則奇數要排在偶數前面。若兩奇數除以M餘數大小相等，則原本數值較大的奇數排在前面。同樣的，若兩偶數除以M餘數大小相等，則較小的偶數排在前面。至於負數的餘數計算和 C 語言裡的定義相同，即負數的餘數絕對不會大於零。例如 -100 MOD 3 = -1, -100 MOD 4 = 0 依此類推。

### 解法
```
對於每一組輸入請輸出 N+1 行整數。第一行為兩個整數 N, M。接下來的 N 行都包含一個整數、及上述的數字按上述規則排列後的結果。對於輸入測資尾端的兩個 0, 0 請也輸出兩個空白分隔的 0, 0。
```

## 10035 - Primary Arithmetic

### 中文翻譯
> 在小學時我們都做過加法的運算，就是把2個整數靠右對齊然後，由右至左一位一位相加。如果相加的結果大於等於10就有進位（carry）的情況出現。你的任務就是要判斷2個整數相加時產生了幾次進位的情況。這將幫助小學老師分析加法題目的難度。

### 解法
```
每列測試資料輸出該2數相加時產生多少次進位，請參考Sample Output。注意進位超過1次時operation有加s
```
