<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.eager.inf_callback" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.eager.inf_callback

``` python
tf.contrib.eager.inf_callback(
    op_type,
    inputs,
    attrs,
    outputs,
    op_name,
    action=tf.contrib.eager.ExecutionCallback.RAISE
)
```

A specialization of `inf_nan_callback` that checks for `inf`s only.