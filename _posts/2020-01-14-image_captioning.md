### Sequence Models Notes 

##### Vanishing gradients with RNNs

* If the neural network is a deep neural network then the gradient will have difficult time travelling back to the initial layers. 
* Exploding gradients are easier to spot -> numerical overflow. Solution : gradient clipping
* Vanishing gradient is much harder to solve.
* GRU : Gated Recurrent Unit : The addition in  GRU in comparison with RNNs is that GRU has a memory cell and employs the cocept of gates.


