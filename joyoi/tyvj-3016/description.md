# 

 
 # 题目描述 
<p>
　　某工厂收到了n个产品的订单，这n个产品分别在A、B两个车间加工，并且必须先在A车间加工后才可以到B车间加工。

 
 # 输入格式 
<p>
　　第一行仅—个数据n(0 < n < 1000)，表示产品的数量。

 
 # 输出格式 
<p>
　　一行一个数据，表示最少的加工时间。</p> 

 
 # 提示 
<p>
　　本题是要求一个加工顺序使得总的加工时间最少，而要使加工时间最少，就是让各车间的空闲时间最少。一旦A车间开始加工，便会不停地进行加工(我们不要去管车间是否能够一直生产，因为他们有三班，可以24时间不停地运转)。关键是B车间在生产的过程中，有可能要等待A车间的初加工产品。很显然所安排的第一个产品在A车间加工时，B车间是要等待的，最后一个产品在B车间加工时，A车间已经完成了任务。
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
<tr><td>5
3 5 8 7 10
6 2 1 4 9
</td><td>34</td></tr></table>