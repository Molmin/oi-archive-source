# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>


 
 # 输出格式 
<p>
* 第一行: 一个整数,最多可以喂饱的牛数.
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
<tr><td>
4 3 3
2 2 1 2 3 1
2 2 2 3 1 2
2 2 1 3 1 2
2 1 1 3 3

输入解释:

牛 1:  食品从 {1,2}, 饮料从 {1,2} 中选
牛 2:  食品从 {2,3}, 饮料从 {1,2} 中选
牛 3:  食品从 {1,3}, 饮料从 {1,2} 中选
牛 4:  食品从 {1,3}, 饮料从 {3} 中选
</td><td>
3
输出解释:

一个方案是:
Cow 1: 不吃
Cow 2: 食品 #2, 饮料 #2
Cow 3: 食品 #1, 饮料 #1
Cow 4: 食品 #3, 饮料 #3
用鸽笼定理可以推出没有更好的解 (一共只有3总食品和饮料).当然,别的数据会更难.</td></tr></table>