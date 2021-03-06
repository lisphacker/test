<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.ones_like" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.ones_like

``` python
tf.keras.backend.ones_like(
    x,
    dtype=None,
    name=None
)
```

Instantiates an all-ones variable of the same shape as another tensor.

#### Arguments:

* <b>`x`</b>: Keras variable or tensor.
* <b>`dtype`</b>: String, dtype of returned Keras variable.
         None uses the dtype of x.
* <b>`name`</b>: String, name for the variable to create.


#### Returns:

    A Keras variable with the shape of x filled with ones.

Example:
```python
>>> from keras import backend as K
>>> kvar = K.variable(np.random.random((2,3)))
>>> kvar_ones = K.ones_like(kvar)
>>> K.eval(kvar_ones)
array([[ 1.,  1.,  1.],
       [ 1.,  1.,  1.]], dtype=float32)
```