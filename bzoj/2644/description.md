
# Description

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">New labyrinth attraction is open in New Lostland amusement park. The labyrinth consists of <i>n</i> rooms connected by <i>m</i> passages. Each passage is colored into some color <i>c<sub>i</sub></i>. Visitors of the labyrinth are dropped from the helicopter to the room number 1 and their goal is to get to the labyrinth exit located in the room number <i>n</i>.<br/>
<br/>
Labyrinth owners are planning to run a contest tomorrow. Several runners will be dropped to the room number 1. They will run to the room number <i>n</i> writing down colors of passages as they run through them. The contestant with the shortest sequence of colors is the winner of the contest. If there are several contestants with the same sequence length, the one with the <i>ideal path</i> is the winner. The path is the ideal path if its color sequence is the lexicographically smallest among shortest paths.<br/>
<br/>
Andrew is preparing for the contest. He took a helicopter tour above New Lostland and made a picture of the labyrinth. Your task is to help him find the ideal path from the room number 1 to the room number <i>n</i> that would allow him to win the contest. <br/>
<br/>
<b>Note</b><br/>
<br/>
A sequence (<i>a<sub>1</sub></i>, <i>a<sub>2</sub></i>, . . . , <i>a<sub>k</sub></i>) is lexicographically smaller than a sequence (<i>b<sub>1</sub></i>, <i>b<sub>2</sub></i>, . . . , <i>b<sub>k</sub></i>) if there exists i such that <i>a<sub>i</sub></i> &lt; <i>b<sub>i</sub></i>, and <i>a<sub>j</sub></i> = <i>b<sub>j</sub></i> for all <i>j</i> &lt; <i>i</i>.</span></div>
<ol>
    <li><span style="font-size: medium">给定无向图（有重边）每条边有一种颜色，边权为1，让你找到从1到n的最短路，并且 </span></li>
    <li class="alt"><span style="font-size: medium"><span class="comment">经过的边的颜色组成的序列的字典序最小。</span> </span></li>
</ol></div>

# Input

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">The first line of the input file contains integers <i>n</i> and <i>m</i> —the number of rooms and passages, respectively (2 &lt;= <i>n</i> &lt;= 100 000, 1 &lt;= <i>m</i> &lt;= 200 000). The following <i>m</i> lines describe passages, each passage is described with three integer numbers: <i>a<sub>i</sub></i>, <i>b<sub>i</sub></i>, and <i>c<sub>i</sub></i> — the numbers of rooms it connects and its color (1 &lt;= <i>a<sub>i</sub></i>, <i>b<sub>i</sub></i> &lt;= n, 1 &lt;= <i>c<sub>i</sub></i> &lt;= 10<sup>9</sup>). Each passage can be passed in either direction. Two rooms can be connected with more than one passage, there can be a passage from a room to itself. It is guaranteed that it is possible to reach the room number <i>n</i> from the room number 1.</span></div></div>

# Output

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">The first line of the output file must contain <i>k</i> — the length of the shortest path from the room number 1 to the room number <i>n</i>. The second line must contain <i>k</i> numbers — the colors of passages in the order they must be passed in the ideal path.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
1 2 1<br/>
1 3 2<br/>
3 4 3<br/>
2 3 1<br/>
2 4 4<br/>
3 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1 3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

