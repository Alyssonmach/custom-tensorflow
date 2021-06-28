# custom-tensorflow
***
Custom Models, Layers, and Loss Functions with TensorFlow. Program Files for TensorFlow Integrated Courses: Advanced Techniques.

### Week 1 - Functional APIs
***
Compare how the Functional API differs from the Sequential API, and see how the Functional API gives you additional flexibility in designing models. Practice using the functional API and build a Siamese network!

- Review Sequential API and compare with Functional API
- Describe new model types that you can build with Functional API
- Functional API: define input, layers, and model
- Use Functional API to build a model
- Use Functional API to create a model that produces multiple outputs
- Use Functional API to build a Siamese network

### Week 2 - Custom Loss Functions
***
Loss functions help measure how well a model is doing, and are used to help a neural network learn from the training data. Learn how to build custom loss functions, including the contrastive loss function that is used in a Siamese network.

- Describe when you need to build a custom loss function
- Implement Huber Loss with a custom loss function
- Add an adjustable hyper parameter to custom loss using a wrapper function
- Define a custom loss using an object oriented class
- Implement contrastive loss function used in a Siamese network

### Week 3 - Custom Layers
***
Custom layers give you the flexibility to implement models that use non-standard layers. Practice building off of existing standard layers to create custom layers for your models.

- Define a custom layer to include the activation function
- Define a custom layer class by inheriting from the Layer class
- Describe the two components of a custom layer
- Describe what a custom layer can do that a lambda layer cannot
- Use a lambda layer to customize a network layer

### Week 4 - Custom Models
***
You can build off of existing models to add custom functionality. This week, extend the TensorFlow Model Class to build a ResNet model!

- Explain some benefits to defining a custom model class instead of using the Functional or Sequential APIs
- Define a model by creating a Python class that inherits from TensorFlow's Model class
- Describe functions that can be inherited from the TensorFlow Model class
- Build a residual network by defining a custom model class

### Week 5 - Callbacks
***
Custom callbacks allow you to customize what your model outputs or how it behaves during training. This week, implement a custom callback to stop training once the callback detects overfitting.

- Describe tasks that callbacks can do while a model is training
- Create a callback and assign it to a model's training
- Use a ModelCheckpoint object to save model parameters during training
- Use the EarlyStopping callback to keep a model from overfitting
- Describe an example where you may want to create a custom callback
- Implement a custom callback to detect overfitting

### Informations
***
- Course produced by **Laurence Moroney**, **Andrew Ng.** and **Eddy Shyu**.
- [Visit the course](https://www.coursera.org/learn/custom-models-layers-loss-functions-with-tensorflow).
