# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
第一行有一个字符串，由A、C、T、G、*、? 组成。表示“病毒模版片段”。“病毒模版片段”的长度不超过1000。第二行有一个整数N（0<N<500），表示机器人搜集到的RNA片段的数目。随后的N行，每一行有一个字符串，由A、C、T、G组成，表示一个RNA片段。每个RNA片段的长度不超过500。注意：“病毒模版片段”和RNA片段的长度都至少为1。

 
 # 输出格式 
<p>
只有一行输出，为整数M，即不是病毒的RNA片段的数目。

 
 # 提示 
<p>
输入中的RNA片段AGTGC不是病毒。
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
<tr><td>A*G?C
3
AGTC
AGTGTC
AGTGC
</td><td>    1