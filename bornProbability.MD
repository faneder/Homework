# Born Probability Homework

## 一對夫婦計劃生孩子生到有女兒才停，或生了三個就停止。他們會擁有女兒的機率是多少？
### step 1：機率模型

- 每一個孩子是女孩的機率是0.49 ，是男孩的機率是0.51。

各個孩子的性別是互相獨立的。
### step 2：分配隨機數字。
- 用兩個數字模擬一個孩子的性別: 00, 01, 02, …, 48 ＝ 女孩; 49, 50, 51, …, 99 ＝ 男孩

### step 3：模擬生孩子策略
- 從表A當中讀取一對一對的數字，直到這對夫婦有了女兒，或已有三個孩子。
- 10次重複中，有9次生女孩。會得到女孩的機率的估計是9/10=0.9。
- 如果機率模型正確的話，用數學計算會有女孩的真正機率是0.867。(我們的模擬答案相當接近了。除非這對夫婦運氣很不好，他們應該可以成功擁有一個女
兒。)