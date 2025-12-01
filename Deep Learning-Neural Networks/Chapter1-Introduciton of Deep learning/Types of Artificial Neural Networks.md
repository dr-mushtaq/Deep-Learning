
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

# **Types of neural networks**
   

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/30a6865d-3c65-43bd-8e4f-e83470dafe95_630x284.jpg"></a>
</p>

So a lot of the value creation through neural networks has been through cleverly selecting what should be x and what should be y for your particular problem, and then fitting this supervised learning component into often a bigger system such as an autonomous vehicle. It turns out that slightly different types of neural networks are useful for different applications.


For example, in the real estate application. we use a universally standard neural network architecture, right? Maybe for real estate and online advertising might be a relatively standard neural network, like the one that we saw.

For image applications, we’ll often use convolutional neural networks, often abbreviated CNN. And for sequence data.

So for example, audio has a temporal component, right? Audio is played out over time, so audio is most naturally represented as a one-dimensional time series or as a one-dimensional temporal sequence. And so for sequence data, you often use an RNN, a recurrent neural network.

Language, English and Chinese, the alphabets or the words come one at a time. So language is also most naturally represented as sequence data. And so more complex versions of RNNs are often used for these applications.

And then, for more complex applications, like autonomous driving, where you have an image, that might suggest more of a CNN, convolution neural network, structure and radar info which is something quite different. You might end up with a more custom, or some more complex, hybrid neural network architecture.

So, just to be a bit more concrete about what are the standard CNN and RNN architectures. So in the literature you might have seen pictures like this. So that’s a standard neural net. You might have seen pictures like this. Well this is an example of a Convolutional Neural Network, and we’ll see in a later course exactly what this picture means and how can you implement this. But convolutional networks are often used for image data. And you might also have seen pictures like this. And you’ll learn how to implement this in a later course. Recurrent neural networks are very good for this type of one-dimensional sequence data that has maybe a temporal component.

# Applications of machine learning to both Structured Data and Unstructured Data.

## Structured Data

You might also have heard about applications of machine learning to both Structured Data and Unstructured Data. Here’s what the terms mean. Structured Data means basically databases of data. So, for example, in housing price prediction, you might have a database or the column that tells you the size and the number of bedrooms. So, this is structured data, or in predicting whether or not a user will click on an ad, you might have information about the user, such as the age, some information about the ad, and then labels why that you’re trying to predict. So that’s structured data, meaning that each of the features, such as size of the house, the number of bedrooms, or the age of a user, has a very well defined meaning.

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/4444.jpg"></a>
</p>

# unstructured data

In contrast, unstructured data refers to things like audio, raw audio, or images where you might want to recognize what’s in the image or text. Here the features might be the pixel values in an image or the individual words in a piece of text. Historically, it has been much harder for computers to make sense of unstructured data compared to structured data. And in fact the human race has evolved to be very good at understanding audio cues as well as images. And then text was a more recent invention, but people are just really good at interpreting unstructured data. And so one of the most exciting things about the rise of neural networks is that, thanks to deep learning, thanks to neural networks, computers are now much better at interpreting unstructured data as well compared to just a few years ago. And this creates opportunities for many new exciting applications that use speech recognition, image recognition, natural language processing on text, much more than was possible even just two or three years ago. I think because people have a natural empathy to understanding unstructured data, you might hear about neural network successes on unstructured data more in the media because it’s just cool when the neural network recognizes a cat. We all like that, and we all know what that means. But it turns out that a lot of short term economic value that neural networks are creating has also been on structured data, such as much better advertising systems, much better profit recommendations, and just a much better ability to process the giant databases that many companies have to make accurate predictions from them. But as you think through applications of neural networks within your own team I hope you find both uses for them in both structured and unstructured data. So neural networks have transformed supervised learning and are creating tremendous economic value. It turns out though, that the basic technical ideas behind neural networks have mostly been around, sometimes for many decades. So why is it, then, that they’re only just now taking off and working so well? .

Please Follow and Subscribe                                           
 

# References
[How to Configure Visual Studio Code and Anaconda for Python Programming](https://mushtaqmsit.substack.com/p/how-to-configure-visual-studio-code)










































































