# Loss Functions

## MAE(Maen Absolute Error, mean l1 loss)

$$
\begin{aligned}

MAE(x, y) = \frac{1}{N}\sum_i^N\left\vert x_i - y_i \right\vert

\end{aligned}
$$

## MSE(Mean Squared Error, mean l2 loss)

$$
\begin{aligned}

MAE(x, y) = \frac{1}{N}\sum_i^N(x_i - y_i)^2

\end{aligned}
$$

## RMSE(Root Mean Squred Error)

$$
\begin{aligned}

RMSE(x, y) = \sqrt{\frac{1}{N}\sum_i^N(x_i - y_i)^2}

\end{aligned}
$$

## Cross Entropy

$$
\begin{aligned}

CE(x, y) = -\frac{1}{N}\sum_i^Ny_i * log(x_i)

\end{aligned}
$$