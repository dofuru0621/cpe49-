# cpe49-1星題 

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

> 用 map 來實作，因為每個元素都唯一且排序，直接 key 放國名，value 放次數

```

