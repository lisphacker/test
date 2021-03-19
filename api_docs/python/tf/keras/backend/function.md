<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.function" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.function

``` python
tf.keras.backend.function(
    inputs,
    outputs,
    updates=None,
    name=None,
    **kwargs
)
```

Instantiates a Keras function.

#### Arguments:

* <b>`inputs`</b>: List of placeholder tensors.
* <b>`outputs`</b>: List of output tensors.
* <b>`updates`</b>: List of update ops.
* <b>`name`</b>: String, name of function.
* <b>`**kwargs`</b>: Passed to <a href="../../../tf/InteractiveSession.md#run"><code>tf.Session.run</code></a>.


#### Returns:

Output values as Numpy arrays.


#### Raises:

* <b>`ValueError`</b>: if invalid kwargs are passed in or if in eager execution.