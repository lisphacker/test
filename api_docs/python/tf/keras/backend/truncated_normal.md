<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.truncated_normal" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.truncated_normal

``` python
tf.keras.backend.truncated_normal(
    shape,
    mean=0.0,
    stddev=1.0,
    dtype=None,
    seed=None
)
```

Returns a tensor with truncated random normal distribution of values.

The generated values follow a normal distribution
with specified mean and standard deviation,
except that values whose magnitude is more than
two standard deviations from the mean are dropped and re-picked.

#### Arguments:

* <b>`shape`</b>: A tuple of integers, the shape of tensor to create.
* <b>`mean`</b>: Mean of the values.
* <b>`stddev`</b>: Standard deviation of the values.
* <b>`dtype`</b>: String, dtype of returned tensor.
* <b>`seed`</b>: Integer, random seed.


#### Returns:

A tensor.