# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;经过在机房里数日的切磋，LYD从杜神牛那里学会了分离与合体，出关前，杜神牛给了他一个测试......<BR>&nbsp;&nbsp;&nbsp;杜神牛造了n个区域，它们紧邻着排成了一行，编号1~n。在这每个区域里都放着一把OI界的金钥匙，每一把都有一定的价值，LYD当然想得到它们了。然而杜神牛规定LYD不可以一下子把它们全部拿走，而是每次只可以拿一个。为了尽快的拿到所有的金钥匙，LYD自然就用上了刚学的分离与合体特技。<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;一开始LYD可以选择从1~n-1的任何一个区域(记为K)进入，进入后LYD会在K区域发生分离，从而分离为两个小LYD。分离完成的同时会有一面墙在K和K+1区域之间升起，从而把1~k和k+1~n阻断为两个独立的区间。然后两个小LYD分别进入1~k和k+1~n，并在各自的区间内任选除了区间末尾区域以外(即1~k-1或k+1~n-1)的任何一个区域再次发生分离，就一共有了4个小小LYD……重复进行以上所叙述的分离，直到每个小LYD发现自己所在的区间只剩下了一个区域，他们就可以抱起自己梦寐以求的OI金钥匙。<BR>&nbsp;&nbsp;&nbsp;&nbsp;但是LYD不能就这么分成n多个个体存在于世界上，这些小LYD还会再合体，合体的两个小LYD所在的区间中间的墙会消失。合体会获得一定的价值，计算方法是：(合并后所在区间的左右端区域里金钥匙的价值之和)&nbsp;乘&nbsp;(之前分离的时候所在区域的金钥匙价值)。<BR>{例如：LYD曾经在1~3区间中的2号区域分离成为1~2和3两个区间，合并时获得的价值就是（1号金钥匙价值+3号价值）*(2号金钥匙价值)。}<BR>&nbsp;&nbsp;&nbsp;LYD请你编程求出最终可以获得的总价值最大是多少。并按照分离阶段从前到后，区域从左向右的顺序，输出发生分离的区域编号&nbsp;(例如：先打印1分为2的分离区域，然后从左到右打印2分为4的分离区域，然后是4分为8的......)&nbsp;。<BR>&nbsp;&nbsp;&nbsp;&nbsp;注意：若有多种方案，选择分离区域尽量靠左的方案（也可以理解为输出字典序最小的）。 

 
 # 输入格式 
第一行:正整数n&nbsp;(2&lt;=n&lt;=300)<BR>第二行:n个正整数，表示1~n区域里每把金钥匙的价值。<BR>保证答案及运算过程中不超出longint范围。<BR> 

 
 # 输出格式 
第一行一个数，即获得的最大价值<BR>第二行按照分离阶段从前到后，区域从左向右的顺序，输出发生分离的区域编号，中间用一个空格隔开，若有多种方案，选择分离区域尽量靠左的方案（也可以理解为输出字典序最小的）。<BR> 

 
 # 提示 
数据范围约定<BR>对于%20的数据&nbsp;&nbsp;N&lt;=10&nbsp;&nbsp;<BR>对于%40的数据&nbsp;&nbsp;N&lt;=50<BR>对于%100的数据&nbsp;N&lt;=300&nbsp;&nbsp;a[i]&lt;=300&nbsp;幻影^九天麟日（LYD）&nbsp;&nbsp;TYVJ首届月赛&nbsp;第二道 
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
<tr><td>7
1 2 3 4 5 6 7

</td><td>238
1 2 3 4 5 6</td></tr></table>