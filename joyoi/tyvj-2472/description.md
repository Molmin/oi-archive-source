# 

 
 # 题目描述 
<p>
The cows have taken up alphabetical jigsaw puzzles. In these puzzles

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: R and C

 
 # 输出格式 
<p>
* Lines 1..R*C: Line R*(i-1)+j describes the puzzle piece placed a row
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
<tr><td>2 3
1 c d 0 0
2 0 d b 0
3 c 0 d a
4 b a b 0
5 d 0 0 e
6 0 0 b e

INPUT DETAILS:

Describes the input puzzle although with some of the pieces rotated
compared to the sample solution.


</td><td>1 0 c d 0
3 0 d a c
5 0 0 e d
2 d b 0 0
4 a b 0 b
6 e 0 0 b

OUTPUT DETAILS:

As shown in the diagram in the task text. Other solutions (like
reflections) are possible; a grading program will check your answer.
