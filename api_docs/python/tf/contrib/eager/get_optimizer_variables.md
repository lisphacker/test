<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.eager.get_optimizer_variables" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.eager.get_optimizer_variables

``` python
tf.contrib.eager.get_optimizer_variables(optimizer)
```

Returns a list of variables for the given `tf.compat.v1.train.Optimizer`.

Equivalent to `optimizer.variables()`.

#### Args:

* <b>`optimizer`</b>: An instance of `tf.compat.v1.train.Optimizer` which has created
    variables (typically after a call to `Optimizer.minimize`).


#### Returns:

A list of variables which have been created by the `Optimizer`.