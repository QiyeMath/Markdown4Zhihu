设  <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1">  是  <img src="https://www.zhihu.com/equation?tex=\mathbb{R}" alt="\mathbb{R}" class="ee_img tr_noresize" eeimg="1">  上的奇函数，当  <img src="https://www.zhihu.com/equation?tex=x\ge 0" alt="x\ge 0" class="ee_img tr_noresize" eeimg="1">  时， <img src="https://www.zhihu.com/equation?tex=f'(x)-\cos x<0" alt="f'(x)-\cos x<0" class="ee_img tr_noresize" eeimg="1"> ，则不等式  <img src="https://www.zhihu.com/equation?tex=f(x)<\sin x" alt="f(x)<\sin x" class="ee_img tr_noresize" eeimg="1">  的解集为\_\_\_\_\_\_

本题考察**奇函数的性质**以及**构造函数**。

---

**解题思路：**

构造函数的题一般会给一个和函数导数相关的不等式，要先移项让不等式的一边为  <img src="https://www.zhihu.com/equation?tex=0" alt="0" class="ee_img tr_noresize" eeimg="1">  再进行构造。（注意一定要根据条件里的已知的不等式来构造，而不是根据所求解集的不等式构造）

如果处理完的式子是  <img src="https://www.zhihu.com/equation?tex=h(x)<0" alt="h(x)<0" class="ee_img tr_noresize" eeimg="1"> （或者  <img src="https://www.zhihu.com/equation?tex=h(x)>0" alt="h(x)>0" class="ee_img tr_noresize" eeimg="1"> ） ，我们一般要构造一个函数  <img src="https://www.zhihu.com/equation?tex=g(x)" alt="g(x)" class="ee_img tr_noresize" eeimg="1">  使得  <img src="https://www.zhihu.com/equation?tex=g'(x)=\phi(x)h(x)" alt="g'(x)=\phi(x)h(x)" class="ee_img tr_noresize" eeimg="1">  ，其中  <img src="https://www.zhihu.com/equation?tex=\phi(x)" alt="\phi(x)" class="ee_img tr_noresize" eeimg="1">  是一个已知的函数。（在附录里有常见构造函数条件对应的构造方法）

这样的话我们就能利用题目已知的条件得到  <img src="https://www.zhihu.com/equation?tex=g'(x)" alt="g'(x)" class="ee_img tr_noresize" eeimg="1">  和  <img src="https://www.zhihu.com/equation?tex=0" alt="0" class="ee_img tr_noresize" eeimg="1">  的关系，进而得到  <img src="https://www.zhihu.com/equation?tex=g(x)" alt="g(x)" class="ee_img tr_noresize" eeimg="1">  的增减性。

再接下来，这类题目所解的不等式一般都能转化为  <img src="https://www.zhihu.com/equation?tex=g(x)<g(x_0)" alt="g(x)<g(x_0)" class="ee_img tr_noresize" eeimg="1">  （或者 <img src="https://www.zhihu.com/equation?tex=g(x)>g(x_0)" alt="g(x)>g(x_0)" class="ee_img tr_noresize" eeimg="1"> ），其中  <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1">  是常量。

最后，再结合函数的增减性求解不等式。

---

**解题过程：**

在这道题里，题目给的条件便满足  <img src="https://www.zhihu.com/equation?tex=h(x)<0" alt="h(x)<0" class="ee_img tr_noresize" eeimg="1">  的形式（其中  <img src="https://www.zhihu.com/equation?tex=h(x)=f'(x)-\cos x" alt="h(x)=f'(x)-\cos x" class="ee_img tr_noresize" eeimg="1"> ），所以不需要进行转化。

我们可以把  <img src="https://www.zhihu.com/equation?tex=\cos x" alt="\cos x" class="ee_img tr_noresize" eeimg="1">  看作是  <img src="https://www.zhihu.com/equation?tex=\sin' x" alt="\sin' x" class="ee_img tr_noresize" eeimg="1">  ，那么就可以构造出  <img src="https://www.zhihu.com/equation?tex=g(x)=f(x)-\sin x" alt="g(x)=f(x)-\sin x" class="ee_img tr_noresize" eeimg="1"> （此时  <img src="https://www.zhihu.com/equation?tex=g'(x)=f'(x)-\cos x=h(x)" alt="g'(x)=f'(x)-\cos x=h(x)" class="ee_img tr_noresize" eeimg="1"> ），那么条件自然而然的就转化为当  <img src="https://www.zhihu.com/equation?tex=x\ge 0" alt="x\ge 0" class="ee_img tr_noresize" eeimg="1">  时，  <img src="https://www.zhihu.com/equation?tex=g'(x)<0" alt="g'(x)<0" class="ee_img tr_noresize" eeimg="1">  （也就是说  <img src="https://www.zhihu.com/equation?tex=g(x)" alt="g(x)" class="ee_img tr_noresize" eeimg="1">  在  <img src="https://www.zhihu.com/equation?tex=[0,+\infty)" alt="[0,+\infty)" class="ee_img tr_noresize" eeimg="1">  上为减函数）. 而题目让我们所求的不等式的解集也可以转化为  <img src="https://www.zhihu.com/equation?tex=f(x)-\sin x<0" alt="f(x)-\sin x<0" class="ee_img tr_noresize" eeimg="1">  即  <img src="https://www.zhihu.com/equation?tex=g(x)<0" alt="g(x)<0" class="ee_img tr_noresize" eeimg="1"> .

这时候我们在用定义在  <img src="https://www.zhihu.com/equation?tex=\mathbb R" alt="\mathbb R" class="ee_img tr_noresize" eeimg="1">  上的奇函数的性质（ <img src="https://www.zhihu.com/equation?tex=f(0)=0" alt="f(0)=0" class="ee_img tr_noresize" eeimg="1"> ，证明见附录）可以得到  <img src="https://www.zhihu.com/equation?tex=g(0)=f(0)-\sin 0=0" alt="g(0)=f(0)-\sin 0=0" class="ee_img tr_noresize" eeimg="1"> .

所以题目让我们求解集的不等式可以转化为  <img src="https://www.zhihu.com/equation?tex=g(x)<g(0)" alt="g(x)<g(0)" class="ee_img tr_noresize" eeimg="1"> . 而我们又知道  <img src="https://www.zhihu.com/equation?tex=g(x)" alt="g(x)" class="ee_img tr_noresize" eeimg="1">  在  <img src="https://www.zhihu.com/equation?tex=[0,+\infty)" alt="[0,+\infty)" class="ee_img tr_noresize" eeimg="1">  为减函数，所以说不等式在非负数部分解集是  <img src="https://www.zhihu.com/equation?tex=(0,+\infty)" alt="(0,+\infty)" class="ee_img tr_noresize" eeimg="1"> . 这时候再考虑  <img src="https://www.zhihu.com/equation?tex=x<0" alt="x<0" class="ee_img tr_noresize" eeimg="1">  时， <img src="https://www.zhihu.com/equation?tex=f(x)=-f(-x)>0" alt="f(x)=-f(-x)>0" class="ee_img tr_noresize" eeimg="1">  ，所以在  <img src="https://www.zhihu.com/equation?tex=x<0" alt="x<0" class="ee_img tr_noresize" eeimg="1">  时，这个不等式是无解的。

那么综上所述，这道题的答案是  <img src="https://www.zhihu.com/equation?tex=(0,+\infty)" alt="(0,+\infty)" class="ee_img tr_noresize" eeimg="1"> .

---

**附录：**

一些常见的构造函数方式（不等式以大于  <img src="https://www.zhihu.com/equation?tex=0" alt="0" class="ee_img tr_noresize" eeimg="1">  为例，小于  <img src="https://www.zhihu.com/equation?tex=0" alt="0" class="ee_img tr_noresize" eeimg="1">  同理）：

1.  <img src="https://www.zhihu.com/equation?tex=f(x)+f'(x)>0" alt="f(x)+f'(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=e^xf(x)" alt="g(x)=e^xf(x)" class="ee_img tr_noresize" eeimg="1"> .
2.  <img src="https://www.zhihu.com/equation?tex=nf(x)+f'(x)>0" alt="nf(x)+f'(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=e^{nx}f(x)" alt="g(x)=e^{nx}f(x)" class="ee_img tr_noresize" eeimg="1"> .
3.  <img src="https://www.zhihu.com/equation?tex=f(x)-f'(x)>0" alt="f(x)-f'(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=\frac {f(x)}{e^x}" alt="g(x)=\frac {f(x)}{e^x}" class="ee_img tr_noresize" eeimg="1"> .

4.  <img src="https://www.zhihu.com/equation?tex=xf'(x)+f(x)>0" alt="xf'(x)+f(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=xf(x)" alt="g(x)=xf(x)" class="ee_img tr_noresize" eeimg="1"> .

5.  <img src="https://www.zhihu.com/equation?tex=xf'(x)+nf(x)>0" alt="xf'(x)+nf(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=x^nf(x)" alt="g(x)=x^nf(x)" class="ee_img tr_noresize" eeimg="1"> .

6.  <img src="https://www.zhihu.com/equation?tex=xf'(x)-nf(x)>0" alt="xf'(x)-nf(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=\frac{f(x)}{x^n}" alt="g(x)=\frac{f(x)}{x^n}" class="ee_img tr_noresize" eeimg="1"> .

7.  <img src="https://www.zhihu.com/equation?tex=f'(x)+g'(x)>0" alt="f'(x)+g'(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=h(x)=f(x)+g(x)" alt="h(x)=f(x)+g(x)" class="ee_img tr_noresize" eeimg="1"> .

8.  <img src="https://www.zhihu.com/equation?tex=f'(x)-g'(x)>0" alt="f'(x)-g'(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=h(x)=f(x)-g(x)" alt="h(x)=f(x)-g(x)" class="ee_img tr_noresize" eeimg="1"> .
9.  <img src="https://www.zhihu.com/equation?tex=f'(x)\sin x+f(x)\cos x>0" alt="f'(x)\sin x+f(x)\cos x>0" class="ee_img tr_noresize" eeimg="1">  或  <img src="https://www.zhihu.com/equation?tex=f'(x)\tan x+f(x)>0" alt="f'(x)\tan x+f(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=f(x)\sin x" alt="g(x)=f(x)\sin x" class="ee_img tr_noresize" eeimg="1"> .
10.  <img src="https://www.zhihu.com/equation?tex=f'(x)\sin x-f(x)\cos x>0" alt="f'(x)\sin x-f(x)\cos x>0" class="ee_img tr_noresize" eeimg="1">  或  <img src="https://www.zhihu.com/equation?tex=f'(x)\tan x-f(x)>0" alt="f'(x)\tan x-f(x)>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=\frac {f(x)}{\sin x}" alt="g(x)=\frac {f(x)}{\sin x}" class="ee_img tr_noresize" eeimg="1"> .
11.  <img src="https://www.zhihu.com/equation?tex=f'(x)\cos x-f(x)\sin x>0" alt="f'(x)\cos x-f(x)\sin x>0" class="ee_img tr_noresize" eeimg="1">  或  <img src="https://www.zhihu.com/equation?tex=f'(x)-f(x)\tan x>0" alt="f'(x)-f(x)\tan x>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=f(x)\cos x" alt="g(x)=f(x)\cos x" class="ee_img tr_noresize" eeimg="1"> .
12.  <img src="https://www.zhihu.com/equation?tex=f'(x)\cos x+f(x)\sin x>0" alt="f'(x)\cos x+f(x)\sin x>0" class="ee_img tr_noresize" eeimg="1">  或  <img src="https://www.zhihu.com/equation?tex=f'(x)+f(x)\tan x>0" alt="f'(x)+f(x)\tan x>0" class="ee_img tr_noresize" eeimg="1"> ，构造  <img src="https://www.zhihu.com/equation?tex=g(x)=\frac{f(x)}{\cos x}" alt="g(x)=\frac{f(x)}{\cos x}" class="ee_img tr_noresize" eeimg="1"> .



定义在  <img src="https://www.zhihu.com/equation?tex=\mathbb R" alt="\mathbb R" class="ee_img tr_noresize" eeimg="1">  上的奇函数的一个重要性质是它过原点。

证明：

设  <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1">  是定义在  <img src="https://www.zhihu.com/equation?tex=\mathbb R" alt="\mathbb R" class="ee_img tr_noresize" eeimg="1">  上的一个奇函数。则有，对于任意  <img src="https://www.zhihu.com/equation?tex=x\in \mathbb R" alt="x\in \mathbb R" class="ee_img tr_noresize" eeimg="1">  ，有  <img src="https://www.zhihu.com/equation?tex=-f(x)=f(-x)" alt="-f(x)=f(-x)" class="ee_img tr_noresize" eeimg="1"> . 自然这个任意的  <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">  也是包括  <img src="https://www.zhihu.com/equation?tex=0" alt="0" class="ee_img tr_noresize" eeimg="1">  在内的，所以有  <img src="https://www.zhihu.com/equation?tex=-f(0)=f(-0)" alt="-f(0)=f(-0)" class="ee_img tr_noresize" eeimg="1">  ，可得  <img src="https://www.zhihu.com/equation?tex=f(0)=0" alt="f(0)=0" class="ee_img tr_noresize" eeimg="1"> . 

