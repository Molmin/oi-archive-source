# 

 
 # 题目背景 
如果您不想看这个扯淡的背景，可以直接移步Hint，有简洁版。。。<BR><BR>一天，蓬莱の魚の形误闯了迷途森林，于是光荣地迷路了。。此时，一个白发红眼的少女出现了。。<BR>少女：你迷路了吗？<BR>蓬莱の魚の形：。。是。。<BR>少女：你叫什么名字？<BR>蓬莱の魚の形：蓬莱の魚の形。。<BR>少女（仔细打量其一番）：本来还准备帮你的，但是一想到一个妖怪鱼有这个名字。。。就让我看看你有多大本事吧！（突然从背后扇动出熊熊燃烧的翅膀）「Imperishable&nbsp;Shooting」!<BR>蓬莱の魚の形：啊啊啊～～ 

 
 # 题目描述 
蓬莱の魚の形的能力是可以事先选好一些点做好魔法阵，在对方每一波弹幕展开前可以瞬间跳跃到一个魔法阵中。但是，如果三个魔法阵在同一条直线上，就会出现干扰，而消失作用，蓬莱の魚の形当然不会犯这种低级错误。而根据蓬莱の魚の形多年玩永夜抄的经验，「Imperishable&nbsp;shooting」的弹幕是一个个多边形，而这些多边形的顶点都在蓬莱の魚の形做的魔法阵上（难道是因为这样威力更大？），然后弹幕会以鱼眼无法企及的速度散开，只要在这多边形外面，就一定会被打中。于是蓬莱の魚の形在每次多边形展开之前，会跳跃到多边形内部的魔法阵中。但是他想知道，每次他有多少个魔法阵可以选择。当然，如果蓬莱の魚の形在某一波中无论如何也躲不过，那么只好杯具地miss然后重生了（为啥这家伙也有重生的能力-&nbsp;-）。 

 
 # 输入格式 
输入格式<BR>第一行n表示蓬莱の魚の形制作了n个魔法阵。<BR>后面n行每行两个整数xi,yi，表示第i个魔法阵的坐标为(xi,yi)。（数据保证没有两个魔法阵位置相同，没有三个魔法阵在同一条直线上）<BR>然后是m表示「Imperishable&nbsp;shooting」依次有m波多边形弹幕。<BR>下面2m行每两行的第一行有一个数s，表示这一波弹幕是s边形，下面一行有s个数，表示按顺时针顺序或逆时针顺序的多边形顶点所在魔法阵的编号（编号为0到n-1，多边形可能是凹的，不确定顺时针还是逆时针）。 

 
 # 输出格式 
输出格式<BR>m行，对于每波弹幕，输出蓬莱の魚の形有多少个魔法阵可以选择。特别的，如果蓬莱の魚の形在某一波无论如何都躲不过去，这一行就输出"Miss!"（不包括引号）。 

 
 # 提示 
数据范围<BR>n&lt;=1000<BR>m&lt;=10000<BR>s&lt;=100<BR>-10000&lt;=x,y&lt;=10000<BR>提示：由于数据比较大，建议使用C++的童鞋们使用stdio来读入和输出。<BR><BR>题目描述简洁版：给出平面上n个点，保证无三点共线，再给出m个多边形（可能是凹多边形），求每个多边形内部包含的点的个数（特别的，如果结果是0的话请输出"Miss!"，不包含引号）。蓬莱の魚の形（其实还有个网名叫小小鱼。。）<BR><BR>后记：蓬莱の魚の形最终败倒在少女脚下，被她红烧，虽说死不了，但是有多么悲剧大家都明白。。。<BR> 
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
<tr><td>6
1 1
3 2
2 3
1 -1
-1 -2
-1 1
3
3
4 3 2
3
0 4 5
5
4 3 1 2 5
</td><td>1
Miss!
1
</td></tr></table>