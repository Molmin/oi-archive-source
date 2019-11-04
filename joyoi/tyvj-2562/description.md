# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: F and R

 
 # 输出格式 
<p>
* Line 1: A single integer that is the number of new paths that must
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
<tr><td>
7 7
1 2
2 3
3 4
2 5
4 5
5 6
5 7

INPUT DETAILS:

One visualization of the paths is:
   1   2   3
   +---+---+  
       |   |
       |   |
 6 +---+---+ 4
      / 5
     / 
    / 
 7 +
</td><td>
2

OUTPUT DETAILS:

Building new paths from 1 to 6 and from 4 to 7 satisfies the conditions.
   1   2   3
   +---+---+  
   :   |   |
   :   |   |
 6 +---+---+ 4
      / 5  :
     /     :
    /      :
 7 + - - - - 
Check some of the routes:
1 - 2:  1 -> 2 and 1 -> 6 -> 5 -> 2
1 - 4:  1 -> 2 -> 3 -> 4 and 1 -> 6 -> 5 -> 4
3 - 7:  3 -> 4 -> 7 and 3 -> 2 -> 5 -> 7
Every pair of fields is, in fact, connected by two routes.

It's possible that adding some other path will also solve the problem
(like one from 6 to 7). Adding two paths, however, is the minimum.