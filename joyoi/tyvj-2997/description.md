# 

 
 # 题目描述 
<p>
暑假到了，Philia想回家乡度过一个愉快的旅程。假设有N个地方是Philia很感兴趣的。对于任意两个地方，有且只有两条公路，一条从A到B，一条从B到A。公路有两种类型，R1和R2。公共汽车在R1上行走，人们在R2上行走。如果从A到B，走R2会花费T2分钟，而走R1只需要花费T1分钟（当然，T1 < T2）。

 
 # 输入格式 
<p>
输入包含多组测试数据。第一行包含一个正整数T，表示测试数据数目。每组测试数据包含两部分，第一部分包含四个整数N (1<N<100), T, T1, T2 (0<T, T1, T2<100)。第二部分包含N*N的矩阵M。Philia需要花费M[i][j]分钟从i地到达j地。数据保证当i=j，则M[i][j]=0，否则M[i][j]必定等于T1或T2 (T1<T2)。</p> 

 
 # 输出格式 
<p>
对每一组测试数据。输出一行包含一个整数S，表示Philia需要花费的最少时间。</p> 
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
<tr><td>1
4 10 10 20
0 10 10 10
20 0 20 20
20 20 0 10
20 20 20 0
</td><td>100</td></tr></table>