<span style="font-size:2rem;color:Green">**Welcome to Easy-Operation-Research**</span>

* <span style='font-size:1.5rem;color:Purple'>**The purpose of this web is to make Operation Research(OR)  a little bit more specific and funnier  : )**</span> 

* <span style='font-size:1.5rem;color:Purple'>**Readers need to read something they need, rather than read all contents in this web, which will be time-consuming and useless!**</span> 

### Some Note in 2020/9/15

> Today is rainy. But if you wear a pair of slipper, you will feel nothing upsetting.

#### Note 1: 强局部最优解与严格局部最优解的关系

如果某个解是<span style='color:Green'>**强局部最优解**</span>，那么它<span style='color:Green'>**必定是严格局部最优解**</span>；但<span style='color:Green'>**反之却不一定成立。**</span>也就是说前者是后者的充分不必要条件。

证明方式采用经典的<span style='color:Green'>**充分性证明**</span>与<span style='color:Green'>**不必要性证明**</span>。

<span style='color:Green'>**充分性证明**</span>：强局解一定是严局解

​	使用反证法：假设一个解<span style='color:Red'>**X**</span>为强局部最优解，而其不为严格局部最优解。

* 由于解<span style='color:Red'>**X**</span>不为严局解，那就意味着解<span style='color:Red'>**X**</span>的任意邻域内都存在着另外一个与<span style='color:Red'>**X**</span>具有相同函数值的解<span style='color:Red'>**Y**</span>，也就意味着解<span style='color:Red'>**X**</span>的任意邻域都至少有两个局部最优解：解<span style='color:Red'>**X**</span>与解<span style='color:Red'>**Y**</span>。

* 由于解<span style='color:Red'>**X**</span>为强局解，那么存在一个解<span style='color:Red'>**X**</span>的邻域，只存在解<span style='color:Red'>**X**</span>一个局部最优解。但这与前面的论点矛盾，所以原假设不成立。所以解<span style='color:Red'>**X**</span>为强局部最优解，其必定为严格局部最优解。

<span style='color:Green'>**不必要性证明**</span>：严局解不一定是强局解

​	使用<span style='color:Green'>**举特例**</span>的方式证明。

​	