 # physics-informed-neural-nets
  We recreated Physics Informed Neural Networks (PINNs) (https://arxiv.org/pdf/1711.10561.pdf), developed by Dr. George Karniadakis and his team.
  
  PINNs  are Deep Neural Networks (DNN) that have special loss functions. The loss function of such models is made up of the sum of two parts, one is any loss function normaly required (like RMSE) and the other is any linear or nonlinear partial differential equation used to describe the physical phenomenon this model is trying to simulate. The resulting model respects both the underlying physical law and tne samples used to train it.
  This project updated the existing implementation from tensorflow 1 to tensorflow 2, and also used newer state of the art optimizers (like Adam).
