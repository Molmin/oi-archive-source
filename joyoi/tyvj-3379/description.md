# 

 
 # 题目描述 
<p>
神奇的供水系统（water.pas\c\cpp）

 
 # 输入格式 
<p>
　　输入文件water.in的第一行包括四个整数n,m,s_rain,t_rain(1<=n<=1000,1<=m<=1000000)分别表示n个贮水器，m个集水器，了方便计算，Z4人为地把他们分别按1..n,1..m标号，而其中第n个贮水器即为中央贮水器，s_rain表示单位时间里单位面积的降雨量，t_rain表示该次降雨持续时间。

 
 # 输出格式 
<p>
　　输出文件water.out只有一行，表示雨停后直到得到水供应的时间.(结果肯定<=maxlongint)
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
<tr><td>5 5 1 1
10 1 1 2
5 1 3 4
10 1 4 3
10 1 4 6
8 1 5 9
2 2
5 1
5 2
5 2
</td><td>100</td></tr></table>