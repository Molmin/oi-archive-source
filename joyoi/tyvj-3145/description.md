# 

 
 # 题目描述 
<p>
　　给定一个m行n列的方格阵，每个方格边长为1。要从方格阵左上方的顶点（0，0）走到右下方的顶点（m，n），中间有若干个格子是障碍物，无法通过。人可以从（x1，y1）走到（x2，y2），当且仅当（x1<=x2）且（y1<=y2）且线段（x1，y1）-（x2，y2）不穿过任意一个障碍方格。求最短路长度。</p> 

 
 # 输入格式 
<p>
　　文件的第一行包括3个用空格分开的正整数m，n。以下是一个邻接矩阵A，1表示表示障碍。</p> 

 
 # 输出格式 
<p>
　　文件只有一行。文件应只一个精确到小数点后面2位小数的实数，表示最短路径的长度。</p> 

 
 # 提示 
<p>
【提示】
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
<tr><td>　　3 　4
　　0 0 1 0
　　0 1 0 0
　　0 0 0 1
</td><td>　5.47</td></tr></table>