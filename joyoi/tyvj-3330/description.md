# 

 
 # 题目描述 
<p>
最后的战犯（maze.pas/c/cpp）

 
 # 输入格式 
<p>
　　输入文件maze.in第一行是一个整数N。以下N行每行N个字符，“*”表示岩洞中的障碍物，“.”表示空地，“J”表示小犬（一开始他会向北走），“F”表示Feli。上北下南左西右东。</p> 

 
 # 输出格式 
<p>
　　输出文件maze.out仅一行，如果Feli能抓到小犬，那么输出所需的最短时间，如果Feli抓不到小犬，那么这个最后的日本战犯将在岩洞中饿死（因为Feli将在离开的时候封闭岩洞的所有出口），此时输出“No solution.”，不要输出引号。</p> 
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
<tr><td>3
F*J
.*.
...
</td><td>3</td></tr></table>