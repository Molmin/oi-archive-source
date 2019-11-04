# 

 
 # 题目描述 
鲁宾逊先生有一只宠物猴，名叫多多。这天，他们两个正沿着乡间小路散步，突然发现路边的告示牌上贴着一张小小的纸条：“欢迎免费品尝我种的花生！——熊字”。<BR>鲁宾逊先生和多多都很开心，因为花生正是他们的最爱。在告示牌背后，路边真的有一块花生田，花生植株整齐地排列成矩形网格（如图1）。有经验的多多一眼就能看出，每棵花生植株下的花生有多少。为了训练多多的算术，鲁宾逊先生说：“你先找出花生最多的植株，去采摘它的花生；然后再找出剩下的植株里花生最多的，去采摘它的花生；依此类推，不过你一定要在我限定的时间内回到路边。”<BR><img src="/source/joyoi/tyvj-1907/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkwNy8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwNDMuanBn.jpg" border=0 align=middle>我们假定多多在每个单位时间内，可以做下列四件事情中的一件：<BR>1)	从路边跳到最靠近路边（即第一行）的某棵花生植株；<BR>2)	从一棵植株跳到前后左右与之相邻的另一棵植株；<BR>3)	采摘一棵植株下的花生；<BR>4)	从最靠近路边（即第一行）的某棵花生植株跳回路边。<BR>现在给定一块花生田的大小和花生的分布，请问在限定时间内，多多最多可以采到多少个花生？注意可能只有部分植株下面长有花生，假设这些植株下的花生个数各不相同。<BR>例如在图2所示的花生田里，只有位于(2,&nbsp;5),&nbsp;(3,&nbsp;7),&nbsp;(4,&nbsp;2),&nbsp;(5,&nbsp;4)的植株下长有花生，个数分别为13,&nbsp;7,&nbsp;15,&nbsp;9。沿着图示的路线，多多在21个单位时间内，最多可以采到37个花生。 

 
 # 输入格式 
第一行包括三个整数，M,&nbsp;N和K，用空格隔开；表示花生田的大小为M&nbsp;*&nbsp;N（1&nbsp;&lt;=&nbsp;M,&nbsp;N&nbsp;&lt;=&nbsp;20），多多采花生的限定时间为K（0&nbsp;&lt;=&nbsp;K&nbsp;&lt;=&nbsp;1000）个单位时间。接下来的M行，每行包括N个非负整数，也用空格隔开；第i&nbsp;+&nbsp;1行的第j个整数Pij（0&nbsp;&lt;=&nbsp;Pij&nbsp;&lt;=&nbsp;500）表示花生田里植株(i,&nbsp;j)下花生的数目，0表示该植株下没有花生。<BR> 

 
 # 输出格式 
一行，这一行只包含一个整数，即在限定时间内，多多最多可以采到花生的个数。 
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
<tr><td>【样例输入1】

6 7 21
0 0 0 0 0 0 0
0 0 0 0 13 0 0
0 0 0 0 0 0 7
0 15 0 0 0 0 0
0 0 0 9 0 0 0
0 0 0 0 0 0 0
【样例输入2】

6 7 20
0 0 0 0 0 0 0
0 0 0 0 13 0 0
0 0 0 0 0 0 7
0 15 0 0 0 0 0
0 0 0 9 0 0 0
0 0 0 0 0 0 0

</td><td>【样例输出1】

37
【样例输出2】

28
</td></tr></table>