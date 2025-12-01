
# Introduction 


Def: Artificial Neural Networks (ANNs) have revolutionized the field of machine learning and have become a cornerstone of artificial intelligence. ANNs are designed to mimic the structure and functionality of the human brain, enabling computers to learn and make decisions in a way that resembles human thinking.

Short History:ANN was first introduced in 1943 by the neurophysiologist Warren McCulloch and the mathematician Walter Pitts. However, ANN had its ups and downs. Post-1960 there was a drop in interest and excitement among researchers w.r.t neural networks with the advancement of Support Vector Machines and other powerful Machine Learning techniques that produced better accuracy and had a stronger theoretical foundation. Neural networks were complex and required tremendous computation power and time to train. However post 1990, the advancement in the field of computation (refer to Moore’s law) followed by the production of powerful GPU cards brought some interest back.

Application :ANNs are versatile, adaptive, and scalable, making them appropriate to tackle large datasets and highly complex Machine Learning tasks such as image classification (e.g., Google Images), speech recognition (e.g., Apple’s Siri), video recommendation (e.g., YouTube), or analyzing sentiments among customers (e.g. Twitter Sentiment Analyzer).

In this blog post, we will delve into the various types of artificial neural networks, exploring their unique characteristics and applications.


## 📑 Table of Contents  

- [Software Categories](#Software-Categories)  
- [What is meant by programming](#1-What-is-meant-by-programming)  


# Section 1- Perceptron
A perceptron is the earliest and simplest form of a neural network. It was introduced by Frank Rosenblatt in 1958. It is mainly used for linearly separable binary classification problems. It takes input features, find their linear combination, apply activation function (usually a step function) and make a binary classification decision

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/4305806d-ca2d-444e-8983-1b932987f6b2_1618x680.png"></a>
</p>

## Components of a Perceptron:

- Inputs: The perceptron takes several inputs (x1,x2,…,xn)
- Weights: These determine the contribution of each feature in the linear combination or final result. There is a weight corresponding to each input feature like (w1, w2,…,wn).
- Bias: A bias term (b) is added to shift the decision boundary.
- Activation Function: The perceptron uses a step function (a simple thresholding function) to determine whether the weighted sum of inputs plus the bias is above or below a certain threshold.
- Activation function: The usual activation function used in a perceptron is ‘step function’. It is a simple function which makes binary decision (0 or 1) based on the linear combination of weights and bias.
- Output: The output of a perceptron is class label (0 or 1).

The mathematical representation is:

Section 2- Feed-forward Neural Networks (FNNs)
FNNs are the simplest form of neural networks, where the information flows in one direction, from Input to output, without any loops or cycles. They consist of an input layer, one or more hidden layers, and an output layer. These networks are used for tasks like classification and regression.


Section 3- ANN (Artificial Neural Networks):
Artificial Neural Network (ANN), architecture is inspired by the biological neural network of the human brain. The network consists of interconnected layers, input, hidden, and output. Each layer contains multiple neurons that are connected to every neuron in the adjacent layer.

As data moves through the network, each connection applies a weight, and each neuron applies an activation function like ReLU, Sigmoid, or Tanh. These functions introduce non-linearity, making it possible for the network to learn from errors and make complex decisions.

During training, a technique called backpropagation is used to adjust these weights. This technique uses gradient descent to minimize a predefined loss function, aiming to make the network’s predictions as accurate as possible.ANN Use Cases for example,Customer Churn Prediction,Sales Forecasting

Section 4- Convolutional Neural Networks (CNNs)
CNNs are specialized for processing grid-like data, such as images and videos. The network uses specialized layers called convolutional layers to apply a series of filters to an input image, producing a set of feature maps.

These feature maps are then passed through pooling layers that reduce their dimensionality, making the network computationally more efficient. Finally, one or more fully connected layers perform classification.

The training process involves backpropagation, much like ANNs, but tailored to preserve the spatial hierarchy of features.

CNNs are widely used in computer vision tasks, such as image classification, object detection, and
image segmentation.




Section 5- Recurrent Neural Networks (RNNs)
RNNs are designed to handle sequential data, where the order of Inputs matters. They have recurrent connections that allow information to be passed from one step to the next. This makes them ideal for handling sequential data, as each neuron can use its internal state to remember information from previous time steps in the sequence.

While processing the data, the network takes into account both the current and previous inputs, allowing it to develop a kind of short-term memory. However, RNNs can suffer from issues like vanishing and exploding gradients, which make learning long-range dependencies in data difficult.

To address these issues, more advanced versions like Long Short-Term Memory (LSTM) and Gated Recurrent Units (GRU) networks were developed.

RNNs are used In tasks like natural language processing, speech recognition, and time series analysis.




Section 7-Long Short-Term Memory (LSTM) Networks
LSTMs are a type of RNN that addresses the vanishing gradient problem and allows for better handling of long-term dependencies In sequential data. LSTMs are particularly useful for tasks that involve complex temporal patterns.

Section 8-Gated Recurrent Units (GRUs)
Similar to LSTMs, GRUs are another type of RNN that addresses the vanishing gradient problem and improves the learning of long-range dependencies. GRUs have a simpler structure compared to LSTMs and are often used when computational efficiency is a concern.

Section 9- Deep belief networks:
Deep belief networks: Deep belief networks (DBNs) are a type of neural network that is made up of multiple stacked restricted Boltzmann machines (RBMs). RBMs are a type of probabilistic neural network that can learn to represent the probability distribution of a given data set. DBNs are often used for image classification and natural language processing tasks.

Section 10-Generative adversarial networks (GAN)
Def: Generative adversarial networks: Generative adversarial networks (GANs) are a type of neural network that are used to generate new data. They consist of two neural networks, a generator and a discriminator. The generator is responsible for generating new data, while the discriminator is responsible for distinguishing between real and generated data. GANs are often used for image generation and text generation tasks.

Def: GANs consist of two neural networks, a generator, and a discriminator, that are trained in a game-like setting. The generator tries to generate data that is indistinguishable from real data,while the discriminator tries to different ate between real and generated data. GANs are used for tasks like Image generation, style transfer, and data augmentation.

Section 11- Autoencoders
Autoencoders are used for unsupervised learning and feature learning. They consist of an encoder that maps input data to a lower-dimensional representation (latent space) and a decoder that reconstructs the original data from the latent representation. Autoencoders are used for tasks like dimensionality reduction and anomaly detection.

Section 12- Self-Organizing Maps (SOMs):
SOMs are used for clustering and visualizing high-dimensional data in lower dimensions. They use unsupervised learning to map input data onto a lower-dimensional grid, preserving the topological relationships between data points.

Section 13-Radial Basis Function Networks (RBFNS)
RBFNs are used for pattern recognition and funct on approximation. They consist of hidden neurons with radial basis functions as activated on functions.RBFNs are often used in cases where the relationships between input and output are nonlinear.

Section 14- Transfоrmers
Transfоrmers intrоduсed the transfоrmer arсhiteсture that esсhewed reсurrenсe and relied соmрletely оn an attentiоn meсhanism tо learn relatiоnshiрs between sequenсe elements based оn their glоbal signifiсanсe. Researсhers aррlied transfоrmers tо natural language рrосessing, aсhieving state-оf-the-art results in maсhine translatiоn, text сlassifiсatiоn, and language mоdeling with mоdels like Gооgle’s BERT and OрenAI’s GPT-3. The transfоrmer рaradigm made significant contributions in enabling deeр learning mоdels tо better рrосess language data [5].

Section 15- Graрh neural netwоrks
While many neural netwоrks рrосess Euсlidean data like images оr text, graрh neural netwоrks are sрeсifiсally designed tо рrосess graрh data with соmрlex relatiоnshiрs between elements. They generalize соnvоlutiоnal netwоrk aррrоaсhes like filtering tо graрh-struсtured data and learn distributed reрresentatiоns оf nоdes based оn graрh tороlоgy and nоde attributes[5].

Graрh neural netwоrks demonstrated high aссuraсy at tasks like link рrediсtiоn, nоde сlassifiсatiоn, and соmmunity deteсtiоn within netwоrks. They shоw рrоmise fоr use сases invоlving highly relatiоnal data [5].

Section 16- Deeр Q-Netwоrks:
Deeр Q-Netwоrks: Deeр Q-netwоrks (DQNs) drоve breakthrоughs in using deeр reinfоrсement learning tо master соmрlex games. DQNs emрlоy neural netwоrks as funсtiоn aррrоximatоrs tо estimate quality value (Q) funсtiоns that determine орtimal aсtiоns, maximizing exрeсted rewards. Nvidia researchers соmbined CNNs and Q-learning intо DQNs that delivered human-level gameрlay aсrоss many Atari 2600 games. DeeрMind later used DQNs tо achieve suрerhuman gameрlay in 3D games and master the game оf Gо. DQNs remain widely used within deeр reinfоrсement learning [5].

Section 17- Gaussian Prосesses:
Gaussian Prосesses: While mоst deeр learning aррrоaсhes рerfоrm disсriminative learning tо mоdel соnditiоnal рrоbabilities оf оutрuts given inрuts, Gaussian рrосesses сan рerfоrm рrоbabilistiс regressiоn mоdeling tо рrediсt соntinuоus variables direсtly. They mоdel distributiоns оver funсtiоns based оn sets оf оbservatiоns and рrоvide unсertainty estimates regarding рrediсtiоns [5].

Gaussian рrосesses are highly flexible fоr aррliсatiоns like blaсk-bоx орtimizatiоn as well as visualizing mоdel unсertainty. When соmbined with neural netwоrks in hybrid aррrоaсhes, Gaussian рrосesses enhanсe рrediсtive сaрabilities [5].

Conclusion
Artificial Neural Networks come in various types, each with its own unique characteristics and applications. In this blog post, we explored five types of ANNs: Feedforward Neural Networks, Recurrent Neural Networks, Convolutional Neural Networks, Generative Adversarial Networks, and Self-Organizing Maps. Each type has contributed significantly to different areas of machine learning and artificial intelligence, offering powerful tools for solving complex problems and advancing technology further. As research continues to evolve, we can expect even more innovative types of artificial neural networks to emerge in the future.                                         
 

# References
[How to Configure Visual Studio Code and Anaconda for Python Programming](https://mushtaqmsit.substack.com/p/how-to-configure-visual-studio-code)











































































