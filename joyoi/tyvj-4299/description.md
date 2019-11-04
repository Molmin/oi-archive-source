# 

 
 # 题目背景 
<p>虽然马克得到了队友的救援，但是队友的燃料已经不够了。队友们发现太空中的一种陨石可以当作燃料，而收集这种陨石的办法只有一个，就是用一块巨型的板材挡住陨石然后集中收集。但是陨石中混有杂质又无法分离，所以有的陨石甚至可能会降低燃料的纯度，价值是负数。现在面前就是一个可燃陨石带，马克只有一块板材，因此只能收集一次，但是长度可以控制。</p> 

 
 # 题目描述 
<p>与马克同行的化学家（谁是主角？）阿莱克斯沃格尔可以监视这些陨石，分析陨石含有的燃料价值v。但是由于阿莱克斯的经验是有限的，所以预判可能会出现偏差，需要不断校正。阿莱克斯发现有N块陨石连成了一条线，两两之间的距离都是1。<strong>收集陨石的总价值</strong><strong>=</strong><strong>所有收集陨石价值的最小值</strong><strong>*</strong><strong>收集陨石的区间陨石能量总和。</strong>现在要求你计算出收集陨石的最大总价值，并且为了防止燃料太纯造成不知道的后果，这一批陨石的价值的最小值必须是负数。（什么？你说如果都是负数怎么办？题目不是说的很清楚了吗，总价值当然是正数咯！宇宙的神奇可不是我们能揣摩的）。如果没有合适的方案，请输出0。</p> 

 
 # 输入格式 
<p>输入第一行一个正整数N，表示陨石的个数。</p>

<p>接下来一行N个数，表示陨石的价值v，v是绝对值小于2000的整数。</p>

<p>接下来一个正整数M，表示阿莱克斯修改预判的次数。</p>

<p>接下来M+P行。每行有两种可能：①三个数L,R,U，表示从L~R的所有陨石价值都加上U，U是绝对值小于100的整数。②一个字符Q，则输出当前的最大值和区间位置。</p> 

 
 # 输出格式 
<p>输出共P行，每行一个数表示最大价值。</p> 

 
 # 提示 
<p>对于30%的数据，1&le;N，M&le;200；</p>

<p>对于70%的数据，1&le;N&le;10<sup>4</sup>，1&le;M&le;500；</p>

<p>对于100%的数据，1&le;N，M&le;10<sup>4</sup>，Q的出现次数不超过100。</p> 
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
311 364 -362 -1739 30
29
Q
4 5 21
1 3 59
1 4 -100
3 4 -113
Q
3 4 -91
1 3 -56
1 2 -145
2 5 -31
1 5 -177
2 4 80
4 5 -40
1 4 -63
1 3 -45
3 5 -94
Q
1 3 78
1 3 -18
Q
1 5 2
1 3 137
4 5 -48
4 5 -27
3 5 139
1 5 129
1 2 -20
1 5 -73
4 5 64
2 4 173
2 4 103
Q
2 4 5
2 4 -39
Q
Q
</td><td>//311 364 -362 -1739 30 
3653639
//270 323 -516 -1931 51 
4725157
//-216 -114 -993 -2347 -291 
9296467
//-156 -54 -933 -2347 -291 
8874007
//19 397 -323 -1885 -105 
4360005
//19 363 -357 -1919 -105 
4569139
//19 363 -357 -1919 -105 
4569139
</td></tr><tr><td>6
3 1 6 4 5 2
1
Q
1 6 -4
Q
</td><td>//3 1 6 4 5 2 
0
//-1 -3 2 0 1 -2 
12
</td></tr><tr><td>20
1227 -1229 -568 -1225 -1615 -189 -1657 -529 -1724 333 -83 -557 -248 -563 -219 1039 -1949 1251 -1602 100
99
Q
11 16 -79
5 13 78
5 9 -10
1 11 -67
9 15 57
5 16 -123
Q
1 17 -124
2 11 42
12 19 60
Q
7 19 -7
10 16 38
6 10 78
13 18 -27
1 8 96
7 16 -100
1 18 61
1 17 111
11 17 -8
1 16 -135
Q
7 15 10
7 18 -161
7 11 -129
8 11 28
4 9 -19
9 17 -34
9 17 -13
1 8 -112
6 11 -83
14 19 84
1 19 -81
Q
12 16 55
Q
5 20 -51
1 11 66
1 11 -107
5 13 44
5 16 -17
14 18 -47
5 18 77
1 4 -85
13 20 -127
13 20 -27
1 11 55
10 13 -154
5 14 -26
7 13 -81
3 15 84
5 13 -154
3 15 168
3 14 -25
2 6 -26
13 19 -54
9 16 2
1 9 -31
6 11 -134
3 16 -13
1 13 -37
6 9 41
5 14 30
1 8 -22
Q
1 11 -23
Q
6 11 20
1 13 -63
12 17 -73
4 16 -28
6 15 35
1 13 -43
2 14 -19
1 13 -23
9 17 -156
7 16 -19
3 11 60
3 15 -27
6 16 -58
1 19 108
1 15 -134
9 17 -168
9 13 112
1 8 6
Q
1 17 114
1 13 77
5 11 23
4 15 43
10 13 22
4 13 130
7 12 -44
Q
1 16 64
1 11 19
4 17 66
1 10 66
2 9 -56
1 11 -32
4 20 34
Q
2 16 -57
6 18 -107
6 16 -93
1 5 93
4 15 69
1 5 22
10 19 -93
Q
</td><td>//1227 -1229 -568 -1225 -1615 -189 -1657 -529 -1724 333 -83 -557 -248 -563 -219 1039 -1949 1251 -1602 100 
22089966
//1160 -1296 -635 -1292 -1737 -311 -1779 -651 -1789 278 -217 -624 -315 -708 -364 837 -1949 1251 -1602 100 
25147947
//1036 -1378 -717 -1374 -1819 -393 -1861 -733 -1871 196 -299 -688 -379 -772 -428 773 -2013 1311 -1542 100 
28155831
//1169 -1245 -584 -1241 -1686 -182 -1757 -629 -1863 242 -339 -728 -446 -839 -495 706 -1883 1338 -1549 100 
24817940
//976 -1438 -777 -1453 -1898 -477 -2332 -1176 -2345 -221 -802 -1007 -725 -1034 -690 501 -2088 1180 -1546 100 
42979160
//976 -1438 -777 -1453 -1898 -477 -2332 -1176 -2345 -221 -802 -952 -670 -979 -635 556 -2088 1180 -1546 100 
42334285
//815 -1625 -750 -1426 -1883 -555 -2465 -1309 -2454 -494 -1075 -1105 -1031 -1005 -640 299 -2317 951 -1805 -105 
51257210
//792 -1648 -773 -1449 -1906 -578 -2488 -1332 -2477 -517 -1098 -1105 -1031 -1005 -640 299 -2317 951 -1805 -105 
52307712
//643 -1816 -908 -1612 -2069 -744 -2673 -1517 -2880 -920 -1501 -1661 -1587 -1544 -1160 -95 -2606 1059 -1697 -105 
74983680
//834 -1625 -717 -1248 -1682 -357 -2330 -1174 -2537 -555 -1136 -1319 -1201 -1387 -1003 19 -2492 1059 -1697 -105 
54512519
//951 -1564 -656 -1087 -1521 -196 -2169 -1013 -2376 -338 -985 -1155 -1037 -1223 -839 183 -2392 1093 -1663 -71 
45469528
//1066 -1506 -598 -960 -1394 -384 -2357 -1201 -2564 -619 -1266 -1436 -1318 -1504 -1120 -167 -2592 893 -1756 -71 
56816640
</td></tr></table>