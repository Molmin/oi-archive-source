# 

 
 # 题目背景 
NOIP2010普及组复赛第4题<BR> 

 
 # 题目描述 
小涵很喜欢电脑游戏，这些天他正在玩一个叫做《三国》的游戏。<BR>在游戏中，小涵和计算机各执一方，组建各自的军队进行对战。游戏中共有N&nbsp;位武将（N<BR>为偶数且不小于4），任意两个武将之间有一个“默契值”，表示若此两位武将作为一对组合<BR>作战时，该组合的威力有多大。游戏开始前，所有武将都是自由的（称为自由武将，一旦某<BR>个自由武将被选中作为某方军队的一员，那么他就不再是自由武将了），换句话说，所谓的<BR>自由武将不属于任何一方。游戏开始，小涵和计算机要从自由武将中挑选武将组成自己的军<BR>队，规则如下：小涵先从自由武将中选出一个加入自己的军队，然后计算机也从自由武将中<BR>选出一个加入计算机方的军队。接下来一直按照“小涵→计算机→小涵→……”的顺序选择<BR>武将，直到所有的武将被双方均分完。然后，程序自动从双方军队中各挑出一对默契值最高<BR>的武将组合代表自己的军队进行二对二比武，拥有更高默契值的一对武将组合获胜，表示两<BR>军交战，拥有获胜武将组合的一方获胜。<BR>已知计算机一方选择武将的原则是尽量破坏对手下一步将形成的最强组合，它采取的具<BR>体策略如下：任何时刻，轮到计算机挑选时，它会尝试将对手军队中的每个武将与当前每个<BR>自由武将进行一一配对，找出所有配对中默契值最高的那对武将组合，并将该组合中的自由<BR>武将选入自己的军队。<BR>下面举例说明计算机的选将策略，例如，游戏中一共有6&nbsp;个武将，他们相互之间的默契<BR>值如下表所示<BR>武将<BR>编号<BR>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6<BR>1&nbsp;5&nbsp;28&nbsp;16&nbsp;29&nbsp;27<BR>2&nbsp;5&nbsp;23&nbsp;3&nbsp;20&nbsp;1<BR>3&nbsp;28&nbsp;23&nbsp;8&nbsp;32&nbsp;26<BR>4&nbsp;16&nbsp;3&nbsp;8&nbsp;33&nbsp;11<BR>5&nbsp;29&nbsp;20&nbsp;32&nbsp;33&nbsp;12<BR>6&nbsp;27&nbsp;1&nbsp;26&nbsp;11&nbsp;12<BR>双方选将过程如下所示：<BR>小涵&nbsp;轮到计算机时可<BR>选的自由武将<BR>计算机计算机选将说明<BR>第一轮&nbsp;5&nbsp;1&nbsp;2&nbsp;3&nbsp;4&nbsp;6&nbsp;4&nbsp;小涵手中5&nbsp;号武将与4&nbsp;号的默契值<BR>最高，所以选择4&nbsp;号<BR>第二轮&nbsp;5&nbsp;3&nbsp;1&nbsp;2&nbsp;6&nbsp;4&nbsp;1&nbsp;小涵手中的5&nbsp;号和3&nbsp;号武将与自由<BR>武将中配对可产生的最大默契值<BR>为29，是由5&nbsp;号与1&nbsp;号配对产生<BR>的，因此计算机选择1&nbsp;号<BR>第三轮&nbsp;5&nbsp;3&nbsp;6&nbsp;2&nbsp;4&nbsp;1&nbsp;2<BR>小涵想知道，如果计算机在一局游戏中始终坚持上面这个策略，那么自己有没有可能必<BR>胜？如果有，在所有可能的胜利结局中，自己那对用于比武的武将组合的默契值最大是多<BR>少？<BR>假设整个游戏过程中，对战双方任何时候均能看到自由武将队中的武将和对方军队的武<BR>将。为了简化问题，保证对于不同的武将组合，其默契值均不相同。 

 
 # 输入格式 
共N&nbsp;行。<BR>第一行为一个偶数N，表示武将的个数。<BR>第2&nbsp;行到第N&nbsp;行里，第（i+1）行有（N-i）个非负整数，每两个数之间用一个空格隔<BR>开，表示i&nbsp;号武将和i+1，i+2，……，N&nbsp;号武将之间的默契值（0&nbsp;≤&nbsp;默契值≤&nbsp;1,000,000,000）。 

 
 # 输出格式 
共1&nbsp;或2&nbsp;行。<BR>若对于给定的游戏输入，存在可以让小涵获胜的选将顺序，则输出1，并另起一行输出<BR>所有获胜的情况中，小涵最终选出的武将组合的最大默契值。<BR>如果不存在可以让小涵获胜的选将顺序，则输出0。 

 
 # 提示 
【输入输出样例1的说明】<BR>首先小涵拿走5&nbsp;号武将；计算机发现5&nbsp;号武将和剩下武将中的4&nbsp;号默契值最高，于是拿<BR>走4&nbsp;号；小涵接着拿走3&nbsp;号；计算机发现3、5&nbsp;号武将之一和剩下的武将配对的所有组合中，<BR>5&nbsp;号和1&nbsp;号默契值最高，于是拿走1&nbsp;号；小涵接着拿走2&nbsp;号；计算机最后拿走6&nbsp;号。在小涵<BR>手里的2，3，5&nbsp;号武将中，3&nbsp;号和5&nbsp;号配合最好，默契值为32，而计算机能推出的最好组合<BR>为1&nbsp;号和6&nbsp;号，默契值为27。结果为小涵胜，并且这个组合是小涵用尽所有方法能取到的<BR>最好组合。<BR>【数据范围】<BR>对于40%的数据有N≤&nbsp;10。<BR>对于70%的数据有N≤&nbsp;18。<BR>对于100%的数据有N≤&nbsp;500。NOIP2010普及组复赛——NO.4<BR>感谢徐戍 
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
<tr><td>【输入样例1】
6
5 28 16 29 27
23 3 20 1
8 32 26
33 11
12
【输入样例2】
8
42 24 10 29 27 12 58
31 8 16 26 80 6
25 3 36 11 5
33 20 17 13
15 77 9
4 50
19</td><td>输出样例1:
1
32
输出样例2:
1
77
</td></tr></table>