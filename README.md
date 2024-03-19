# Deep-Learning
Algorithms code and books I read
Life sucks. 

## Regularization Techniques
1. Early Stopping
When the test error starts to grow, stop training. 

2. Weight-decay Regularization
Penal large weight

3. Injecting noise to Input
$c= \sum_{i=1}^n || f(x_i + n_i) - y_i ||^2$
where $n_i$ is a noise instance.

4. Dropout
Dropout some units randomly.

5. Small Network

6. Batch Normalization
It's not a regulariztion technique, but useful to prevent overfitting. Especially, reducing the oscillation of training errors.
