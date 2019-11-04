# 

 
 # 题目描述 
<p>
Woody实在是太饿了。他打算在接下来的n天中自己做菜。每天做一道菜。他能做各种各样的不同的菜。他事先就知道做各道菜的花费以及各道菜对他的好处值。但如果Woody连续两天做同一道菜，那么第二天得到的该到菜的好处值将是第一天的得到的该道菜的好处值的一半。如果一道菜连续做i(i >= 3)天，那么从第三天开始一直到第i天，Woody每天从该道菜上得到的好处值将为0。

 
 # 输入格式 
<p>
第一行3个数，n（1 <= n <= 21），m（1 <= m <= 50），k（0 <= k <= 100）。n表示Woody做菜的总天数。m表示Woody会做的菜的总数。k表示Woody现有的钱数。

 
 # 输出格式 
<p>
仅一行，输出一个数，表示这n天中Woody能够得到的最大的好处总值。答案保留一位小数。
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>【输入样例一】
2 1 5
3 5

【输出样例一】
0.0

【样例解释】
Woody共要做2天菜，他只会做1道菜。该道菜的花费为3，好处值为5。
那他这两2天只能做这道菜，总共的花费为3 + 3 = 6。但他一共只有5块钱。6 > 5。不能保证他每天都吃到菜，所以输出0.0。


【输入样例二】
3 5 20
2 5
18 6
1 1
3 3
2 3

【输出样例二】
13.0

【样例解释】
一种可行的方案为第1天做第1种菜，第2天做第5种菜，第3天做第1种菜。总花费2 + 2 + 2 = 6 < 20，好处总值为5 + 3 + 5 = 13。


【输入样例三】
5 1 20
1 5

【输出样例三】
7.5

【样例解释】
连续5天，每天都吃同一道菜。总花费1 + 1 + 1 + 1 + 1 = 5 < 20，由于连续5天吃同一道菜，所以Woody只有第1天和第2天得到了好处值，后3天得到的好处值为0，所以好处总值为5 + 5 / 2 = 7.5。

</td><td>（见上）	</td></tr></table>