<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.batch_get_value" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.batch_get_value

``` python
tf.keras.backend.batch_get_value(tensors)
```

Returns the value of more than one tensor variable.

#### Arguments:

* <b>`tensors`</b>: list of ops to run.


#### Returns:

A list of Numpy arrays.


#### Raises:

* <b>`RuntimeError`</b>: If this method is called inside defun.