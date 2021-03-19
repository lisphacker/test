<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.model_pruning.apply_mask" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.model_pruning.apply_mask

``` python
tf.contrib.model_pruning.apply_mask(
    x,
    scope=''
)
```

Apply mask to a given weight tensor.

#### Args:

* <b>`x`</b>: Input weight tensor
* <b>`scope`</b>: The current variable scope. Defaults to "".

#### Returns:

Tensor representing masked_weights