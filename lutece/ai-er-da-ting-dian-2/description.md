
# Content

（剧情提要：请看上题）

阿塔尼斯的新式矩形能量场成功的研制出来了。但是实验过程中却发现了一个巨大的问题，一股神秘的东方力量影响了新式能量场，两个能量场互相覆盖的区域将会互相抵消，变回无能量场区。

有趣的是，如果这个区域被第三个能量场覆盖，它将仍是有效的能量场区，当然如果有第四个能量场，那么就会和第三个能量场抵消，又变成无能量场区……也就是说，一个能量场将会把它范围内的能量场区变为非能量场区，把非能量场区变为能量场区。

现在，阿塔尼斯正在建造一些能量场，你需要知道某些时刻某个坐标点上是否是有效的能量场区。

# Standard Input

（注意能量场形式与上题的不同）

本题有多组数据。第一行一个正整数T（T<=10）表示数据的组数。

每组数据第一行一个正整数N(N<=50000)，表示操作的次数。

接下来N行形容按时间顺序进行的N次操作，每行可能有两种形式：

1、一个大写字母C和四个正整数   C x1 y1 x2 y2 (1 <= x1 <= x2 <= 1000, 1 <= y1 <= y2 <= 1000) 表示以(x1,y1)为左下角(x2,y2)为右上角建造一个平行坐标轴的矩形能量场（包括边界）。

2、一个大写字母Q和两个正整数 Q x y (1 <= x, y <= 1000) 表示询问坐标(x,y)是否是有效的能量场区。

# Standard Output

对于每个询问输出一行一个整数。如果是有效的能量场区输出1，否则输出0。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1
10
C 2 1 2 2
Q 2 2
C 2 1 2 1
Q 1 1
C 1 1 2 1
C 1 2 1 2
C 1 1 2 2
Q 1 1
C 1 1 2 1
Q 2 1</td><td>1
0
0
1
</td></tr></table>


# Constraints



# Note



# Source

