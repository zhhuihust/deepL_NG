## Activation function
Activation function tanh
$$a = \frac{e^z - e^{-z}}{e^z + e^{-z}}$$
<!-- $$a = \frac{a}{b+1}{\frac{a}{c}}$$ -->

ReLU activation function:
$$a = max(0,z)$$

usually ReLU is used


### 使用非线性激活函数的原因
使用线性激活函数和不使用激活函数、直接使用 Logistic 回归没有区别，那么无论神经网络有多少层，输出都是输入的线性组合，与没有隐藏层效果相当，就成了最原始的感知器了。

激活函数的导数
sigmoid 函数：
$$g(z) = \frac{1}{1+e^{-z}}$$

$$g\prime(z)=\frac{dg(z)}{dz} = \frac{1}{1+e^{-z}}(1-\frac{1}{1+e^{-z}})=g(z)(1-g(z))$$

tanh 函数：
$$g(z) = tanh(z) = \frac{e^z - e^{-z}}{e^z + e^{-z}}$$

$$g\prime(z)=\frac{dg(z)}{dz} = 1-(tanh(z))^2=1-(g(z))^2$$