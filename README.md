# Modelling in ANN

Deep Learning is the most exciting and powerful branch of Machine Learning. It's a technique that teaches computers to do what comes naturally to humans: learn by example. Deep learning is a key technology behind many of the technologies we are using today.

Goal is to provide an efficient system that can recoginize the correct type of cloth from a set of data containing numerous values.

## 🔨 Basic Working 

We took one of the most famous datasets, i.e., Fashion Mnist and on this dataset we splitted the data into train and test data.
After making the proper installations data is plotted so that the structure can be analysed which is then led by normalizing the data.

Flattening of dataset is done in order to convert 3D matrix in 2D after which the model is optimized using SGD(Stochastic Gradient Descent) optimizer. Performance is tested in order to seize best possible parameters. Based on the difference between the actual value and the predicted value, an error value also called Cost Function is computed and sent back through the system.

### Training ANN with Stochastic Gradient Descent

- Step-1 Randomly initialize the weights to small numbers close to 0 but not 0.
- Step-2 Input the first observation of your dataset in the input layer, each feature in one node.
- Step-3 Forward-Propagation: From left to right, the neurons are activated in a way that the impact of each neuron's activation is   limited by the weights. Propagate the activations until getting the predicted value.
- Step-4 Compare the predicted result to the actual result and measure the generated error(Cost function).
- Step-5 Back-Propagation: from right to left, the error is backpropagated. Update the weights according to how much they are responsible for the error. The learning rate decides how much we update weights.
- Step-6 Repeat step-1 to 5 and update the weights after each observation(Reinforcement Learning)
- Step-7 When the whole training set passed through the ANN, that makes and epoch. Redo more epochs.



