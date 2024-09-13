# HomeWork 2 "Neural Networks" Course

The goal is to learn ***pytorch*** basics while MNIST processing. 
<br> Couple of activations were tested: </br>

## ReLU (Rectified Linear Unit)

### $ReLU(z) = max(0, z)$ 

<img src="pictures_and_plots/relu_pic.png" alt="ReLU plots" width="800"/>

## ELU (Exponential Linear Unit)

$$
\text{ELU}(x) =
\begin{cases}
x & \text{if } x \geq 0 \\
\alpha (\exp(x) - 1) & \text{if } x < 0
\end{cases}
$$

$\alpha$ - hyperparameter which controls value for negative inputs.

<img src="pictures_and_plots/elu_pic.png" alt="ELU plots" width="800"/>

## tanh (Hyperbolic tangent)

### $tanh(z) = \frac{2}{1 + e^{-2z}} - 1 = \frac{e^{z} - e^{-z}}{e^{z} + e^{-z}} = \frac{e^{2z} - 1}{e^{2z} + 1}$ - hyperbolic tangent
### $\frac{\partial tanh(z)}{\partial z} = 1 - tanh^{2}(z)$ - derivative

