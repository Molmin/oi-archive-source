# 

 
 # 题目描述 
<p>
可可和卡卡家住合肥市的东郊，每天上学他们都要转车多次才能到达市区西端的学校。直到有一天他们两人参加了学校的信息学奥林匹克竞赛小组才发现每天上学的乘车路线不一定是最优的。

 
 # 输入格式 
<p>
输入文件中第一行有两个正整数N和M，分别表示合肥市公交车站和公交汽车路线的个数。以下M行，每行（第i行，总第(i+1)行）用四个正整数描述第i条路线：pi, qi, ti, ci；具体含义见上文描述。

 
 # 输出格式 
<p>
输出文件最多有两行。

 
 # 提示 
<p>
2<=N<=500, 1<=M<=124 750, 1<=ti, ci<=10 000
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
<tr><td>6 7
1 2 1 3
2 6 1 5
1 3 1 1
3 4 1 1
4 6 1 1
5 6 1 2
1 5 1 4
</td><td>
2 
5

</td></tr></table>