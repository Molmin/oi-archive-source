# 

 
 # 题目描述 
<p>
在计算机中，CPU只能和高速缓存Cache直接交换数据。当所需的内存单元不在Cache中时，则需要从主存里把数据调入Cache。此时，如果Cache容量已满，则必须先从中删除一个。

 
 # 输入格式 
<p>
输入文件第一行包含两个整数N和M(1<=M<=N<=100,000)，分别代表了主存访问的次数和Cache的容量。

 
 # 输出格式 
<p>
输出一行，为Cache缺失次数的最小值。

 
 # 提示 
<p>
在第4次缺失时将3号单元换出Cache。
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
1 2 3 1 2 3</td><td>4</td></tr></table>