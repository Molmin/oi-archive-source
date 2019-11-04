# 

 
 # 题目背景 
2007年江苏省省选第二试 

 
 # 题目描述 
比较网络仅由线路和比较器构成。如图3.1所示，比较器是具有两个输入x和y以及两个输出x’和y’的一个装置，且执行下列函数：<BR>x’=min(x,y)<BR>y’=max(x,y)<BR><BR><img src="/source/joyoi/tyvj-1796/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTc5Ni9Qcm9ibGVtSW1nLzE3OTYuYm1w.bmp" border=0 align=middle><BR><BR>因为图3.1中给出的比较器的图形表示太大而不方便，所以我们将按常规把比较器画为一条垂直线，如图3.2所示。输入在左面，输出在右面，较小的输入值在输出端的上部，较大的输入值在输出端的下部。因此可以认为比较器对两个输入进行了排序。<BR>线路把一个值从一处传输到另一处，它可以把一个比较器的输出端与另一个比较器的输入端相连，在其他情况下它要么是网络的输入线，要么是网络的输出线。我们假定比较网络含n条输入线和n条输出线，需要排序的值通过输入线进入网络，由网络计算出的结果通过输出线输出。我们所说的输入序列&lt;a1,a2,a3……an&gt;和输出序列&lt;b1,b2,b3……bn&gt;分别指输入线和输出线中的值。<BR>图3.3说明了一个比较网络，它是一个由线路互相连接着的比较器的集合，我们把具有n个输入和n个输出的比较网络画成一个由n条水平线组成的图，比较器则垂直地与两条水平线相连接。需要注意的是图中的一条水平线并不是仅代表一条线路，而是连接到各个比较器上的不同线路的一个序列。每个比较器的输入端要么与网络的n条输入线路a1,a2,a3……an中的一条相连接，要么与另一个比较器的输出端相连接。类似的，每个比较器的输出端要么与网络的n条输出线路b1,b2,b3……bn中的一条相连接，要么与另一个比较器的输入端相连接。互相连接的比较器主要应满足如下要求：其互相连接所成的图中必须没有回路——如果我们沿图中一个比较器的输出端到达另一个比较器的输入端再到输出端、输入端……，如此下去，我们通过的路径必须不能回到第一个比较器，也不能两次经过同一个比较器。因此，如图3.3所示，我们画一个比较网络时可以把网络输入端画在左边，而把网络的输出端画在右边，数据从网络左边向右边移动从而通过网络。只有当同时有两个输入时，比较器才能产生输出值。<BR>对于一个固定的比较网络，一种输出输入只会产生一种输出序列，但是一种输出序列却可能对应着多种输入序列。现在已知一个固定的比较网络，和一种输出序列，要求有多少种不同的输入序列会产生这种输出序列。<BR> 

 
 # 输入格式 
输入文件的第一行是输入端和输出端的数目n和网络中比较器的数目m。<BR>接下来的m行每行有两个用空格符隔开的数字(第一个数字小于第二个数字)。这m行数据按照比较器在比较网络中从左到右出现的顺序依次说明每个比较器连接的两条水平线的编号(即水平线从上往下数处在的位置)。<BR>第m+2行是n个用空格符隔开的正整数，表示一种固定的输出序列。<BR> 

 
 # 输出格式 
输出文件只有一行，为对应于已知的输出序列的不同的输入序列的种类数。 

 
 # 提示 
1&lt;n&lt;=30<BR>1&lt;=m&lt;=10000<BR>输入序列的种类数不多于7位<BR>2007年江苏省省选第二试 
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
<tr><td>3 3
1 2
2 3
1 2
1 2 3
</td><td>6</td></tr></table>