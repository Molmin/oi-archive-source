# 

 
 # 题目描述 
<p>
如果某个无向连通图的任意一条边至多只出现在一条简单回路（simple cycle）里，我们就称这张图为仙人图（cactus）。所谓简单回路就是指在图上不重复经过任何一个顶点的回路。

 
 # 输入格式 
<p>
输入的第一行包括两个整数n和m（1≤n≤50000以及0≤m≤10000）。其中n代表顶点个数，我们约定图中的顶点将从1到n编号。

 
 # 输出格式 
<p>
只需输出一个数，这个数表示仙人图的直径长度。

 
 # 提示 
<p>
对第一个样例的说明：
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
<tr><td>15 3
9 1 2 3 4 5 6 7 8 3
7 2 9 10 11 12 13 10
5 2 14 9 15 10	8
10 1
10 1 2 3 4 5 6 7 8 9 10	
</td><td>
9
</td></tr></table>