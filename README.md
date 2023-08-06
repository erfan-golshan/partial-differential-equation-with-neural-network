# partial-differential-equation-with-neural-network
In this project we are going to train a neural network to find the solutions of partial differential equations.

The first problem is

du/dx + du/dy = 1 + 2y + 2x , u(0,0) = 0.0

which the exact answer is

u(x,y) = x + 2*x*y

we use one-point-forward formula to approximate the differentiations and then we start the training.

Our loss function has to aspects, one of them is the difference between the two sides of the equation, and the other one is the difference from the fixed point (which in this problem is u(0,0) ).

the loss plot is

![image](https://github.com/erfan-golshan/partial-differential-equation-with-neural-network/assets/129675348/e067365c-bc42-42be-bfb1-59e4e28ce240)

and the predicted function is 

![image](https://github.com/erfan-golshan/partial-differential-equation-with-neural-network/assets/129675348/4d9270cc-a414-465a-abb2-c5167f8d9b8d)

and also the exact function is

![image](https://github.com/erfan-golshan/partial-differential-equation-with-neural-network/assets/129675348/dedb09ff-b790-43a1-9d90-9317603f19fb)

as we can see, our predicted plot and the exact function are somehow similar.

For the next part we use shuffled data.

the predicted solution with shuffledd data is

![image](https://github.com/erfan-golshan/partial-differential-equation-with-neural-network/assets/129675348/96714d65-eae9-4d04-9a9e-473fc720637b)

with the loss of

![image](https://github.com/erfan-golshan/partial-differential-equation-with-neural-network/assets/129675348/bdb38979-46fe-4400-89f2-d63b70bd96bb)










