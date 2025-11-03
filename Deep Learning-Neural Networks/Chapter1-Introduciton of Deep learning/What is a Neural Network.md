
# Description:
This blog post aims to provide a basic understanding of neural networks, a fundamental concept in the field of artificial intelligence and machine learning. Starting from the basics, we will explore the structure, functioning, and applications of neural networks. Whether you are a beginner or a professional, this guide will equip you with the knowledge to grasp the core concepts and unleash the potential of neural networks.

## 📑 Table of Contents  

- [Definition of Neural Networks](#definition-of-neural-networks)  
- [Definition of Deep Learning](#definition-of-deep-learning)  
- [Why use Deep Learning](#Why-use-Deep-Learning)  
- [Difference between Deep Learning and Machine Learning](#Difference-between-Deep-Learning-and-Machine-Learning)  
- [Applications](#applications)  


## **Definition of neural networks** 
**Def:** Neural networks, also called artificial neural networks (ANNs) or simulated neural networks (SNNs), are a subset of machine learning and are the backbone of deep learning algorithms. They are called “neural” because they mimic how neurons in the brain signal one another. A neural network is a type of machine-learning algorithm that is inspired by the human brain. It is a network of interconnected nodes, or artificial neurons, that learn to recognize patterns in data. Neural networks are used in a wide variety of applications, including image recognition, natural language processing, and speech recognition.

**Def:** Artificial Neural Networks (ANNs) are computational models inspired by the structure and functioning of biological neural networks in the human brain.ANNs consist of interconnected nodes, or "neurons," that process and transmit information.

## **Definition of Deep learning**

Deep learning is a subfield of machine learning that has gained significant attention in recent years due to its ability to tackle complex problems with large amounts of data. The motivation behind deep learning stems from the desire to replicate the human mind’s ability to learn and make decisions.

**Def:**  The term, Deep Learning, refers to training Neural Networks, sometimes very large Neural Networks.

**Def:** Deep learning refers to the process of involving a system that thinks and learns exactly like humans using an artificial neural network

**Def**: Deep learning is a subset of machine learning that uses artificial neural networks to learn from data. the “deep” in deep learning refers to the depth of layers in a neural network. 

 **Def:**  A neural network of more than three layers, including the inputs and the output, can be considered a deep-learning algorithm. 

**Def:** Deep learning is a subcategory of machine learning that uses artificial neural networks to process large amounts of data. It enables machines to learn complex patterns and make decisions based on this data.

**Def:** Deep learning is a subset of machine learning that focuses on building and training neural networks with multiple layers. These neural networks are inspired by the structure and function of the human brain, with each layer processing and transforming data in a hierarchical manner. Deep learning algorithms learn from vast amounts of labeled data to make predictions or decisions.
Application:Deeр learning underрins tоday’s raрid advanсes in areas like соmрuter visiоn, sрeeсh reсоgnitiоn, natural language рrосessing, and artifiсial intelligenсe.

## **Why use Deep Learning**

Deep learning is particularly effective for analyzing massive, complex data, such as images, videos or text. It excels in fields such as facial recognition, machine translation and autonomous driving.

## **Difference between Deep Learning and Machine Learning**

Deep learning and machine learning are both subfields of artificial intelligence (AI), but they differ significantly in their approach and capabilities. Here’s a breakdown of their key differences:

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/Untitled.png"></a>
</p>


1. **Data Dependence**:

Machine Learning: Generally performs well with structured, labeled data. It requires features to be explicitly engineered by humans. While it can handle some unstructured data, its performance is often limited. 1, 2

Deep Learning: Thrives on large amounts of unstructured data. It automatically learns features from raw data, eliminating the need for manual feature engineering. This allows it to handle complex patterns and relationships that traditional machine learning struggles with. 1, 2

2. **Algorithm Complexity**:

Machine Learning: Employs relatively simpler algorithms. Examples include linear regression, support vector machines (SVMs), decision trees, and random forests. 3

Deep Learning: Uses complex, multi-layered artificial neural networks. These networks have many layers (hence “deep”), allowing them to learn intricate hierarchical representations of data. Convolutional Neural Networks (CNNs) for image processing and Recurrent Neural Networks (RNNs) for sequential data are prime examples. 3

3. **Feature Extraction**:

Machine Learning: Requires manual feature extraction. Data scientists must carefully select and engineer relevant features from the raw data before training the model. This is a time-consuming and often challenging process. 4

Deep Learning: Automatically learns features through multiple layers of the neural network. This eliminates the need for manual feature engineering, making it more efficient for complex data. 4

4. **Computational Power**:

Machine Learning: Can often be trained on relatively modest computational resources.

Deep Learning: Demands significantly more computational power due to the complexity of its algorithms and the large datasets it processes. This often requires specialized hardware like GPUs or TPUs. 5

5. **Interpretability**:

Machine Learning: Generally more interpretable. It’s often easier to understand how a simpler machine learning model arrives at its predictions.

Deep Learning: Often considered a “black box.” The intricate workings of deep neural networks can be difficult to interpret, making it challenging to understand why a model makes a specific prediction. 4

In short: Deep learning is a specialized subset of machine learning. Machine learning is suitable for simpler tasks with structured data, while deep learning excels at complex tasks with large amounts of unstructured data, but requires significantly more computational resources. The choice between them depends on the specific problem and available resources.

## **History of Deep learning**
The first ANN was proposed in 1944, but it has become very popular in recent years. Deep learning was introduced in the early 50s but it became popular in recent years due to the increase in AI-oriented applications and the data that is being generated by the companies. While classical machine learning algorithms fell short of analyzing big data, artificial neural networks performed well on big data. The history of deep learning can be traced back to the early days of artificial intelligence (AI). In 1943, **Warren McCulloch and Walter Pitts** created a mathematical model of neurons in the brain, which was the first artificial neural network.

- In the 1950s, **Frank Rosenblatt developed the perceptron**, a simple two-layer neural network that could be trained to recognize patterns. However, the perceptron had limitations, and it was not until the 1980s that neural networks began to be used more widely.

- In the 1980s, **Geoffrey Hinton** and others developed a new type of neural network called the **backpropagation algorithm**. Backpropagation allowed neural networks to learn more complex patterns, and it led to a renewed interest in neural networks.

- In the 1990s, deep learning research continued, but it was still a relatively niche field. However, in the early 2000s, there were a number of breakthroughs that led to a resurgence of interest in deep learning.

- One of the most important breakthroughs was the development of the  **convolutional neural network (CNN)**. CNNs are a type of neural network that is specifically designed for image processing. They have been used to achieve state-of-the-art results in a variety of image recognition tasks, such as face recognition and object detection.

- Another important breakthrough was the development of the  **recurrent neural network (RNN) **. RNNs are a type of neural network that is specifically designed for processing sequential data. They have been used to achieve state-of-the-art results in a variety of natural language processing tasks, such as machine translation and speech recognition.

In the past decade, deep learning has made significant progress in a wide variety of tasks, including image recognition, natural language processing, speech recognition, and machine translation. It is now one of the most active and promising areas of research in AI.

Here are some of the major milestones in the history of deep learning:

- 1943: Warren McCulloch and Walter Pitts create a mathematical model of neurons in the brain.

- 1958: Frank Rosenblatt develops the perceptron, a simple two-layer neural network that can be trained to recognize patterns.

- 1986: Geoffrey Hinton and others develop the backpropagation algorithm, which allows neural networks to learn more complex patterns.

- 1998: Yann LeCun et al. develop the LeNet-5 CNN, which achieves state-of-the-art results in handwritten digit recognition.

- 2006: Geoffrey Hinton et al. develop the Deep Belief Network, which is a type of neural network that can be pre-trained on a large amount of unlabeled data.

- 2012: Alex Krizhevsky et al. develop the AlexNet CNN, which achieves state-of-the-art results in image classification.

- 2014: Ilya Sutskever et al. develop the Transformer, a new type of neural network that is specifically designed for natural language processing tasks.

- 2015: Google Translate uses deep learning to achieve human-level performance in machine translation.

- 2016: AlphaGo defeats a professional Go player using deep learning.

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/39660106-7d4b-4ebf-b8fa-756ac0385194_630x638.jpg"></a>
</p>

## **How does the Biological and Artificial Neuron work?**

So, when you think about mimicking the brain while one of the human brain does tell me same things, right? The brain can learn to see process images than to hear, learn to process our sense of touch. We can, you know, learn to do math, learn to do calculus, and the brain does so many different and amazing things. It seems like if you want to mimic the brain it seems like you have to write lots of different pieces of software to mimic all of these different fascinating, amazing things that the brain tell us, but does is this fascinating hypothesis that the way the brain does all of these different things is not worth like a thousand different programs, but instead, the way the brain does it is worth just a single learning algorithm.

The brain is the most complex part of the human body and researchers are still uncovering its working. To better understand the Brain let’s consider a simple examples.

**Example 1**

Imagine a ball coming towards us. What would be our first reaction mostly likely we will our hands to catch the ball. Behind the scene, this can be translated into input and output. our eyes sense the incoming ball and sent input signals to our brains. The brain receives these signals, analyzes them, and generates the output reaction of moving our hand to catch the ball.

In biological term, brain cells have perceptrons or receivers known as dendrites that receive electrical singal as input data from out sensory organs such as the eyes, nose,skin etc. The brain cells analyze these signals and respond by releasing reachtion singnals through axon terminals as output data.

**Example 2**

Let me explain a scenario when you touch a hot object with your hand, you would feel the pain and remove the hand immediately. This action and reaction are done within a fraction of a second. Have you ever got a feeling that how this is happening? Well, they are trillions of neurons connected in the body when you touch a hot object the electrical impulse will travel from the neurons in your hand to the neurons in your brain. Then the decision is taken and immediately electrical impulse travels back to the neurons in hand instructing to remove it.

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/ecfb8f31-e792-4e78-8b5c-bd4c0fc0ee4f_630x356.jpg"></a>
</p>

This is just a hypothesis but let me share with you some of the evidence for this. This part of the brain, that little red part of the brain, is your auditory cortex and the way you’re understanding my voice now is your ear is taking the sound signal and routing the sound signal to your auditory cortex and that’s what’s allowing you to understand my words.

Neuroscientists have done the following fascinating experiments where you cut the wire from the ears to the auditory cortex and you re-wire, in this case an animal’s brain, so that the signal from the eyes to the optic nerve eventually gets routed to the auditory cortex. If you do this it turns out, the auditory cortex will learn to see. And this is in every single sense of the word see as we know it. So, if you do this to the animals, the animals can perform visual discrimination task and as they can look at images and make appropriate decisions based on the images and they’re doing it with that piece of brain tissue.

**Neuro-rewiring experiments 2**

Here’s another example. That red piece of brain tissue is your somatosensory cortex. That’s how you process your sense of touch. If you do a similar re-wiring process then the somatosensory cortex will learn to see. Because of this and other similar experiments, these are called neuro-rewiring experiments.

There’s this sense that if the same piece of physical brain tissue can process sight or sound or touch then maybe there is one learning algorithm that can process sight or sound or touch. And instead of needing to implement a thousand different programs or a thousand different algorithms to do, you know, the thousand wonderful things that the brain does, maybe what we need to do is figure out some approximation or to whatever the brain’s learning algorithm is and implement that and that the brain learned by itself how to process these different types of data. To a surprisingly large extent, it seems as if we can plug in almost any sensor to almost any part of the brain and so, within the reason, the brain will learn to deal with it.

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/d2dce6ed-456f-4202-b3a1-bbadff1275e0_630x309.jpg"></a>
</p>

So, it’s pretty amazing to what extent is as if you can plug in almost any sensor to the brain and the brain’s learning algorithm will just figure out how to learn from that data and deal with that data. And there’s a sense that if we can figure out what the brain’s learning algorithm is, and, you know, implement it or implement some approximation to that algorithm on a computer, maybe that would be our best shot at, you know, making real progress towards the AI, the artificial intelligence dream of someday building truly intelligent machines.

**Explanation**

Inside neurons, Dendrites act as neuro receptors nothing but the input layer. Axons act as neurotransmitters nothing but the output layer. The nucleus is where the action potential is compared to the threshold. If the action potential is greater than the threshold, the electrical impulse will transmit to another neuron. If the action potential is lesser than the threshold, the electrical impulse won’t transmit to another neuron.

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/c2b4d6e4-009e-42bd-a2c9-a11e53ee2d25_630x315.jpg"></a>
</p>

A biological neuron operates through a series of simple electrochemical processes.It receives signals from other neurons through its dendrites. When these incoming signals add up to a certain level (a predetermined threshold), the neuron switches on and sends an electrochemical signal along its axon. This, in turn, affects the neurons connected to its axon terminals. The key thing to note here is that a neuron’s response is like a binary switch: it either fires (activates) or stays quiet, without any in-between states [9].

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/2636c301-fe49-4157-88f0-f4ee5e97a834_630x372.jpg"></a>
</p>

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/178e818d-a72b-409c-a34e-55d0c4fcccd5_327x172.png"></a>
</p>

Similarly, artificial neurons receive the information from the input layer and transmit the information to other neurons through the output layer. Here, the neurons are connected and certain weights are assigned to that particular connection. These weights represent the strength of the connection and they play an important role in the activation of the neuron. The bias is like an intercept in the linear equation.

Here, the inputs (x1 to xn) get multiplied with corresponding weights (w1 to wn) and then they get summated along with the bias. The result would be taken as input for the activation function this is where the decision happens and the output of the activation function is transferred to other neurons. There are different types of activation functions some are linear, step, sigmoid, RelU, etc.

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/6e35ff43-06b2-48bf-87e2-7266f430924c_630x272.jpg"></a>
</p>

In our childhood we may have struggled with catching balls . However, through practice our brain eventually learns how to do so. During this process the brain effectively learns the mapping function from inputs to outputs. In other word the process of learning a mapping function through repeated experience is referred to as intelligence in living things. Now the critical question is What if some nonliving things start doing the same?
can we develop the same capability for our computer . that where the concept of Machine learning come into play

<p align="center">
<img src="https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/v.jpg "></a>
</p>
What does this have to do with the brain( Dr. Andrew)

<p align="center">
<img src=" https://github.com/dr-mushtaq/Deep-Learning/blob/master/Deep%20Learning-Neural%20Networks/Chapter1-Introduciton%20of%20Deep%20learning/fdfd.jpg "></a>
</p>

I think because it’s been difficult to convey intuitions about what these equations are doing, really creating the sense on a very complex function, the analogy that it’s like the brain has become an oversimplified explanation for what this is doing. But the simplicity of this makes it seductive for people to just say it publicly as well as for media to report it, and it is certainly called the popular imagination. There is a very loose analogy between, let’s say, a logistic regression unit with a sigmoid activation function. Here’s a cartoon of a single neuron in the brain. In this picture of a biological neuron, this neuron, which is a cell in your brain, receives electric signals from other neurons, X1, X2, X3, or maybe from other neurons, A1, A2, A3, does a simple thresholding computation, and then if this neuron fires, it sends a pulse of electricity down the axon, down this long wire, perhaps to other neurons. There is a very simplistic analogy between a single neuron in a neural network, and a biological neuron like that shown on the right. But I think that today even neuroscientists have almost no idea what even a single neuron is doing. A single neuron appears to be much more complex than we are able to characterize with neuroscience, and while some of what it’s doing is a little bit like logistic regression, there’s still a lot about what even a single neuron does that no one human today understands. For example, exactly how neurons in the human brain learns is still a very mysterious process, and it’s completely unclear today whether the human brain uses an algorithm, does anything like back propagation or gradient descent or if there’s some fundamentally different learning principle that the human brain uses. When I think of deep-learning, I think of it as being very good and learning very flexible functions, very complex functions, to learn X to Y mappings, to learn input-output mappings in supervised learning. Whereas this is like the brain analogy, maybe that was useful once, I think the field has moved to the point where that analogy is breaking down, and I tend not to use that analogy much anymore. So that’s it for neural networks and the brain. I do think that maybe the field of computer vision has taken a bit more inspiration from the human brain than other disciplines that also apply deep learning, but I personally use the analogy to the human brain less than I used to. That’s it for this video. You now know how to implement forward prop and back prop and gradient descent even for deep neural networks. Best of luck with the programming exercise, and I look forward to sharing more of these ideas with you in the second course.



### References

1-[Natural Language Processing (NLP) with Python](https://pub.towardsai.net/natural-language-processing-nlp-with-python-tutorial-for-beginners-1f54e610a1a0)



<p align="center">
  <a href="#previous-section" style="text-decoration:none;">
    <button style="padding:20px 40px; font-size:24px; font-weight:bold; border-radius:12px; background-color:#007BFF; color:white; border:none; cursor:pointer;">
      ⬅️ Previous
    </button>
  </a>

  <a href="#next-section" style="text-decoration:none;">
    <button style="padding:20px 40px; font-size:24px; font-weight:bold; border-radius:12px; background-color:#28A745; color:white; border:none; cursor:pointer;">
      Next ➡️
    </button>
  </a>
</p>



 



