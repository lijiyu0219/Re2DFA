## Re2DFA —— Regular Expression to Deterministic Finite Automata
### 功能介绍
本程序支持根据输入的字符集以及正规表达式生成个可视化的epsilon-NFA，DFA以及最小化的DFA以及它们的显示
### 使用说明
打开程序之后最先弹出来一个界面要求输入字符集，光标自动进入文本框，这个时候需要输入正规表达式里所有可能出现的有效字符（括号和星号不算）

![](https://github.com/lijiyu0219/Re2DFA/blob/master/pictures/pic1.png)

输入完毕可以点击开始或者回车，就会弹出主界面，光标自动进入输入文本框
这个时候就可以在右边的输入框中输入正规表达式，输入框上面显示的是之前输入的字符集。程序有一定的查错功能，不知道全不全面，输入完毕后回车或者点击Generate！就会自动生成图片，支持键盘的方向键操作图片的移动，如果想查看矢量图，可以点击“高清无码”，会使用浏览器打开svg格式的矢量图，最好在此之前把浏览器先打开，这样图片会一次全部出现。

![](https://github.com/lijiyu0219/Re2DFA/blob/master/pictures/pic2.png)

如果出现了问题，程序会跳出这样的一个窗口：

![](https://github.com/lijiyu0219/Re2DFA/blob/master/pictures/pic3.png)

如果窗口处于选中状态，按下Enter键就会将它关闭，当然也可以点那个×来关闭。
