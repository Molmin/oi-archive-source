# 

 
 # 题目描述 
<p>
农夫约翰的奶牛住在N (2 <= N <= 200,000)片不同的草地上，标号为1到N。恰好有N-1条单位长度的双向道路，用各种各样的方法连接这些草地。而且从每片草地出发都可以抵达其他所有草地。也就是说，这些草地和道路构成了一种叫做树的图。输入包含一个详细的草地的集合，详细说明了每个草地的父节点P_i (0 <= P_i <= N)。根节点的P_i == 0, 表示它没有父节点。因为奶牛建立了1到K一共K (1 <= K <= N/2)个政党。每只奶牛都要加入某一个政党，其中，

 
 # 输入格式 
<p>
* 第一行: 两个由空格隔开的整数: N 和 K

 
 # 输出格式 
<p>
* 第1到第K行: 第i行包含一个单独的整数，表示第i个政党的范围。
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
<tr><td>6 2
1 3
2 1
1 0
2 1
2 1
1 5

</td><td>3
2