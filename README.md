# deep_dive_NN
deep dive into the core of neural networks. lessons from Andrej Karpathy. The lesson goals are to learn Neural Network from scratch and code by code in-depth explanation. The final project is to **build an LLM from scratch.** using pytorch and tensor libraries.
Useful for learning "**what happens inside of a neural network?**", this course also helps to build an intuitive analytical capability for NN learners. Own notes and comments are added in the code files.

# Lesson-1: Micrograd
A tiny **Autograd engine**. performs Backpropagation (main function) on small Neural Networks. useful for learning how parameters of neural network is tuned and loss is minimized.

# Lesson-2: Makemore
Learning to build a tiny **Bigram Language model**. first step of understanding Large language model.
Makemore takes one character and predicts the next character. in the exercise part, I've built a **trigram language model** and compared the loss and accuracy between both.

# Lesson-3: Makemore on MLP
Building a **character-level language model on MLP**.

# Lesson-4: 
Implementing activation and batchnormalization layers from scratch (spelled out in-depth codes and explanation).

# Lesson-5:
**Implement Backpropagation** on the MLP, atfirst **manually** then using the **micrograd** through the cross entropy loss, 2nd linear layer, tanh, batchnorm, 1st linear layer, and the embedding table(character mapping)
outcome is that we get a **strong intuitive understanding about how gradients flow backwards and network optimization**. gives a base to **innovate optimization** techniques and **debug** the network.



