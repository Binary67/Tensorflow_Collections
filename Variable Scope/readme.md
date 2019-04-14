# Tensorflow Sharing Variables
Complex Neural Network models often requires you to share the large sets of variables and you might want to initialize all of them in one place. A common way to share variables is to create them in a separate piece of code and pass them to functions that use them. While convenient, creating variables like above, outside of the code, breaks encapsulation:

  - The code that builds the graph must document the names, types, and shapes of variables to create.
  - When the code changes, the callers may have to create more, or less, or different variables.

One way to address the problem is to use classes to create a model, where the classes take care of managing the variables they need. For a lighter solution, not involving classes, TensorFlow provides a `tf.variable_scope` mechanism that allows to easily share named variables while constructing a graph.

# In this project 
Some demonstration on tensorflow sharing variables method by using *tf.variable_scope* 

# Further Reading
More information on https://www.tensorflow.org/versions/r1.1/programmers_guide/variable_scope
