# Tensorflow_Fundamentals


[Tensorflow documentation](https://www.tensorflow.org/api_docs/python/tf/)

**TENSOR:** <br>
Tensors are multi-dimensional arrays with a uniform type (called a dtype). You can see all supported dtypes at tf.dtypes.DType.
If you're familiar with NumPy, tensors are (kind of) like np.arrays.
All tensors are immutable like Python numbers and strings: you can never update the contents of a tensor, only create a new one.


**tf.variable :** <br>
A TensorFlow variable is the recommended way to represent shared, persistent state your program manipulates. This guide covers how to create, update, and manage instances of tf.Variable in TensorFlow.
Variables are created and tracked via the tf.Variable class. A tf.Variable represents a tensor whose value can be changed by running ops on it. Specific ops allow you to read and modify the values of this tensor. Higher level libraries like tf.keras use tf.Variable to store model parameters.

**tf.constant:** <br>
A constant value and can't be changed. will get a error if we try to modify it

**A.ndim:** <br> finds the dimenesion of the tensor

**A.shape:** <br> finds the shape of the tensor

**A.dtype** <br> finds the type of values in a tensor

**tf.random.Generator.from_seed(42):** <br>
Used to set seed for that perticular block.

**tf.random.normal(shape=[x, y]) and tf.random.uniform(shape=[x, y]):** <br>
used to generate random values for a tensor

**tf.ones([x, y]) and tf.zeros([x, y]):** <br>
used to generate mat with given shape x, y.

**tf.shuffle(A):** <br>
used as the name suggests

**tf.multiply:** <br> Normal multiplation , element wise.

**tf.tensordot(a,b, axex= 1):** <br> matrix multiply

**tf.matmul(a, b):** <br> matrix multiply

**Aggregating Tensors :** <br> condensing them from multiple values down to smaller amount of values <br>
**tf.abs, tf.reduce_sum(), tf.reduce_min(), tf.reduce_mean(), tf.reduce_max(), tf.argmin(), tf.argmax(), tf.squeeze()**

**tf.one_hot(some_list, depth = len(some_list), on_value = "x", off_value ="o"):** <br>
this onehot encode values






