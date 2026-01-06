# Task 2 - Custom digit
## overview
- upload an image of number written on MSpaint software, the image is in the images folder
#### Did the model correctly classify the digit?
- yes it did <br>
#### If not, why? Consider distribution shift, noise, or lack of augmentation.
- the number may not be centered enough for it, line thickness too as we scale the photo down, the background must be black like the introduced images<br>
#### How does this relate to representation learning in neural networks?
- there must be enough data in each class the model trained on to be able to identify any image correctly, each class can have vareity of different positions and line thickness
