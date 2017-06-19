# 非监督学习
## 视频
<iframe height=510 width=900 src="https://d3c33hcgiwev3.cloudfront.net/01.4-V2-Introduction-UnsupervisedLearning-FairUse.8f251df0b23611e4af4203f82f647410/full/540p/index.webm?Expires=1497657600&Signature=cgy7sBQkMxLRrHbRq-gVs4VZ5Sjr3URFsglQHmqH0nsYruHsyN6ftC~NxaxZxdfbsZgjPYoHBHSWi-rtl-Sk3yiMshR6AvQTsSZEk60I9jrF9lC4RXIfRBj4bWPiB46I9mSFqQZ2PCs4cb5b0889SIiQpPqG8Xf7wei7volq2q0_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A"></iframe>
## 中文
### 监督学习样本数据集【有标记】
![监督学习样本数据集【有标记】](amWiki/images/001/01-Week1/2-Introduciton/6-监督学习数据集_有标记.png)
在这段视频中 我们要讲 第二种主要的机器学习问题 叫做无监督学习

在上一节视频中 我们已经讲过了监督学习 回想起上次的数据集 每个样本 都已经被标明为 正样本或者负样本 即良性或恶性肿瘤

因此 对于**监督学习中的每一个样本 我们已经被清楚地告知了 什么是所谓的正确答案 即它们是良性还是恶性** 在无监督学习中 我们用的数据会和监督学习里的看起来有些不一样 **在无监督学习中 没有属性或标签这一概念 也就是说所有的数据 都是一样的 没有区别**

### 非监督学习样本数据集【无标记】
![非监督学习数据集【无标记】](amWiki/images/001/01-Week1/2-Introduciton/7-非监督学习数据集_无标记.png)
所以**在无监督学习中** 我们只有一个数据集 没人告诉我们该怎么做 我们也不知道 每个数据点究竟是什么意思 相反 **它只告诉我们 现在有一个数据集 你能在其中找到某种结构吗？** 对于给定的数据集 无监督学习算法可能判定 该数据集包含两个不同的聚类 你看 这是第一个聚类 然后这是另一个聚类 你猜对了 无监督学习算法 会把这些数据分成两个不同的聚类 所以这就是所谓的聚类算法 实际上它被用在许多地方
### 聚类算法--应用举例
#### 聚类算法例子1-Google 新闻
![聚类算法例子1-Google 新闻](amWiki/images/001/01-Week1/2-Introduciton/8-聚类算法例子1-Google 新闻.png)
我们来举一个聚类算法的栗子 Google 新闻的例子 如果你还没见过这个页面的话 你可以到这个URL news.google.com 去看看 谷歌新闻每天都在干什么呢？ 他们每天会去收集 成千上万的 网络上的新闻 然后将他们分组 组成一个个新闻专题 比如 让我们来看看这里 这里的URL链接 连接着不同的 有关BP油井事故的报道 所以 让我们点击 这些URL中的一个 恩 让我们点一个 然后我们会来到这样一个网页 这是一篇来自华尔街日报的 有关……你懂的 有关BP油井泄漏事故的报道 标题为《BP杀死了Macondo》 Macondo 是个地名 就是那个漏油事故的地方 如果你从这个组里点击一个不同的URL 那么你可能会得到不同的新闻 这里是一则CNN的新闻 是一个有关BP石油泄漏的视频 如果你再点击第三个链接 又会出现不同的新闻 这边是英国卫报的报道 也是关于BP石油泄漏  
所以 谷歌新闻所做的就是 去搜索成千上万条新闻 然后自动的将他们聚合在一起 因此 有关同一主题的 新闻被显示在一起 实际上 聚类算法和无监督学习算法 也可以被用于许多其他的问题 这里我们举个它在基因组学中的应用  

#### 聚类算法例子2-基因组学
![聚类算法例子2-基因组学](amWiki/images/001/01-Week1/2-Introduciton/9-聚类算法例子2-基因组学.png)
下面是一个关于基因芯片的例子 基本的思想是 给定一组不同的个体 对于每个个体 检测它们是否拥有某个特定的基因 也就是说，你要去分析有多少基因显现出来了 因此 这些颜色 红 绿 灰 等等 它们 展示了这些不同的个体 是否拥有一个特定基因 的不同程度 然后你能做的就是 运行一个聚类算法 把不同的个体归入不同的类 或归为不同类型的人 这就是无监督学习 我们没有提前告知这个算法 这些是第一类的人 这些是第二类的人 这些是第三类的人等等 相反我们只是告诉算法 你看 这儿有一堆数据 我不知道这个数据是什么东东 我不知道里面都有些什么类型 叫什么名字 我甚至不知道都有哪些类型 但是 请问你可以自动的找到这些数据中的类型吗？ 然后自动的 按得到的类型把这些个体分类 虽然事先我并不知道哪些类型 因为对于这些数据样本来说 我们没有给算法一个 正确答案 所以 这就是无监督学习

#### 无监督学习-聚类算法在其他领域应用
![无监督学习-聚类算法在其他领域应用](amWiki/images/001/01-Week1/2-Introduciton/10-无监督学习-聚类算法在其他领域应用.png)
**无监督学习或聚类算法在其他领域也有着大量的应用** 它被**用来组织大型的计算机集群** 我有一些朋友在管理 大型数据中心 也就是 大型计算机集群 并试图 找出哪些机器趋向于 协同工作 如果你把这些机器放在一起 你就可以让你的数据中心更高效地工作 第二种应用是**用于社交网络的分析** 所以 如果可以得知 哪些朋友你用email联系的最多 或者知道你的Facebook好友 或者你Google+里的朋友 知道了这些之后 我们是否可以自动识别 哪些是很要好的朋友组 哪些仅仅是互相认识的朋友组 还有**在市场分割中的应用** 许多公司拥有庞大的客户信息数据库 那么 给你一个 客户数据集 你能否 自动找出不同的市场分割 并自动将你的客户分到不同的 细分市场中 从而有助于我在 不同的细分市场中 进行更有效的销售 这也是无监督学习 我们现在有 这些客户数据 但我们预先并不知道 有哪些细分市场 而且 对于我们数据集的某个客户 我们也不能预先知道 谁属于细分市场一 谁又属于细分市场二等等 但我们必须让这个算法自己去从数据中发现这一切 最后 事实上无监督学习也被**用于天文数据分析** 通过这些聚类算法 我们发现了许多 惊人的、有趣的 以及实用的 关于星系是如何诞生的理论 所有这些都是聚类算法的例子 而**聚类只是无监督学习的一种** 现在让我来告诉你另一种 我先来介绍一下鸡尾酒宴问题

#### 无监督学习-非聚类算法应用【鸡尾酒宴会】
![无监督学习-非聚类算法应用【鸡尾酒宴会】](amWiki/images/001/01-Week1/2-Introduciton/11-无监督学习-非聚类算法应用【鸡尾酒宴会】.png)
恩 我想你参加过鸡尾酒会的 是吧？ 嗯 想象一下 有一个宴会 有一屋子的人 大家都坐在一起 而且在同时说话 有许多声音混杂在一起 因为每个人都是在同一时间说话的 在这种情况下你很难听清楚你面前的人说的话 因此 比如有这样一个场景 宴会上只有两个人 两个人 同时说话 恩 这是个很小的鸡尾酒宴会 我们准备好了两个麦克风 把它们放在房间里 然后 因为这两个麦克风距离这两个人 的距离是不同的 每个麦克风都记录下了 来自两个人的声音的不同组合 也许A的声音 在第一个麦克风里的声音会响一点 也许B的声音 在第二个麦克风里会比较响一些 因为2个麦克风 的位置相对于 2个说话者的位置是不同的 但每个麦克风都会录到 来自两个说话者的重叠部分的声音 这里有一个 来自一个研究员录下的两个说话者的声音 让我先放给你听第一个 这是第一个麦克风录到的录音： 一 (UNO) 二 (DOS) 三 (TRES) 四 (CUATRO) 五 (CINCO) 六 (SEIS) 七 (SIETE) 八 (ocho) 九 (NUEVE) 十 (Y DIEZ) 好吧 这大概不是什么有趣的酒会…… ……在这个酒会上 有两个人 各自从1数到10 但用的是两种不同语言 你刚才听到的是 第一个麦克风的录音 这里是第二个的：一 (UNO) 二 (DOS) 三 (TRES) 四 (CUATRO) 五 (CINCO) 六 (SEIS) 七 (SIETE) 八 (ocho) 九 (NUEVE) 十 (Y DIEZ) 所以 我们能做的就是把 这两个录音输入 一种无监督学习算法中 称为“鸡尾酒会算法” 让这个算法 帮你找出其中蕴含的分类 然后这个算法 就会去听这些 录音 并且你知道 这听起​​来像 两个音频录音 被叠加在一起 所以我们才能听到这样的效果 此外 这个算法 还会分离出 这两个被 叠加到一起的 音频源 事实上 这是我们的鸡尾酒会算法的第一个输出 一 二 三 四 五 六 七 八 九 十 所以我在一个录音中 分离出了英文声音 这是第二个输出 Uno dos tres quatro cinco seis siete ocho nueve y diez 听起来不错嘛  

再举一个例子 这是另一个录音 也是在一个类似的场景下 这是第一个麦克风的录音： 一 二 三 四 五 六 七 八 九 十 OK 这个可怜的家伙从 鸡尾酒会回家了 他现在独自一人坐在屋里 对着录音机自言自语
这是第二个麦克风的录音 一 二 三 四 五 六 七 八 九 十 当你把这两个麦克风录音 送给与刚刚相同的算法处理 它所做的还是 告诉你 这听起来有 两种音频源 并且 算法说 这里是我找到的第一个音频源 一 二 三 四 五 六 七 八 九 十 恩 不是太完美 提取到了人声 但还有一点音乐没有剔除掉 这是算法的第二个输出 还好 在第二个输出中 它设法剔除掉了整个人声 只是清理了下音乐 剔除了从一到十的计数 所以 你可以看到 像这样的无监督学习算法 也许你想问 要实现这样的算法 很复杂吧？ 看起来 为了 构建这个应用程序 做这个音频处理 似乎需要写好多代码啊 或者需要链接到 一堆处理音频的Java库 貌似需要一个 非常复杂的程序 分离出音频等
![无监督学习-非聚类算法应用【鸡尾酒宴会】](amWiki/images/001/01-Week1/2-Introduciton/12-无监督学习-非聚类算法应用【鸡尾酒宴会】.png)

### 鸡尾酒宴会算法实现--svd奇异值分解算法
![鸡尾酒宴会算法实现--svd奇异值分解算法](amWiki/images/001/01-Week1/2-Introduciton/13-鸡尾酒宴会算法实现--svd奇异值分解算法.png)
实际上 要实现你刚刚听到的效果 只需要一行代码就可以了 写在这里呢 当然 研究人员 花了很长时间才想出这行代码的 ^-^ 我不是说这是一个简单的问题 但事实上 如果你 使用正确的编程环境 许多学习 算法是用很短的代码写出来的 所以这也是为什么在 这门课中我们要 使用Octave的编程环境 Octave是一个免费的 开放源码的软件 使用Octave或Matlab这类的工具 许多学习算法 都可以用几行代码就可以实现 在后续课程中 我会教你如何使用Octave 你会学到 如何在Octave中实现这些算法 或者 如果你有Matlab 你可以用它 事实上 在硅谷 很多的机器学习算法 我们都是先用Octave 写一个程序原型 因为在Octave中实现这些 学习算法的速度快得让你无法想象 在这里 每一个函数 例如 SVD 意思是奇异值分解 但这其实是解线性方程 的一个惯例 它被内置在Octave软件中了 如果你试图 在C + +或Java中做这个 将需要写N多代码 并且还要连接复杂的C + +或Java库 所以 你可以在C++或 Java或Python中 实现这个算法 只是会 更加复杂而已 在教授机器学习 将近10年后 我得出的一个经验就是 如果你使用Octave的话 会学的更快 并且如果你用 Octave作为你的学习工具 和开发原型的工具 你的学习和开发过程 会变得更快 而事实上在硅谷 很多人会这样做 他们会先用Octave 来实现这样一个学习算法原型 只有在确定 这个算法可以工作后 才开始迁移到 C++ Java或其它编译环境 事实证明 这样做 实现的算法 比你一开始就用C++ 实现的算法要快多了 所以 我知道 作为一个老师 我不能老是念叨： “在这个问题上相信我“ 但对于 那些从来没有用过这种 类似Octave的编程环境的童鞋 我还是要请你 相信我这一次 我认为 你的时间 研发时间 是你最宝贵的资源之一 当见过很多的人这样做以后 我觉得如果你也这样做 作为一个机器学习的 研究者和开发者 你会更有效率 如果你学会先用Octave开发原型 而不是先用其他的编程语言来开发
### 内嵌习题_区分监督学习和非监督学习
最后 总结一下 这里有一个问题需要你来解答 我们谈到了无监督学习 它是一种学习机制 你给算法大量的数据 要求它找出数据中 蕴含的类型结构 以下的四个例子中 哪一个 您认为是 无监督学习算法 而不是监督学习问题 对于每一个选项 在左边的复选框 选中你认为 属于无监督学习的 选项 然后按一下右下角的按钮 提交你的答案 所以 当视频暂停时 请回答幻灯片上的这个问题 恩 没忘记垃圾邮件文件夹问题吧？ 如果你已经标记过数据 那么就有垃圾邮件和 非垃圾邮件的区别 我们会将此视为一个监督学习问题 新闻故事的例子 正是我们在本课中讲到的 谷歌新闻的例子 我们介绍了你可以如何使用 聚类算法这些文章聚合在一起 所以这是无监督学习问题 市场细分的例子 我之前有说过 这也是一个无监督学习问题 因为我是要 拿到数据 然后要求 它自动发现细分市场 最后一个例子 糖尿病 这实际上就像我们 上节课讲到的乳腺癌的例子 只不过这里不是 好的或坏的癌细胞 良性或恶性肿瘤我们 现在是有糖尿病或 没有糖尿病 所以这是 有监督的学习问题 像处理那个乳腺癌的问题一样 我们会把它作为一个 有监督的学习问题来处理 好了 关于无监督学习问题 就讲这么多了 下一节课中我们 会涉及到更具体的学习算法 并开始讨论 这些算法是如何工作的 以及我们如何来实现它们
![无监督学习-非聚类算法应用【鸡尾酒宴会】](amWiki/images/001/01-Week1/2-Introduciton/15-内嵌习题_区分监督学习和非监督学习.png)

## English
英文版本，后续需要补充调整。
精力有限，此处翻译暂略，之后上传到github希望得到大家的补充以及提交到分支上。  
0:00
In this video, we'll talk about the second major type of machine learning problem, called Unsupervised Learning.
0:06
In the last video, we talked about Supervised Learning. Back then, recall data sets that look like this, where each example was labeled either as a positive or negative example, whether it was a benign or a malignant tumor.
0:20
So for each example in Supervised Learning, we were told explicitly what is the so-called right answer, whether it's benign or malignant. In Unsupervised Learning, we're given data that looks different than data that looks like this that doesn't have any labels or that all has the same label or really no labels.
0:39
So we're given the data set and we're not told what to do with it and we're not told what each data point is. Instead we're just told, here is a data set. Can you find some structure in the data? Given this data set, an Unsupervised Learning algorithm might decide that the data lives in two different clusters. And so there's one cluster
0:59
and there's a different cluster.
1:01
And yes, Supervised Learning algorithm may break these data into these two separate clusters.
1:06
So this is called a clustering algorithm. And this turns out to be used in many places.
1:11
One example where clustering is used is in Google News and if you have not seen this before, you can actually go to this URL news.google.com to take a look. What Google News does is everyday it goes and looks at tens of thousands or hundreds of thousands of new stories on the web and it groups them into cohesive news stories.
1:30
For example, let's look here.
1:33
The URLs here link to different news stories about the BP Oil Well story.
1:41
So, let's click on one of these URL's and we'll click on one of these URL's. What I'll get to is a web page like this. Here's a Wall Street Journal article about, you know, the BP Oil Well Spill stories of "BP Kills Macondo", which is a name of the spill and if you click on a different URL
2:00
from that group then you might get the different story. Here's the CNN story about a game, the BP Oil Spill,
2:07
and if you click on yet a third link, then you might get a different story. Here's the UK Guardian story about the BP Oil Spill.
2:16
So what Google News has done is look for tens of thousands of news stories and automatically cluster them together. So, the news stories that are all about the same topic get displayed together. It turns out that clustering algorithms and Unsupervised Learning algorithms are used in many other problems as well.
2:35
Here's one on understanding genomics.
2:38
Here's an example of DNA microarray data. The idea is put a group of different individuals and for each of them, you measure how much they do or do not have a certain gene. Technically you measure how much certain genes are expressed. So these colors, red, green, gray and so on, they show the degree to which different individuals do or do not have a specific gene.
3:02
And what you can do is then run a clustering algorithm to group individuals into different categories or into different types of people.
3:10
So this is Unsupervised Learning because we're not telling the algorithm in advance that these are type 1 people, those are type 2 persons, those are type 3 persons and so on and instead what were saying is yeah here's a bunch of data. I don't know what's in this data. I don't know who's and what type. I don't even know what the different types of people are, but can you automatically find structure in the data from the you automatically cluster the individuals into these types that I don't know in advance? Because we're not giving the algorithm the right answer for the examples in my data set, this is Unsupervised Learning.
3:44
Unsupervised Learning or clustering is used for a bunch of other applications.
3:48
It's used to organize large computer clusters.
3:51
I had some friends looking at large data centers, that is large computer clusters and trying to figure out which machines tend to work together and if you can put those machines together, you can make your data center work more efficiently.
4:04
This second application is on social network analysis.
4:07
So given knowledge about which friends you email the most or given your Facebook friends or your Google+ circles, can we automatically identify which are cohesive groups of friends, also which are groups of people that all know each other?
4:22
Market segmentation.
4:24
Many companies have huge databases of customer information. So, can you look at this customer data set and automatically discover market segments and automatically
4:33
group your customers into different market segments so that you can automatically and more efficiently sell or market your different market segments together?
4:44
Again, this is Unsupervised Learning because we have all this customer data, but we don't know in advance what are the market segments and for the customers in our data set, you know, we don't know in advance who is in market segment one, who is in market segment two, and so on. But we have to let the algorithm discover all this just from the data.
5:01
Finally, it turns out that Unsupervised Learning is also used for surprisingly astronomical data analysis and these clustering algorithms gives surprisingly interesting useful theories of how galaxies are formed. All of these are examples of clustering, which is just one type of Unsupervised Learning. Let me tell you about another one. I'm gonna tell you about the cocktail party problem.
5:26
So, you've been to cocktail parties before, right? Well, you can imagine there's a party, room full of people, all sitting around, all talking at the same time and there are all these overlapping voices because everyone is talking at the same time, and it is almost hard to hear the person in front of you. So maybe at a cocktail party with two people,
5:45
two people talking at the same time, and it's a somewhat small cocktail party. And we're going to put two microphones in the room so there are microphones, and because these microphones are at two different distances from the speakers, each microphone records a different combination of these two speaker voices.
6:05
Maybe speaker one is a little louder in microphone one and maybe speaker two is a little bit louder on microphone 2 because the 2 microphones are at different positions relative to the 2 speakers, but each microphone would cause an overlapping combination of both speakers' voices.
6:23
So here's an actual recording
6:26
of two speakers recorded by a researcher. Let me play for you the first, what the first microphone sounds like. One (uno), two (dos), three (tres), four (cuatro), five (cinco), six (seis), seven (siete), eight (ocho), nine (nueve), ten (y diez).
6:41
All right, maybe not the most interesting cocktail party, there's two people counting from one to ten in two languages but you know. What you just heard was the first microphone recording, here's the second recording.
6:57
Uno (one), dos (two), tres (three), cuatro (four), cinco (five), seis (six), siete (seven), ocho (eight), nueve (nine) y diez (ten). So we can do, is take these two microphone recorders and give them to an Unsupervised Learning algorithm called the cocktail party algorithm, and tell the algorithm - find structure in this data for you. And what the algorithm will do is listen to these audio recordings and say, you know it sounds like the two audio recordings are being added together or that have being summed together to produce these recordings that we had. Moreover, what the cocktail party algorithm will do is separate out these two audio sources that were being added or being summed together to form other recordings and, in fact, here's the first output of the cocktail party algorithm.
7:39
One, two, three, four, five, six, seven, eight, nine, ten.
7:47
So, I separated out the English voice in one of the recordings.
7:52
And here's the second of it. Uno, dos, tres, quatro, cinco, seis, siete, ocho, nueve y diez. Not too bad, to give you
8:03
one more example, here's another recording of another similar situation, here's the first microphone : One, two, three, four, five, six, seven, eight, nine, ten.
8:16
OK so the poor guy's gone home from the cocktail party and he 's now sitting in a room by himself talking to his radio.
8:23
Here's the second microphone recording.
8:28
One, two, three, four, five, six, seven, eight, nine, ten.
8:33
When you give these two microphone recordings to the same algorithm, what it does, is again say, you know, it sounds like there are two audio sources, and moreover,
8:42
the album says, here is the first of the audio sources I found.
8:47
One, two, three, four, five, six, seven, eight, nine, ten.
8:54
So that wasn't perfect, it got the voice, but it also got a little bit of the music in there. Then here's the second output to the algorithm.
9:10
Not too bad, in that second output it managed to get rid of the voice entirely. And just, you know, cleaned up the music, got rid of the counting from one to ten.
9:18
So you might look at an Unsupervised Learning algorithm like this and ask how complicated this is to implement this, right? It seems like in order to, you know, build this application, it seems like to do this audio processing you need to write a ton of code or maybe link into like a bunch of synthesizer Java libraries that process audio, seems like a really complicated program, to do this audio, separating out audio and so on.
9:42
It turns out the algorithm, to do what you just heard, that can be done with one line of code - shown right here.
9:50
It take researchers a long time to come up with this line of code. I'm not saying this is an easy problem, But it turns out that when you use the right programming environment, many learning algorithms can be really short programs.
10:03
So this is also why in this class we're going to use the Octave programming environment.
10:08
Octave, is free open source software, and using a tool like Octave or Matlab, many learning algorithms become just a few lines of code to implement. Later in this class, I'll just teach you a little bit about how to use Octave and you'll be implementing some of these algorithms in Octave. Or if you have Matlab you can use that too.
10:27
It turns out the Silicon Valley, for a lot of machine learning algorithms, what we do is first prototype our software in Octave because software in Octave makes it incredibly fast to implement these learning algorithms.
10:38
Here each of these functions like for example the SVD function that stands for singular value decomposition; but that turns out to be a linear algebra routine, that is just built into Octave.
10:49
If you were trying to do this in C++ or Java, this would be many many lines of code linking complex C++ or Java libraries. So, you can implement this stuff as C++ or Java or Python, it's just much more complicated to do so in those languages.
11:03
What I've seen after having taught machine learning for almost a decade now, is that, you learn much faster if you use Octave as your programming environment, and if you use Octave as your learning tool and as your prototyping tool, it'll let you learn and prototype learning algorithms much more quickly.
11:22
And in fact what many people will do to in the large Silicon Valley companies is in fact, use an algorithm like Octave to first prototype the learning algorithm, and only after you've gotten it to work, then you migrate it to C++ or Java or whatever. It turns out that by doing things this way, you can often get your algorithm to work much faster than if you were starting out in C++.
11:44
So, I know that as an instructor, I get to say "trust me on this one" only a finite number of times, but for those of you who've never used these Octave type programming environments before, I am going to ask you to trust me on this one, and say that you, you will, I think your time, your development time is one of the most valuable resources.
12:04
And having seen lots of people do this, I think you as a machine learning researcher, or machine learning developer will be much more productive if you learn to start in prototype, to start in Octave, in some other language.
12:17
Finally, to wrap up this video, I have one quick review question for you.
12:24
We talked about Unsupervised Learning, which is a learning setting where you give the algorithm a ton of data and just ask it to find structure in the data for us. Of the following four examples, which ones, which of these four do you think would will be an Unsupervised Learning algorithm as opposed to Supervised Learning problem. For each of the four check boxes on the left, check the ones for which you think Unsupervised Learning algorithm would be appropriate and then click the button on the lower right to check your answer. So when the video pauses, please answer the question on the slide.
13:01
So, hopefully, you've remembered the spam folder problem. If you have labeled data, you know, with spam and non-spam e-mail, we'd treat this as a Supervised Learning problem.
13:11
The news story example, that's exactly the Google News example that we saw in this video, we saw how you can use a clustering algorithm to cluster these articles together so that's Unsupervised Learning.
13:23
The market segmentation example I talked a little bit earlier, you can do that as an Unsupervised Learning problem because I am just gonna get my algorithm data and ask it to discover market segments automatically.
13:35
And the final example, diabetes, well, that's actually just like our breast cancer example from the last video. Only instead of, you know, good and bad cancer tumors or benign or malignant tumors we instead have diabetes or not and so we will use that as a supervised, we will solve that as a Supervised Learning problem just like we did for the breast tumor data.
13:58
So, that's it for Unsupervised Learning and in the next video, we'll delve more into specific learning algorithms and start to talk about just how these algorithms work and how we can, how you can go about implementing them.
