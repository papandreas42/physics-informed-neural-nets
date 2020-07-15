# physics-informed-neural-nets
  We recreated Physics Informed Neural Networks (PINNs) (https://arxiv.org/pdf/1711.10561.pdf
) , knowledge obtained from the work of Dr. George Karniadakis and his team, in tensorflow 2. 
  PINNs are Deep Neural Networks (DNN) that respect any given law of physics described by general nonlinear and linear partial differential equations. PINN’s discovery is of great value, giving to simple Neural Networks any underlying physical law as prior information. This is achieved making the model differentiable with respect to all input coordinates and free parameters.
  This said, upgrading this already existing work from tensorflow 1 to tensorflow 2 is inspired by the need to be up-to date with the constantly evolving world of Machine Learning, both in implementations and new architectures but also in the “tools” used to build the ideas on, such as tensorflow packages which are broadly known in the field.
  Inspired by a trained PINN in Dr. Karniadakis work that solves Burger’s partial differential equation, we updated the code in tensorflow 2 and further implemented its architecture to solve a different partial differential equation, the 2-D Poisson, showing the robustness of their models. That said, we indeed made some changes, best believed to represent the current state of the art optimization packages. 
  The aim of our work is to present how PINNs are built and used, while outlining the process and difficulties that come along with implementing known methodologies, not written by you, to new problems. 

