# 

 
 # 题目描述 
<p>
A civil engineer that has recently graduated from the Czech Technical University encountered an interesting problem and asked us for a help. The problem is more of economical than engineering nature. The engineer needs to connect several buildings with an infrastructure. Unfortunately, the investor is not the owner of all the land between these places. Therefore, some properties have to be bought first. 

 
 # 输入格式 
<p>
The input contains several scenarios. Each scenario begins with an integer number H , which specifies the size of the land, 2 H 20 . Then there are 2*H - 1 lines representing individual ``rows" of the land (always oriented as in the picture). The lines contain one non-space character for each parcel. It means the first line will contain H characters, the second line H + 1 , and so on. The longest line will be the middle one, with 2*H - 1 characters. Then the ``length" descends and the last line contains H parcels, again. 

 
 # 输出格式 
<p>
For each scenario, output one line with the sentence ``You have to buy P parcels.", where P is the minimal number of parcels that must be acquired to make all four areas connected together. 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2302/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjMwMi9wcm9ibGVtc19pbWFnZXMvMjY3OC8xNDAxLmpwZw==.jpg">
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
<tr><td>4 
    B . . C 
   . . . . C 
  . A . . C . 
 . A A . . . .
  . A . . . . 
   . . . D D 
    . . . . 
0
</td><td>You have to buy 4 parcels.</td></tr></table>