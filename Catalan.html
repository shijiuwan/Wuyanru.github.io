<h1>Catalan数</h1>

### 问题引入

使用 $ n $ 个相同的节点可构造多少种不同的二叉树？其中 $ 1\le n\le5000 $。

设 $ f_i $ 表示用 $ i $ 个节点构造的的二叉树形态的个数，不难发现 $ f_0=1 $,为空树。

由于非空的二叉树是由根节点、左子树、右子树组成的，考虑对左子树节点数量进行枚举，所以有：

$$
f_n=\sum\limits_{i=0}^{n-1}f_i\times f_{n-1-i}
$$
这里 $ f $ 序列就是 Catalan 序列。

### 基本模型

#### 模型 1：

给定 $ n $ 个相同的节点，求可以组成的二叉树形态总数。

一开始就已经说过了，证明略。

#### 模型 2：

长度为 $ 2n $ 的合法括号序列的形态个数。

**证明：**

记长度为 $ 2i $ 的合法括号序列形态个数为 $ h_i $。

首先当 $ n $ 为 $ 0 $ 或 $ 1 $ 时，都只有一种形态，即 $ h_0=h_1=1 $。

考虑 $ n\ge2$ 的情况，由于这是一个合法的括号序列，所以最后一个括号必定为右括号。

我们再将最后一个右括号所对应的左括号表示出来，括号序列就可以表示为如下形式：A(B)。

其中 A 与 B 必为合法的括号序列（可能为空），枚举 A 的长度，所以有：
$$
h_n=\sum\limits_{i=0}^{n-1}h_i\times h_{n-i-1}
$$
所以这是卡特兰数。

#### 模型 3：

长度为 $ n $ 的序列的出栈序列种数：

**证明：**

不难发现，对于两种不同的进出栈操作，他们的出栈序列肯定是不同的，所以出栈序列种数其实就是求合法操作数。

那什么样的操作是合法的呢？

我们将一次进栈操作看为一个左括号，一次出栈操作看为一个右括号。

那么，当进栈次数与出栈次数相同，且任何时候当前进栈次数大于等于出栈次数时，

这个出栈序列是合法的，且括号序列也是合法的。

反之也成立。

所以其实这和模型2是一样的。

#### 模型 4：

给定 $ -1 $ 与 $ 1 $ 各 $ n $ 个，问这样的序列的个数：对于每一个 $ i\in\left[1,2n\right]$,$ \sum\limits_{i=0}^{2n}a_i\ge0 $。

**证明：**

只需要让任何时候 $ 1 $ 的数量大于等于 $ -1 $ 的数量即可。

将 $ 1 $ 看作左括号， $ -1 $ 看作右括号，其实就是求合法的括号序列数，与模型2一模一样。

#### 模型 5：

一个圆上有 $ 2n $ 个点，求连 $ n $ 条线段使得任两线段之间没有交点的方案数（端点处相交也算有交点）。

#### 证明

将这 $ 2n $ 个点进行标号，枚举 $ 1 $ 号点与几号点连线，之后这个圆就被分为了两个圆弧。

也可以将其看成一个括号序列，与前面的相同。

### 问题扩展

使用 $ n $ 个相同的节点可构造多少种不同的二叉树？其中 $ 1\le n\le10^5 $。

显然，如果利用上述公式进行计算，时间复杂度为 $ O\left(n^2\right) $,无法接受。

定理一：
$$
Catalan_n=C_{2n}^n-C_{2n}^{n+1}
$$
证明：

使用模型 $ 4 $,考虑求出合法方案数。

首先我们知道 $ 1 $ 与 $ -1 $ 各有 $ n $ 个，我们先将这 $ n $ 个 $ 1 $ 插入 $ 2n $ 个空中，总方案数（可能不合法）即为 $ C_{2n}^n $。

令构造出的序列前 $ i $ 个数和为 $ s_i $,则对于一个不合法的序列，总能找到一个 $ k $,使得 $ k\le2\times n$ 且 $ s_i=-1 $。

对于每一个不合法的序列，我们令 $ p $ 为最小的使得 $ s_p=-1 $ 的位置，接下来，让这个序列中前 $ p $ 个数字翻转，也就是 $ 1 $ 变成 $ -1 $,$ -1 $ 变成 $ 1 $。

翻转后的序列恰好有 $ n+1 $ 个 $ 1 $ 与 $ n-1 $ 个 $ -1 $,每一个这样的序列又恰好与不合法的序列一一对应，所以不合法的序列恰好就有 $ C_{2n}^{n+1} $ 个。
$$
\therefore Catalan_n=C_{2n}^n-C_{2n}^{n+1}
$$


定理二：
$$
Catalan_n=\dfrac{C_{2n}^n}{n+1}
$$
证明：

考虑使用定理一进行推导：
$$
Catalan_n=C_{2n}^n-C_{2n}^{n+1}
$$

$$
=\dfrac{\left(2n\right)!}{n!\times n!}-\dfrac{\left(2n\right)!}{\left(n+1\right)!\times\left(n-1\right)!}
$$

$$
=\dfrac{1}{n+1}\times\left(\dfrac{\left(2n\right)!\times\left(n+1\right)}{n!\times n!}-\dfrac{\left(2n\right)!\times\left(n+1\right)}{\left(n+1\right)!\times\left(n-1\right)!}\right)
$$

$$
=\dfrac{1}{n+1}\times\left(\dfrac{\left(2n\right)!\times\left(n+1\right)}{n!\times n!}-\dfrac{\left(2n\right)!}{n!\times\left(n-1\right)!}\right)
$$

$$
=\dfrac{1}{n+1}\times\left(\dfrac{\left(2n\right)!\times\left(n+1\right)}{n!\times n!}-\dfrac{\left(2n\right)!\times n}{n!\times n!}\right)
$$

$$
=\dfrac{1}{n+1}\times\left(\dfrac{\left(2n\right)!\times\left(n+1\right)}{n!\times n!}-\dfrac{\left(2n\right)!\times n}{n!\times n!}\right)
$$

$$
=\dfrac{1}{n+1}\times\dfrac{\left(2n\right)!}{n!\times n!}
$$

$$
=\dfrac{1}{n+1}\times C_{2n}^n
$$

$$
\therefore Catalan_n=\dfrac{C_{2n}^n}{n+1}
$$

他的另一种形式是：
$$
\therefore Catalan_n=\dfrac{\left(2n\right)!}{n!\times n! \times\left(n+1\right)}
$$

$$
=\dfrac{\left(2n\right)!}{\left(n+1\right)!\times n!}
$$

$$
=\dfrac{\prod\limits_{i=n+2}^{2n}i}{\prod\limits_{i=1}^ni}
$$



定理三：
$$
Catalan_n=\dfrac{4n-2}{n+1}\times Catalan_{n-1}
$$
证明：

考虑使用定理二：
$$
Catalan_n=\dfrac{C_{2n}^n}{n+1}
$$

$$
=\dfrac{1}{n+1}\times\dfrac{\left(2n\right)!}{n!\times n!}
$$

$$
=\dfrac{1}{n+1}\times\dfrac{\left(2n-2\right)!\times \left(2n-1\right)\times\left(2n\right)}{\left(n-1\right)!\times\left(n-1\right)!\times n^2}
$$

$$
=\dfrac{1}{n+1}\times\dfrac{\left(2n-1\right)\times\left(2n\right)}{n}\times\dfrac{1}{n}\times\dfrac{\left(2n-2\right)!}{\left(n-1\right)!\times\left(n-1\right)!}
$$

$$
=\dfrac{1}{n+1}\times\dfrac{2\left(2n-1\right)}{n}\times C_{2n-2}^{n-1}
$$

$$
=\dfrac{4n-2}{n+1}\times\dfrac{C_{2n-2}^{n-1}}{n}
$$

$$
\therefore Catalan_n=\dfrac{4n-2}{n+1}\times Catalan_{n-1}
$$

注：上述证明参考自：

[Catalan通项公式的推导](https://www.136.la/shida/show-228451.html)

[n对括号的匹配方式以及Catalan数通项公式的推导](https://www.cnblogs.com/suijie/p/3989352.html)

[【知识总结】卡特兰数 (Catalan Number) 公式的推导](https://www.cnblogs.com/zyt1253679098/p/9190217.html)

### 例题

[洛谷P1044栈](https://luogu.com.cn/problem/P1044)

与模型三一样，证明略。

[洛谷P2532树屋阶梯](https://www.luogu.com.cn/problem/P2532)

不难发现，由于填充物体呈楼梯状，所以每摆放一份钢材，必有一行和一列被填满。

给出 $ n=4 $ 时第一次放钢材的方案，供大家理解：

![](https://z3.ax1x.com/2021/10/21/5yVxXV.png)

![](https://z3.ax1x.com/2021/10/21/5yZ97F.png)

![](https://z3.ax1x.com/2021/10/21/5yZp0U.png)

![](https://z3.ax1x.com/2021/10/21/5yZSmT.png)

摆放钢材后这个楼梯形状的物品便被分为了两个楼梯，故这是一个 Catalan 数列。

注意：本题没有模，所以需要使用高精。

[洛谷P1641生成字符串](https://www.luogu.com.cn/problem/P1641)

与模型 $ 4 $ 一样，证明略。

[洛谷P3200有趣的数列](https://luogu.com.cn/problem/P3200)

首先我们对题意进行转化，不妨将整个序列拆成两个，一个由原下标为奇数的组成，另一个由原下标为偶数的组成。

显然，这两个序列都是递增的。

那么，题意就可以转化为：对于 $ 1 $ 至 $ 2n $ 中的每个正整数，要么将其放到奇数序列的当前最后一个的后面，要么将其放到偶数序列当前最后一个的后面。

现在我们还有一个条件：就是奇数序列对应数字比偶数序列对应数字小。

这该怎么办呢？其实我们再将这个条件进行转化：

在任意时候，偶数序列数字个数都比奇数序列数字个数多。

所以，当序列长度为 $ 2n $ 时，答案即为 $ Catalan_n $。

本题还有一个难点，就是没有保证模数是质数。实际上，我们只要求出 $ 2\sim 2n $ 中，每个正整数的质因数及个数，再利用公式：
$$
=\dfrac{\prod\limits_{i=n+2}^{2n}i}{\prod\limits_{i=1}^ni}
$$
即可计算答案。

注：此题转化题意部分主要受[题解 P3200[HNOI2009]有趣的数列](https://www.luogu.com.cn/blog/zwq/solution-p3200)启发。
