## 注意点

- 观察函数性质(奇偶，单调.etc)

### 极限及其计算

#### 数列极限

##### 考法

- 定义法(先斩后奏解出极限为A)
  - 然后用递推式, 如: `$ \frac{x_n}{x_{n-1}} $` 推出 `$lim|x_n-A|=0$`

- 唯一性
  - 子列极限唯一
- 有界性
- 局部保号性
- 夹逼准则
- 数学归纳法
- 单调有界准则
  - 见递推式用 (一般)
- 归结原则 (海涅定理)
  - 洛必达 (转换为函数极限后)



#### 函数极限

##### 考法

- 定义法

- 唯一性

- 考察左右极限[*](https://raw.githubusercontent.com/OUTSHIN/Markdown_Image/master/image-20200208113705969.png)

- 局部有界性

- 局部保号性

- 夹逼准则

- 洛必达法则(存在或∞)

- 泰勒公式

- 换元法

- 无穷小运算

- 中值定理

- 等价无穷小[*](https://md-imag.oss-accelerate.aliyuncs.com/20200214185813.png)
```math
  \log _a\left( 1+x \right) \ ~\ \frac{1}{\ln a}x\ \left( a>0,a\ne 1 \right)
```

- 整体代换，反用等价无穷小[*](https://md-imag.oss-accelerate.aliyuncs.com/20200219170826.png)

- 反用洛必达法则(类似辅助函数)[*](https://md-imag.oss-accelerate.aliyuncs.com/20200219171354.png)

- 七种未定式

  - 化简

    - 有理化
    - 因式分解

  - `$\infty-\infty$`

    - 有分母，通分

    - 无分母，提取公因式或倒代换

      1. 设`$\lim_{x\rightarrow \infty} \,\,\left[ \left(x^5+7x^4+2\right)^a-x\right], b\ne 0, 求a,b的值$`

         > 同除x后移项提取公因式 [(月度测试题极限16)](https://md-imag.oss-accelerate.aliyuncs.com/20200214112526.png)

#### 连续与间断

> 左右极限存在且等于函数值

1. 闭区间
   1. 有界性最大最小值定理
   2. 零点定理
   3. 介值定理
   4. 连续函数的局部保号性
2. 开区间
   1. 开区间有界
      - 开区间连续
      - 左端点右极限 *和*  右端点左极限存在

### 一元函数微分学

#### 求导

##### 考法

- 高阶导数
  1. 分解因式
  2. 泰勒展开系数对比
- 极坐标转换为参数方程

#### 中值定理

##### 考法

- 辅助函数(求导)，罗
- f(a)-f(b)，拉[*](https://md-imag.oss-accelerate.aliyuncs.com/20200217110548.png)
- 遇到三个点，拉[*](https://md-imag.oss-accelerate.aliyuncs.com/20200217110456.png)
- 不等式证明[*](https://md-imag.oss-accelerate.aliyuncs.com/20200219094856.png)
- 证明方程根，零/罗(找辅助函数)
- f(a)=0,拉
- ≠0，柯西
- 相除，柯西

#### 泰勒定理

> 证明题用带拉格朗日余项展开式
>
> 计算题用佩亚诺(小o)余项展开式

##### 考法

- 出现高阶可导

### 不定积分

##### 凑微分

- 复杂部位求导后再凑
- 分子分母同乘或分子加项再减项[*](https://md-imag.oss-accelerate.aliyuncs.com/20200225091209.png)

##### 换元法

- 三角代换
- 根式代换[*](https://md-imag.oss-accelerate.aliyuncs.com/20200220165045.png)
- 倒代换[*](https://md-imag.oss-accelerate.aliyuncs.com/20200220164914.png)