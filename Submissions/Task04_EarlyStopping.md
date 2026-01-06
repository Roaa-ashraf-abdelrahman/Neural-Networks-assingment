# Task 4 - Early Stopping
### conclusion:
- training stops at epoch number 12
- validation loss controls the decision because upon it change, we decide when to stop, if patience is three, we find the lowest validation loss, then we see the following 3 epochs, when no decrease in loss is observed, the training stops
- different optimizers affect early stopping patterns as they converge at different speeds
- early stopping halts the training to prevent overfitting when it notices increase in loss after reaching a low point, so it is a type of regulization, in a way
