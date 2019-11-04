# 

 
 # 题目描述 
<p>
有一个掷骰子游戏。玩家掷一个骰子（6个面，标号1到6）多次并统计点数和。玩家可以随时结束，但是至少要掷一次。如果点数和超过21，玩家就输了。当玩家结束后，庄家（庄家就是赌场老大）按一样的规则掷骰子。设玩家的点数和为Sp，庄家的点数和为Sc，玩家赢了当且仅当(Sp ≤ 21 and (Sc > 21 or Sc < Sp))。最优的庄家策略，让赌场的胜率超过了2/3。但是Andrew发现了提高他赢的概率的方法。他会和Big Man一起玩。Big Man每场游戏会押X欧元，Andrew每场押1欧元。赢家可以得到他的押注的双倍（包括他押下去的那份，即实际上只赢了一份），输的就会失去他的押注。

 
 # 输入格式 
<p>
输入包含一个数X (0 ≤ X ≤ 1000)。

 
 # 输出格式 
<p>
输出一个数字—Andrew赢的概率。精确到10-5。
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
<tr><td>1</td><td>0.345634