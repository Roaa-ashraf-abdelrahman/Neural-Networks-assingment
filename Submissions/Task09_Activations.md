# Task 9 - Activation
## conclusion
- tanh makes the gradient shrink rapidly, which puts the model at high risk of vanishing gradient
- as for softsign, it also shrinks the gradient but at slower rate, still risk vanishing gradient but better than tanh
- GELU scales input instead of thresholding it, so it leads to smoother gradient, low risk of vanishing gradients
- GELU works well with transformers as transformers are very deep and it's output got large range, so GELU is suitable
- ReLU is still perferred because it is much simpler and cheaper to compute
