# 

 
 # 题目描述 
<p>
After World War X, a lot of cities have been seriously damaged, and we need to rebuild those cities. However, some materials needed can only be produced in certain places. So we need to transport these materials from city to city. For most of roads had been totally destroyed during the war, there might be no path between two cities, no circle exists as well.

 
 # 输入格式 
<p>
Input consists of multiple problem instances.For each instance, first line contains three integers n, m and c, 2<=n<=10000, 0<=m<10000, 1<=c<=1000000. n represents the number of cities numbered from 1 to n. Following m lines, each line has three integers i, j and k, represent a road between city i and city j, with length k. Last c lines, two integers i, j each line, indicates a query of city i and city j.</p> 

 
 # 输出格式 
<p>
For each problem instance, one line for each query. If no path between two cities, output “Not connected”, otherwise output the length of the shortest path between them.</p> 

 
 # 提示 
<p>
Huge input, scanf recommended.
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
<tr><td>5 3 2
1 3 2
2 4 3
5 2 3
1 4
4 5</td><td>Not connected
6</td></tr></table>