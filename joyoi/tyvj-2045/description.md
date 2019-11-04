# 

 
 # 题目背景 
“扫地”杯III&nbsp;NOIP2012模拟赛&nbsp;day2&nbsp;第三题<br><br><br> 

 
 # 题目描述 
神犇zzy要出门旅游啦！！！<br>与其说是去旅游，不如说是去冒险。<br>在遥遥旅途中，zzy走到了A国，当然，他还要去到下一个国家B国，所谓环游世界嘛。<br>但是A国和B国之间是一片沙漠，并没有修建公路，而且zzy孤身独行，他为了显示大男子气概，决定一人独闯沙漠。<br>在独闯沙漠之前，zzy当然先要调查地形，据悉沙漠中有N个停靠站，分别编号为1…N，这些停靠站都建立在绿洲旁。特别的，1号停靠站就是A国的边境，zzy从1号停靠站出发；N号停靠站是B国的边境，zzy只要到达N号停靠站就认为他到达了B国。<br>zzy有一个方便携带的容积为V的背包，可以装纳体积之和不超过V的水和食物。zzy每走一单位的距离，他就要消耗一单位的水和一单位的食物，这是必须的。<br>由于停靠站建立在绿洲旁，zzy可以在停靠站上装任意多的水。<br>但是绿洲毕竟是绿洲，就没有什么食物了，所以想要食物就必须从A国买食物，再从1号停靠站进入沙漠，可以认为在1号停靠站可以得到任意多的食物。当然，zzy可以把食物存放在任意一个停靠站。<br>由于zzy孤身独行，当然了他的Money自然不紧缺，但是A国真是太XX了，连个ATM都没有，于是zzy只有手中剩下的一些钱币。<br>食物是要用钱币买的，在没办法的情况下，只能尽量的节约用钱，食用最少的食物。<br><br><br> 

 
 # 输入格式 
输入数据第一行是三个正整数N，M，V，分别表示停靠站的个数，停靠站之间的双向道路条数，以及zzy背包的容积。<br>接下来M行，每行包括三个正整数x，y，d，表示停靠站x与y之间存在一条长度为d的边。<br><br><br> 

 
 # 输出格式 
输出数据仅包含一行，输出最少食用的食物数量。题目保证zzy一定可以从A国到达B国。保证答案一定小于10^15。<br><br> 

 
 # 提示 
方案是：<br>①	从A国出来，在1号停靠站处，背包装上7单位食物和3单位水；<br>②	走到2号停靠站，背包上剩下4单位食物和0单位水，这时把1单位食物留下，把6单位水放入背包；<br>③	走回1号停靠站，背包上剩下0单位食物和3单位水，这时把7单位食物放入背包；<br>④	走到2号停靠站，背包上剩下4单位食物和0单位水，这时把留在2号停靠站的1单位食物放入背包，再把5单位水放入背包；<br>⑤	走到6号停靠站，背包上剩下0单位食物和0单位水，到达B国！<br>一共用了14单位食物。<br>而且没有更好的方案可以减少食物的使用量。<br><br>对于30%的数据，N&lt;=10，M&lt;=20，V&lt;=20；<br>对于60%的数据，N&lt;=50，M&lt;=200，V&lt;=200；<br>对于90%的数据，N&lt;=1,000，M&lt;=2,000，V&lt;=10,000；<br>对于100%的数据，N&lt;=10,000，M&lt;=20,000，V&lt;=1,000,000，任意道路的长度d&lt;=1,000,000。<br>平均分布着30%的数据，满足M=N-1。<br><br><br>FDU&nbsp;zzy<br><br><br> 
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
<tr><td>6 7 10
1 2 3
1 5 2
2 3 5
2 4 3
2 5 4
2 6 5
3 4 2


</td><td>14

</td></tr></table>