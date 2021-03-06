<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.variable" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.variable

``` python
tf.keras.backend.variable(
    value,
    dtype=None,
    name=None,
    constraint=None
)
```

Instantiates a variable and returns it.

#### Arguments:

* <b>`value`</b>: Numpy array, initial value of the tensor.
* <b>`dtype`</b>: Tensor type.
* <b>`name`</b>: Optional name string for the tensor.
* <b>`constraint`</b>: Optional projection function to be
        applied to the variable after an optimizer update.


#### Returns:

    A variable instance (with Keras metadata included).

Examples:
```python
>>> import numpy as np
>>> from keras import backend as K
>>> val = np.array([[1, 2], [3, 4]])
>>> kvar = K.variable(value=val, dtype='float64', name='example_var')
>>> K.dtype(kvar)
'float64'
>>> print(kvar)
example_var
>>> kvar.eval()
array([[ 1.,  2.],
       [ 3.,  4.]])
```