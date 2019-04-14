# Eager Execution
Tensorflow is a graph execution engine for machine learning. Your computation is represented as an platform independent graph. By doing this, you will have few advantages with you
  1. Automatic differentiation
  2. Deployment to a python-free server, phone
  3. Graph based optimization (GSE, layout, etc)
  4. Compilation, kernel fusion, layout selection
  5. Automatic distribution to 100s of machines
  
Eager execution is an imperative programming environment that evaluates operations immediately, without building graphs. Operations return concrete values instead of constructing a computational graph to run later. This makes it easy to get started with TensorFlow and debug models, and it reduces boilerplate as well.

# In this project
Eager execution will be used along with `tf.GradientTape` to differentiate an equation.

# Further Reading
[Eagle Execution](https://www.tensorflow.org/guide/eager)

[tf.GradientTape](https://www.tensorflow.org/api_docs/python/tf/GradientTape)

[Tensorflow Dev Summit 2018](https://www.youtube.com/watch?v=T8AW0fKP0Hs)
