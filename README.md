# Hard_10835_CardGame

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/10835_CardGame/blob/main/10835_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

I think I'm weak at recursive dp problems.

Let's say dp[l][r] is we are seeing th l card in the left , r card in the right.

If left[l] > right[r] , taking score(abandon right) will alway give more socore.

If not, find the max of dp[l+1][r] , dp[1+1][r+1] will be the answer.

I forgot to check when l or r is bigger than n. It takes a while to find it...

ha...

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
