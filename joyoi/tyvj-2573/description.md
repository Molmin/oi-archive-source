# 

 
 # 题目描述 
<p>
Like everyone else, cows like to stand close to their friends when

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: N, ML, and MD.

 
 # 输出格式 
<p>
* Line 1: A single integer. If no line-up is possible, output -1.  If
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
<tr><td>4 2 1
1 3 10
2 4 20
2 3 3

INPUT DETAILS:

There are 4 cows.  Cows #1 and #3 must be no more than 10 units
apart, cows #2 and #4 must be no more than 20 units apart, and cows
#2 and #3 dislike each other and must be no fewer than 3 units apart.

有4头奶牛。奶牛1和奶牛3必须在10个单位之内，奶牛2和奶牛4必须在20个单位之内，奶牛2和奶牛3不喜欢对方，必须在3个单位之外。

</td><td>27

OUTPUT DETAILS:

The best layout, in terms of coordinates on a number line, is to put cow #1
at 0, cow #2 at 7, cow #3 at 10, and cow #4 at 27.

最好的布局是，在同一条坐标上，把奶牛1放在0处，把奶牛2放在7处，把奶牛3放在10处，把奶牛4放在27处。</td></tr></table>