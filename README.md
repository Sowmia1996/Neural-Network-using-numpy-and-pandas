# Neural-Network-using-numpy-and-pandas
This project is for understanding how a neural network works.The code is in no way close to optimised and established libraries.Its just for understanding purpose.<br><br>I have implemented the algorithm with different hyperparamters:<br><br>
- Number of neurons in hidden layer
- type of activation:
  - sigmoid
  - tanh
  - ELU
  - RELU
  - Leaky RELU
  - softmax(for output layer)
- Different optimization algorithms
  - batch GD
  - mini-batch GD
  - SGD
<br><br>
Since GD algorithm has its own limitations and challenges like momentum or getting caught in local minima,some advanced first-order optimisation methods were implemented.<br><br>methods  like:
- SGD with momentum
- Adagrad
- Ada delta
- Adam
- RMS prop
- Nadam
And tested the  optimizers on a toy-dataset<br><br>
<br><br>Later we Will also try to modify /add code for a Multi label classifier
