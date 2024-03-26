# Layers

## Linear

$$
\begin{aligned}

y = xW + b

\end{aligned}
$$


```python
class Linear:
    def __init__(self, w, b):
        self.w = w
        self.b = b

        self.w_grad = None
        self.b_grad = None

    def forward(self, x):
        self.x = x
        return np.matmul(x, self.w) + self.b
    
    def backward(self, dout):
        self.dw = np.matmul(self.x.T, dout)
        self.db = dout

```