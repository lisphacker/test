<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.placeholder" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.placeholder

``` python
tf.keras.backend.placeholder(
    shape=None,
    ndim=None,
    dtype=None,
    sparse=False,
    name=None,
    ragged=False
)
```

Instantiates a placeholder tensor and returns it.

#### Arguments:

* <b>`shape`</b>: Shape of the placeholder
        (integer tuple, may include `None` entries).
* <b>`ndim`</b>: Number of axes of the tensor.
        At least one of {`shape`, `ndim`} must be specified.
        If both are specified, `shape` is used.
* <b>`dtype`</b>: Placeholder type.
* <b>`sparse`</b>: Boolean, whether the placeholder should have a sparse type.
* <b>`name`</b>: Optional name string for the placeholder.
* <b>`ragged`</b>: Boolean, whether the placeholder should have a ragged type.
        In this case, values of 'None' in the 'shape' argument represent
        ragged dimensions. For more information about RaggedTensors, see this
        [guide](https://www.tensorflow.org/guide/ragged_tensors).


#### Raises:

* <b>`ValueError`</b>: If called with eager execution
* <b>`ValueError`</b>: If called with sparse = True and ragged = True.


#### Returns:

    Tensor instance (with Keras metadata included).

Examples:
```python
>>> from keras import backend as K
>>> input_ph = K.placeholder(shape=(2, 4, 5))
>>> input_ph
<tf.Tensor 'Placeholder_4:0' shape=(2, 4, 5) dtype=float32>
```