# PINN_Tutorial

### Problem Description

Suppose we have a simple partial differential equation as follows.

$$\frac{1}{2}\frac{\partial u}{\partial t}=\frac{\partial^2u}{\partial x^2},\quad u(x,0)=\sin(\pi x)$$

If we look into another equation (2), you can see this is one of the possible solutions of (1).

$$u(x,t)=e^{-2\pi^2t}\sin(\pi x)$$

Now we will use (2) to create training dataset, build custom loss function according to the concept of PINN, train our model with or without PINN concept.

### Training Data Generation

Let’s create our training data first. The sampling domain was set to be $(x,t)\in[-5,5]\times[0,0.2]$

### Reference
https://lazyjobseeker.github.io/en/posts/physics-informed-neural-network-tutorials/#training-model-with-pinn
