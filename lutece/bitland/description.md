
# Content

很久很久以前曾经有一个古老的国度叫做bitland，bitland原本是三个小的国家，and, or, xor, 他们分别由各自的君主anddy, orry, xorry统治着，后来在三个君主的协商下，合并为一个共同的国家，并由三个君主共同制定宪法，在制定法律时，需要采用某种方式来管理三个国家的人口关系，为了体现自己国家的个性，三个君主分别制定了一条规则。分别是，三个国家的人口数`and`起来必须为$0$，三个国家的人口数`or`起来并取补必须为$0$，三个国家的人口数`xor`起来并取补必须为$0$。

这个联盟维持了上百年的时间，最终还是因为三个君主利益不合的问题而发生了分裂，战争爆发了，没有人知道一共经历了多少场大大小小的战斗。但古老的羊皮卷记载着战争的一些琐碎：bitland的每一个臣民都参加拿起了武器，参加到战斗中，每一个国家都将他们的所有人口编为很多小队，为了方便管理和记录，每个小队的人数必须是$2$的方幂（别忘了他们采用2进制计数），另外在分队时还会使小队的数目尽量地少。

当两个国家爆发一场战斗，他们派出各自的人数最少的一个小队，他们的战斗没有任何战术可言，人多的一方一定会胜利，并俘虏敌方的整个小队成为自己的战斗力，并将俘虏带回自己的国家。另外如果一个小队到达另外一个国家时，那个国家已经没有任何人口，他们就会生出反叛之心，自己占领那个国家。

几亿年后，战争终于结束了，三个国家又重归于好，bitland的臣民又过上了幸福的生活，没有人再提起那场战争，你是bitland的一个考古学家，当你从祖父口中偶然得知了这场辉煌的战争，你决定要去走访bitland的每一个角落，去了解这场战争的每一个细节。第一步，你必须去了解一共发生了多少场战斗。你查找古老的羊皮卷，得知了战争开始前每个国家有多少人口，并统计到了战争结束时三个国家的人口数，你现在希望算出至少发生过多少场战争。

# Standard Input

每行分别是六个整数,$x_1$,$y_1$,$z_1$,$x_2$,$y_2$,$z_2$，分别代表战争前和战争后三个国家的人口数，每个数在`long long`范围内，输入包含多组数据，以$6$个$0$结束。

# Standard Output

一个整数，即最少一共经历了多少战争，答案保证在`long long`范围内。

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
<tr><td>1 0 0 0 0 1
0 0 0 0 0 0</td><td>1</td></tr></table>


# Constraints



# Note

初始状态符合条件：$1$ and $0$ and $0=0$, not($1$ or $0$ or $0$)$=0$, not($1$ xor $0$ xor $0$)$=0$，最少经历了一场战争，即and和xor发生一场战斗，and国家有$1$个小队，每个小队$1$人，xor国家没有人口，故and国家的小队会占领xor国家，人口数变成$0$,$0$,$1$。

# Source

