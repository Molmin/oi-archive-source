# 

 
 # 题目描述 
<p>
Farmer John's N (1 <= N <= 50,000) cows (numbered 1..N) are planning

 
 # 输入格式 
<p>
* Line 1: A single line with the integer N.

 
 # 输出格式 
<p>
* Line 1: A single integer, giving the largest risk of all the cows in
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
10 3
2 5
3 3
</td><td>2

OUTPUT DETAILS:

Put the cow with weight 10 on the bottom. She will carry the other
two cows, so the risk of her collapsing is 2+3-3=2. The other cows
have lower risk of collapsing.