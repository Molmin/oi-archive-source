# 

 
 # 题目描述 
<p>
大sz最近在玩一个由星球大战改编的游戏。话说绝地武士当前共控制了N个星球。但是，西斯正在暗处悄悄地准备他们的复仇计划。绝地评议会也感觉到了这件事。于是，准备加派绝地武士到各星球防止西斯的突袭。一个星球受到攻击以后，会尽快通知到总基地。需要的时间越长的星球就需要越多绝地武士来防御。为了合理分配有限的武士，大sz需要你帮他求出每个星球各需要多少时间能够通知到总基地。

 
 # 输入格式 
<p>
第一行两个正整数N、L。接下来N-1行，总共第i行包含了三个正整数xi、yi、li，其中li表示第i个星球距离1号星球li，满足li严格递增。

 
 # 输出格式 
<p>
总共N-1行，每行一个数分别表示2到N号星球至少需要多少单位时间，总基地能够处理好数据，如果无法传到总基地则输出-1。
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
<tr><td>input1
3 1
1 2 1
2 3 2
input 2
3 3
1 2 1
2 3 2
</td><td>
output1
1
2
output2
1
1
30%的数据满足N <=20000; 
100%的数据满足2 <=N<= 2.5*10^5、0<=xi，yi，li<=2*10^9，1<=L<=2*10^9,xi<=yi． 
</td></tr></table>