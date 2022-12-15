# d2l-annot

![diveinto](https://user-images.githubusercontent.com/72039442/207805770-89f269f0-0758-4fd0-8fe9-dc5318656df9.png)

# What is the project about
  - ***Chapter 2*** 
    - **ndarray**
      - Is introduced the main structure that we will use throughout the book, the tensors and a library to create and manipulate it, we learn to
          - indexing and Slicing Tensors
          - some basics operations 
            - sum, comparison
          - broadcasting
          - saving memory 
            - referencing already created tensors
          - how to convert tensors to other python objects
          
    - ***pandas***
      - Pandas is a library that we are going to use to read various data, in this chapter we are introduced to it and we learn its main routines, such as
        - reading a Dataset
        - how to preparate data 
        - conversion to the tensor format 
    
  - ***Chapter 3*** 
    - **linear-regression**
      - Linear regression may be both the simplest and most popular among the standard tools for tackling regression problems, in this chapter we develop the idea, using a suposed linear problem, of 
        - how we can modelate a model of linear regression
        - how measure the quality of actual set of weights(loss function)
        - how we can use this loss function to update a set of weights 
        
    - **weight-decay**
      - Weight decay is ubiquitous in neural network optimization, the deep learning framework(like pytorch) makes it especially convenient, integrating weight decay into the optimization algorithm itself for easy use in combination with any loss function, we learned to 
        - how to implement the weight-decay, using model of linear regression, from scratch
        - how to concisely implement
    
  - ***Chapter 4***
    - **classification**
      - We are introduced to the classification problem, its differences from the regression problem and how to extract the main metric of this type of problem, the accuracy.
     
    - **softmax-regression-concise**
      - Concise, and more useful, implementation of softmax regressio, it showed 
        - definition of model 
        - how to train the model 
        - construction of loss function
     
    - **softmax-regression-scratch**
      - Because softmax regression is so fundamental, implementing it from scratch is very constructive for knowledge
      
  - ***Chapter 5***
     - **mlp-implementation**
        - Multilayer perceptrons (MLPs) is one of the strongest structures within the context of deep learning, as its concatenation can generate a multi-layer model capable of performing highly complex tasks, with a cost associated with this operation, in this capter we learned to
          - initializing model parameters
          - training the model

# What technologies were used
  - ***numpy***        
    - to do some manipulations and create only tensors, importing the numpy array
  - ***pandas***
    - to data manipulation
  - ***pytorch***
    - to do key tensor manipulations, instantiate model layers
  - ***math***
    - apply some specific mathematical expressions throughout the code
